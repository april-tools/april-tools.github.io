---
collection: publications
ref: "maveli2026compress"
permalink: "publications/maveli2026compress"
title: "Can LLMs Compress (and Decompress)? Evaluating Code Understanding and Execution via Invertibility"
date: 2026-01-19 00:00
tags: generative llms evaluation
image: "/images/papers/maveli2026compress/llm_compress.png"
authors: "Nickil Maveli, Antonio Vergari, Shay B. Cohen"
paperurl: "https://arxiv.org/abs/2601.13398"
pdf: "https://arxiv.org/pdf/2601.13398"
venue: "arXiv 2026"
excerpt: "We introduce RTCE, a new benchmark which shows that even state-of-the-art code LLMs struggle to maintain consistent reasoning between forward and reverse execution, highlighting a lack of true round-trip coherence."
abstract: "LLMs demonstrate strong performance on code benchmarks, yet round-trip code execution reveals limitations in their ability to maintain consistent reasoning across forward and backward execution. We present RoundTripCodeEval (RTCE), a comprehensive benchmark consisting of four distinct code execution reasoning tasks designed to rigorously test round-trip consistency. RTCE provides an execution-free, exact-match evaluation of bijection fidelity, assessing whether models preserve a consistent one-to-one mapping between encoding and decoding operations across various algorithms and directions. We systematically evaluate state-of-the-art Code-LLMs using zero-shot prompting, supervised fine-tuning on execution traces, and self-reflection mechanisms. Each yields modest improvements, but none closes the gap, indicating that current LLMs struggle with true round-trip consistency, which demonstrates that they lack the internal coherence required for trustworthy code reasoning. RTCE surfaces several new and previously unmeasured insights that are not captured by existing I/O-prediction, execution-reasoning, or round-trip natural-language benchmarks. We will release the code and the dataset upon acceptance."
supplemental: 
bibtex: "@misc{maveli2026llmscompressanddecompress,
  title={Can LLMs Compress (and Decompress)? Evaluating Code Understanding and Execution via Invertibility}, 
  author={Nickil Maveli and Antonio Vergari and Shay B. Cohen},
  year={2026},
  eprint={2601.13398},
  archivePrefix={arXiv},
  primaryClass={cs.LG},
  url={https://arxiv.org/abs/2601.13398}, 
}"
---