# CASCON 2019 AI in Finance workshop - Part 1

**Presentations**

Wednesday, November 6 | 13:00 - 14:45 | Primrose

<p>&nbsp;</p>


## Presentation 1 - 13:00-13:25

**Title**: Overview of Financial Modeling

**Presenter**: Oleksandr Romanko, Senior Research Analyst, Watson Financial Services, IBM

## Presentation 2 - 13:25-13:50

**Title**: Artificial Intelligence Enhancements to Financial Modeling

**Presenter**: Oleksandr Romanko, Senior Research Analyst, Watson Financial Services, IBM

### Presentation 3 - 13:50-14:15

**Title**: Generalized Risk Parity Portfolio Optimization: An ADMM Approach

**Presenter**: Giorgio Costa, PhD Candidate, University of Toronto

**Abstract**: The risk parity solution to the asset allocation problem yields portfolios where the risk contribution from each asset is made equal. We consider a generalized approach to this problem. First, we set an objective that seeks to maximize the portfolio expected return while minimizing portfolio risk. Second, we relax the risk parity condition and instead bound the risk dispersion of the constituents within a predefined limit. This allows an investor to prescribe a desired risk dispersion range, yielding a portfolio with an optimal risk--return profile that is still well-diversified from a risk-based standpoint. We add robustness to our framework by introducing an ellipsoidal uncertainty structure around our estimated asset expected returns to mitigate estimation error. Our proposed framework does not impose any restrictions on short selling. A limitation of risk parity is that allowing of short sales leads to a non-convex problem. However, we propose an approach that relaxes our generalized risk parity model into a convex semidefinite program. We proceed to tighten this relaxation sequentially through the alternating direction method of multipliers. This procedure iterates between the convex optimization problem and the non-convex problem with a rank constraint. In addition, we can exploit this structure to solve the non-convex problem analytically and efficiently during every iteration. Numerical results suggest that this algorithm converges to a higher quality optimal solution when compared to the competing non-convex problem.  

### Presentation 4 - 14:15-14:40

**Title**: Data-Driven Factor Models

**Presenter**: Hassan Anis, PhD Candidate, University of Toronto

**Abstract**: Factor models are central to understanding risk-return trade-offs in finance. Since Fama and French (1993), many have been creating new factors that add explanatory power for asset pricing, relative to the existing set of hundreds of factors. To construct a factor model, two tasks have to be performed: Feature Selection, selecting a small subset given a large number of factors to overcome the curse of dimensionality and overfitting in regression, and Feature Engineering, determining the interactions between the factors. In this work, we provide a unified, data-driven framework that produces general factor models. Comparisons between LASSO- and MIP-based formulations for feature selection models are presented. Two-stage models are proposed to generalize factor models to include nonlinear interactions. Results of computational experiments, on historical financial data, suggest that MIP formulations may be more suitable for the task of financial factor selection and that the second-stage nonlinearity improves accuracy.

<p>&nbsp;</p>

