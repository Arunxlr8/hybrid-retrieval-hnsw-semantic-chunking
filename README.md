# Hybrid Retrieval Search using HNSW, Semantic, and Agentic Chunking

This repository implements a production-grade Retrieval-Augmented Generation (RAG) pipeline designed to maximize text precision and minimize retrieval latency for enterprise documents.

## 🚀 Architectural Foundations
* **Multimodal Extraction:** High-fidelity layout parsing via `PyMuPDF`.
* **Advanced Chunking Frameworks:** Mathematical sliding cosine thresholds (Semantic) alongside LLM validation (Agentic).
* **Open-Source Vector Foundations:** Local instances of `BAAI/bge-large-en-v1.5` mapped directly into an optimized $O(\log N)$ HNSW graph.
