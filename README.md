# Byte Pair Encoding and Autoregressive Causal Language Model from Scratch

##  Overview

This project implements two fundamental Natural Language Processing (NLP) concepts from scratch:

1. **Byte Pair Encoding (BPE)**
2. **Autoregressive Causal Language Model**

Byte Pair Encoding is used to divide text into meaningful subword tokens. These tokens are converted into numerical token IDs and provided as input to an autoregressive causal language model. The language model learns to predict the next token based on the previous tokens in a sequence.

This project provides a complete understanding of the basic pipeline used in modern language processing systems.

---

##  Objective

The main objectives of this project are:

- To implement Byte Pair Encoding from scratch.
- To understand subword tokenization.
- To build a vocabulary using frequent symbol pair merging.
- To encode text into subword tokens and token IDs.
- To implement an autoregressive causal language model.
- To understand token embeddings and positional encoding.
- To implement causal masking and self-attention.
- To predict the next token in a sequence.
- To calculate prediction loss.
- To understand the complete workflow of text generation.

---

##  Technology Used

- **Python** – Core programming language.
- **NumPy** – Numerical computation and matrix operations.
- **Jupyter Notebook / JupyterLab** – Development and experimentation environment.
- **GitHub** – Project version control and documentation.

The major algorithms are implemented from scratch without using pre-built tokenizer or language model libraries.

---

##  Applications

This project has applications in:

- Natural Language Processing (NLP)
- Text Tokenization
- Language Modeling
- Text Generation
- Chatbots
- Machine Translation
- Text Completion
- Autocomplete Systems
- Generative Artificial Intelligence
- Large Language Model (LLM) Foundations

---

##  Project Description

###  Byte Pair Encoding

Byte Pair Encoding is a subword tokenization algorithm.

The algorithm begins by representing words as individual characters. It then identifies the most frequently occurring adjacent pair of symbols and merges them into a single token.

For example:

```text
Input:
lowest
## Workflow

Raw Text
    ↓
Corpus
    ↓
Byte Pair Encoding
    ↓
Subword Tokens
    ↓
Vocabulary Creation
    ↓
Token-to-ID Mapping
    ↓
Input-Target Sequences
    ↓
Token Embedding
    ↓
Positional Encoding
    ↓
Causal Masking
    ↓
Self-Attention
    ↓
Linear Layer
    ↓
Softmax
    ↓
Next Token Prediction
    ↓
Loss Calculation
    ↓
Backpropagation
    ↓
Text Generation

---
## Project structure

Byte-Pair-Encoding-and-Causal-Language-Model/
│
├── corpus.txt
│
├── BPE_Tokenizer.ipynb
│
├── Autoregressive_Causal_Language_Model.ipynb
│
└── README.md

---
## Conclusion

This project demonstrates the complete foundation of a modern language processing pipeline.

The Byte Pair Encoding tokenizer converts raw text into meaningful subword tokens and numerical token IDs. These token IDs are then used by the autoregressive causal language model to learn the relationship between tokens and predict the next token in a sequence.

By implementing these concepts from scratch, this project provides a deeper understanding of:

Subword tokenization
Vocabulary construction
Token embeddings
Positional encoding
Causal masking
Self-attention
Next-token prediction
Loss calculation
Backpropagation
Autoregressive text generation
