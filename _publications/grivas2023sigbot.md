---
collection: publications
ref: "grivas2023sigbot"
permalink: "publications/grivas2023sigbot"
title:  "Taming the Sigmoid Bottleneck: Provably Argmaxable Sparse Multi-Label Classification"
date:   2023-10-26 00:00
tags: constraints robustness
image: "/images/papers/grivas2023sigbot/sigbot.png"
spotlight: "/images/papers/grivas2023sigbot/sigbot-spotlight.png"
authors: "Andreas Grivas, Antonio Vergari, Adam Lopez"
paperurl: "https://arxiv.org/abs/2310.10443"
pdf: "https://arxiv.org/pdf/2310.10443.pdf"
venue: "arXiv 2023"
code: "https://github.com/andreasgrv/sigmoid-bottleneck"
excerpt: "We highlight a weakness of low-rank linear multi-label classifiers: they can have meaningful outputs that cannot be predicted. We design a classifier which guarantees that sparse outputs can be predicted while using less trainable parameters."
abstract: "Sigmoid output layers are widely used in multi-label classification (MLC) tasks, in which multiple labels can be assigned to any input. In many practical MLC tasks, the number of possible labels is in the thousands, often exceeding the number of input features and resulting in a low-rank output layer. In multi-class classification, it is known that such a low-rank output layer is a bottleneck that can result in unargmaxable classes: classes which cannot be predicted for any input. In this paper, we show that for MLC tasks, the analogous sigmoid bottleneck results in exponentially many unargmaxable label combinations. We explain how to detect these unargmaxable outputs and demonstrate their presence in three widely used MLC datasets. We then show that they can be prevented in practice by introducing a Discrete Fourier Transform (DFT) output layer, which guarantees that all sparse label combinations with up to k active labels are argmaxable. Our DFT layer trains faster and is more parameter efficient, matching the F1@k score of a sigmoid layer while using up to 50% fewer trainable parameters. Our code is publicly available at https://github.com/andreasgrv/sigmoid-bottleneck."
supplemental: 
bibtex: "@article{grivas2023taming,<br/>
  title={Taming the Sigmoid Bottleneck: Provably Argmaxable Sparse Multi-Label Classification},<br/>
  author={Andreas Grivas and Antonio Vergari and Adam Lopez},<br/>
  journal={arXiv preprint arXiv:2310.10443},<br/>
  year={2023}
}"
---
