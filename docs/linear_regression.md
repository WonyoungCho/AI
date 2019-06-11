# Linear Regression

데이터에 맞는 선형 모델을 가정을 하는 것.

H(x) = W x + b

* b : bias

## Cost Function

위 가정에서 구한 모델 H(x)와 실제 데이터 값의 차이를 제곱하여 데이터 갯수로 나눈 값.


## Minimize Cost

Cost 값이 최소가 되는 모델을 찾는 것이 목표.


## Gradient Descent Algorithm

기울기 W 와 cost function의 이분 값의 차이를 통해 cost 값이 최소가 되는 모델을 찾는 알고리즘.

# Multi-variable Linear Regression

여러개의 변수가 있을 때 가정할 수 있는 선형 모델.

H(x1,x2,x3) = w1 x1 + w2 x2 + w3 x3 + b

이것을 matrix 형태로 쓸 수 있다.

H(X) = X W

- (x1, x2, x3) 값을 instance 라고 부른다.
