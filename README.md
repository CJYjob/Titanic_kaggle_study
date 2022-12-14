# Titanic_kaggle_study
# kaggle adress : https://www.kaggle.com/competitions/titanic/overview

## 2022.09.17 0회차

스터디 참여자 : 최준영, 신희승, 장선영, 배혜빈

이유한님 유튜브와 블로그를 참조해, 데이터 사이언스, 머신러닝 스터디를 시작합니다.(2022.09.24)   
전체에 대한 필사를 진행하고, 각자 맡은 부분을 설명하는 방식으로 초기 진행방식을 잡았습니다.(추후 적절한 방향으로 수정하며 진행할 계획입니다.)   

## 2022.09.24 1회차 모임

# 참조 링크

https://kaggle-kr.tistory.com/17?category=868316

본 튜토리얼을 설명한 강의가 제 유투브에 있으니 참고하시면 됩니다^^   
https://www.youtube.com/channel/UC--LgKcZVgffjsxudoXg5pQ   

## Contents   
### 1. 데이터셋 확인   
#### 1.1 Null data check   
#### 1.2 Target label 확인   
### 2. Exploratory data analysis   
#### 2.1 Pclass   
#### 2.2 Sex   
#### 2.3 Both Sex and Pclass   
#### 2.4 Age   
#### 2.5 Pclass, Sex, Age   
#### 2.6 Embarked   
#### 2.7 Family - SibSp(형제 자매) + Parch(부모, 자녀)   
#### 2.8 Cabin

만약 데이터 사이언스, 머신러닝 또는 캐글에서 어떤 것을 해야하는 지 잘 모르는 newbie 라면, 타이타닉을 하시는 게 가장 좋은 선택입니다.   
타이타닉은 아시다시피, 사상 최대 해난사고로써, 1,500여명의 희생자가 생겼습니다.   
우리는 이 튜토리얼에서 타이타닉에 탑승한 사람들의 신상정보를 활용하여, 승선한 사람들의 생존여부를 예측하는 모델을 생성할 것입니다.   
본 튜토리얼에서는 여러 시각화 도구(matplotlib, seaborn, plotly), 데이터 분석 도구(pandas, numpy), 머신 러닝 도구(sklearn)을 사용할 것입니다.
본 튜토리얼은 캐글에 있는 여러 커널들을 참조하여 만들었습니다. 본 튜토리얼을 공부하신 뒤에, 캐글 타이타닉 컴퍼티션에 존재하는 여러 다른 커널들을 더 공부하시면 됩니다.   
본 튜토리얼은 파이썬 문법에 어려움이 없으셔야 수월할 것입니다. 여기서 사용하는 라이브러리들을 써본 경험이 있으면 좋겠지만, 경험이 없다하더라도 한 줄씩 천천히 적어나가시면 충분히 하실 수 있습니다.   
