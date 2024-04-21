---
collection: publications
ref: "beltran-jimenez2024galerkin"
permalink: "publications/beltran-jimenez2024galerkin"
title:  "Galerkin meets Laplace: Fast uncertainty estimation in neural PDEs"
date:   2024-03-05 00:00
tags: uq probml pinns
image: "/images/papers/beltran-jimenez2024galerkin/gala.png"
authors: "Christian Jimenez Beltran, Antonio Vergari, Aretha L Teckentrup, Konstantinos C. Zygalakis"
paperurl: "https://openreview.net/forum?id=HdzFecgdzB"
pdf: "https://openreview.net/pdf?id=HdzFecgdzB"
venue: "AI4DifferentialEquations @ ICLR 2024"
excerpt: "We propose DeepGALA as a fast and effective way to estimate uncertainty in deep neural PDE solvers that allows us to capture meaningful uncertainty in out of domain of the PDE solution and in low data regimes with little overhead."
abstract: "The solution of partial differential equations (PDEs) by deep neural networks trained to satisfy the differential operator has become increasingly popular. While these approaches can lead to very accurate approximations, they tend to be over- confident and fail to capture the uncertainty around the approximation. In this work, we propose a Bayesian treatment to the deep Galerkin method (Sirignano & Spiliopoulos, 2018), a popular neural approach for solving parametric PDEs. In particular, we reinterpret the deep Galerkin method as the maximum a posteriori estimator corresponding to a likelihood term over a fictitious dataset, leading thus to a natural definition of a posterior. Then, we propose to model such posterior via the Laplace approximation, a fast approximation that allows us to capture mean- ingful uncertainty in out of domain interpolation of the PDE solution and in low data regimes with little overhead, as shown in our preliminary experiments."
bibtex: "@inproceedings{beltran-jimenez2024galerkin,
  title={Galerkin meets Laplace: Fast uncertainty estimation in neural PDEs},
  author={Christian Jimenez Beltran, Antonio Vergari, Aretha L Teckentrup, Konstantinos C. Zygalakis},
  booktitle={ICLR 2024 Workshop on AI4DifferentialEquations},
  year={2024}
}"
---
