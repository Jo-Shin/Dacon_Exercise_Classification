# [Dacon_운동 동작 분류 AI 경진대회](https://dacon.io/competitions/official/235689/overview/description)

- **Data**: 3축 가속도계(accelerometer)와 3축 자이로스코프(gyroscope)를 활용해 측정된 센서 데이터
- **대회 목적**: 센서 데이터를 분석해 운동 동작 종류를 예측(classification)
- **코드 흐름**
  - 센서 데이터에서 추출한 max, min, SMA, kurtosis 등의 통계량을 XgBoost 모델이 학습
  - 어떤 통계량을 추출할 지 논문 [Feature Analysis to Human Activity Recognition](http://univagora.ro/jour/index.php/ijccc/article/view/2787)을 참고
