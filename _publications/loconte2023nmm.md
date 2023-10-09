---
collection: publications
ref: "loconte2023nmm"
permalink: "publications/loconte2023nmm"
title:  "Negative Mixture Models via Squaring: Representation and Learning"
date:   2023-08-18 00:00
tags: circuits probml
image: "/images/papers/loconte2023nmm/nmm.png"
authors: "Lorenzo Loconte, Stefan Mengel, Nicolas Gillis, Antonio Vergari"
paperurl: "https://openreview.net/forum?id=uTAzte88a2"
pdf: "https://openreview.net/pdf?id=uTAzte88a2"
venue: "TPM 2023"
code:
excerpt: "We propose to build (hierarchical) negative mixture models by squaring circuits. We theoretically prove their expressiveness by deriving an exponential lowerbound on the size of circuits with positive parameters only."
abstract: "Negative mixture models (NMMs) can potentially be more expressive than classical non-negative ones by allowing negative coefﬁcients, thus greatly reducing the number of components and parameters to ﬁt. However, modeling NMMs features a number of challenges, from ensuring that negative combinations still encode valid densities or masses, to effectively learning them from data. In this paper, we investigate how we can model both shallow and hierarchical NMMs in a generic framework, via squaring. We do so by representing NMMs as probabilistic circuits (PCs) – structured computational graphs that ensure tractability. Then, we show when and how we can represent these squared NMMs as tensorized computational graphs efﬁciently, while theoretically proving that for certain function classes including negative parameters can exponentially reduce the model size."
supplemental: 
bibtex: "@inproceedings{loconte2023nmm,<br/>
title={Negative Mixture Models via Squaring: Representation and Learning},<br/>
author={Lorenzo Loconte and Stefan Mengel and Nicolas Gillis and Antonio Vergari},<br/>
booktitle={The 6th Workshop on Tractable Probabilistic Modeling},<br/>
year={2023}}"
---
