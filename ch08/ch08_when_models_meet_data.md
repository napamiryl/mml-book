# Chapter 8 - When Models Meet Data

## 8.1 Data, Models, and Learning
- Concept: data as vectors in feature space
- Definition: predictor / hypothesis class
- Concept: training vs. generalisation
- Definition: overfitting vs. underfitting

## 8.2 Empirical Risk Minimization
- Definition: loss function
- Definition: empirical risk (average loss over training data)
- Concept: minimising empirical risk as a proxy for true risk
- Definition: regularisation (penalising model complexity)
- Concept: bias-variance trade-off

## 8.3 Parameter Estimation
- Method: maximum likelihood estimation (MLE)
- Method: maximum a posteriori (MAP) estimation
- Relationship: MAP with Gaussian prior = L2-regularised MLE

## 8.4 Probabilistic Modeling and Inference
- Definition: probabilistic model (joint distribution over data and parameters)
- Concept: posterior inference
- Definition: predictive distribution (marginalising over parameters)

## 8.5 Directed Graphical Models
- Definition: Bayesian network / directed acyclic graph (DAG)
- Concept: conditional independence encoded in graph structure
- Method: reading off (in)dependencies via d-separation

## 8.6 Model Selection
- Problem: choosing between models of different complexity
- Method: nested cross-validation
- Concept: Bayesian model selection via marginal likelihood (evidence)
- Concept: model evidence as a balance between fit and complexity
