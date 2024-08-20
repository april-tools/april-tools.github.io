---
collection: publications
ref: "marconato2024bears"
permalink: "publications/marconato2024bears"
title:  "BEARS Make Neuro-Symbolic Models Aware of their Reasoning Shortcuts"
date:   2024-04-26 00:00
tags: nesy shortcuts reasoning uq
image: "/images/papers/marconato2024bears/bears.png"
authors: "Emanuele Marconato, Samuele Bortolotti, Emile van Krieken, Antonio Vergari, Andrea Passerini, Stefano Teso"
paperurl: "https://arxiv.org/abs/2402.12240"
pdf: "https://arxiv.org/pdf/2402.12240.pdf"
venue: "UAI 2024"
award: "spotlight"
code: "https://github.com/samuelebortolotti/bears"
excerpt: "NeSy models can suffer from reasoning shortcuts, and to make them shortcut-aware, we sprinkle a pinch of Bayes to quantify the uncertainty over the extracted concepts, showing it is correlated to the presence of reasoning shortcuts."
abstract: "Neuro-Symbolic (NeSy) predictors that conform to symbolic knowledge - encoding, e.g., safety constraints - can be affected by Reasoning Shortcuts (RSs): They learn concepts consistent with the symbolic knowledge by exploiting unintended semantics. RSs compromise reliability and generalization and, as we show in this paper, they are linked to NeSy models being overconfident about the predicted concepts. Unfortunately, the only trustworthy mitigation strategy requires collecting costly dense supervision over the concepts. Rather than attempting to avoid RSs altogether, we propose to ensure NeSy models are aware of the semantic ambiguity of the concepts they learn, thus enabling their users to identify and distrust low-quality concepts. Starting from three simple desiderata, we derive bears (BE Aware of Reasoning Shortcuts), an ensembling technique that calibrates the model's concept-level confidence without compromising prediction accuracy, thus encouraging NeSy architectures to be uncertain about concepts affected by RSs. We show empirically that bears improves RS-awareness of several state-of-the-art NeSy models, and also facilitates acquiring informative dense annotations for mitigation purposes."
supplemental: 
bibtex: "@inproceedings{marconato2024bears,<br/>
  title={BEARS Make Neuro-Symbolic Models Aware of their Reasoning Shortcuts},<br/>
  author={Emanuele Marconato, Samuele Bortolotti, Emile van Krieken, Antonio Vergari, Andrea Passerini, Stefano Teso,<br/>
  booktitle={Uncertainty in Artificial Intelligence (UAI)},<br/>
  year={2024}
}"
---
