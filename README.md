# MASC 515 Assignment 3: microGPT Enhancements

## Overview
This project extends Karpathy's microGPT implementation by adding modern deep learning techniques:
- GELU activation
- RoPE positional encoding
- LoRA (Low-Rank Adaptation)
- Mixture of Experts (MoE)

---

## 1. GELU (Gaussian Error Linear Unit)
GELU is a smooth activation function that improves performance over ReLU by allowing small negative values to pass through in a probabilistic way.

---

## 2. RoPE (Rotary Positional Embedding)
RoPE replaces traditional positional embeddings by rotating token representations using sine and cosine functions, improving sequence modeling.

---

## 3. LoRA (Low-Rank Adaptation)
LoRA reduces training cost by approximating weight updates using low-rank matrices instead of updating full weight matrices.

---

## 4. Mixture of Experts (MoE)
MoE uses multiple neural network “experts” and combines their outputs, allowing the model to learn specialized behaviors efficiently.

---

## Conclusion
These enhancements demonstrate how modern techniques improve transformer architectures in terms of efficiency and performance.
