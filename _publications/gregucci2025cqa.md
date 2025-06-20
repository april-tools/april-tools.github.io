---
collection: publications
ref: "gregucci2025cqa"
permalink: "publications/gregucci2025cqa"
title:  "Is Complex Query Answering Really Complex?"
date:   2025-05-01 00:00
tags: cqa knowledge-graphs
image: "/images/papers/gregucci2025cqa/cqa.png"
authors: "Cosimo Gregucci, Bo Xiong, Daniel Hernández, Lorenzo Loconte, Pasquale Minervini, Steffen Staab, Antonio Vergari"
paperurl: "https://openreview.net/forum?id=F8NTPAz5HH"
pdf: "https://openreview.net/pdf?id=F8NTPAz5HH"
venue: "ICML 2025"
award: "spotlight (top 2.6%)"
excerpt: "We highlight how common benchmarks for complex query answering with neural models are skewed towards 'simple' queries and propose new more challenging benchmarks that solve this issue."
abstract: "Complex query answering (CQA) on knowledge graphs (KGs) is gaining momentum as a challenging reasoning task. In this paper, we show that the current benchmarks for CQA might not be as complex as we think, as the way they are built distorts our perception of progress in this field. For example, we find that in these benchmarks most queries (up to 98% for some query types) can be reduced to simpler problems, e.g., link prediction, where only one link needs to be predicted. The performance of state-of-the-art CQA models drops significantly when such models are evaluated on queries that cannot be reduced to easier types. Thus, we propose a set of more challenging benchmarks, composed of queries that require models to reason over multiple hops and better reflect the construction of real-world KGs. In a systematic empirical investigation, the new benchmarks show that current methods leave much to be desired from current CQA methods."
supplemental: 
code: "https://github.com/april-tools/is-cqa-complex"
bibtex: "@inproceedings{gregucci2025cqa,
  title={Is Complex Query Answering Really Complex?},
  author={Gregucci, Cosimo and Xiong, Bo and Hernández, Daniel  and  Loconte, Lorenzo and Minervini, Pasquale and Staab, Steffen and Vergari, Antonio},
  booktitle={ICML},
  year={2025}
}"
---