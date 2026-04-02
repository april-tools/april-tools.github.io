---
collection: publications
ref: "javaloy2026optimize"
permalink: "publications/javaloy2026optimize"
title:  "An Embarrassingly Simple Way to Optimize Orthogonal Matrices at Scale"
date: 2026-02-16 00:00
tags: probml
image: "/images/papers/javaloy2026optimize/pogo.png"
authors: "Adrián Javaloy, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2602.14656"
pdf: "https://arxiv.org/pdf/2602.14656"
venue: "arXiv 2026"
excerpt: "We optimize orthogonal matrices with 5 matrix multiplications per iteration, beating in minutes baselines that take hours."
abstract: "Orthogonality constraints are ubiquitous in robust and probabilistic machine learning. Unfortunately, current optimizers are computationally expensive and do not scale to problems with hundreds or thousands of constraints. One notable exception is the Landing algorithm (Ablin et al., 2024) which, however comes at the expense of temporarily relaxing orthogonality. In this work, we revisit and improve on the ideas behind Landing, enabling the inclusion of modern adaptive optimizers while ensuring that orthogonal constraints are effectively met. Remarkably, these improvements come at little to no cost, and reduce the number of required hyperparemeters. Our algorithm POGO is fast and GPU-friendly, consisting of only 5 matrix products, and in practice maintains orthogonality at all times. On several challenging benchmarks, POGO greatly outperforms recent optimizers and shows it can optimize problems with thousands of orthogonal matrices in minutes while alternatives would take hours. As such, POGO sets a milestone to finally exploit orthogonality constraints in ML at scale. A PyTorch implementation of POGO is publicly available at this https URL. "
supplemental: 
bibtex: "@misc{javaloy2026embarrassinglysimplewayoptimize,
  title={An Embarrassingly Simple Way to Optimize Orthogonal Matrices at Scale}, 
  author={Adrián Javaloy and Antonio Vergari},
  year={2026},
  eprint={2602.14656},
  archivePrefix={arXiv},
  primaryClass={cs.LG},
  url={https://arxiv.org/abs/2602.14656}, 
}"
---