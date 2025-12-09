# RAG
📘 Retrieval-Augmented Generation on MedMCQA

    This project implements a lightweight Retrieval-Augmented Generation (RAG) pipeline using Qwen3-4B-Instruct on the MedMCQA medical multiple-choice dataset.
It includes NER-based entity extraction, Wikipedia retrieval, vector database construction, RAG inference, chain-of-thought reasoning, and constrained decoding.

🚀 Project Overview

This project explores how external knowledge retrieval affects LLM performance on medical exam-style questions.

Key components:

    spaCy NER for entity extraction

    Wikipedia API for retrieving external knowledge

    SentenceTransformer embeddings + ChromaDB for retrieval

    Qwen3-4B-Instruct-2507 as the base LLM

Evaluation of:

    Baseline LLM

    LLM + RAG

    LLM + Chain-of-Thought reasoning

    LLM + Constrained Decoding (Outlines + Pydantic)

All code and experiments are contained in:

    WU-wanxing_WU-kaiying.ipynb
