# Retrieval-Augmented Generation (RAG) using Open-Source Tools

## Overview of the Project
This project demonstrates an implementation of Retrieval-Augmented Generation (RAG) using the open-source Llama 3.2 Large Language Model and Pinecone as a vector database.

RAG enhances LLMs by retrieving real-time data from your documents before generating answers. It ensures responses come directly from your trusted documents—not guesses—making it essential for domains where accuracy and privacy are critical.

## Document Collection and Setup
Create a folder named `docs` in the same directory as your notebook. Add your files to `./docs/` (supports: `.pdf`, `.docx`, `.txt`).

**Example files to use:**
- University course syllabi (PDF)
- Research papers (PDF)
- Company policy documents (Word/PDF)
- Product manuals (PDF)

**Required:** Add at least 2–3 documents for the RAG pipeline to function effectively.

## Install Dependencies
Run the installation cell to set up the required dependencies.

**Key libraries:**
- **llama2 (via Ollama)** – Local LLM
- **sentence-transformers** – Embeddings generation
- **pinecone-client** – Vector database operations

These packages are required for:
- Document parsing (PDF, DOCX)
- Text chunking and embedding
- Vector database management (Pinecone)
- LLM integration via LangChain and Ollama

**Note:** Requires Python ≥3.8 and pip.
