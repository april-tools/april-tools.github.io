---
collection: publications
ref: "loconte2024sos"
permalink: "publications/loconte2024sos"
title:  "Sum of Squares Circuits"
date:   2024-12-10 00:00
tags: circuits probml
image: "/images/papers/loconte2024sos/sos-hierarchy.png"
spotlight: "/images/papers/loconte2024sos/sos-spotlight.png"
authors: "Lorenzo Loconte, Stefan Mengel, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2408.11778"
pdf: "https://arxiv.org/abs/2408.11778"
venue: "AAAI 2025"
code: "https://github.com/april-tools/sos-npcs"
excerpt: "We theoretically prove an expressiveness limitation of deep subtractive mixture models learned by squaring circuits. To overcome this limitation, we propose sum of squares circuits and build an expressiveness hierarchy around them, allowing us to unify and separate many tractable probabilistic models."
abstract: "Designing expressive generative models that support exact and efficient inference is a core question in probabilistic ML. Probabilistic circuits (PCs) offer a framework where this tractability-vs-expressiveness trade-off can be analyzed theoretically. Recently, squared PCs encoding subtractive mixtures via negative parameters have emerged as tractable models that can be exponentially more expressive than monotonic PCs, i.e., PCs with positive parameters only. In this paper, we provide a more precise theoretical characterization of the expressiveness relationships among these models. First, we prove that squared PCs can be less expressive than monotonic ones. Second, we formalize a novel class of PCs -- sum of squares PCs -- that can be exponentially more expressive than both squared and monotonic PCs. Around sum of squares PCs, we build an expressiveness hierarchy that allows us to precisely unify and separate different tractable model classes such as Born Machines and PSD models, and other recently introduced tractable probabilistic models by using complex parameters. Finally, we empirically show the effectiveness of sum of squares circuits in performing distribution estimation."
supplemental: 
bibtex: "@inproceedings{loconte2024sos,<br/>
      title={Sum of Squares Circuits},<br/>
      author={Lorenzo Loconte and Stefan Mengel and Antonio Vergari},<br/>
      year={2025},<br/>
      booktitle={The 39th Annual AAAI Conference on Artificial Intelligence}}"
---
