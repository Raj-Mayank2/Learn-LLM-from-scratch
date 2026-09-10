# 🧠 LLM Learning — From Fundamentals to Production

A structured, hands-on journey to understand **Large Language Models from first principles**, implement the core concepts from scratch, and gradually build a complete LLM-powered application.

---

## 📚 Learning Philosophy

This repository focuses on **understanding, not memorization**.

For every chapter:

```text
📖 Theory
   ↓
🧮 Necessary Mathematics
   ↓
💻 Implement From Scratch
   ↓
🔥 PyTorch Implementation
   ↓
🧪 Experiments
   ↓
🎤 Interview Questions
   ↓
📓 Clean Colab Notebook
   ↓
🐙 GitHub
   ↓
➡️ Next Chapter
```

### Notebook Learning Flow

```text
📝 Markdown Explanation
        ↓
💻 Code
        ↓
🔍 Understand the Output
        ↓
📝 Markdown Explanation
        ↓
💻 Code
        ↓
🧪 Experiment
        ↓
➡️ Next Concept
```

---

# 🗺️ Complete Roadmap

## Phase 1 — Foundations

| #  | Chapter                               | Status      |
| -- | ------------------------------------- | ----------- |
| 01 | What Is an LLM?                       | ✅ Completed |
| 02 | Tokenization & Embeddings             | ✅ Completed |
| 03 | Neural Networks for Language Modeling | ✅ Completed |

```text
██████████  3/3
```

---

## Phase 2 — Transformers

| #  | Chapter                               | Status      |
| -- | ------------------------------------- | ----------- |
| 04 | Attention                             | ✅ Completed |
| 05 | Self-Attention & Multi-Head Attention | ✅ Completed |
| 06 | Transformer Architecture              | ✅ Completed |

```text
██████████  3/3
```

---

## Phase 3 — Build GPT

| #  | Chapter          | Status     |
| -- | ---------------- | ---------- |
| 07 | GPT From Scratch | 🔜 Next    |
| 08 | Train GPT        | ⬜ Upcoming |
| 09 | Text Generation  | ⬜ Upcoming |

```text
░░░░░░░░░░  0/3
```

---

## Phase 4 — Modern LLMs

| #  | Chapter                   | Status     |
| -- | ------------------------- | ---------- |
| 10 | Pretraining & Fine-Tuning | ⬜ Upcoming |
| 11 | LoRA & Instruction Tuning | ⬜ Upcoming |
| 12 | Hugging Face & LLM APIs   | ⬜ Upcoming |

```text
░░░░░░░░░░  0/3
```

---

## Phase 5 — LLM Applications

| #  | Chapter                      | Status     |
| -- | ---------------------------- | ---------- |
| 13 | Prompt Engineering           | ⬜ Upcoming |
| 14 | Embeddings & Semantic Search | ⬜ Upcoming |
| 15 | RAG                          | ⬜ Upcoming |
| 16 | LLM Agents & Tool Calling    | ⬜ Upcoming |

```text
░░░░░░░░░░  0/4
```

---

## Phase 6 — LLM Engineering

| #  | Chapter                                | Status     |
| -- | -------------------------------------- | ---------- |
| 17 | Evaluation, Hallucinations & Inference | ⬜ Upcoming |
| 18 | Final LLM Application                  | ⬜ Upcoming |

```text
░░░░░░░░░░  0/2
```

---

# 📊 Overall Progress

```text
██████░░░░  6/18
```

**6 of 18 chapters completed**

---

# 📖 Chapter Details

## Chapter 1 — What Is an LLM?

### Topics Covered

* AI → ML → Deep Learning → NLP → LLM
* Language modeling
* Tokens
* Next-token prediction
* Training vs inference
* Parameters and weights
* Basic statistical language models

### Notebook

`01_what_is_an_llm.ipynb`

---

## Chapter 2 — Tokenization & Embeddings

### Topics Covered

* Character-level tokenization
* Word-level tokenization
* Subword tokenization
* Vocabulary
* Token IDs
* Encoding and decoding
* Token embeddings
* Embedding dimensions
* Embedding matrices
* Positional information

### Notebook

`02_tokenization_embeddings.ipynb`

---

## Chapter 3 — Neural Networks for Language Modeling

### Topics Covered

