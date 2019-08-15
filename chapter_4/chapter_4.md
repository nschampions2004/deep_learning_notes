# Numerical Computation

## Introduction
Numerical computate refers to the process of solving mathematical problems by methods that update estimates of solutions by way of an iterative process, rather than analytically deriving a formula which would provide a solution to the problem.  In this space you'd find optimization and solving systems of linear equations.  

## 4.1 Overflow and Underflow
Many of the problems that numerical computation faces is that algorithms derived theoretically don't have always have a one-to-one translation to a computer.  Rounding errors are a great example and can compound across multiple computations.  A form of rounding error is called **underflow** and this is where numbers near zero are rounded to zero.  The opposite is **overflow**.  Overflow occurs when large numbers are approximated as positive or negative infinity.  In the context of deep learning, the softmax function $softmax(x_{i})$


## 4.2 Poor Conditioning    
**Conditioning** is defined as the pace at which a function changes w.r.t. small changes in its inputs.  Those that explode on minor tweaks to their inputs are troublesome for scientific computing.  Let's take a look at a function: ![equation](https://latex.codecogs.com/gif.latex?f%28%5Ctextbf%7Bx%7D%29%20%3D%20%5Ctextbf%7BA%7D%5E%7B-1%7D%5Ctextbf%7Bx%7D).  When A is in the Real space and has eigenvalue decomposition, we say its **condition number** is ![equation](https://latex.codecogs.com/gif.latex?max_%7Bi%2Cj%7D%7C%5Cfrac%7B%5Clambda_%7Bi%7D%7D%7B%5Clambda_%7Bj%7D%7D%7C).  This value is the ratio of the magnitude of the largest and smallest eigenvalues.  You can expect that when this ratio is large, the matrix inversion is _very_ sensitive to error in the input.  

## 4.3 Gradient-Based Optimization
Optimiazation is apart of many deep learning operations.  You use it to minimize or maximize some function ![equation](https://latex.codecogs.com/gif.latex?f%28%5Ctextbf%7Bx%7D%29).  
