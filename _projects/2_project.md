---
layout: page
title: LLM Evaluation Framework
description: An evaluation harness for clinical and general-purpose LLMs, with a depth-vs-cost analysis of recursive self-refinement.
importance: 2
category: Production
---

A reproducible evaluation framework for benchmarking LLM outputs on accuracy, faithfulness, and semantic similarity, with a CI pipeline that reruns benchmarks on every change.

**Stack:** FastAPI · Streamlit · Docker · GitHub Actions CI

**Results:**

- PubMedQA accuracy 0.70
- Faithfulness 0.84
- BERTScore 0.693
- Average latency 3.8s, cost $0.000053 / 1k tokens

**RLM Depth Analyzer:** a recursive self-refinement module that empirically shows refinement past depth 1 yields no accuracy gain, at 3.5x the cost — a concrete argument against over-engineering agentic reasoning loops.

**Links:** [GitHub](https://github.com/Neel-K26/llm-eval)