* Neural networks
* Parameters and weights
* Forward propagation
* Activation functions
* Logits
* Probabilities
* Cross-entropy loss
* Gradients
* Backpropagation
* Gradient descent
* Training loop
* Tiny neural language model

### Notebook

`03_neural_language_model.ipynb`

---

## Chapter 4 — Attention

### Topics Covered

* Why attention is needed
* Query, Key, Value
* Dot-product similarity
* Attention scores
* Softmax
* Attention weights
* Weighted aggregation
* Multiple queries
* Scaling
* Attention from scratch
* NumPy implementation
* PyTorch implementation
* Attention experiments




## Chapter 5 — Self-Attention & Multi-Head Attention

### Topics Covered

* Self-attention
* Q, K, V projections
* Attention score matrix
* Scaled dot-product attention
* Softmax
* Attention weights
* Weighted aggregation
* Causal masking
* Why GPT requires causal masking
* Self-attention from scratch
* NumPy implementation
* PyTorch implementation
* Multi-head attention
* Attention heads
* Head dimension
* Concatenation of heads
* Output projection
* Self-attention vs cross-attention
* Multi-head attention experiments

### Core Equations

$$
Q=XW_Q
$$

$$
K=XW_K
$$

$$
V=XW_V
$$

$$
Attention(Q,K,V)
=
softmax
\left(
\frac{QK^T}{\sqrt{d_k}}
\right)V
$$

$$
MultiHead =
Concat(head_1,\ldots,head_h)W_O
$$

### Notebook

`05_self_attention.ipynb`

---

## Chapter 6 — Transformer Architecture

### Topics Covered

* Transformer blocks
* Multi-head self-attention
* Residual connections
* Layer normalization
* Feed-forward networks
* GELU activation
* Dropout
* Causal attention
* Complete Transformer block
* PyTorch implementation
* Transformer shape tracking

### Core Equations

Residual connection:

$$
Y=X+F(X)
$$

Feed-forward network:

$$
FFN(x)=W_2\,GELU(W_1x+b_1)+b_2
$$

Transformer block:

```text
Input
  ↓
Multi-Head Self-Attention
  ↓
Residual + LayerNorm
  ↓
Feed-Forward Network
  ↓
Residual + LayerNorm
  ↓
Output
```

### Notebook

`06_transformer.ipynb`

---

# 🔜 Current Chapter

## Chapter 7 — GPT From Scratch

Now we move from understanding individual Transformer components to building an actual **GPT-style model**.

### Topics

* Decoder-only architecture
* Token embeddings
* Positional embeddings
* Transformer blocks
* Causal self-attention
* Feed-forward networks
* Language-model head
* Complete GPT model
* Forward pass
* Parameter counting

### Notebook

`07_gpt_from_scratch.ipynb`

---

# 🗂️ Repository Structure

```text
llm-learning/
│
├── README.md
│
├── 01_what_is_an_llm.ipynb
├── 02_tokenization_embeddings.ipynb
├── 03_neural_language_model.ipynb
├── 04_attention.ipynb
├── 05_self_attention.ipynb
├── 06_transformer.ipynb
├── 07_gpt_from_scratch.ipynb
├── 08_train_gpt.ipynb
├── 09_text_generation.ipynb
├── 10_pretraining_finetuning.ipynb
├── 11_lora_instruction_tuning.ipynb
├── 12_huggingface_and_apis.ipynb
├── 13_prompt_engineering.ipynb
├── 14_semantic_search.ipynb
├── 15_rag.ipynb
├── 16_llm_agents.ipynb
├── 17_llm_engineering.ipynb
│
└── 18_final_llm_application/
```

---

# 🎯 Final Goal

Understand the complete LLM stack:

```text
Language
   ↓
Tokens
   ↓
Embeddings
   ↓
Neural Networks
   ↓
Attention
   ↓
Self-Attention
   ↓
Multi-Head Attention
   ↓
Transformer
   ↓
GPT
   ↓
Pretraining
   ↓
Fine-Tuning
   ↓
Instruction Tuning
   ↓
Prompting
   ↓
Embeddings
   ↓
Semantic Search
   ↓
RAG
   ↓
Agents & Tool Calling
   ↓
Evaluation
   ↓
Production LLM Application
```

---

# 🚀 Status

**Current:** Chapter 6 completed ✅

**Next:** Chapter 7 — GPT From Scratch 🔜

**Overall:** 6 / 18 chapters completed
