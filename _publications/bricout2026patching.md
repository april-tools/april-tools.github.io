---
collection: publications
ref: "bricout2026patching"
permalink: "publications/bricout2026patching"
title:  "Patching Up Circuit Learning via Parameter Sharing"
date: 2026-10-11 00:00
tags: probml
image: "/images/papers/bricout2026patching/repa.png"
authors: "Charles Bricout, Gennaro Gala, Viacheslav Borovitskiy, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2611.12436"
pdf: "https://arxiv.org/pdf/2611.12436"
venue: "NeurIPS26"
excerpt: "We introduce new forms of parameter sharing that improve the efficiency of probabilistic circuits—measured by FLOPs, memory use, and runtime—on image and tabular data while maintaining or even improving likelihood estimation."
abstract: "Probabilistic circuits (PCs) have emerged as generative models guaranteeing tractable probabilistic inference. However, tractability comes at the price of larger model sizes than in other generative models. As such, to scale PCs to high-dimensional data such as images, previous work has devised several parameter sharing techniques as well as fast evaluation protocols that consider learning PCs on independent image patches. In this work, we revisit this practice to highlight a surprising learnability issue: models that assume independence counterintuitively can yield better likelihoods than models that do not. To break this apparent bottleneck and to scale PCs further, we introduce a recursive parameter sharing construction (RePA) that fosters efficiency without assuming independence. We show empirically that RePA can greatly reduce time and memory consumption while yielding competitive likelihoods. Inspired by these results, we further generalize the approach to data modalities that do not inherently exhibit patch-structure (NoPA), such as tabular data, showing similar efficiency improvements, with marginal changes in likelihoods and sample quality on seven tabular datasets. Code available at [this https URL](https://github.com/april-tools/RePA)."
supplemental: 
bibtex: "@misc{bricout2026patchingcircuitlearningparameter,
      title={Patching Up Circuit Learning via Parameter Sharing}, 
      author={Charles Bricout and Gennaro Gala and Viacheslav Borovitskiy and Antonio Vergari},
      year={2026},
      eprint={2611.12436},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2611.12436}, 
}"
---
