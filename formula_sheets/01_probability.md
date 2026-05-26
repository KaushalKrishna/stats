# Formula Sheet: Probability

## Distributions

| Item | Formula / reminder | Use |
|---|---|---|
| Distribution function | `F(x)=P(X<=x)` | Transformations and probability intervals |
| Marginal density | `f_X(x)=integral f(x,y) dy` | Start of every joint-density question |
| Conditional density | `f(y|x)=f(x,y)/f_X(x)` | Conditional expectation/variance |
| Independence | `f(x,y)=f_X(x)f_Y(y)` | Joint distribution checks |
| MGF | `M_X(t)=E(e^{tX})` | Moments and distribution recognition |
| PGF | `G_X(s)=E(s^X)` | Discrete non-negative integer variables |
| CF | `phi_X(t)=E(e^{itX})` | Distribution recognition and limits |

## Moments

- `E(aX+b)=aE(X)+b`
- `Var(aX+b)=a^2 Var(X)`
- `Cov(X,Y)=E(XY)-E(X)E(Y)`
- `Var(X+Y)=Var(X)+Var(Y)+2Cov(X,Y)`
- `E(Y)=E[E(Y|X)]`
- `Var(Y)=E[Var(Y|X)] + Var[E(Y|X)]`

## Inequalities and Limits

- Markov: `P(X>=a) <= E(X)/a` for non-negative `X`.
- Chebyshev: `P(|X-mu|>=epsilon) <= sigma^2/epsilon^2`.
- WLLN route: show `Var(Xbar)->0`, then use Chebyshev.
- CLT route: standardize the sum/sample mean and approximate by `N(0,1)`.

## Transformation Checklist

1. Find range of transformed variable.
2. Prefer CDF if transformation is many-to-one.
3. Use Jacobian for one-to-one transformations.
4. Check final density integrates to 1.
