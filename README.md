# 🧠 LLM Learning From Scratch

A **hands-on, code-first journey to understanding Large Language Models from the ground up**.

This repository contains my learning notes, explanations, experiments, and Google Colab notebooks as I work through LLM concepts step by step.

The goal is not simply to learn how to **use** LLMs, but to understand **how they work internally** and eventually build a complete LLM-powered application.

---

## 🎯 Goal

By completing this repository, I aim to understand:

* How language models work
* How text is represented numerically
* How neural networks learn language
* How attention and Transformers work
* How GPT-style models are built
* How LLMs are trained and fine-tuned
* How modern LLM applications are built
* How RAG and tool-using agents work
* How LLM applications are evaluated and optimized

---

# 📚 Learning Path

The course is divided into six phases.

## Phase 1 — Foundations

| #  | Chapter                               | Status      |
| -- | ------------------------------------- | ----------- |
| 01 | What Is an LLM?                       | ✅ Completed |
| 02 | Tokenization & Embeddings             | ✅ Completed |
| 03 | Neural Networks for Language Modeling | ✅ Completed |

### 01 — What Is an LLM?

Learn the fundamental idea behind language models.

**Topics:**

* AI → ML → Deep Learning → NLP → LLM
* Language modeling
* Tokens and next-token prediction
* Training vs inference
* Parameters and weights
* Basic statistical language model

**Notebook:** `01_what_is_an_llm.ipynb`

---

### 02 — Tokenization & Embeddings

Understand how text is converted into numerical representations.

**Topics:**

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

**Notebook:** `02_tokenization_embeddings.ipynb`

---

### 03 — Neural Networks for Language Modeling

Understand how neural networks learn to predict the next token.

**Topics:**

* Neural networks
* Parameters and weights
* Forward propagation
* Activation functions
* Logits and probabilities
* Loss
* Cross-entropy
* Gradients
* Backpropagation
* Gradient descent
* Training loop
* Tiny neural language model

**Notebook:** `03_neural_language_model.ipynb`

---

# Phase 2 — Transformers

| #  | Chapter                               | Status     |
| -- | ------------------------------------- | ---------- |
| 04 | Attention                             | 🔜 Next    |
| 05 | Self-Attention & Multi-Head Attention | ⬜ Upcoming |
| 06 | Transformer Architecture              | ⬜ Upcoming |

### 04 — Attention

* Query, Key, Value
* Attention scores
* Scaling
* Softmax
* Weighted aggregation
* Attention from scratch

**Notebook:** `04_attention.ipynb`

### 05 — Self-Attention & Multi-Head Attention

* Self-attention
* Causal masking
* Multiple attention heads
* Concatenation
* Projection

**Notebook:** `05_self_attention.ipynb`

### 06 — Transformer Architecture

* Transformer blocks
* Residual connections
* Layer normalization
* Feed-forward networks
* Dropout
* Positional embeddings

**Notebook:** `06_transformer.ipynb`

---

# Phase 3 — Build GPT

| #  | Chapter          | Status     |
| -- | ---------------- | ---------- |
| 07 | GPT From Scratch | ⬜ Upcoming |
| 08 | Train GPT        | ⬜ Upcoming |
| 09 | Text Generation  | ⬜ Upcoming |

### 07 — GPT From Scratch

Build a complete decoder-only GPT-style model.

**Notebook:** `07_gpt_from_scratch.ipynb`

### 08 — Train GPT

Train our GPT model using next-token prediction.

**Notebook:** `08_train_gpt.ipynb`

### 09 — Text Generation

Understand and implement:

* Logits
* Probabilities
* Temperature
* Greedy decoding
* Random sampling
* Top-K
* Top-P

**Notebook:** `09_text_generation.ipynb`

---

# Phase 4 — Modern LLMs

| #  | Chapter                   | Status     |
| -- | ------------------------- | ---------- |
| 10 | Pretraining & Fine-Tuning | ⬜ Upcoming |
| 11 | LoRA & Instruction Tuning | ⬜ Upcoming |
| 12 | Hugging Face & LLM APIs   | ⬜ Upcoming |

### 10 — Pretraining & Fine-Tuning

* Pretraining
* Supervised fine-tuning
* Instruction datasets
* Base vs fine-tuned models
* Parameter-efficient fine-tuning

**Notebook:** `10_pretraining_finetuning.ipynb`

### 11 — LoRA & Instruction Tuning

* Parameter freezing
* LoRA
* Instruction following
* Chat formatting
* Fine-tuning a model

**Notebook:** `11_lora_instruction_tuning.ipynb`

### 12 — Hugging Face & LLM APIs

* Pretrained models
* Tokenizers
* Model inference
* Generation
* LLM APIs
* Streaming

**Notebook:** `12_huggingface_and_apis.ipynb`

---

# Phase 5 — LLM Applications

