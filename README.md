인공지능개론 수업용 깃

#과제 진행</br>

2주차(3월 11일) 과제 完

1. breast_cancer.csv 데이터를 이용하여 여러가지 ML 진행
2. 1번 코드를 응용하여 diabetes.csv 데이터로 여러가지 ML 진행

3주차(3월 18일) 과제 完
1. iris.data를 사용해서 헤더가 없을 때 피쳐명 설정 후 ML 진행
2. Raisin.xlsx을 사용해서 csv 파일과 xlsx 파일의 차이를 알고 ML 진행
3. 타이타닉 데이터를 사용해서 데이터 관리 진행 방식과 방법 숙지
4. *당뇨병 데이터를 사용해서 사이버캠퍼스 과제 완료

#중요 개념<br>

2주차 진행과정
1. 데이터에서 label을 제외한다.
2. 제외된 데이터와 label 데이터를 train 데이터와 test 데이터로 나눈다,
3. 각train 데이터로 학습을 하고 label을 제외한 test 데이터로 예측을 진행한다.
4. 예측한 label 값을 기존 test label과 비교하여 정확도를 측정한다.

평가 방식</br>
분류 = 정확도, confusion_matrix / 1에 가까울수록 좋음</br>
회귀 = mse(예측값 - 실제값)^2의 평균 / 작을수록 좋음. 오차의 제곱의 합의 평균이기 때문

3주차 진행과정
1. 내용 복습
2. .csv는 read_csv / .xlsx는 read_excel
3. data Loading
   data collection
   data cleaning (결측치, outlier)
   feature extraction (범주형을 0,1로 바꿔주기)
   feature selection


