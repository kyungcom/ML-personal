# ML-personal

## What is this?
```
kt AIVLE 스쿨에서 배운 machine learning을 복습하기 위해서 진행해본 프로젝트입니다.
1. regression: 스마트폰 가격측정 예측(1~20으로 원래는 범주형이지만 수치형으로 진행해봄)
2. classification: 타이타닉 생존자 예측
```

## 2. 프로젝트 구성
### 2-1. regression
* 스마트폰 데이터
* LinearRegression
* KNeighborsRegressor
* DecisionTreeRegressor
* SVR
* RandomForestRegressor
* GridSearchCV

### 2-2. Classification
* LogisticRegression
* KNeighborsClassifier
* DecisionTreeClassifier
* SVC
* RandomForestClassifier
* GridSearchCV


## 실행결과
regression: r2_score기준 RandomForest가 가장 성능이 좋았으며
Classification: accuracy기준 RandomForest + GridSearch 가 가장 성능이 좋았고, 딥러닝과 비교했을때도 성능이 더 높았다.

## License
````````
The MIT License

Copyright (c) 2022 ParkInho

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
``````````