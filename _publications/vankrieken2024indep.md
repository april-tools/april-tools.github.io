---
collection: publications
ref: "vankrieken2024indep"
permalink: "publications/vankrieken2024indep"
title:  "On the Independence Assumption in Neurosymbolic Learning"
date:   2024-04-12 00:00
tags: nesy reasoning uq
image: "/images/papers/vankrieken2024indep/indep.png"
authors: "Emile van Krieken, Pasquale Minervini, Edoardo M. Ponti, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2404.08458"
pdf: "https://arxiv.org/pdf/2404.08458.pdf"
venue: "ICML 2024"
excerpt: "We theoretically analyze the common assumption that many NeSy models -- from the semantic loss to deep Problog -- do: the independence among terms of a logical formula, and highlight how this biases learning and make some solutions impossible to retrieve."
abstract: "State-of-the-art neurosymbolic learning systems use probabilistic reasoning to guide neural networks towards predictions that conform to logical constraints over symbols. Many such systems assume that the probabilities of the considered symbols are conditionally independent given the input to simplify learning and reasoning. We study and criticise this assumption, highlighting how it can hinder optimisation and prevent uncertainty quantification. We prove that loss functions bias conditionally independent neural networks to become overconfident in their predictions. As a result, they are unable to represent uncertainty over multiple valid options. Furthermore, we prove that these loss functions are difficult to optimise: they are non-convex, and their minima are usually highly disconnected. Our theoretical analysis gives the foundation for replacing the conditional independence assumption and designing more expressive neurosymbolic probabilistic models."
supplemental: 
bibtex: "@article{vankrieken2024indep,<br/>
  title={On the Independence Assumption in Neurosymbolic Learning},<br/>
  author={Emile van Krieken, Pasquale Minervini, Edoardo M. Ponti, Antonio Vergari,<br/>
  journal={arXiv preprint arXiv:404.08458},<br/>
  year={2024}
}"
---
