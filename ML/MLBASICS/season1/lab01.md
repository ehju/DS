## Tenserflow

#### TensorFlow is an open source software library for numerical computation using data flow graphs.

Google 에서 만든 Machine intelligence 를 위한 opensource library

Most Popular tool for ML/DL

python 으로 프로그래밍 가능

이외 pytorch , Keras 등 있음 ( https://www.upgrad.com/blog/top-deep-learning-frameworks/ )


### Data Flow Graph?

![image](https://user-images.githubusercontent.com/13077196/158571502-9606ba96-a831-4c74-80e9-261cd67391bb.png)


Graph : node 와 node 를 연결하는 edge 로 구성  
NODE : 하나의 operation  
EDGE : 데이터 arrays (tensors)  
그래프 위에서 tensors( data) 가 돌아다니는 -> tensorflow!


### Installing TensorFlow
설치는  홈페이지 등 참고

Google Colab : 클라우드 기반의 Jupyter notebook 개발환경   
https://theorydb.github.io/dev/2019/08/23/dev-ml-colab/




** 강의는 TensorFlow 1.0 기준이지만 현재 2022.03 TensorFlow는 2.0 임
Tensorflow 2.0 코드 : https://github.com/hunkim/DeepLearningZeroToAll/tree/master/tf2

Tensorflow 1.0과 2.0은 차이가 크다고 함

### Computational Graph 구현
![image](https://user-images.githubusercontent.com/13077196/158772590-41f52a37-efc8-4182-a376-7f76bf9c2f72.png)

Tensorflow 를 사용하여 Machine learning 알고리즘을 만드는경우,   
ML model designs 을 Tensorflow Computational Graph로 변환하여 Runtime에 제출한다.   
그러면 Runtime이 이를 수행한다.   


![image](https://user-images.githubusercontent.com/13077196/158588741-ac8651ab-8872-4a72-89a1-9a0964f8bb18.png)

Computational Graph란 ? 노드의 작업을 설명하는 방향그래프  



reference:  
https://medium.com/ai%C2%B3-theory-practice-business/tensorflow-1-0-vs-2-0-part-1-computational-graphs-4bb6e31c1a0f  
https://towardsdatascience.com/whats-new-in-tensorflow-2-0-ce75cdd1a4d1  




