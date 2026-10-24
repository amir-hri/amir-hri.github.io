---
title: RAG Doesn’t Need the Entire Suitcase!
date: 2026-10-24
topic: RAG, Information Theory
summary: "RAG gives an LLM retrieved documents to help answer a question, but
  useful evidence often arrives with extra baggage. An ACL 2024 paper applies
  information bottleneck theory to train a filter that preserves information
  useful for answering while compressing the context. Think of packing a
  suitcase: bring what the answer needs, not the entire wardrobe! In their
  question-answering experiments, the filter reduced the retrieved text to about
  2.5% of its original length while improving answer accuracy. That doesn’t mean
  everything removed was useless, or that every system can achieve the same
  result. The goal is enough evidence for a correct answer, with fewer
  distractions."
takeaway: More context isn’t automatically better. The goal is to preserve
  useful evidence while reducing distractions, then check whether the answer
  actually improves.
source: https://aclanthology.org/2024.acl-long.59/
published: true
---
