# LLM Engineering Learning

A hands-on learning repository for building practical intuition around Large Language Models, local LLM workflows, Hugging Face tooling, UI integration, tool calling, and Retrieval-Augmented Generation (RAG).

This repo documents my notebook-based learning journey through the core building blocks of modern LLM engineering — from prompt-based APIs and tokenization to local inference, evaluation, Gradio apps, and RAG pipelines.

---

## Repository Overview

This project is organized primarily as a notebook collection, where each notebook explores one important concept or mini-project in LLM engineering.

Current notebook lineup includes: `01_gemini_basics.ipynb` through `13_rag_retrieval_qa_ollama.ipynb`, along with supporting folders such as `knowledge-base/` and `vector_db/`.

---

## Learning Goals

The purpose of this repository is to:

* build practical understanding of how LLM systems work end to end
* experiment with both hosted and local models
* learn tokenization, prompting, inference, and evaluation workflows
* create simple LLM-powered applications with user interfaces
* understand the foundations of RAG using embeddings, vector stores, and retrieval
* move gradually from notebook experimentation toward production-style LLM projects

---

## Notebook Roadmap

### 01. Gemini Basics

Introduction to working with a hosted LLM API, covering prompting and response generation.

### 02. Local Llama Playground

Experiments with running a local LLM and understanding offline inference workflows.

### 03. Tokenization Basics

Explores how text is split into tokens and its impact on context and performance.

### 04. Smart Brochure Builder LLM

A small project for structured content generation using prompts.

### 05. Multi-LLM Evaluation Framework

Compares outputs across models and introduces evaluation concepts.

### 06. LLM with Gradio

Builds a simple UI for interacting with an LLM.

### 07. LLM Flight Assistant Tool Calling

Introduces tool/function calling for structured assistant workflows.

### 08. Ollama + Gradio + pyttsx

Combines local models with UI and text-to-speech for richer interaction.

### 09. Hugging Face Pipelines Basics

Covers the `transformers` pipeline abstraction.

### 10. Hugging Face LLM Pipeline

Extends pipelines into text generation workflows.

### 11. Pseudo RAG with Ollama

Introduces RAG intuition without full pipeline complexity.

### 12. RAG Vectorstore and Embedding Visualization

Focuses on embeddings and semantic similarity.

### 13. RAG Retrieval QA with Ollama

Implements a full retrieval-based QA system.

---

## Folder Structure

```
llm-engineering-learning/
│
├── notebooks/
│   ├── knowledge-base/
│   ├── vector_db/
│   ├── 01_gemini_basics.ipynb
│   ├── 02_local_llama_playground.ipynb
│   ├── 03_tokenization_basics.ipynb
│   ├── 04_smart_brochure_builder_llm.ipynb
│   ├── 05_Multi_LLM_Evaluation_Framework.ipynb
│   ├── 06_LLM_with_Gradio.ipynb
│   ├── 07_llm_flight_assistant_tool_calling.ipynb
│   ├── 08_ollama_gr_pyttsx.ipynb
│   ├── 09_huggingface_pipelines_basics.ipynb
│   ├── 10_huggingface_llm_pipeline.ipynb
│   ├── 11_pseudo_rag_ollama.ipynb
│   ├── 12_rag_vectorstore_and_embedding_visualization.ipynb
│   └── 13_rag_retrieval_qa_ollama.ipynb
│
├── requirements.txt
└── README.md
```

---

## Tech Stack

* Python
* Jupyter Notebook
* Gemini API
* Ollama
* Hugging Face Transformers
* Gradio
* Vector Databases / Embeddings
* Retrieval-Augmented Generation (RAG)

---

## What This Repository Covers

* LLM fundamentals
* Prompt engineering basics
* Local vs hosted LLM workflows
* Tokenization and context handling
* Hugging Face inference pipelines
* LLM app prototyping with Gradio
* Tool calling patterns
* RAG basics with embeddings and retrieval

---

## How to Use

### Clone the repository

```
git clone https://github.com/DeepuLIN/llm-engineering-learning.git
cd llm-engineering-learning
```

### Create and activate environment

```
python -m venv venv
source venv/bin/activate
```

Windows:

```
venv\Scripts\activate
```

### Install dependencies

```
pip install -r requirements.txt
```

### Launch notebooks

```
jupyter notebook
```

---

## Suggested Learning Order

1. Gemini Basics
2. Local Llama Playground
3. Tokenization Basics
4. Hugging Face Pipelines
5. Hugging Face LLM Pipeline
6. Gradio App
7. Tool Calling
8. Pseudo RAG
9. Embeddings + Vector Store
10. Retrieval QA

---

## Future Improvements

* Convert notebooks into modular Python scripts
* Add evaluation metrics (MRR, nDCG, etc.)
* Expand RAG with reranking and chunking strategies
* Compare hosted vs local LLM performance
* Add fine-tuning (LoRA / QLoRA)
* Deploy selected apps with FastAPI + CI/CD

---

## Why This Repo Exists

This repository is my LLM engineering lab — focused on learning by building real systems rather than just theory.

The goal is to evolve from notebook experiments to production-grade LLM pipelines.

---

## Author

**Deepak Lingaraju**
GitHub: https://github.com/DeepuLIN

---

## License

Open for learning and experimentation. Add a license if needed.
