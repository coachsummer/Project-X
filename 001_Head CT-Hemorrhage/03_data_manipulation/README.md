{"type":"mission","id":"3","description":"data manipulation & split"}
## 데이터 가공
학습을 위해 이미지의 크기를 동일하게 만들어야 한다.
크기 변환 후 적당한 크기인지 확인을 위해 샘플로 몇 개를 출력하라.
## 데이터 구분
학습을 위해 데이터를 train 80%, validation 10%, test 10%로 나누어라.
## 추가데이터 확보
데이터 변환으로 추가데이터를 확보한다는 것은 train과 validation 데이터를 가공하여 추가 데이터를 확보한다는 의미이다.
test데이터는 가공할 이유가 없으므로 추가데이터 확보는 반드시 데이터를 train과 test로 구분하고 난 뒤에 한다.
이 작업음 04_image_data_generator에서 진행한다.
## 키워드
image to numpy array, opencv, train_test_split

## 평가
1. 모든 이미지 데이터의 크기를 동일하게 변환하였는가?
2. 샘플을 출력하였는가?
3. 데이터를 train, validation, test로 나누었는가?
