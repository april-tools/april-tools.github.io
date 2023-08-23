---
collection: publications
ref: "loconte2023gekcs"
permalink: "publications/loconte2023gekcs"
title:  "How to Turn Your Knowledge Graph Embeddings into Generative Models via Probabilistic Circuits"
date:   2023-07-04 00:00
tags: nesy kge circuits constraints
image: "/images/papers/loconte2023gekcs/gekcs.png"
spotlight: "/images/papers/loconte2023gekcs/gekcs-spotlight.png"
authors: "Lorenzo Loconte, Nicola Di Mauro, Robert Peharz, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2305.15944"
pdf: "https://arxiv.org/pdf/2305.15944.pdf"
venue: "arXiv 2023"
code:
excerpt: "KGE models such as CP, RESCAL, TuckER, ComplEx can be re-interpreted as circuits to unlock their generative capabilities, scaling up inference and learning and guaranteeing the satisfaction of logical constraints by design."
abstract: "Some of the most successful knowledge graph embedding (KGE) models for link prediction -- CP, RESCAL, TuckER, ComplEx -- can be interpreted as energy-based models. Under this perspective they are not amenable for exact maximum-likelihood estimation (MLE), sampling and struggle to integrate logical constraints. This work re-interprets the score functions of these KGEs as circuits -- constrained computational graphs allowing efficient marginalisation. Then, we design two recipes to obtain efficient generative circuit models by either restricting their activations to be non-negative or squaring their outputs. Our interpretation comes with little or no loss of performance for link prediction, while the circuits framework unlocks exact learning by MLE, efficient sampling of new triples, and guarantee that logical constraints are satisfied by design. Furthermore, our models scale more gracefully than the original KGEs on graphs with millions of entities. "
supplemental: 
bibtex: "@article{loconte2023gekcs,<br/>
  title={How to Turn Your Knowledge Graph Embeddings into Generative Models via Probabilistic Circuits},<br/>
  author={Loconte, Lorenzo and Di Mauro, Nicola and Peharz, Robert and Vergari, Antonio},<br/>
  journal={arXiv preprint arXiv:2305.15944},<br/>
  year={2023}
}"
---
