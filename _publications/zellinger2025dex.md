---
collection: publications
ref: "zellinger2025dex"
permalink: "publications/zellinger2025dex"
title:  "Scalable Expectation Estimation with Subtractive Mixture Models"
date: 2025-03-27 00:00
tags: probml
image: "/images/papers/zellinger2025dex/dex.png"
authors: "Lena Zellinger, Nicola Branchini, Víctor Elvira, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2503.21346"
pdf: "https://arxiv.org/pdf/2503.21346"
venue: "arxiv 2025"
excerpt: "We motivate the use of subtractive mixture models as proposals for importance sampling and derive a scalable estimator that exploits the decomposition of a subtractive mixture model into a difference of two monotonic mixtures."
abstract: "Many Monte Carlo (MC) and importance sampling (IS) methods use mixture models (MMs) for their simplicity and ability to capture multimodal distributions. Recently, subtractive mixture models (SMMs), i.e. MMs with negative coefficients, have shown greater expressiveness and success in generative modeling. However, their negative parameters complicate sampling, requiring costly auto-regressive techniques or accept-reject algorithms that do not scale in high dimensions. In this work, we use the difference representation of SMMs to construct an unbiased IS estimator ($\\Delta$Ex) that removes the need to sample from the SMM, enabling high-dimensional expectation estimation with SMMs. In our experiments, we show  that $\\Delta$Ex can achieve comparable estimation quality to auto-regressive sampling while being considerably faster in MC estimation. Moreover, we conduct initial experiments with $\\Delta$Ex using hand-crafted proposals, gaining first insights into how to construct safe proposals for $\\Delta$Ex."
supplemental: 
bibtex: "@article{zellinger2025scalable,
  title={Scalable Expectation Estimation with Subtractive Mixture Models},
  author={Zellinger, Lena and Branchini, Nicola and Elvira, V{\\'\\i}ctor and Vergari, Antonio},
  journal={arXiv preprint arXiv:2503.21346},
  year={2025}
}"
---
