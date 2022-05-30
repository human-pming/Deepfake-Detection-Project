# 딥페이크 감지 모델 비교 프로젝트
Deepfacke Detection using Image Crop and Image recognition
( 2022.04.01 ~ 2022.05.30 )

## 프로젝트 소개
위 프로젝트의 목적은  영상 속 얼굴 객체를 탐지 후 , 딥페이크 여부를 분류하는 것입니다. <br>

영상 속 얼굴 객체 탐지에는 MTCNN 모델을 사용했고, 딥페이크 여부 감지에는 Resnet과 Facenet 모델을 사용했습니다.<br>

## 사용 데이터
전체 영상 데이터셋의 경우, 캐글에서 개최한 Deepfake Detection Challenge에서 제공한 데이터셋을 활용했습니다. <br>

- Image Crop

- Image Recognition
---- Resnet
---- Facenet

## 사용 모델

[Facenet](https://drive.google.com/drive/folders/12aMYASGCKvDdkygSv1yQq8ns03AStDO) <br>
[Resnet,MTCNN](https://github.com/timesler/facenet-pytorch/tree/master/models)


## 결과 비교

|모델|정확도|
|----|------|
|Resnet|테스트|
|Facenet|테스트|


## 참고 문헌

[MTCCN](https://arxiv.org/abs/1604.02878)
[Facenet](https://jkisaaclee.kro.kr/keras/facenet/deep%20learning/computer%20vision/2019/10/01/how_to_develop_a_face_recognition_system_using_facenet_in_keras_ko/)

## 참여자



