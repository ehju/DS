# Lecture 1 : Machine Learning basics

https://hunkim.github.io/ml/


## What is MachineLearning

일종의 SW 

Explicit programming (명시적 프로그래밍 )  : 입력에 따른 결과가 나오게 함 ( rule 기반)

문제점 : too many rules ->  Data를 보고 Program이 스스로 학습하게 하자  

ML :  field of study that gives computers the ability to learn without being explicitly programmed


## Learning

### Supervised  Learning : 
- learning with labeled examples - training set 
- 레이블이 된 training set 을 가지고 학습
- image labeling , email span filtering , predicting exam score



### Unsupervised Learning : 
- unlabeled data
- 비슷한것들끼리 모으기 :  Google news grouping / Word clustering 


### Training data set
x     |   y  
-------------  
3,6,9 |   3       =>   ML  
1,2,3 |   2  
2,3,5 |   1  
traiing data set 으로 모델을 만들고  

x[2,1,6] => ML -> ?  

새로운 data 의 결과 예측  

### Types of superviesed learning

- regression  
predictiong examscore  based on time spent 

- binary classification (분류)  
pass / nonpass based on time spent

- Multi-label classification  
 A, B, C, D, F  based on time spent




