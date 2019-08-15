# Numerical Computation

## Introduction
Numerical computate refers to the process of solving mathematical problems by methods that update estimates of solutions by way of an iterative process, rather than analytically deriving a formula which would provide a solution to the problem.  In this space you'd find optimization and solving systems of linear equations.  

## 4.1 Overflow and Underflow
Many of the problems that numerical computation faces is that algorithms derived theoretically don't have always have a one-to-one translation to a computer.  Rounding errors are a great example and can compound across multiple computations.  A form of rounding error is called **underflow** and this is where numbers near zero are rounded to zero.  The opposite is **overflow**.  Overflow occurs when large numbers are approximated as positive or negative infinity.  In the context of deep learning, the softmax function $softmax(x_{i})$


## 4.2 Poor Conditioning    
**Conditioning** is defined as the pace at which a function changes w.r.t. small changes in its inputs.  Those that explode on minor tweaks to their inputs are troublesome for scientific computing.  
