---
collection: publications
ref: "lazzari2026nesy"
permalink: "publications/lazzari2026nesy"
title:  "To Neuro-Symbolic Classification and Beyond by Compiling Description Logic Ontologies to Probabilistic Circuits"
date:   2026-01-21 00:00
tags: nesy probml 
image: "/images/papers/lazzari2026nesy/kb_example.png"
authors: "Nicolas Lazzari, Valentina Presutti, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2601.14894"
pdf: "https://arxiv.org/pdf/2601.14894"
venue: "arXiv 2026"
excerpt: "We compile Description Logic ontologies into differentiable circuits to enable scalable reasoning, generate data, and build neuro-symbolic models that produce reliable, ontology-consistent predictions."
abstract: "Background: Neuro-symbolic methods enhance the reliability of neural network classifiers through logical constraints, but they lack native support for ontologies.
    
    Objectives: We aim to develop a neuro-symbolic method that reliably outputs predictions consistent with a Description Logic ontology that formalizes domain-specific knowledge.
    
    Methods: We encode a Description Logic ontology as a circuit, a feed-forward differentiable computational graph that supports tractable execution of queries and transformations. We show that the circuit can be used to (i) generate synthetic datasets that capture the semantics of the ontology; (ii) efficiently perform deductive reasoning on a GPU; (iii) implement neuro-symbolic models whose predictions are approximately or provably consistent with the knowledge defined in the ontology.
    
    Results We show that the synthetic dataset generated using the circuit qualitatively captures the semantics of the ontology while being challenging for Machine Learning classifiers, including neural networks. Moreover, we show that compiling the ontology into a circuit is a promising approach for scalable deductive reasoning, with runtimes up to three orders of magnitude faster than available reasoners. Finally, we show that our neuro-symbolic classifiers reliably produce consistent predictions when compared to neural network baselines, maintaining competitive performances or even outperforming them.
    
    Conclusions By compiling Description Logic ontologies into circuits, we obtain a tighter integration between the Deep Learning and Knowledge Representation fields. We show that a single circuit representation can be used to tackle different challenging tasks closely related to real-world applications."
supplemental: 
bibtex: "@misc{lazzari2026neurosymbolicclassificationcompilingdescription,
    title={To Neuro-Symbolic Classification and Beyond by Compiling Description Logic Ontologies to Probabilistic Circuits}, 
    author={Nicolas Lazzari and Valentina Presutti and Antonio Vergari},
    year={2026},
    eprint={2601.14894},
    archivePrefix={arXiv},
    primaryClass={cs.AI},
    url={https://arxiv.org/abs/2601.14894}, 
}"
---