---
collection: publications
ref: "kurscheidt2025pal"
permalink: "publications/kurscheidt2025pal"
title:  "A Probabilistic Neuro-symbolic Layer for Algebraic Constraint Satisfaction"
date: 2025-03-25 00:00
tags: probml nesy constraints
image: "/images/papers/kurscheidt2025pal/pal.png"
authors: "Leander Kurscheidt, Paolo Morettin, Roberto Sebastiani, Andrea Passerini, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2503.19466"
pdf: "https://arxiv.org/pdf/2503.19466"
venue: "UAI 2025"
award: "oral"
excerpt: "Our paper introducing PAL, a neurosymbolic layer for algebraic constraint satisfaction, got accepted at UAI 2025 as an oral."
abstract: "In safety-critical applications, guaranteeing the satisfaction of constraints over continuous environments is crucial, e.g., an autonomous agent should never crash into obstacles or go off-road. Neural models struggle in the presence of these constraints, especially when they involve intricate algebraic relationships. To address this, we introduce a differentiable probabilistic layer that guarantees the satisfaction of non-convex algebraic constraints over continuous variables. This probabilistic algebraic layer (PAL) can be seamlessly plugged into any neural architecture and trained via maximum likelihood without requiring approximations. PAL defines a distribution over conjunctions and disjunctions of linear inequalities, parameterized by polynomials. This formulation enables efficient and exact renormalization via symbolic integration, which can be amortized across different data points and easily parallelized on a GPU. We showcase PAL and our integration scheme on a number of benchmarks for algebraic constraint integration and on real-world trajectory data."
supplemental: 
bibtex: "@article{kurscheidt2025probabilistic,
  title={A probabilistic neuro-symbolic layer for algebraic constraint satisfaction},
  author={Kurscheidt, Leander and Morettin, Paolo and Sebastiani, Roberto and Passerini, Andrea and Vergari, Antonio},
  journal={arXiv preprint arXiv:2503.19466},
  year={2025}
}"
---
