# Logistic Classification

## Binary Classification

0과 1의 값을 같는 Sigmoid function을 가정해 볼 수 있다.

g(z) = 1/(1+exp(-z))

## Cost Function

가정한 모델이 exponential의 형태이기 때문에 cost function을 log 함수로 생각할 수 있다. 

c(H(x),y) = -y log(H(x)) -(1-y) log(1-H(x))

# Multinomial Classification

W X = Y

## Softmax Classification

Sigmoid function을 이용하기 위해서는 Y가 0~1 사이의 값이여야 한다.

Values -> Probabilities

S(y_i) = exp(y_i)/Sum(exp(y_j),j)

> ex) Y = [2.0, 1.0, 0.1]-> S = [exp(2.0), exp(1.0), exp(0.1)]/(exp(2.0)+exp(1.0)+exp(0.1)) = [0.7, 0.2, 0.1]

한 가지 값만 취하는 technique을 One-Hot encoding 이라 한다.

> ex) [0.7, 0.2, 0.1] -> [1, 0, 0]
