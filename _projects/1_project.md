---
layout: page
title: MedRAG — Clinical Intelligence System
description: Faithfulness score 1.0 on first live query. Pure RAG, no LangChain abstraction.
importance: 1
category: Production
---

A retrieval-augmented generation system for clinical question answering, built without a framework abstraction layer so every step of retrieval and generation is inspectable and tunable.

**Stack:** FastAPI · FAISS · sentence-transformers · Groq (llama-3.1-8b-instant) · Streamlit

**Results:**

- Faithfulness score of 1.0 on its first live query
- Hand-rolled retrieval pipeline — no LangChain or similar abstraction

**Links:** [GitHub](https://github.com/Neel-K26/MedRag) · [Live demo](https://nkempire11-medrag.hf.space)
