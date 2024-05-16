---
collection: publications
ref: "tai2024pixar"
permalink: "publications/tai2024pixar"
title:  "PIXAR: Auto-Regressive Language Modeling in Pixel Space"
date:   2024-05-16 00:00
tags: generative llms 
image: "/images/papers/tai2024pixar/pixar.apng"
authors: "Yintao Tai, Xiyang Liao, Alessandro Suglia, Antonio Vergari"
paperurl: "https://arxiv.org/abs/2401.03321"
pdf: "https://arxiv.org/pdf/2401.03321.pdf"
venue: "ACL 2024 Findings"
code: "https://github.com/april-tools/pixar"
excerpt: "Can LLMs understand, reason about and generate text by operating only on perceptual information such as pixels? We build PIXAR, the first generative pixel-based LLM to answer it."
abstract: "Recent work showed the possibility of building open-vocabulary large language models (LLMs) that directly operate on pixel representations. These models are implemented as autoencoders that reconstruct masked patches of rendered text. However, these pixel-based LLMs are limited to discriminative tasks (e.g., classification) and, similar to BERT, cannot be used to <i>generate text</i>. Therefore, they cannot be used for generative tasks such as free-form question answering. In this work, we introduce PIXAR, the first pixel-based autoregressive LLM that performs text generation. Consisting of only a decoder, PIXAR can perform free-form generative tasks 
while keeping the number of parameters on par with previous encoder-decoder models. Furthermore, we highlight the challenges of generating text as non-noisy images and show this is due to using a maximum likelihood objective. To overcome this problem, we propose an adversarial pretraining stage that improves the readability and accuracy of PIXAR by 8.1 on LAMBADA and 8.5 on bAbI--- making it comparable to GPT-2 on text generation tasks. This paves the way to build open-vocabulary LLMs that operate on perceptual input only and calls into question the necessity of the usual symbolic input representation, i.e., text as (sub)tokens."
supplemental: 
bibtex: "@inproceedings{tai2024pixar,<br/>
  title={PIXAR: Auto-Regressive Language Modeling in Pixel Space},<br/>
  author={Yintao Tai, Xiyang Liao, Alessandro Suglia, Antonio Vergari,<br/>
  booktitle={Findings of the Association for Computational Linguistics: ACL 2024},<br/>
  year={2024}
}"
---