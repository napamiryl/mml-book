# Chapter 7 - Continuous Optimization

## 7.1 Optimization Using Gradient Descent
- Definition: unconstrained optimization problem (min f(x))
- Definition: local vs. global minimum
- Definition: stationary point (∇f = 0)
- Algorithm: gradient descent (x ← x - α∇f(x))
- Concept: learning rate / step size
- Variant: stochastic gradient descent (SGD)
- Variant: mini-batch gradient descent

## 7.2 Constrained Optimization and Lagrange Multipliers
- Problem: equality-constrained optimization
- Method: Lagrangian L(x, λ) = f(x) + λg(x)
- Definition: Lagrange multiplier
- Condition: KKT conditions for inequality constraints

## 7.3 Convex Optimization
- Definition: convex set
- Definition: convex function (Jensen's inequality)
- Property: local minimum = global minimum for convex problems
- Definition: convex optimization problem
- Concept: linear programming as a special case
