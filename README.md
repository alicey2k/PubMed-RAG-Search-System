# PubMed-RAG-Search-System
## Project Goal

Search biomedical papers using:

- PubMed API
- BioBERT
- FAISS
- FLAN-T5

## Pipeline

Query
↓
PubMed
↓
BioBERT
↓
FAISS
↓
Top-k Papers
↓
RAG
↓
FLAN-T5
↓
Answer
