# Notebooks

This folder contains **learning-focused Jupyter notebooks** covering core topics in:

- **NLP**
- **LLMs**
- **LangChain**
- **LangGraph**
- **Vector Databases / Embeddings**
- **RAG (Retrieval-Augmented Generation)**

The emphasis is on **concept clarity, experimentation, and trade-offs** — not production-ready pipelines.

---

## 📂 Folder Structure

```bash
notebooks/
├── nlp/                 # NLP fundamentals + practice tasks
├── llms/                # LLM workflows, tokenizers, QA, classification, training experiments
├── langchain/           # LangChain concepts + RAG notebooks
├── langgraph/           # LangGraph orchestration patterns + persistence experiments
├── vectordatabases/     # Pinecone + semantic search + embedding pipelines
└── README.md
```

---

## 🧠 What You’ll Find Here

### ✅ NLP (`notebooks/nlp`)
Covers NLP foundations and practical workflows:
- text preprocessing (cleaning, tokenization, stopwords, regex)
- POS tagging + NER practice
- sentiment analysis (classical + transformers)
- Bag of Words / TF‑IDF vectorization
- topic modeling
- custom classifiers + practice notebooks

---

### ✅ LLMs (`notebooks/llms`)
Hands-on experiments with pretrained and fine-tuned models:
- Hugging Face pipelines and model usage
- working with tokenizers
- BERT-based QA notebook
- XLNet-based text classification
- training artifacts (fine-tuned model + checkpoints)

> Note: model checkpoints are stored inside subfolders such as  
> `fine_tuned_model/` and `test_trainer/`.

---

### ✅ LangChain (`notebooks/langchain`)
LangChain building blocks and LLM integration:
- basic OpenAI chatbot
- LangChain abstractions (prompts, parsers)
- batching + streaming
- runnable lambda / runnable composition
- full RAG pipeline:
  - indexing
  - retrieval
  - generation

Includes a local vectorstore experiment:
- `vectorstore/rag-practice/` (Chroma artifacts + sqlite)

---

### ✅ LangGraph (`notebooks/langgraph`)
Workflow orchestration using LangGraph:
- graph components and execution flow
- message management (basic + advanced)
- summarization strategies
- thread-level persistence using an SQLite-backed DB (`LangGraph_DB/`)

---

### ✅ Vector Databases (`notebooks/vectordatabases`)
Embeddings + semantic search workflows:
- Pinecone setup and core usage
- semantic search pipelines
- dataset preprocessing for embeddings
- weighted embedding strategies
- BERT embedding experiments

---

## ⚠️ Notes

- Notebooks are **iterative**: the goal is learning and experimentation.
- Some outputs may be stored (e.g., `chroma.sqlite3`, `*.bin`, `checkpoints`).
- If you want a clean run, consider clearing notebook outputs before committing.

---

## 🏁 Recommended Path (if you're new)

1. `nlp/` → fundamentals  
2. `llms/` → transformer workflows  
3. `vectordatabases/` → embeddings + search  
4. `langchain/` → RAG pipelines  
5. `langgraph/` → orchestration + persistence


