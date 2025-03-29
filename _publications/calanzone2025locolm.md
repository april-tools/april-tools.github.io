---
collection: publications
ref: "calanzone2025locolm"
permalink: "publications/calanzone2025locolm"
title:  "Logically Consistent Language Models via Neuro-Symbolic Integration"
date:   2025-01-05 10:00
tags: nesy probml llm
image: "/images/papers/calanzone2024locolm/locolm.png"
authors: "Diego Calanzone, Stefano Teso, Antonio Vergari"
paperurl: "https://openreview.net/forum?id=7PGluppo4k"
pdf: "https://openreview.net/pdf?id=7PGluppo4k"
venue: "ICLR 2025"
excerpt: "We introduce a training objective based on principled probabilistic reasoning that teaches a LLM to be logically consistent with a set of external facts and rules, allowing to extrapolate to unseen but semantically similar factual knowledge."
abstract: "Large language models (LLMs) are a promising venue for natural language understanding and generation tasks. However, current LLMs are far from reliable: they are prone to generate non-factual information and, more crucially, to contradict themselves when prompted to reason about relations between real entities of the world. These problems are currently addressed with large scale fine-tuning or by delegating consistent reasoning to external tools. In this work, we strive for a middle ground and leverage a training objective based on a principled neuro-symbolic loss that teaches a LLM to be consistent with external knowledge in the form of a set of facts and rules. Fine-tuning with such a loss on a limited set of facts enables our LLMs to be more logically consistent than previous baselines for a given constraint. Our approach also allows to easily combine multiple logical constraints at once in a principled way, delivering LLMs that are more consistent w.r.t. all the selected rules. Moreover, our method allows LLMs to extrapolate to unseen but semantically similar factual knowledge, represented in unseen datasets, more systematically."
bibtex: "@inproceedings{calanzone2025locolm,
  title={Towards Logically Consistent Language Models via Probabilistic Reasoning},
  author={Diego Calanzone, Stefano Teso, Antonio Vergari},
  booktitle={ICLR},
  year={2025}
}"
---
