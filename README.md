# Face Recognition
얼굴 인식 라이브러리를 사용하여 방문자의 얼굴을 인식하고 저장한다. 또한, 방문자가 몇 번째 방문인지 체크함으로써 더욱 정확한 얼굴인식 초인종 카메라를 만들 수 있다.

### 얼굴 인식에 필요한 Linux 및 Python 라이브러리 설치
```
sudo apt-get update
sudo apt-get install python3-pip cmake libopenblas-dev liblapack-dev libjpeg-dev
```

```
sudo pip3 -v 설치 Cython face_recognition
```

### 얼굴 인식 초인종 카메라 데모 앱 실행
```
wget -O doorcam.py tiny.cc/doorcam2gb
```
```
gedit doorcam.py
```
```
python3 doorcam.py
```
