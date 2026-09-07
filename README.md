# 🩺 Medical RAG Assistant

## Overview

This project implements a Retrieval-Augmented Generation (RAG) system for answering questions from a medical document using LangChain, FAISS, Hugging Face Embeddings, and OpenAI GPT.

## Features

- PDF document ingestion
- Text chunking
- Hugging Face embeddings
- FAISS vector database
- Semantic retrieval
- OpenAI GPT answer generation
- Evaluation metrics
  - Retrieved chunks
  - Average similarity
  - Retrieval time
  - Generation time

## Tech Stack

- Python
- Google Colab
- LangChain
- FAISS
- Hugging Face
- OpenAI API

## Project Workflow

Medical PDF
↓
PyPDFLoader
↓
Text Chunking
↓
Embeddings
↓
FAISS Vector Store
↓
Semantic Retrieval
↓
OpenAI GPT
↓
Generated Answer

## Installation

```bash
pip install -r requirements.txt
```

## Running the Project

1. Open the notebook in Google Colab.
2. Add your OpenAI API key to Colab Secrets with the name:

```
rag_key
```

3. Run all notebook cells.
4. Upload the medical PDF.
5. Ask questions about the document.

## Example Questions

- What is medicine?
- What is traditional medicine?
- What is medical ethics?
- What is diagnosis?
- What is prognosis?

## Future Improvements

- Hybrid Search (FAISS + BM25)
- Cross-Encoder Reranking
- User Feedback Collection
- Live Dashboard
