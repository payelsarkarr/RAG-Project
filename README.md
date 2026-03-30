# RAG-Based Chatbot Project

## Overview
This project implements a Retrieval-Augmented Generation (RAG) chatbot that combines a language model with external knowledge retrieval to generate accurate and context-aware responses.

## Objective
The goal is to improve answer quality by retrieving relevant information from a dataset and using it to guide the model’s responses, reducing hallucinations.

## Methodology
- Convert documents into embeddings  
- Store them in a vector database  
- Retrieve relevant documents based on user queries  
- Generate responses using an LLM with retrieved context  

## Tech Stack
- Python  
- Jupyter Notebook  
- Embeddings + Vector Database (FAISS/Chroma)  
- LLM (Gemma / OpenAI / HuggingFace)  

## Project File
- `student_rag_project_gemma1b.ipynb`

## How to Run
1. Open the notebook  
2. Run all cells step by step  

## Conclusion
This project demonstrates how RAG improves chatbot accuracy by grounding responses in external data.
