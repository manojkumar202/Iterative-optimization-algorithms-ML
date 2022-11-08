# Iterative-optimization-algorithms-ML

A few of various gradient descent algorithms implemented in Python from scratch

# Introduction
In mathematics, gradient descent (also often called steepest descent) is a first-order iterative optimization algorithm for finding a local minimum of 
a differentiable function. The idea is to take repeated steps in the opposite direction of the gradient (or approximate gradient) of the function at 
the current point, because this is the direction of steepest descent.

# Gradient Descent Algorithms (Implemented here)
1) Gradient Descent
2) Adagrad
3) Adam

# How gradient descent applied on a model

1. Initialize weight w and bias b to any random numbers.
2. Pick a value for the learning rate α. The learning rate determines how big the step would be on each iteration.
3. On each iteration, take the partial derivative of the cost function J(w) w.r.t each parameter (gradient). 
4. Apply te gradient descent to update the parameters for the next step

Continue the process until the cost function converges. That is, until the error curve becomes flat and doesn’t change.

If α is very small, it would take long time to converge.
If α is large, it may fail to converge and overshoot the values.

