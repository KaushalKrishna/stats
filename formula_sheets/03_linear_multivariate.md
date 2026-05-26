# Formula Sheet: Linear and Multivariate

## Linear Model

- Model: `Y = X beta + e`
- Assumptions: `E(e)=0`, `Var(e)=sigma^2 I` unless generalized.
- Normal equations: `X'X beta_hat = X'Y`
- Estimator: `beta_hat=(X'X)^(-1)X'Y` when full rank.
- Variance: `Var(beta_hat)=sigma^2 (X'X)^(-1)`.
- Residual SS: `SSE=Y'Y-beta_hat'X'Y`.

## Estimability

- `l'beta` is estimable iff `l'` lies in the row space of `X`.

## Multivariate Normal

If `X ~ N_p(mu, Sigma)` and `Y=AX`, then:

- `Y ~ N(A mu, A Sigma A')`

Partitioned conditional normal:

- `E(X1|X2=x2)=mu1 + Sigma12 Sigma22^{-1}(x2-mu2)`
- `Var(X1|X2)=Sigma11 - Sigma12 Sigma22^{-1} Sigma21`

## PCA

- Principal components are eigenvector linear combinations of covariance/correlation matrix.
- Variance of component `i` is eigenvalue `lambda_i`.
- Proportion explained: `lambda_i / sum(lambda_i)`.
