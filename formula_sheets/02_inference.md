# Formula Sheet: Statistical Inference

## Estimation

| Task | Formula / route |
|---|---|
| MLE | Maximize `L(theta)=product f(x_i;theta)` or log-likelihood |
| Sufficiency | Factorization: `L(theta;x)=g(T,theta)h(x)` |
| Unbiasedness | Show `E(T)=theta` or target function |
| Consistency | Show convergence in probability, often by WLLN/Chebyshev |
| CRLB | `Var(T)>= [g'(theta)]^2 / I(theta)` |
| Fisher information | `I(theta)=E[(d/dtheta log f)^2]` or `-E[d^2/dtheta^2 log f]` |
| UMVU | Complete sufficient statistic + unbiased function + Lehmann-Scheffe |

## Testing

| Test family | Trigger |
|---|---|
| Neyman-Pearson | Simple vs simple hypotheses |
| UMP / MLR | One-sided alternative in exponential family |
| LRT | Composite hypotheses or nested parameter spaces |
| UMPU | Two-sided single-parameter exponential-family style tests |
| Nonparametric | Distribution-free rank/sign/KS/run/median tests |
| SPRT | Sequential testing with likelihood ratio boundaries |

## SPRT

- Continue while `B < Lambda_n < A`.
- Accept `H1` if `Lambda_n >= A`.
- Accept `H0` if `Lambda_n <= B`.
- Approximate boundaries: `A=(1-beta)/alpha`, `B=beta/(1-alpha)`.
