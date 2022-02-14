# Lower-bounds on the Bayesian Risk in Estimation Procedures via f-Divergences

This repository contains the code for [this](https://arxiv.org/abs/2202.02557) paper.

We provide computations of various lower-bounds that are functions of multiple divergences (or information measures):
- Hellinger Divergence
- Hockey-Stick Divergence
- Shannon's Mutual Information
- Sibson's alpha-Mutual Information
- Maximal Leakage

We consider two settings, namely the Bernoulli Bias and the Gaussian Location Model (Example 1 and Example in the paper, respectively). Since some of the bounds depend on some parameters, we sometimes set them to fixed values, and sometimes optimize numerically over them using SciPy in order to retrieve the best possible bounds.
