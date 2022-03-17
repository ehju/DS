## Multivariable Linear Regression

### Linear Regression 설계

1. Hypothesis  -> 가설  

2. Cost function ( Loss function )  -> model 을 평가  

3. Gradient descent algorithm  -> cost 를 최적화


### Multi-variable Linear Regression

![image](https://user-images.githubusercontent.com/13077196/158775643-a1b6f6a1-cede-4c5c-b072-d26e7fc4d660.png)

variable 이 여러개 인 경우

H(x) = Wx + b

Hypothesis 

![image](https://user-images.githubusercontent.com/13077196/158775860-fde96d26-fec3-4ddf-9762-217f690515c1.png)




Cost function

![image](https://user-images.githubusercontent.com/13077196/158775931-914d6add-e796-492b-b232-95b8ac974492.png)


### Matrix ( 행렬 ) 

#### Matrix multiplication 곱셈  
 https://www.mathsisfun.com/algebra/matrix-multiplying.html 

#### Hypothesis using matrix


![image](https://user-images.githubusercontent.com/13077196/158776141-3707e77c-ba00-4833-b271-ea66db31537d.png)
![image](https://user-images.githubusercontent.com/13077196/158776850-fd33c872-5d13-433d-9ea4-d758cd8f4857.png)


Matrix 를 사용해 복잡한 Hypothesis  를 간단하게 표현 가능.

H(X) = X W     
X:data   W : weight


### Hypothesis using matrix + Data
![image](https://user-images.githubusercontent.com/13077196/158777835-e83624e8-f328-4f50-ab8e-46a0426ee2db.png)


각 instance 를 대입한 식을 행렬로 한번에 얻게 됨. 

#### W 의 크기 결정
![image](https://user-images.githubusercontent.com/13077196/158778702-43936da5-2d9f-4263-a185-1d0747356f59.png)


[ # instance , #   x variable ]   * [ ? , ? ]  = [#instance , 1 ( Y, linear Regression) ]

W 의 크기 : [# x , # y ]

#instance는 데이터의 개수에 따라 가변하는 값




