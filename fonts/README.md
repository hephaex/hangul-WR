## 글꼴 디렉토리

이 디렉토리에는 한글 지원하는 글꼴 파일이 몇 개 있어야 합니다. 글꼴 파일은 .ttf(트루 타입 형식)이어야 합니다. hangul-image-generator.py 스크립트는 이 디렉토리의 글꼴들을 이용하여 TensorFlow 모델 훈련을 위한 한글 이미지 데이터를 생성합니다.

#### 글꼴 파일 얻기

한글 글꼴에 대한 좋은 자료는 [네이버 웹사이트](http://software.naver.com/software/fontList.nhn?categoryId=I0000000), [Clova.AI](https://clova.ai/handwriting/)에서 찾을 수 있습니다.

이 웹사이트에서 글꼴을 다운로드하려면 원하는 글꼴을 클릭만하면 되는데, 실제 ttf 파일을 다운로드하게 될 때까지 커다란 파란색 다운로드 버튼을 계속 클릭해야 합니다. Mac 영역에서는 ttf가 아니라 otf 파일을 얻게 되므로, 이를 주의해서 ttf 형식을 받아주세요. 
