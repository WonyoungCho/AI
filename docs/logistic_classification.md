# Logistic Classification

## Binary Classification

0과 1의 값을 같는 Sigmoid function을 가정해 볼 수 있다.

g(z) = 1/(1+exp(-z))

## Cost Function

가정한 모델이 exponential의 형태이기 때문에 cost function을 log 함수로 생각할 수 있다. 

> -log(H(x))   : y=1

> -log(1-H(x)) : y=0
