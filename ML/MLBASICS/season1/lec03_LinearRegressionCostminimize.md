## Linear Regression 의 Cost 최소화 알고리즘의 원리

Linear regression의 목표 : Cost 를 최소화

### What cost(W) looks like ?
![image](https://user-images.githubusercontent.com/13077196/158552788-6b565bd5-63a5-4364-a311-3e6b4563ef9e.png)

m=3 일때

W=0, cost(W) = 4.67
W=1, cost(W) = 0  
W=2, cost(W) = 4.67 

![image](https://user-images.githubusercontent.com/13077196/158559291-4a6b6012-89d7-470c-99ae-75e3d3809589.png)

cost 가 최소값이 되는 W,b 을 기계적으로 찾아내야 함

### Gradient descent algorithm

- Gradient : 경사  descent : 내려감
- Minimize cost function
- 많은 Minization problem 에 사용됨
- For given cost function, cost(W,b)  -> find W,b to minimize cost
- 함수의 경사를 보고 경사를 따라서 내려가는 원리


### How it works  
- start at any value
- Keep changing W and b a little bit try and reduce cost (W,b)
- select gradient which reduce cost(W,b) most possible
- Repeat

미분을 이용

### Formal definition
![image](https://user-images.githubusercontent.com/13077196/158560750-a465f085-fa64-433a-86cb-d3efc007c9aa.png)

α 는 learning rate 이며 상수 어느정도 크기로 이동할지 나타냄  
기울기가 양수일때 음의방향, 음수일때 양의 방향으로 이동  
Gradient 의 크기와 방향 모두 이용

![image](https://user-images.githubusercontent.com/13077196/158560878-2f4b0806-1bc1-4e16-a460-3554971d01b3.png)

미분 과정을 통해 얻은 최종 식





### convex function
![image](https://user-images.githubusercontent.com/13077196/158562867-656d14a1-3d4b-4fd3-8c30-9a12b76f92b9.png)

cost function의 모양이 convex function이 된다면 descent algorithm을 통해 항상 답을 찾을 수 있다.

![image](https://user-images.githubusercontent.com/13077196/158562710-1a48fbb6-f18c-4217-90f0-261c4a1f6a9d.png)

convex function 이 아니라면 알고리즘이 잘 동작하지 않을 수 있다.

