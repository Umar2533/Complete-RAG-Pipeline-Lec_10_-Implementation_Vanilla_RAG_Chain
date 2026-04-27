# Lecture 10 — Vanilla RAG Pipeline (LangChain + Qdrant + OpenAI)

## Overview
This project implements a complete Retrieval-Augmented Generation (RAG) pipeline using LangChain, Qdrant Vector Database, and OpenAI Embeddings.

It demonstrates how to build a question-answering system over custom documents.

---

## Pipeline Steps

1. Load Data  
   Text file is loaded using LangChain document loaders.

2. Split Documents  
   Text is divided into chunks with overlap for better context preservation.

3. Embeddings  
   OpenAI `text-embedding-3-small` model is used to convert text into vectors.

4. Vector Store  
   Qdrant Cloud is used to store embeddings.

5. Retriever  
   Top-k relevant chunks are retrieved based on the query.

6. RAG Chain  
   Context and question are passed to the LLM to generate answers.

---

## Features

- End-to-end RAG pipeline  
- Source chunk tracking  
- Latency measurement  
- Modular architecture (retriever, prompt, chain)

---

## Example Queries

- What is Natural Language Processing?  
- How do transformers work?  
- What are NLP tasks?  

---

## Environment Variables

Create a `.env` file in the root directory:


---

## Tech Stack

- Python  
- LangChain  
- Qdrant  
- OpenAI API  

---

## Learning Outcomes

- Understanding RAG architecture  
- Working with vector databases  
- Building LLM-powered QA systems  

---
---

## Author DEX_pert

This project is part of a hands-on NLP and LLM engineering journey, focused on building production-ready RAG systems.
