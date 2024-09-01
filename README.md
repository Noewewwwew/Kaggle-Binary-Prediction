# Kaggle_Binary_Prediction
#### 해당 프로젝는 2024년 8월 한 달 동안 케글 독 버섯 이진 분류 예측 대회에 출전을 목표로 진행했습니다.
![image](https://github.com/user-attachments/assets/96612e10-3a0d-4ac5-9a00-86f797d80e4b)


## 1. 프로젝트 인원 및 맡은 역할
- XGBoost + LightGBM : 조현상
- CatBoost : 강하운


## 2. 시나리오
데이터 분석 -> 레이블 인코딩 -> 적절한 모델 찾기 -> 베이지안 최적화 -> 스태킹 앙상블

## 3. 알고리즘 단계
1. pandas를 사용해서 데이터 분석
2. Null값과 Outlier 값 분석
3. 기존 레이블 인코딩 튜닝
4. XGBoost를 사용해서 각 피처에 중요도 확인
5. 베이지안 최적화를 이용해서 하이퍼 파라미터 찾기
6. 여러가지 모델과 스태킹

## 4. 최종 결과
![image](https://github.com/user-attachments/assets/4f67c301-3a32-4cd5-a260-cf6979b20857)


## 5. 개선 해야 할 사항
- 결측값 데이터를 깔끔하게 처리하지 못한 게 노이즈로 작용해서 점수를 떨어뜨렸던 거 같다.
- 다른 케글 고수분들이 한 데이터 드리블 방법을 보고 배울 것이다.
