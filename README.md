# Implementation-from-scratch-of-svm-and-gradient-descent
class project

## For the support vector machine implémentation we used a simple binary classification probleme to solve
We implement some svm with different parameter 

## For the gradient descent
we want to find the minimum of a function
### the three stop conditions used are:
-norm of the gradient inferior than an epsilone of the order 10E-8

-norm of xk+1 - xk inferior than an epsilone of the order 10E-8

-norm of f(xk+1) - f(xk) inferior than an epsilone of the order 10E-8
### We tried:
-descent of the gradient with a constant step

-descent of the gradient with a optimal step:
  
   --calculation of the step by finding the minimum of the function by iterative method 
  
   --calculation of the step by finding the minimum of the function by exact method 

-descent of the gradient with a direction of descent calculated by the newton method

-descent of the gradient with a direction of descent calculated by the stochastic method
