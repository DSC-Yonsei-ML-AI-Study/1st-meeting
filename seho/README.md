# Keywords of week 1
- What is ML?
- ML vs Rule-based
- AI, ML, Deep Learning
- Type of ML (Classification, Clustering, Regression, Sequence Prediction)
- Kind of Bias (Interaction bias, latent bias, selection bias)


## What is Machine Learning
> Machine learning (ML) is the scientific study of algorithms and statistical models that computer systems use to perform a specific task **without using explicit instructions, relying on patterns and inference instead.** It is seen as a subset of artificial intelligence... 
-Wikipedia

 즉, 사람이 일일이 명령(프로그램)하지 않고, 데이터, 패턴 또는 직관(?)에 따라 일을 수행하는 알고리즘 또는 통계적 모델을 말한다.



## Rule-Based Learning ?
> Rule-based machine learning (RBML) is a term in computer science intended to encompass any machine learning method that identifies, learns, or evolves 'rules' to store, manipulate or apply.[1][2][3]

 저장하고, 조정하고, 적용하는 'rule' 을 학습, 발전, 발견하는 머신러닝 방법을 지칭.


> The defining characteristic of a rule-based machine learner is the identification and utilization of a set of relational rules that collectively represent the knowledge captured by the system.

 어떤 예측을 하는데 범용적인 하나의 모델을 찾는 다른 머신러닝 방법과 다르게, rule-based learning은 rule의 집합을 식별하고 활용한다고 한다.


> Rule-based machine learning approaches include learning classifier systems,[4] association rule learning,[5] artificial immune systems,[6] and any other method that relies on a set of rules, each covering contextual knowledge.

   대표적인 예로 Learning classifier, association rule, artificial immune system 등이 있다고 한다...


> While rule-based machine learning is conceptually a type of rule-based system, **it is distinct from traditional rule-based systems**, which are often hand-crafted, and other rule-based decision makers. This is because rule-based machine learning **applies some form of learning algorithm to automatically identify useful rules**, rather than a human needing to apply prior domain knowledge to manually construct rules and curate a rule set.
-Wikipedia

  Rule-based machine learning은 자동으로 유용한 rule을 찾아내는 학습 알고리즘이 적용되어 있기 때문에, 사람이 직접 rule을 지정하는 rule-based system과는 다르다.
    
     
   
## AI, ML, Deep Learning ?
![image](https://user-images.githubusercontent.com/45113485/68264043-f4c10a00-008a-11ea-8ee5-d91f31dc9196.png)


## Type of ML (Classification, Clustering, Regression, Sequence Prediction)
### Classification (분류)
 지도학습의 일종으로, 어떤 분류에 대한 정보(레이블 종류, 속성 등)를 이미 가지고 있을 때 특정 개체를 분류하는 것. 
 비지도학습이며 사전 정보가 없는 군집화(Clustering)과 구별된다.
 
### Clustering
 사전에 레이블이 알려져 있지 않은 상태에서 데이터의 속성이 비슷한 것을 묶는 것.
 

### Regression
 독립변수에 대한 종속변수의 값에 따라 가중치를 조정(학습)하여 회귀 모델을 만들고, 독립 변수들이 주어졌을 때 종속변수를 예측하는 방법.


### Sequence Prediction
 순서가 있는 데이터를 예측하는 것이다. 예를 들면 사람이 움직이는 좌표 데이터 (1,1) (1,2) (1,3) ... 이 주어졌을 때 다음 움직일 위치를 예측하는 것이다.
 
 
 
## Kind of Bias (Interaction bias, latent bias, selection bias)
사람이 일일이 코딩을 하는 전통적인 방법과 다르게 Machine Learning은 데이터로 부터 패턴 등을 학습한다. 그래서 그렇게 생성된 모델은 사람의 편견(bias)이 개입되지 않았을 것이라고 생각하기 쉽다. 하지만 다양한 경로로 우리의 bias는 우리가 만든 기술의 일부로 녹아든다.
예를 들면 다음 세 가지의 경우가 있다. 

### Interaction bias
 인공지능 시스템이 신발을 그려달라고 했을 때, 일반적인 운동화만 그려준다면 하이힐 역시 신발임은 학습하지 못할 것이다.


### latent bias
 물리학자가 어떻게 생겼는지에 대해 학습을 시킨다고 할 때, 과거 물리학자의 사진으로 학습을 시킨다면(대부분이 남자), 그 알고리즘은 물리학자에 대해서 남성으로 치우친 bias를 가지게 될 것이다.


### selection bias
 얼굴 인식을 한다고 할 때, 대부분이 백인의 사진으로만 학습했다면 그 모델은 백인에 편향될 수 밖에 없다.
