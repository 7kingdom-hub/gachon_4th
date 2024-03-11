인공지능개론 수업용 깃

#과제 진행</br>

3월 11일 과제

1. breast_cancer.csv 데이터를 이용하여 여러가지 ML 진행
2. 1번 코드를 응용하여 diabetes.csv 데이터로 여러가지 ML 진행

#중요 개념

진행 과정 
1. 데이터에서 label을 제외한다.
2. 제외된 데이터와 label 데이터를 train 데이터와 test 데이터로 나눈다,
3. 각train 데이터로 학습을 하고 label을 제외한 test 데이터로 예측을 진행한다.
4. 예측한 label 값을 기존 test label과 비교하여 정확도를 측정한다.

평가 방식</br>
분류 = 정확도, confusion_matrix / 1에 가까울수록 좋음</br>
회귀 = mse(예측값 - 실제값)^2의 평균 / 크면 클수록 좋음
