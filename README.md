## A. "Dlib 설치"
> $ sudo apt-get install build-essential cmake

> $ sudo apt-get install libgtk-3-dev

> $ sudo apt-get install libboost-all-dev

> $ wget https://bootstrap.pypa.io/get-pip.py

> $ sudo python get-pip.py

> $ pip install numpy

> $ pip install scipy

> $ pip install scikit-image

> $ pip install dlib

오류 발생 시,

> $ pip install dlib --user

설치 후,

> $ python

'>>> import dlib'

오류 없으면 성공!


## B. face_detector.py 실행하기
> python3 face_detector.py 파일경로/파일이름.확장자

>>> ex1) python3 face_detector.py ../src/1.jpg

>>>> 실행 시, 1.jpg의 얼굴인식이 실행됨

>>> ex2) python3 face_detector.py ../src/1.jpg ../src/2.jpg  

>>>> 실행 시, 1.jpg와 2.jpg의 얼굴인식이 실행됨

>>> ex3) python3 face_detector.py ../src/*.jpg 

>>>> 실행 시, src폴더내의 얼굴인식이 실행됨


## C. face_landemark_detection.py 실행하기
> ./face_landmark_detection.py shape_predictor_68_face_landmarks.dat 폴더 경로
>>>> bash permission이 denied 된 경우,
>>>> chmod +x face_landmark_detection.py로 권한 
