## Lecture 2 : Linear Regression

https://hunkim.github.io/ml/


### Predicting exam score : regression

  dataset   
 x  |  y   
 1  |  1   
 2  |  2   
 3  |  3   
 
 ####  (Linear) Hypothesis   
 ![image](https://user-images.githubusercontent.com/13077196/158549736-0c6ceed3-ac30-44df-8b6c-7ad2a2d6b71c.png)

 
많은 실생활 현상들이 Linear 로 설명됨  
여러 linear 수식 중 어떤 선이 데이터에 가장 잘 맞는지 알아내는것 -> linear regression

### 어떤 모델 / hypothesis 가 가장 좋은가?

#### Cost function

모델을 평가할 방법

![image](https://user-images.githubusercontent.com/13077196/158550768-4d67c9e7-ecb3-46d6-898d-b4359c599467.png)

실제 값과 가설에서 세운 값의 차이를 제곱 한 값을 평균냄 ( + - 효과 없앰)

m = 데이터의 개수

![image](https://user-images.githubusercontent.com/13077196/158551448-a009e866-105d-41fa-96ce-1f2e41f8dc5b.png)

=> W 와 b 의 function



Linear regression의 학습 목표 : Cost 를 최소화 하는것 

minimize cost(W,b)


이를 위한 여러 알고리즘들 있음

