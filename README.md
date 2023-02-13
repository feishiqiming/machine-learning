# IBA6102 Machine Learning for Business
## Assignment 1 
## Q1
A-> it will rain tomorrow when forecast is not given
B-> the weatherman is forecasting rain for tomorrow
P(A)=5/365=1/73
P(B|A) = 0.9 = P(AB)/P(A)-> P(AB) = 9/730
P(B)= P(-AB)+P(AB)=P(-AB)/P(-A) = 81/730
P(A|B)=P(AB)/P(B) = 1/9

## Q2

f(x,θ) = 1/θ WHEN 0<xi<θ
       =0 other
MLE = argmax 1/θ^n
∂(L(θ))/∂(θ) = -n/θ^n+1 <0
so θ = max<x1,...,xn>

## Q3

a.MLE θ=0.7
MAP θ=0.558

b.MLE θ=0.7
MAP θ=0.664

c.MLE θ=0.7
MAP θ=0.696
