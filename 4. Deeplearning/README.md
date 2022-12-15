# Project 4 - Deep-learning
Deeplearning(MLP, NLP, RNN, LSTM, CNN, GAN)

-------------------------------------------------------------------------
# 기본적 목표 <br>
목표 직군, 업무와 연관된 데이터셋과 기술 찾아보기 <br>
Deep-learning에서 배운 여러 모델을 사용해본다. <br>
Deep-learning에서 찾은 여러 모델을 사용해본다. <br>

-------------------------------------------------------------------------
# ABSTRACT(초록 - 250자 이내)
Alzheimer 정도에 따라 공통된 비활성화 위치가 있을 것이다.

## 데이터(Brain-CT-Image)<br>
1. Kaggle에서 수집한 Brain-CT-Image를 사용
2. K-병원에서 제공한 Brain-Activate-Image를 사용

## 1차 단계(Segmentation) <br>
Brain-CT로 뇌 활성화(Ah 정도)를 구분 학습한다.

## 2차 단계(Segmentation) <br>
Brain-Act로 활성화 위치를 학습한다.

## 목표 단계(ML - Tree model) <br>
1, 2차단계로 학습된 결과를 Input으로 사용하여 <br>
분류 모델에 적용하여, Ah에 비활성화되는 위치 찾기

-------------------------------------------------------------------------
# 딥러닝 파이프라인(가설 검증용)
![image](https://user-images.githubusercontent.com/88294272/205585133-f290ccbf-8876-4b5a-8798-832d16fdef10.png)

-------------------------------------------------------------------------
# 목표 - 참고 및 소스 분해하기(Tree-CNN)
https://github.com/evertonaleixo/Tree-CNN
