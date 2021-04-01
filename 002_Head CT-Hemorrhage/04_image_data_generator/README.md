{"type":"mission","id":"4","description":"image_data_generator"}
## 이미지 변형 기법
* 데이터 변환으로 추가데이터를 확보한다는 것은 train과 validation 데이터를 가공하여 추가 데이터를 확보한다는 의미이다.
test데이터는 가공할 이유가 없으므로 추가데이터 확보는 반드시 데이터를 train과 test로 구분하고 난 뒤에 한다.
* 이미지를 여러 방법으로 변형시켜 더 많은 데이터를 생성하라.
* ImageDataGenerator를 사용하라.
* 이미지를 출력하여 확인하라.
* ImageDateGenerator의 인수 rescale, shear_range, rotation_range, width_shift_range, height_shift_range, horizontal_flip에 대해서 자세히 공부하고, 팀원들과 앞에서 제시한 인수들을 분할하여 서로 설명하라.
## 키워드
ImageDataGenerator
## 평가
* 추가 데이터를 생성했는가?
* 이미지를 출력했는가?
* ImageDataGenerator의 옵션들을 숙지하였는가? (멘토는 팀원들의 토의에 참가하여 관찰하고 잘 설명한 사람 순으로 점수 부여)
