---
collection: publications
ref: "gala2023pic"
permalink: "publications/gala2023pic"
title:  "Probabilistic Integral Circuits"
date:   2024-01-19 00:00
tags: circuits probml
image: "/images/papers/gala2023pic/pic-comp.png"
authors: "Gennaro Gala, Cassio de Campos, Robert Peharz, Antonio Vergari, Erik Quaeghebeur"
paperurl: "https://proceedings.mlr.press/v238/gala24a.html"
pdf: "https://proceedings.mlr.press/v238/gala24a/gala24a.pdf"
venue: "AISTATS 2024"
code: "https://github.com/gengala/pic"
excerpt: "We represent hierarchical continuous latent variable models as computational graph that allow us to efficiently approximate intractable distributions via recursive quadrature rules"
abstract: "Continuous latent variables (LVs) are a key ingredient of many generative models, as they allow modelling expressive mixtures with an uncountable number of components. In contrast, probabilistic circuits (PCs) are hierarchical discrete mixtures represented as computational graphs composed of input, sum and product units. Unlike continuous LV models, PCs provide tractable inference but are limited to discrete LVs with categorical (i.e. unordered) states. We bridge these model classes by introducing probabilistic integral circuits (PICs), a new language of computational graphs that extends PCs with integral units representing continuous LVs. In the first place, PICs are symbolic computational graphs and are fully tractable in simple cases where analytical integration is possible. In practice, we parameterise PICs with light-weight neural nets delivering an intractable hierarchical continuous mixture that can be approximated arbitrarily well with large PCs using numerical quadrature. On several distribution estimation benchmarks, we show that such PIC-approximating PCs systematically outperform PCs commonly learned via expectation-maximization or SGD."
supplemental: 
bibtex: "
@InProceedings{gala2024pic,
  title = 	 { Probabilistic Integral Circuits },
  author =       {Gala, Gennaro and de Campos, Cassio and Peharz, Robert and Vergari, Antonio and Quaeghebeur, Erik},
  booktitle = 	 {Proceedings of The 27th International Conference on Artificial Intelligence and Statistics},
  pages = 	 {2143--2151},
  year = 	 {2024},
  editor = 	 {Dasgupta, Sanjoy and Mandt, Stephan and Li, Yingzhen},
  volume = 	 {238},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {02--04 May},
  publisher =    {PMLR},
  pdf = 	 {https://proceedings.mlr.press/v238/gala24a/gala24a.pdf},
  url = 	 {https://proceedings.mlr.press/v238/gala24a.html},
  abstract = 	 { Continuous latent variables (LVs) are a key ingredient of many generative models, as they allow modelling expressive mixtures with an uncountable number of components. In contrast, probabilistic circuits (PCs) are hierarchical discrete mixtures represented as computational graphs composed of input, sum and product units. Unlike continuous LV models, PCs provide tractable inference but are limited to discrete LVs with categorical (i.e. unordered) states. We bridge these model classes by introducing probabilistic integral circuits (PICs), a new language of computational graphs that extends PCs with integral units representing continuous LVs. In the first place, PICs are symbolic computational graphs and are fully tractable in simple cases where analytical integration is possible. In practice, we parameterise PICs with light-weight neural nets delivering an intractable hierarchical continuous mixture that can be approximated arbitrarily well with large PCs using numerical quadrature. On several distribution estimation benchmarks, we show that such PIC-approximating PCs systematically outperform PCs commonly learned via expectation-maximization or SGD. }
}
"
---