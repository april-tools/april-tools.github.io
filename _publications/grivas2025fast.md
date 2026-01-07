---
collection: publications
ref: "grivas2025fast"
permalink: "publications/grivas2025fast"
title:  "Fast and Expressive Multi-Token Prediction with Probabilistic Circuits"
date:   2025-11-14 00:00
tags: llms speculative-decoding circuits probml
image: "/images/papers/grivas2025fast/tradeoff.png"
authors: "Andreas Grivas, Lorenzo Loconte, Emile van Krieken, Piotr Nawrot, Yu Zhao, Euan Wielewski, Pasquale Minervini, Edoardo Ponti, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2511.11346"
pdf: "https://arxiv.org/abs/2511.11346"
venue: "arXiv 2025"
excerpt: "We propose a framework for multi-token prediction using speculative decoding, allowing us to easily explore different parameterizations balancing expressiveness and efficiency, and generalize other approaches based on tensor factorizations."
abstract: "Multi-token prediction (MTP) is a prominent strategy to significantly speed up generation in large language models (LLMs), including byte-level LLMs, which are tokeniser-free but prohibitively slow. However, existing MTP methods often sacrifice expressiveness by assuming independence between future tokens. In this work, we investigate the trade-off between expressiveness and latency in MTP within the framework of probabilistic circuits (PCs). Our framework, named MTPC, allows one to explore different ways to encode the joint distributions over future tokens by selecting different circuit architectures, generalising classical models such as (hierarchical) mixture models, hidden Markov models and tensor networks. We show the efficacy of MTPC by retrofitting existing byte-level LLMs, such as EvaByte. Our experiments show that, when combined with speculative decoding, MTPC significantly speeds up generation compared to MTP with independence assumptions, while guaranteeing to retain the performance of the original verifier LLM. We also rigorously study the optimal trade-off between expressiveness and latency when exploring the possible parameterisations of MTPC, such as PC architectures and partial layer sharing between the verifier and draft LLMs."
supplemental: 
bibtex: "@misc{grivas2025fast,<br/>
      title={Fast and Expressive Multi-Token Prediction with Probabilistic Circuits},<br/> 
      author={Andreas Grivas and Lorenzo Loconte and Emile van Krieken and Piotr Nawrot and Yu Zhao and Euan Wielewski and Pasquale Minervini and Edoardo Ponti and Antonio Vergari},<br/>
      year={2025},<br/>
      eprint={2511.11346},<br/>
      archivePrefix={arXiv},<br/>
      primaryClass={cs.LG}}"
---
