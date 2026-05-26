# Question Bank: Statistical Inference

Use this file by family. Do not solve it top-to-bottom in one sitting. Pick a family, learn its trigger, then write 3-5 answers in exam format.

## MUST COVER: MLE

**Recognition trigger:** find MLE, properties.

**Standard framework:** Likelihood, log-likelihood, support, derivative/boundary..

**Practice questions**

1. For iid exponential observations with mean `theta`, find the MLE and show consistency.
2. For iid Bernoulli observations, find the MLE of `theta` and of `theta(1-theta)` by invariance.
3. For iid `Uniform(0,theta)`, find the MLE and discuss bias.
4. For a shifted exponential density with support depending on `alpha`, find the MLEs of `alpha` and `beta`.
5. For iid normal observations with both mean and variance unknown, derive both MLEs.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: Sufficiency and factorization

**Recognition trigger:** sufficient statistic.

**Standard framework:** Factor likelihood into g(T,theta)h(x)..

**Practice questions**

6. For a Poisson sample, use factorization theorem to show `sum X_i` is sufficient for `lambda`.
7. For Bernoulli observations, identify a sufficient statistic and its distribution.
8. Show that one proposed statistic is sufficient while another is not for a simple parametric family.
9. For exponential observations, find a minimal sufficient statistic using likelihood ratios.
10. For normal observations with unknown mean and variance, identify a sufficient statistic.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: Completeness and UMVU

**Recognition trigger:** UMVU, Rao-Blackwell, Lehmann-Scheffe.

**Standard framework:** Find complete sufficient statistic, express unbiased estimator as function of it..

**Practice questions**

11. Find the UMVU estimator of `theta(1-theta)` for Bernoulli observations.
12. For a Poisson sample, find a UMVU estimator of `e^{-lambda}`.
13. Use Rao-Blackwell theorem to improve an unbiased estimator in a Bernoulli model.
14. State Lehmann-Scheffe theorem and apply it to an exponential family example.
15. Show how completeness is used to prove uniqueness of a UMVU estimator.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: CRLB

**Recognition trigger:** minimum variance, information.

**Standard framework:** Compute score/information and apply bound..

**Practice questions**

16. Compute the CRLB for unbiased estimators of `theta` in a Bernoulli sample.
17. Find Fisher information for an exponential sample and state the variance lower bound.
18. Check whether the sample mean attains the CRLB for a normal mean with known variance.
19. State regularity conditions for Cramer-Rao inequality and give one failure case.
20. Find the CRLB for estimating a function `g(theta)` in a Poisson model.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: NP lemma and MP tests

**Recognition trigger:** simple vs simple.

**Standard framework:** Likelihood ratio critical region..

**Practice questions**

21. Use NP lemma to test `H0:p=p0` against `H1:p=p1` in a Bernoulli sample.
22. Find the MP test for simple hypotheses in a Poisson model.
23. Derive the critical region and power for a normal mean simple-vs-simple test.
24. Explain randomized tests when exact size cannot be obtained.
25. State NP lemma and prove the optimality inequality.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: UMP and MLR

**Recognition trigger:** one-sided test.

**Standard framework:** Use monotone likelihood ratio in statistic..

**Practice questions**

26. Show that the Poisson family has MLR and derive the UMP test for `lambda>lambda0`.
27. Construct a UMP test for the Bernoulli parameter against a one-sided alternative.
28. Use MLR to identify the rejection region in an exponential family.
29. Explain why a two-sided UMP test usually does not exist in common one-parameter families.
30. State Karlin-Rubin theorem and apply it to a sample-sum statistic.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: LRT

**Recognition trigger:** composite hypotheses.

**Standard framework:** Restricted/unrestricted likelihood ratio..

**Practice questions**

31. Construct the LRT for the mean of a normal distribution with unknown variance.
32. Construct the LRT for equality of probabilities in a multinomial model.
33. Derive the asymptotic chi-square distribution of `-2 log Lambda` in a regular case.
34. Use LRT for testing variance in a normal population.
35. Compare LRT and Wald-style tests in one paragraph with an example.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## MUST COVER: SPRT

**Recognition trigger:** sequential, OC, ASN.

**Standard framework:** Likelihood ratio boundaries A and B..

**Practice questions**

36. Derive SPRT for testing two Bernoulli parameter values.
37. Derive SPRT for a Poisson mean and express the boundaries in terms of `sum X_i`.
38. Derive OC and ASN functions for a simple Bernoulli SPRT.
39. State Wald's fundamental identity and explain its role.
40. Compare fixed-sample NP testing with SPRT for the same hypotheses.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## GOOD TO COVER: Bayes/minimax

**Recognition trigger:** prior, posterior, risk.

**Standard framework:** Posterior mean under squared error; risk comparison..

**Practice questions**

41. Solve a numerical UPSC-style question on bayes/minimax and state the final interpretation.
42. Derive the main formula or ANOVA/table structure used in bayes/minimax and name all assumptions.
43. Compare bayes/minimax with a nearby syllabus family and illustrate with a small example.
44. Write a short note on bayes/minimax with formula, use case, and limitation.
45. Answer a mixed 15-mark question where bayes/minimax is the main hidden trigger.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.

## GOOD TO COVER: Nonparametric tests

**Recognition trigger:** KS, sign, Wilcoxon, run, median.

**Standard framework:** Statistic, null distribution, critical region..

**Practice questions**

46. Solve a numerical UPSC-style question on nonparametric tests and state the final interpretation.
47. Derive the main formula or ANOVA/table structure used in nonparametric tests and name all assumptions.
48. Compare nonparametric tests with a nearby syllabus family and illustrate with a small example.
49. Write a short note on nonparametric tests with formula, use case, and limitation.
50. Answer a mixed 15-mark question where nonparametric tests is the main hidden trigger.

**Mock links:** Use the full-set mocks in [../mocks](../mocks/) and filter questions tagged with this topic.
