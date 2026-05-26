# Formula Sheet: Industrial Statistics and Optimization

## Control Charts

- Xbar chart: `CL=Xbarbar`; limits use chart constant and `Rbar` or `sbar`.
- R chart: `CL=Rbar`; limits use `D3 Rbar`, `D4 Rbar`.
- p chart: `CL=pbar`; limits `pbar ± 3 sqrt(pbar(1-pbar)/n)`.
- np chart: `CL=npbar`; limits `npbar ± 3 sqrt(npbar(1-pbar))`.
- c chart: `CL=cbar`; limits `cbar ± 3 sqrt(cbar)`.

## Acceptance Sampling

- OC curve: probability of accepting lot as a function of defect proportion.
- Single sampling plan: accept if defectives `<=c`.
- AOQ, ASN, ATI describe outgoing quality, expected sample size, and total inspection.

## Reliability

- `R(t)=P(T>t)=1-F(t)`
- `h(t)=f(t)/R(t)`
- Series system: product of reliabilities.
- Parallel system: `1 - product failure probabilities`.

## Optimization

- LP: variables, objective, constraints, non-negativity.
- Duality: primal resources correspond to dual prices.
- Transportation: balance, initial feasible solution, optimality test.
- Assignment: Hungarian method.
- Game: check saddle point, else mixed strategy.
- Queue: identify model, check stability, compute `L, Lq, W, Wq`.
