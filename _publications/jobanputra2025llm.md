---
collection: publications
ref: "jobanputra2025llm"
permalink: "publications/jobanputra2026llm"
title:  "Can LLMs subtract numbers?"
date:   2025-11-04 00:00
tags: llm reasoning nesy
image: "/images/papers/jobanputra2025llm/llm_subtraction.png"
authors: "Mayank Jobanputra, Nils Philipp Walter, Maitrey Mehta, Blerta Veseli, Evan Parker Kelly Chapple, Yifan Wang, Sneha Chetani, Ellie Pavlick, Antonio Vergari, Vera Demberg"
paperurl: "https://arxiv.org/abs/2511.02795"
pdf: "https://arxiv.org/pdf/2511.02795"
venue: "arXiv 2025"
excerpt: "We show that LLMs' subtraction accuracy significantly lags behind addition, but that instruction tuning can largely fix this weakness."
abstract: "We present a systematic study of subtraction in large language models (LLMs). While prior benchmarks emphasize addition and multiplication, subtraction has received comparatively little attention despite being structurally distinct as a non-commutative operation. We evaluate eight pretrained LLMs spanning four families on addition and subtraction problems. Our experiments reveal that subtraction accuracy lags behind addition by a wide margin. We find that the errors for (a - b) are concentrated in cases where (a < b). In such cases, LLMs frequently produce the correct magnitude but omit the negative sign. Probing analyses show that LLMs internally encode whether results should be negative, yet this information is often not reflected in generated outputs. We further test well-known techniques such as few-shot learning and instruction-tuning to see if they can improve the LLMs' performance. Our results suggest that while few-shot prompting yields modest gains, the instruction-tuned models achieve near-perfect accuracies in generating the negative sign. Together, these findings provide a clearer characterization of the limitations and recoverability of LLMs' arithmetic capabilities in subtraction."
supplemental: 
bibtex: "@misc{jobanputra2025llmssubtractnumbers,
  title={Can LLMs subtract numbers?}, 
  author={Mayank Jobanputra and Nils Philipp Walter and Maitrey Mehta and Blerta Veseli and Evan Parker Kelly Chapple and Yifan Wang and Sneha Chetani and Ellie Pavlick and Antonio Vergari and Vera Demberg},
  year={2025},
  eprint={2511.02795},
  archivePrefix={arXiv},
  primaryClass={cs.LG},
  url={https://arxiv.org/abs/2511.02795}, 
}"
---
