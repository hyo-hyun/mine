# python을 이용한 얼굴인식
### 1. opencv를 활용하자
#### opencv는 Open Source Computer Vision 의 약자이다.



* Open Source: 코드를 누구나 볼 수 있게 개방한 소스 


* Computer Vision: 사람의 시각 체계의 기능을 컴퓨터로 구현하는 것.

* 즉 opencv 는 사람의 눈을 대신한다고 생각하면 된다.


### 2. dlib를 활용하자

#### dlib은 distribution library 의 약자이다.
* 프로그래밍 언어 C ++로 작성된 범용 크로스 플랫폼 소프트웨어 라이브러리 
* Library: 컴퓨터 프로그램에서 자주 사용되는 부분 프로그램들을 모아 놓은 것.
### 3. numpy를 활용하자
* Numpy는 행렬 연산 library이다.

* 외부 패키지이므로 import 명령어를 통해 불러와야 한다.
```python
    import numpy as np
```
* numpy는 list 혹은 tuple을 데이터로 입력할 수 있다.


--------------------------
## PIP (python package index)
* pip은 python 패키지를 설치하고 관리하는 프로그램 이며,

명령어 pip을 통해 opencv , dlib, numpy 를 설치할 수 있습니다.


* 먼저, pycharm을 켜서 새로운 프로젝트를 생성해봅시다.

<img src="image/ee.PNG" height="300" width="600">

pycharm 하단에 있는 Terminal 버튼을 클릭해줍니다.

<img src="image/2.PNG" height="150" width="300" align="center">

커서가 깜빡거리는게 보이시나요? 
 

``pip install opencv-contrib-python``을 치면 pycharm에서 자동으로
opencv가 설치가 됩니다.
<img src="image/opencv.PNG" height="300" width="600">

똑같은 방식으로 ``pip install numpy``를 입력해주세요.
<img src="image/numpy.png" height="300" width="600">

dlib을 사용하기 위해서는 우선 ```pip install cmake```를 입력해서 `cmake`를 설치해주세요.

dlib은  c++로 짜여진 언어이기 때문에 compiler가 필요합니다. 
https://visualstudio.microsoft.com/ko/thank-you-downloading-visual-studio/?sku=Community&rel=16
로 들어가셔서 visual studio를 깔아주세요.

visual studio installer에서 `c++를 사용한 데스크톱 개발`버튼을 클릭해서 설치해주세요.
<img src="image/es.png" height="300" width="600">
설치를 완료 하셨으면 다시 pycharm으로 돌아가서 이전과 같이 terminal 창에서 `pip install dlib`을 해줍니다.

1단계를 완료했으니 이젠 python 코드를 작성해봅시다.

# 2단계

