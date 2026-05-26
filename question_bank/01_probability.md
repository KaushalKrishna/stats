# Question Bank: Probability

Use this file by family. Do not solve it top-to-bottom in one sitting. Pick a family, learn its trigger, then write 3-5 answers in exam format.

## MUST COVER: Joint distributions

**Recognition trigger:** joint pdf/pmf, support, marginal, conditional.

**Standard framework:** Draw support, normalize, marginalize, condition, compute..

**Practice questions**

1. Let `f(x,y)=c(x+y)` on `0<x<1, 0<y<1`. Find `c`, marginals, `E(Y|X=x)`, and `Cov(X,Y)`.
2. Let `f(x,y)=c x` on `0<x<y<1`. Find the marginal density of `Y` and `P(X<Y/2)`.
3. A joint pmf is proportional to `x+y` for `x,y=1,2,3`. Find the constant and test independence.
4. Let `f(x,y)=2e^{-(x+y)}` on `0<x<y<infinity`. Find `P(Y<1)` and `P(Y>3X|Y>2X)`.
5. Given a bivariate density on a triangular region, derive `f_{X|Y}(x|y)` and compute `E(X|Y=y)`.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: Conditional expectation

**Recognition trigger:** E(Y|X=x), Var(Y|X=x).

**Standard framework:** Find conditional density, integrate under conditional law..

**Practice questions**

6. For a joint density on `0<x<1, 0<y<x`, compute `E(Y|X=x)` and `Var(Y|X=x)`.
7. Show that `E(Y)=E[E(Y|X)]` for a given two-variable density by direct computation.
8. For a discrete joint distribution table, compute both conditional expectations and compare with unconditional means.
9. Given `Y|X=x ~ Poisson(x)` and a distribution for `X`, compute `E(Y)` and `Var(Y)`.
10. Use conditional expectation to find the mean and variance in a two-stage coin-toss experiment.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: Transforms

**Recognition trigger:** distribution of X^2, ratios, sums.

**Standard framework:** Use CDF for many-to-one; Jacobian for one-to-one..

**Practice questions**

11. Let `X` have density proportional to `x+2` on `-2<=x<=3`. Find the distribution and density of `Y=X^2`.
12. Let `X` and `Y` be independent exponentials. Find the density of `X/Y`.
13. Find the distribution of `U=X+Y` and `V=X/(X+Y)` for independent gamma variables with common scale.
14. If `X` is uniform on `(0,1)`, find the density of `-log X` and identify it.
15. Use the CDF method to find the density of `Y=(X-a)^2` when the support crosses `a`.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: Moments and generating functions

**Recognition trigger:** MGF, PGF, CF, moments.

**Standard framework:** Differentiate generating function or match known form..

**Practice questions**

16. Given `M_X(t)=exp(3(e^t-1))`, identify the distribution and find mean and variance.
17. Given a PGF `G(s)=(1-p)/(1-ps)`, identify the distribution and compute the first two moments.
18. Use the characteristic function `exp(-t^2+2it)` to identify the distribution.
19. If `E(X^n)` is specified for all `n`, infer the support and probabilities of a finite-valued random variable.
20. Derive the MGF of a sum of independent variables and apply it to a binomial distribution.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: Limit theorems

**Recognition trigger:** CLT, WLLN, SLLN, convergence.

**Standard framework:** Standardize, check theorem conditions, conclude..

**Practice questions**

21. Use Chebyshev's inequality to prove WLLN for iid variables with finite variance.
22. Let `X_n ~ Poisson(n theta)`. Use CLT to approximate `P(|X_n/(n theta)-1|<0.1)`.
23. For iid uniforms, approximate the probability that their sum exceeds a given value.
24. Distinguish convergence in probability and distribution using a concrete example.
25. State conditions of Lindeberg-Levy CLT and apply them to a standardized sample mean.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## GOOD TO COVER: Inversion and characteristic functions

**Recognition trigger:** jumps, discrete distribution recovery.

**Standard framework:** State theorem, evaluate discontinuities..

**Practice questions**

26. Solve a numerical UPSC-style question on inversion and characteristic functions and state the final interpretation.
27. Derive the main formula or ANOVA/table structure used in inversion and characteristic functions and name all assumptions.
28. Compare inversion and characteristic functions with a nearby syllabus family and illustrate with a small example.
29. Write a short note on inversion and characteristic functions with formula, use case, and limitation.
30. Answer a mixed 15-mark question where inversion and characteristic functions is the main hidden trigger.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## GOOD TO COVER: Vector random variables

**Recognition trigger:** joint transformations.

**Standard framework:** Map region and use Jacobian..

**Practice questions**

31. Solve a numerical UPSC-style question on vector random variables and state the final interpretation.
32. Derive the main formula or ANOVA/table structure used in vector random variables and name all assumptions.
33. Compare vector random variables with a nearby syllabus family and illustrate with a small example.
34. Write a short note on vector random variables with formula, use case, and limitation.
35. Answer a mixed 15-mark question where vector random variables is the main hidden trigger.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.
