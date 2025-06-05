# 🚀 Startup Success Prediction Hackathon

> 데이콘에서 주최한 "기업 성공 확률 예측 해커톤: 미래의 성공기업을 발굴하라!" 대회 참가 프로젝트

---

## 프로젝트 개요

- **목표**  
  기업의 성공 가능성을 예측하여 미래 유망 기업을 발굴하는 머신러닝 모델 개발

- **사용 데이터**  
  기업 재무정보 및 산업 관련 데이터

- **주요 기법**  
  데이터 전처리, 탐색적 데이터 분석(EDA), MLP 및 Random Forest 등 머신러닝 모델링, 하이퍼파라미터 튜닝


## 주요 자료 링크

| 자료명            | 링크                                                                                             |
|-----------------|------------------------------------------------------------------------------------------------|
| 📄 프로젝트 보고서    | [프로젝트 보고서](https://github.com/kimyoungho010311/Startup_Success_Prediction_Hackathon/blob/main/notebooks/Ocean/Report.ipynb)           |
| 🛠 데이터 전처리 노트북 | [데이터 전처리 과정](https://github.com/kimyoungho010311/Startup_Success_Prediction_Hackathon/blob/main/notebooks/Ocean/%EC%A0%84%EC%B2%98%EB%A6%AC%EB%85%B8%ED%8A%B8%EB%B6%81.ipynb)  |
| 📊 탐색적 데이터 분석 | [탐색적 데이터 분석](https://github.com/kimyoungho010311/Startup_Success_Prediction_Hackathon/blob/main/notebooks/Ocean/Dacon_statrup_EDA.ipynb)    |
| 🔗 All-in-One 노트북  | [모든 과정 통합](https://github.com/kimyoungho010311/Startup_Success_Prediction_Hackathon/blob/main/notebooks/Ocean/%EC%B5%9C%EC%A2%85%EB%B3%B8.ipynb)      |


## 기술 스택

## 기술 스택

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)  [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  [![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)  [![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  

[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)  

[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)  


## 결과

### 1. 연구 요약  
스타트업은 경제 성장과 혁신을 주도하는 핵심 주체로, 성공 여부에 따라 투자자, 창업자, 그리고 직원들의 미래가 크게 달라진다.  
본 연구는 다양한 기업 데이터를 활용하여 스타트업의 성공 가능성(0.1~0.9 확률)을 조기에 예측하는 회귀 모델을 개발함으로써 투자 위험을 줄이고 효율적인 자원 배분 전략 수립에 기여하는 것을 목적으로 한다.

### 2. 데이터 및 연구 방법

- 데이콘 스타트업 데이터 사용 (train.csv, test.csv)
- 결측치 처리: 중앙값, 평균, 최빈값, ‘Unknown’ 대체
- 인코딩: 원핫 인코딩 및 순서형 변수 매핑
- 파생변수 생성: 기업나이, 직원당 매출, 투자 수익비 등
- 스케일링: Min-Max 스케일링 적용 (타깃 변수 제외)
- 모델: Random Forest, LightGBM, XGBoost, MLP 등 비교 학습
- 평가: 10-Fold 교차검증 및 MAE 지표 사용

### 3. 주요 결과

- 최종 모델 성능: XGBoost 모델 MAE 0.2068
- 주요 변수: 총 투자금, 가치대비 매출, 직원 수, SNS 팔로워 수, 고객 수 등 수치형 변수 중심으로 변수 중요도 분석
- 인사이트: 수치형 변수들이 예측에 큰 영향을 미쳤으며, 파생변수 로그 변환 및 주요 변수 선정이 성능 향상에 기여함

### 4. 향후 개선 방향

- 추가적인 파생변수 개발과 비정형 데이터(텍스트, 이미지) 활용 가능성 탐색
- 다양한 모델 앙상블 및 딥러닝 모델 실험
- 실시간 데이터 반영 및 외부 경제 지표 연동 고려


## 연락처

- GitHub: [kimyoungho010311](https://github.com/kimyoungho010311)  
- 이메일: ohhunmi24@gmail.com