| #  | Chapter                      | Status     |
| -- | ---------------------------- | ---------- |
| 13 | Prompt Engineering           | ⬜ Upcoming |
| 14 | Embeddings & Semantic Search | ⬜ Upcoming |
| 15 | RAG                          | ⬜ Upcoming |
| 16 | LLM Agents & Tool Calling    | ⬜ Upcoming |

### 13 — Prompt Engineering

* Zero-shot prompting
* Few-shot prompting
* Structured prompts
* Output constraints
* Prompt experimentation

**Notebook:** `13_prompt_engineering.ipynb`

### 14 — Embeddings & Semantic Search

* Document embeddings
* Cosine similarity
* Vector search
* Semantic retrieval

**Notebook:** `14_semantic_search.ipynb`

### 15 — RAG

* Retrieval-Augmented Generation
* Document ingestion
* Chunking
* Embeddings
* Retrieval
* Context construction
* Generation

**Notebook:** `15_rag.ipynb`

### 16 — LLM Agents & Tool Calling

* Tools
* Function calling
* Tool selection
* Tool execution
* Agent loop

**Notebook:** `16_llm_agents.ipynb`

---

# Phase 6 — LLM Engineering

| #  | Chapter                                | Status     |
| -- | -------------------------------------- | ---------- |
| 17 | Evaluation, Hallucinations & Inference | ⬜ Upcoming |
| 18 | Final LLM Application                  | ⬜ Upcoming |

### 17 — Evaluation, Hallucinations & Inference

* LLM evaluation
* Perplexity
* Hallucinations
* Grounding
* KV cache
* Quantization
* Inference efficiency

**Notebook:** `17_llm_engineering.ipynb`

### 18 — Final LLM Application

Build a complete LLM application combining:

* LLM
* Prompting
* Conversation
* Embeddings
* RAG
* Tool calling
* Evaluation
* API

**Project:** `18_final_llm_application/`

---

# 🧠 Learning Method

Every chapter follows the same process:

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
🎯 Interview Questions
   ↓
📓 Google Colab Notebook
   ↓
🐙 GitHub
   ↓
➡️ Next Chapter
```

The focus is **understanding, not memorization**.

Important concepts will first be implemented from scratch so that the underlying mechanics are clear before using higher-level libraries.

---

# 📁 Repository Structure

```text
llm-learning/
│
├── README.md
│
├── 01_what_is_an_llm.ipynb
├── 02_tokenization_embeddings.ipynb
├── 03_neural_language_model.ipynb
│
├── 04_attention.ipynb
├── 05_self_attention.ipynb
├── 06_transformer.ipynb
│
├── 07_gpt_from_scratch.ipynb
├── 08_train_gpt.ipynb
├── 09_text_generation.ipynb
│
├── 10_pretraining_finetuning.ipynb
├── 11_lora_instruction_tuning.ipynb
├── 12_huggingface_and_apis.ipynb
│
├── 13_prompt_engineering.ipynb
├── 14_semantic_search.ipynb
├── 15_rag.ipynb
├── 16_llm_agents.ipynb
│
├── 17_llm_engineering.ipynb
│
└── 18_final_llm_application/
```

---

# 📊 Progress

```text
Phase 1 — Foundations       ██████████  3/3
Phase 2 — Transformers      ░░░░░░░░░░  0/3
Phase 3 — Build GPT         ░░░░░░░░░░  0/3
Phase 4 — Modern LLMs       ░░░░░░░░░░  0/3
Phase 5 — Applications      ░░░░░░░░░░  0/4
Phase 6 — Engineering       ░░░░░░░░░░  0/2
```

**Overall: 3 / 18 chapters completed**

---

# 🛠️ Tools & Technologies

The learning process primarily uses:

* Python
* NumPy
* PyTorch
* Google Colab
* Hugging Face
* LLM APIs

Tools and frameworks will be introduced **only when they are relevant to the current chapter**.

---

# 📓 Notebooks

Each chapter contains a corresponding Google Colab/Jupyter notebook with:

* Explanations
* Code
* Experiments
* Outputs
* Exercises
* Interview questions
* Key takeaways

The notebooks are designed to be understandable independently, so another learner can follow the repository without needing access to the original learning sessions.

---

# 🚫 Scope

This repository follows a **fixed 18-chapter syllabus**.

No unrelated topics or random technologies will be added during the learning process.

The progression is intentionally structured:

```text
LLM Fundamentals
       ↓
Tokenization & Embeddings
       ↓
Neural Networks
       ↓
Attention
       ↓
Transformers
       ↓
GPT
       ↓
Training & Fine-Tuning
       ↓
Modern LLM Tools
       ↓
RAG & Agents
       ↓
LLM Engineering
       ↓
Final Application
```

---

# 🎯 Final Outcome

At the end of this journey, this repository will contain a complete collection of hands-on notebooks demonstrating my understanding of LLMs from fundamentals to practical applications.

The final project will combine the concepts learned throughout the course into a complete LLM application.

---

## 🚀 Current Chapter

**Chapter 4 — Attention**

The next step is to understand how a model can determine **which parts of the input are important when processing a token**.

---
