# Polynomial_Linear_Regression
## Definition
Polynomial Regression is a method used to predict an outcome (dependent variable) based on a curved relationship with one or more input values (independent variables).
> Imagine you want to draw a smooth curve through scattered points on a graph—this method allows you to do that by creating a mathematical equation with powers of the input values (like squares, cubes, etc.).
---

## Simple Example
>If you're trying to predict the growth of a plant based on the amount of water given, but the growth pattern isn't a straight line (like more water always equals more growth), a curved line might describe the relationship better. Polynomial Regression can model that curve.
>It can also be use in predicting disease spread, 
---

## Formula
> $y=β 
0
​
 +β 
1
​
 x+β 
2
​
 x 
2
 +β 
3
​
 x 
3
 +⋯+β 
n
​
 x 
n
 +ϵ$

## Here:
> + β0 ,β1 ,…,βn : Coefficients of the polynomial.
> + $x,x 
2
 ,x 
3
 ,…,x 
n$ : Features derived from the original 
𝑥
x.
> ϵ: Error term.
---
## Why is it still call Linear?
> It is because of the coefficient present in the formula. Polynomial regression is called linear regression because, despite including non-linear terms (e.g., 
𝑥2,𝑥3), the model is linear in the parameters (coefficients). The relationship between the coefficients (𝛽0,𝛽1,𝛽2,…) and the outcome (𝑦) is linear.
> The non-linearity comes from the input features (e.g.,𝑥2,𝑥3), but the model still solves for the coefficients using linear techniques.










