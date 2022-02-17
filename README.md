# DL_CNN_Study

### 자료

- 파이썬 머신러닝 완벽 가이드의 저자 '권철민'의 [딥러닝 CNN 완벽 가이드 - Fundamental 편](https://www.inflearn.com/course/%EB%94%A5%EB%9F%AC%EB%8B%9D-cnn-%EC%99%84%EB%B2%BD-%EA%B8%B0%EC%B4%88) 강의를 수강하며 실행해본 코드 정리.

### 학습 동기
- 추천시스템을 다루기 위해 NLP와 CV의 기본적인 배경지식이 필요하다고 생각하여 CV 학습을 위해 선택.
- 딥러닝 모델을 구현하여 원하는 도메인과 문제에 맞춰 모델을 만들기 위해서는 Keras에 대한 깊은 이해가 필요할 것이라 생각.

### 학습 목표
- Computer Vision의 주요 모델에 대해 이해하고 있으며, 코드로 구현할 수 있다.
- Keras를 Seqeuence하게 사용하여 Customize할 수 있도록 깊은 이해도를 가진다.

### 내용
- 딥러닝 전반에 대한 이해
  - 퍼셉트론, 경사하강법, 역전파, 활성화 함수, 손실 함수, 옵티마이저
- Keras Framework
  - Sequential API, Functional API, Callback(ModelCheckpoint, ReduceLROnPlateau, EarlyStopping)
- CNN
  - Kernel, Feature Map, Stride, Padding, Pooling
  - Weight Initailization, Batch Normalization, Shuffle, Global Average Pooling, Weight Regularization
- Augmentation
  - Keras ImageDataGenerator => flow
  - Preprocessing
  - Albumentations
- Pretrained Model
  - AlexNet
  - VGG
  - GoogLeNet (Inception)
  - ResNet
  - EfficientNet
