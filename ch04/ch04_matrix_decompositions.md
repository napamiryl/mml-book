# Chapter 4 - Matrix Decompositions

## 4.1 Determinant and Trace
- Definition: determinant (det or |A|)
- Properties: det(AB) = det(A)det(B), det(Aᵀ) = det(A)
- Theorem: Laplace expansion
- Definition: trace (sum of diagonal elements)
- Properties of trace: tr(A+B) = tr(A)+tr(B), tr(AᵀB) = tr(BᵀA)
- Concept: characteristic polynomial

## 4.2 Eigenvalues and Eigenvectors
- Definition: eigenvalue and eigenvector (**Ax = λx**)
- Method: finding eigenvalues via characteristic polynomial
- Definition: eigenspace Eλ
- Theorem: eigenvectors of distinct eigenvalues are linearly independent
- Definition: algebraic vs. geometric multiplicity

## 4.3 Cholesky Decomposition
- Theorem: Cholesky decomposition (**A = LLᵀ** for SPD matrices)
- Definition: symmetric positive definite (SPD) matrix

## 4.4 Eigendecomposition and Diagonalization
- Theorem: eigendecomposition **A = PDP⁻¹**
- Condition: when a matrix is diagonalizable
- Application: computing matrix powers

## 4.5 Singular Value Decomposition (SVD)
- Theorem: SVD **A = UΣVᵀ** (exists for any matrix)
- Definition: singular values, left/right singular vectors
- Relationship: SVD and eigendecomposition of **AᵀA** and **AAᵀ**

## 4.6 Matrix Approximation
- Theorem: Eckart-Young theorem (best low-rank approximation via truncated SVD)

## 4.7 Matrix Phylogeny
- Overview: relationships between special matrix types (SPD, normal, orthogonal, diagonal…)
