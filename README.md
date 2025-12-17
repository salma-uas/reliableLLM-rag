# Retrieval-Augmented Generation(RAG) using Open-Source Tools

## Overview of the Project
This project demonstrates an implementation of Retrieval-Augmented Generation (RAG) using an open-source Large Language Model (LLM)-llama3.2 and Pinecone as a vector database.

RAG enhances LLMs by fetching real-time data from your documents before generating answers. It ensures responses come directly from your trusted documents—not guesses—making it essential for domains where accuracy and privacy matter.

## Documents Collection and Library Installation
Create a folder named docs in the same directory as your notebook. Add your files to ./docs/ (supports: .pdf, .docx, .txt). Example files to use:

University course syllabi (PDF)
Research papers (PDF)
Company policy documents (Word/PDF)
Product manuals (PDF)

Required: Add at least 2-3 documents for the RAG pipeline to work.

## Install Dependencies
Run the cell below to install required dependencies

Key libraries:

llama2 (via Ollama) - Local LLM
sentence-transformers
pinecone-client

These packages are needed for Document parsing (PDF, DOCX), Text chunking and embedding, Vector database (Pinecone) and LLM integration via LangChain and Ollama. Note: Requires Python ≥3.8 and pip.
