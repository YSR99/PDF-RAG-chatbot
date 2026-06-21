# PDF RAG Chatbot

A Retrieval-Augmented Generation (RAG) based Question Answering system built using Sentence Transformers, FAISS, and LLM APIs.

## Overview

This project allows users to ask questions about a PDF document in natural language.

The pipeline:

* Load PDF document
* Split text into chunks
* Convert chunks into embeddings
* Store embeddings in FAISS vector database
* Retrieve relevant chunks for a query
* Send retrieved context to an LLM
* Generate final answer

---

## Architecture

PDF → Chunking → Embeddings → FAISS → Retrieval → Prompt → LLM → Answer

---

## Tech Stack

* Python
* Sentence Transformers
* FAISS
* NumPy
* OpenRouter API
* GPT-3.5 Turbo

---

## Features

* Semantic search over PDF documents
* Fast vector similarity search using FAISS
* Context-aware question answering
* Retrieval-Augmented Generation pipeline

---

## Example Query

Question:
Where are all the people?

Answer:
All the people are at their summer villas, leaving the speaker feeling deserted and alone.

---

## Installation

```bash
git clone https://github.com/yourusername/pdf-rag-chatbot.git
cd pdf-rag-chatbot
pip install -r requirements.txt
```

Create a `.env` file:

```env
OPENROUTER_API_KEY=your_api_key_here
```

---

## Future Improvements

* Streamlit UI
* Multi-PDF support
* Citation support
* Hybrid search
* Reranking
* Local LLM integration

---

## Learning Outcome

This project helped in understanding:

* Embeddings
* Vector Databases
* Semantic Search
* Retrieval-Augmented Generation (RAG)
* LLM Integration
