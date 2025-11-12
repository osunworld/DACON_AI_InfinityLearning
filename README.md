# DACON_AI_InfinityLearning
>2025 SW중심대학 디지털 경진대회 : AI부문 

## Overview
이 프로젝트는 AI생성 텍스트를 판별하기 위해 제작되었습니다.  
sbert를 이용한 임베딩을 MLP레이어를 통해 판별하는 모델입니다.

## Features
- Sentence-BERT(SBERT)를 이용한 문장 임베딩 생성  
- 임베딩 벡터 기반 다층 퍼셉트론(MLP) 분류기 설계 및 학습  
- Group K-Fold 교차검증을 통한 성능 안정화  
- Fold 앙상블(Fold Ensemble)을 활용한 최종 예측 향상  
- Colab Pro (A100 GPU) 환경에서 메모리 최적화 및 속도 개선
  
## Tech Stack
| Category | Tools / Frameworks |
|-----------|--------------------|
| Language | Python 3.10 |
| Embedding Model | SBERT (Sentence-BERT, `sentence-transformers` library) |
| Neural Network | PyTorch, MLP (Multi-Layer Perceptron) |
| Validation | Group K-Fold (sklearn.model_selection) |
| Optimization | AdamW, BCEWithLogitsLoss, EarlyStopping |
| Environment | Google Colab Pro (A100 GPU) |
| Utilities | NumPy, Pandas, tqdm, scikit-learn, Matplotlib |
| Deployment / Version Control | GitHub, Google Drive |

## 📂 Project Structure
```bash
DACON_AI_InfinityLearning
 ┣ data/           
 ┣ model/          
 ┣ notebooks/       
 ┣ output/          
 ┣ logs/            
 ┣ requirements.txt 
 ┗ README.md
