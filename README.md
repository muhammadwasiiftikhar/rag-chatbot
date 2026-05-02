# RAG Chatbot 

A Retrieval-Augmented Generation (RAG) chatbot that answers questions 
from PDF documents using LangChain, FAISS and Groq LLM.

## What it does
- Loads and reads any PDF document
- Splits it into chunks and stores them as vectors using FAISS
- Finds the most relevant chunks for any question
- Sends them to an LLM (Llama 3.3) via Groq to generate an answer

## Tech Stack
- Python
- LangChain
- FAISS
- HuggingFace Embeddings
- Groq API (Llama 3.3)

## How to run
1. Clone this repo
2. Install dependencies: pip install langchain langchain-community 
   langchain-huggingface langchain-text-splitters faiss-cpu 
   sentence-transformers groq
3. Add your Groq API key
4. Place your PDF in the project folder as document.pdf
5. Run the notebook cell by cell
