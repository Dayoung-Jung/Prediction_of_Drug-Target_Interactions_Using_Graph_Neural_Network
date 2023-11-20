# Prediction_of_Drug-Target_Interactions_Using_Graph_Neural_Network

◾ 프로젝트 목적 
- 신약 후보 물질 도출을 위한, 단백질과 약물 간 상호작용(결합 친화도) 예측 모델 개발

◾ 데이터 셋
- DAVIS: 442개의 단백질과 68개의 약물로 구성
- BindingDB_Kd: 8,661개의 단백질과 1,039,940개의 약물로 구성
- KIBA: 467개의 단백질과 52,498개의 약물로 구성

◾ 프로젝트 과정 ( 1. 데이터셋 변환 )
- 아미노산을 알파벳으로 지정하여 정수와 매핑하는 방식으로, 단백질(Target) 라벨 인코딩
- 스마일즈(SMILES)로 표현된 분자 구조 데이터셋을 그래프 구조로 변환

◾ 프로젝트 과정 ( 2. 모델 학습 및 평가 )
- 사용한 모델: GCN, GAT, GAT + GCN, GIN 모델
- 사용한 평가지표: Mean Square Error, Root Mean Square Error, Pearson Correlation Coefficient, Spearman's Rank Correlation Coefficient, Concordance Index

◾ 프로젝트 결과

<img width="470" alt="스크린샷 2023-11-20 오전 9 02 50" src="https://github.com/Dayoung-Jung/Prediction_of_Drug-Target_Interactions_Using_Graph_Neural_Network/assets/68275740/dcf50e00-7d75-4d46-919b-0a3e29fb896c">
