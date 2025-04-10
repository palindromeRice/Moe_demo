# 🧠 Mixture of Experts (MoE) in LLM Inference – A Simplified Introduction

This notebook introduces the core idea behind the **Mixture of Experts (MoE)** approach used in **large language model (LLM) inference**, through a simplified routing mechanism.

In real-world MoE systems, a gating network dynamically selects a subset of experts based on the input. However, actual implementations are often complex and opaque.  
This notebook simplifies the routing step to help you intuitively understand how expert selection works.

## What This Notebook Demonstrates

- A minimal MoE setup using multiple expert models
- Prompt routing based on semantic similarity instead of a learned gate
- How sentence embeddings and cosine similarity can approximate routing decisions

This is **not a production MoE system**, but a lightweight and interpretable way to **grasp the routing logic** that underpins MoE-based LLMs.

## Requirements

```bash
pip install transformers sentence-transformers
