# 🧠 Simplified Mixture of Experts with Prompt Routing

This notebook demonstrates a minimal implementation of a **Mixture of Experts (MoE)** architecture using pretrained language models and semantic similarity–based routing.

The goal is to provide a clear, educational example of how prompts can be routed to the most relevant "expert" model based on the meaning of the prompt.

## 📌 Overview

- Define a set of expert models, each specialized for a different task (e.g., code generation, classification, question answering).
- Use sentence embeddings to represent both the user prompt and expert capabilities.
- Route prompts to the most relevant expert using cosine similarity.

This is a simplified version of the expert routing logic often used in MoE systems, made beginner-friendly and easy to experiment with.

## 🧰 Requirements

Install dependencies using:

```bash
pip install transformers sentence-transformers
