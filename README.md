# Deeplearning-miniproject

새싹 미니 프로젝트 1조 - 윤태양, 이태훈, 임채범, 윤태웅, 박현주, 구은혜, 김혜리, 명소연, 고남욱, 황희선

## 1. 프로젝트 목적
- 비디오 데이터를 범주에 맞게 분류하는 기존 모델 코드에서 다양한 시도를 통해 정확도를 더 높이고자 진행하였다.

## 2. 데이터
- UCF101 행동 인식 데이터 : YOUTUBE에서 수집한 101개의 액션 카테고리(13320개)로 구성된 영상의 행동 인식 데이터
- Top 5 Activity : CricketsShot / PlayingCello / Punch / ShavingBeard / TennisSwing
- Top 3 Activity : CricketsShot / Punch / TennisSwing

## 3. 전처리 및 모델링
- Fine Tuning, Early Stopping 등 다양한 전처리 기법을 시도해보고, CNN / MobileNet V2 / VGGNet 16 & 19 / ResNet / Xception 다양한 모델 또한 사용함.

## 4. 결과
- Top 5 Activity의 경우, Xception 모델을 사용했을 때 96.82%의 높은 정확도가 나옴.
![image](https://user-images.githubusercontent.com/97076352/167559434-fd2e2981-c8ad-47a8-bdce-fb079c658aa1.png)

- Top 3 Activity의 경우, VGG 16 모델을 사용했을 때 98.25%의 높은 정확도가 나옴.
![image](https://user-images.githubusercontent.com/97076352/167559807-4ecb62dc-bdba-416e-b807-202c802f85fd.png)

![image](https://user-images.githubusercontent.com/97076352/167559701-bbe3d3ad-843f-4486-b181-2b7782bee447.png)

