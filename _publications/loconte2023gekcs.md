---
collection: publications
ref: "loconte2023gekcs"
permalink: "publications/loconte2023gekcs"
title:  "How to Turn Your Knowledge Graph Embeddings into Generative Models via Probabilistic Circuits"
date:   2023-09-22 01:00
tags: nesy kge circuits constraints
image: "/images/papers/loconte2023gekcs/gekcs.png"
spotlight: "/images/papers/loconte2023gekcs/gekcs-spotlight.png"
authors: "Lorenzo Loconte, Nicola Di Mauro, Robert Peharz, Antonio Vergari"
paperurl: "https://openreview.net/forum?id=RSGNGiB1q4"
pdf: "https://openreview.net/pdf?id=RSGNGiB1q4"
venue: "NeurIPS 2023"
award: "oral (top 0.6%)"
code: "https://github.com/april-tools/gekcs"
excerpt: "KGE models such as CP, RESCAL, TuckER, ComplEx can be re-interpreted as circuits to unlock their generative capabilities, scaling up inference and learning and guaranteeing the satisfaction of logical constraints by design."
abstract: "Some of the most successful knowledge graph embedding (KGE) models for link prediction -- CP, RESCAL, TuckER, ComplEx -- can be interpreted as energy-based models. Under this perspective they are not amenable for exact maximum-likelihood estimation (MLE), sampling and struggle to integrate logical constraints. This work re-interprets the score functions of these KGEs as circuits -- constrained computational graphs allowing efficient marginalisation. Then, we design two recipes to obtain efficient generative circuit models by either restricting their activations to be non-negative or squaring their outputs. Our interpretation comes with little or no loss of performance for link prediction, while the circuits framework unlocks exact learning by MLE, efficient sampling of new triples, and guarantee that logical constraints are satisfied by design. Furthermore, our models scale more gracefully than the original KGEs on graphs with millions of entities. "
supplemental: 
bibtex: "@inproceedings{loconte2023how,<br/>
  title={How to Turn Your Knowledge Graph Embeddings into Generative Models},<br/>
  author={Lorenzo Loconte and Nicola Di Mauro and Robert Peharz and Antonio Vergari},<br/>
  booktitle={Thirty-seventh Conference on Neural Information Processing Systems},<br/>
  year={2023},<br/>
  url={https://openreview.net/forum?id=RSGNGiB1q4}}"
---
