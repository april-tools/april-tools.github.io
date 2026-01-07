---
collection: publications
ref: "loconte2025square"
permalink: "publications/loconte2025square"
title:  "How to Square Tensor Networks and Circuits Without Squaring Them"
date:   2025-12-18 00:00
tags: circuits tensor-networks probml
image: "/images/papers/loconte2025square/orthogonal-circuit.png"
authors: "Lorenzo Loconte, Adrián Javaloy, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2512.17090"
pdf: "https://arxiv.org/abs/2512.17090"
venue: "arXiv 2025"
excerpt: "We derive novel circuit properties based on orthogonality to speed-up marginalization in squared circuits and tensor network-based Born machines, as well as to unlock a strictly larger set of factorization structures enabling tractable marginalization"
abstract: "Squared tensor networks (TNs) and their extension as computational graphs--squared circuits--have been used as expressive distribution estimators, yet supporting closed-form marginalization. However, the squaring operation introduces additional complexity when computing the partition function or marginalizing variables, which hinders their applicability in ML. To solve this issue, canonical forms of TNs are parameterized via unitary matrices to simplify the computation of marginals. However, these canonical forms do not apply to circuits, as they can represent factorizations that do not directly map to a known TN. Inspired by the ideas of orthogonality in canonical forms and determinism in circuits enabling tractable maximization, we show how to parameterize squared circuits to overcome their marginalization overhead. Our parameterizations unlock efficient marginalization even in factorizations different from TNs, but encoded as circuits, whose structure would otherwise make marginalization computationally hard. Finally, our experiments on distribution estimation show how our proposed conditions in squared circuits come with no expressiveness loss, while enabling more efficient learning."
supplemental:
bibtex: "@misc{loconte2025square,<br/>
      title={How to Square Tensor Networks and Circuits Without Squaring Them},<br/> 
      author={Lorenzo Loconte and Adrián Javaloy and Antonio Vergari},<br/>
      year={2025},<br/>
      eprint={2512.17090},<br/>
      archivePrefix={arXiv},<br/>
      primaryClass={cs.LG}}"
---
