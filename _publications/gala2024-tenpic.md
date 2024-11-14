---
collection: publications
ref: "gala2024tenpics"
permalink: "publications/gala2024tenpics"
title:  "Scaling Continuous Latent Variable Models as Probabilistic Integral Circuits"
date:   2024-09-26 00:00
tags: circuits probml
image: "/images/papers/gala2024tenpics/tenpics.png"
authors: "Gennaro Gala, Cassio de Campos, Antonio Vergari*, Erik Quaeghebeur*"
paperurl: "https://arxiv.org/abs/2406.06494"
pdf: "https://arxiv.org/pdf/2406.06494"
venue: "NeurIPS 2024"
award: "spotlight (top 2%)"
excerpt: "We scale continuous latent variable mixtures and adapt them to have intricate dependencies, obtaining state-of-the-art likelihoods for tractable models"
abstract: "Probabilistic integral circuits (PICs) have been recently introduced as probabilistic models enjoying the key ingredient behind expressive generative models: continuous latent variables (LVs). PICs are symbolic computational graphs defining continuous LV models as hierarchies of functions that are summed and multiplied together, or integrated over some LVs. They are tractable if LVs can be analytically integrated out, otherwise they can be approximated by tractable probabilistic circuits (PC) encoding a hierarchical numerical quadrature process, called QPCs. So far, only tree-shaped PICs have been explored, and training them via numerical quadrature requires memory-intensive processing at scale. In this paper, we address these issues, and present: (i) a pipeline for building DAG-shaped PICs out of arbitrary variable decompositions, (ii) a procedure for training PICs using tensorized circuit architectures, and (iii) neural functional sharing techniques to allow scalable training. In extensive experiments, we showcase the effectiveness of functional sharing and the superiority of QPCs over traditional PCs."
supplemental: 
bibtex: "@inproceedings{gala2024scaling,
  title={Scaling Continuous Latent Variable Models as Probabilistic Integral Circuits},
  author={Gala, Gennaro and de Campos, Cassio and Vergari, Antonio and Quaeghebeur, Erik},
  booktitle={NeurIPS},
  year={2024}
}"
---