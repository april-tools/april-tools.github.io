---
collection: publications
ref: "faber2024m2i2m"
permalink: "publications/faber2024m2i2m"
title:  "From MNIST to ImageNet and Back: Benchmarking Continual Curriculum Learning"
date:   2024-02-14 00:00
tags: probml continual 
image: "/images/papers/faber2024m2i2m/m2i.png"
authors: "Kamil Faber, Dominik Zurek, Marcin Pietron, Nathalie Japkowicz, Antonio Vergari, Roberto Corizzo"
paperurl: "https://arxiv.org/abs/2303.11076"
pdf: "https://arxiv.org/pdf/2303.11076.pdf"
venue: "Machine Learning"
excerpt: "We create two challenging benchmarks for continual learning (CL) that comprise a sequence of image classification tasks: generalizing from MNIST to (tiny) ImageNet and vice versa, highlighting in a thorough set of experiments that sota CL method fall prey of catastrophic forgetting."
abstract: "Continual learning (CL) is one of the most promising trends in recent machine learning research. Its goal is to go beyond classical assumptions in machine learning and develop models and learning strategies that present high robustness in dynamic environments. The landscape of CL research is fragmented into several learning evaluation protocols, comprising different learning tasks, datasets, and evaluation metrics. Additionally, the benchmarks adopted so far are still distant from the complexity of real-world scenarios, and are usually tailored to highlight capabilities specific to certain strategies. In such a landscape, it is hard to objectively assess strategies. In this work, we fill this gap for CL on image data by introducing two novel CL benchmarks that involve multiple heterogeneous tasks from six image datasets, with varying levels of complexity and quality. Our aim is to fairly evaluate current state-of-the-art CL strategies on a common ground that is closer to complex real-world scenarios. We additionally structure our benchmarks so that tasks are presented in increasing and decreasing order of complexity -- according to a curriculum -- in order to evaluate if current CL models are able to exploit structure across tasks. We devote particular emphasis to providing the CL community with a rigorous and reproducible evaluation protocol for measuring the ability of a model to generalize and not to forget while learning. Furthermore, we provide an extensive experimental evaluation showing that popular CL strategies, when challenged with our benchmarks, yield sub-par performance, high levels of forgetting, and present a limited ability to effectively leverage curriculum task ordering. We believe that these results highlight the need for rigorous comparisons in future CL works as well as pave the way to design new CL strategies that are able to deal with more complex scenarios. "
supplemental: 
bibtex: "@inproceedings{faber2024m2i2m,<br/>
  title={From MNIST to ImageNet and Back: Benchmarking Continual Curriculum Learning},<br/>
  author={Kamil Faber, Dominik Zurek, Marcin Pietron, Nathalie Japkowicz, Antonio Vergari, Roberto Corizzo,<br/>
  booktitle={Proceedings of the AAAI-22 Workshop on Interactive Machine Learning (IML'22)},<br/>
  year={2022}
}"
---