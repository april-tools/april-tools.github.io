---
collection: publications
ref: "maveli2024seqcobench"
permalink: "publications/maveli2024seqcobench"
title: "What can Large Language Models Capture about Code Functional Equivalence?"
date: 2024-08-24 00:00
tags: generative llms evaluation
image: "/images/papers/maveli2024seqcobench/seqcobench.png"
authors: "Nickil Maveli, Antonio Vergari, Shay B. Cohen"
paperurl: "https://www.arxiv.org/abs/2408.11081"
pdf: "https://www.arxiv.org/pdf/2408.11081"
venue: "arXiv 2024"
excerpt: "The performance gap between match-based and LLM-based code evaluation metrics in assessing the code functional equivalence is minimal."
abstract: "Code-LLMs, LLMs pre-trained on large code corpora, have shown great progress in learning rich representations of the structure and syntax of code, successfully using it to generate or classify code fragments. At the same time, understanding if they are able to do so because they capture code semantics, and how well, is still an open question. In this paper, we tackle this problem by introducing SeqCoBench, a benchmark for systematically assessing how Code-LLMs can capture code functional equivalence. SeqCoBench contains over 20 code transformations that either preserve or alter the semantics of Python programs. We conduct extensive evaluations in different settings, including zero-shot and parameter-efficient finetuning methods on state-of-the-art (Code-)LLMs to see if they can discern semantically equivalent or different pairs of programs in SeqCoBench. We find that the performance gap between these LLMs and classical match-based retrieval scores is minimal, with both approaches showing a concerning lack of depth in understanding code semantics."
supplemental: 
bibtex: "@article{maveli2024can,
  title={What can Large Language Models Capture about Code Functional Equivalence?},
  author={Maveli, Nickil and Vergari, Antonio and Cohen, Shay B},
  journal={arXiv preprint arXiv:2408.11081},
  year={2024}
}"
---