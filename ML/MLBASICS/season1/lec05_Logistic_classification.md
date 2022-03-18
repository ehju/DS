# Logistic ( regression ) classification

Classification 알고리즘 중 정확도가 높은 알고리즘으로 알려져 있음  
Neural network / deep learning을 이해하는데 중요함  

## Classification


Regression이 output 값을 예측하는 것이라면   
Classification은  Binary , 즉 둘 중 하나를 고르는 것    
ex) Spam 메일 분류  , Facebook feed show /hide , Credit Card fraud detection , 영상진단 ( 정상/비정상) , 주식 매수 매도  
category를 1,0 으로 나누어 예측 ( spam : 1 , ham : 0 )  


idea : linear regression을 바탕으로 기준점을 정해서 구분 


<img src="https://user-images.githubusercontent.com/13077196/159016837-a6be2d0b-3cf7-48cd-a13d-fb8910936232.png" height="300"> </img>


문제점 :    
특정 값에 의해 모델이 크게 변경 되며 정확도가 떨어질 수 있음.    
linear regression 이 0 ~ 1 범위를 벗어날 수 있음.   





## Logistic Hypothesis
![image](https://user-images.githubusercontent.com/13077196/159012703-e675227a-6a0d-4415-b073-72c948cbdcb6.png)


logistic function / sigmoid function 은 Y를 0 ~ 1  사이 의 값으로 압축함.


![image](https://user-images.githubusercontent.com/13077196/159014828-1c702856-651c-4e2b-bf4a-69216be9a20f.png)

(http://www.saedsayad.com)








## Cost function

logistic Hypothesis 에서 Linear regression과 같은 Cost function을 사용하면  
local minimum 이 발생하여 Gradient descent 알고리즘을 사용할 수 없음. 



exponential 과 반대되는 log 함수를 사용하는 Idea





##  Gradient 


참고 : http://1ambda.github.io/data-analysis/machine-learning-week-3/
