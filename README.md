# Semantic_Search_with_FAISS_and_SentenceTransformers

This project demonstrates how to build a simple and efficient **semantic search engine** using [FAISS](https://github.com/facebookresearch/faiss) and the `sentence-transformers` library. By leveraging vector embeddings and similarity search, it retrieves the most relevant textual information based on semantic meaning rather than keyword matching.

---

## 📌 Objective

To implement a **RAG-style** (Retrieval-Augmented Generation) semantic retrieval system that can return the most relevant sentences from a knowledge base (about BMW) using vector similarity with FAISS.

---

## 🚀 Features

- ✅ Sentence embedding generation using `all-MiniLM-L6-v2`
- ✅ Fast and efficient vector similarity search with FAISS
- ✅ Top-k nearest neighbor retrieval
- ✅ Customizable for any domain (replace sentences with your own)

---

## 🛠️ Installation

Install required libraries:

```bash
pip install faiss-cpu sentence-transformers
