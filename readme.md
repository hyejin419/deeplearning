# 딥러닝 학습 레포지토리

이 레포지토리는 **PyTorch**와 **TensorFlow/Keras**를 활용하여 다양한 딥러닝 모델을 구현하고 실습한 코드들을 정리한 공간입니다.
기초적인 퍼셉트론부터 CNN, VGG, AlexNet과 같은 대표적인 신경망 모델까지 단계적으로 학습할 수 있도록 구성되어 있습니다.


## 프로젝트 구조

### 1. 기초 개념 및 프레임워크

* `1. 파이토치 프레임워크.ipynb` : PyTorch 기본 문법 및 구조 학습
* `2. 파이토치로 구현한 선형회귀.ipynb`
* `2(2). 선형회귀 복습.ipynb`
* `3. 파이토치로 구현한 논리 회귀.ipynb`
* `3(2). 논리회귀 복습.ipynb`
* `텐서플로우.ipynb` : TensorFlow 기본 실습

### 2. 퍼셉트론과 다층 퍼셉트론

* `5. 딥러닝: 퍼셉트론과 다층 퍼셉트론.ipynb`
* `5(2). 다층 퍼셉트론 복습.ipynb`

### 3. 손글씨 숫자(MNIST) 분류

* `4. 손글씨 숫자 데이터셋.ipynb`
* `4(2). 손글씨 숫자 데이터셋 복습.ipynb`
* `8. 손글씨 도형 분류하기.ipynb`
* `8(2). 손글씨 도형 분류 복습.ipynb`

### 4. CNN 및 이미지 분류

* `7. CNN.ipynb`
* `9. Alexnet 구현하기.ipynb`
* `9(2). Alexnet 복습.ipynb`
* `9(3). Alexnet 구현_CIFAR10.ipynb`

### 5. 사전 학습 모델 활용 (전이학습)

* `12. 산타와 일반인 분류.ipynb`
* `12(2). 산타와 일반인 분류 VGG19 적용.ipynb`
* `12(3). 산타와 일반인 분류 VGG19 구현.ipynb`

### 6. 다양한 데이터셋 실습

* `6. Multi-class Weather Dataset.ipynb`
* `6(2). Multi-class Weather Dataset 복습.ipynb`
* `6(2). Multi-class Weather Dataset 주석 버전.ipynb`
* `10. Alien vs. Predator 데이터셋.ipynb`
* `10(2). Alien vs Predator 복습.ipynb`
* `11. Surface Crack Detection 데이터셋.ipynb`



##  사용 기술

* **프레임워크**: PyTorch, TensorFlow/Keras
* **모델**: Linear Regression, Logistic Regression, Perceptron, MLP, CNN, AlexNet, VGG19
* **데이터셋**: MNIST, CIFAR-10, Weather Dataset, Alien vs Predator, Surface Crack Detection, Custom (산타 vs 일반인)



##  학습 목표

* PyTorch와 TensorFlow 기본 문법 학습
* 퍼셉트론 → MLP → CNN → AlexNet/VGG19 순으로 모델 심화 학습
* 전이 학습(Transfer Learning) 실습
* 다양한 실제 데이터셋을 활용한 이미지 분류 경험 쌓기
