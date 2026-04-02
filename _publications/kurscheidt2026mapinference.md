---
collection: publications
ref: "kurscheidt2026mapinference"
permalink: "publications/kurscheidt2026mapinference"
title:  "The Theory and Practice of MAP Inference over Non-Convex Constraints"
date: 2026-02-10 00:00
tags: probml nesy constraints
image: "/images/papers/kurscheidt2026mapinference/map_inference.png"
authors: "Leander Kurscheidt, Gabriele Masina, Roberto Sebastiani, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2602.08681"
pdf: "https://arxiv.org/pdf/2602.08681"
venue: "arXiv 2026"
excerpt: "We investigate under which conditions we can perform constrained MAP inference over continuous variables exactly and efficiently—via a message-passing algorithm—and introduce a general approach that alternates convex partitioning with numerical optimisation."
abstract: "In many safety-critical settings, probabilistic ML systems have to make predictions subject to algebraic constraints, e.g., predicting the most likely trajectory that does not cross obstacles. These real-world constraints are rarely convex, nor the densities considered are (log-)concave. This makes computing this constrained maximum a posteriori (MAP) prediction efficiently and reliably extremely challenging. In this paper, we first investigate under which conditions we can perform constrained MAP inference over continuous variables exactly and efficiently and devise a scalable message-passing algorithm for this tractable fragment. Then, we devise a general constrained MAP strategy that interleaves partitioning the domain into convex feasible regions with numerical constrained optimization. We evaluate both methods on synthetic and real-world benchmarks, showing our approaches outperform constraint-agnostic baselines, and scale to complex densities intractable for SoTA exact solvers."
supplemental: 
bibtex: "@misc{kurscheidt2026mapinference,
  title={The Theory and Practice of MAP Inference over Non-Convex Constraints},
  author={Leander Kurscheidt and Gabriele Masina and Roberto Sebastiani and Antonio Vergari},
  year={2026},
  eprint={2602.08681},
  archivePrefix={arXiv},
  primaryClass={cs.LG},
  url={https://arxiv.org/abs/2602.08681},
  }"
---
