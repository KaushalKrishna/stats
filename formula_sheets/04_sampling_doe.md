# Formula Sheet: Sampling and DOE

## Sampling

| Design | Estimator / reminder |
|---|---|
| SRSWOR mean | `ybar`; `Var(ybar)=(1-f)S^2/n` |
| SRSWR mean | `Var(ybar)=S^2/n` style without FPC |
| Stratified mean | `ystbar=sum W_h ybar_h` |
| Stratified variance | `sum W_h^2 (1-f_h) S_h^2/n_h` |
| Optimum allocation | `n_h proportional N_h S_h` for equal costs |
| Ratio estimator | `yr = xbar_pop * ybar/xbar` |
| Regression estimator | `yreg = ybar + b(Xbar-xbar)` |
| HT total | `sum_{sample} y_i/pi_i` |

## DOE

General ANOVA route:

1. Correction factor.
2. Total SS.
3. Treatment/block/row/column SS as applicable.
4. Error SS by subtraction.
5. MS = SS/df.
6. F = relevant MS / MSE.

## BIBD Identities

- `bk=vr`
- `lambda(v-1)=r(k-1)`
- `b>=v` for many standard BIBD settings.
