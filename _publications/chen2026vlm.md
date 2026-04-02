---
collection: publications
ref: "chen2026vlm"
permalink: "publications/chen2026vlm"
title:  "Can VLMs Reason Robustly? A Neuro-Symbolic Investigation"
date:   2026-03-25 00:00
tags: nesy probml vlm 
image: "/images/papers/chen2026vlm/vlm.png"
authors: "Weixin Chen, Antonio Vergari, Han Zhao"
paperurl: "https://arxiv.org/abs/2603.23867"
pdf: "https://arxiv.org/pdf/2603.23867"
venue: "arXiv 2026"
excerpt: "We show that standard vision-language models fail under covariate shift and propose VLC, a neuro-symbolic approach that combines learned perception with exact symbolic circuits to achieve robust visual reasoning."
abstract: "Vision-Language Models (VLMs) have been applied to a wide range of reasoning tasks, yet it remains unclear whether they can reason robustly under distribution shifts. In this paper, we study covariate shifts in which the perceptual input distribution changes while the underlying prediction rules do not. To investigate this question, we consider visual deductive reasoning tasks, where a model is required to answer a query given an image and logical rules defined over the object concepts in the image. Empirically, we find that VLMs fine-tuned through gradient-based end-to-end training can achieve high in-distribution accuracy but fail to generalize under such shifts, suggesting that fine-tuning does not reliably induce the underlying reasoning function. This motivates a neuro-symbolic perspective that decouples perception from reasoning. However, we further observe that recent neuro-symbolic approaches that rely on black-box components for reasoning can still exhibit inconsistent robustness across tasks. To address this issue, we propose VLC, a neuro-symbolic method that combines VLM-based concept recognition with circuit-based symbolic reasoning. In particular, task rules are compiled into a symbolic program, specifically a circuit, which executes the rules exactly over the object concepts recognized by the VLM. Experiments on three visual deductive reasoning tasks with distinct rule sets show that VLC consistently achieves strong performance under covariate shifts, highlighting its ability to support robust reasoning."
supplemental: 
bibtex: "@misc{chen2026vlmsreasonrobustlyneurosymbolic,
    title={Can VLMs Reason Robustly? A Neuro-Symbolic Investigation}, 
    author={Weixin Chen and Antonio Vergari and Han Zhao},
    year={2026},
    eprint={2603.23867},
    archivePrefix={arXiv},
    primaryClass={cs.LG},
    url={https://arxiv.org/abs/2603.23867}, 
}"
---