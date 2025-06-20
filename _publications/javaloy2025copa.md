---
collection: publications
ref: "javaloy2025copa"
permalink: "publications/javaloy2025copa"
title:  "COPA: Comparing the incomparable in multi-objective model evaluation"
date: 2025-03-18 00:00
tags: probml
image: "/images/papers/javaloy2025copa/copa.png"
authors: "Adrián Javaloy, Antonio Vergari, Isabel Valera"
paperurl: "https://arxiv.org/abs/2503.14321"
pdf: "https://arxiv.org/pdf/2503.14321"
venue: "arxiv 2025"
excerpt: "How can we sensibly aggregate and compare heterogeneous objectives to retrieve the optimal trade-off model the user expects to get? We show that many areas in ML yield biased results due to ignoring this deceptively simple question, and provide a method to overcome these issues by simply re-ranking our objectives before aggregating them."
abstract: "As machine learning (ML) practitioners, we often have hundreds of (trained) ML models at hand from which we need to choose one, based on various objectives such as accuracy, robustness, fairness, scalability, etc. However, how to compare, aggregate and, ultimately, trade-off these objectives is usually a time-consuming task that requires of expert knowledge, as they may be measured in different units or scales. In this work, we investigate how objectives can be automatically normalized and aggregated to systematically navigate their Pareto front. To do so, we make incomparable objectives comparable using their CDFs, approximated by their relative rankings. As a result, we can aggregate them while matching user-specific preferences, allowing practitioners to meaningfully navigate and search for models in the Pareto front. We demonstrate the potential impact of our approach, COPA, in both model selection and benchmarking tasks across diverse ML areas such as fair ML, domain generalization, AutoML and foundation models, where classical ways to normalize and aggregate objectives fall short."
supplemental: 
bibtex: "@article{javaloy2025copa,
  title={COPA: Comparing the incomparable in multi-objective model evaluation},
  author={Javaloy, Adri{\\'a}n and Vergari, Antonio and Valera, Isabel},
  journal={arXiv preprint arXiv:2503.14321},
  year={2025}
}"
---