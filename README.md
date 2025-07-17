# 🧠 XYZ Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that allows users to upload documents (PDF, TXT) and ask questions based on their contents. This project leverages LangChain, HuggingFace embeddings, and FastAPI to create an interactive GenAI pipeline.

## 🚀 Features

- 📄 File upload and ingestion
- 🔍 Document chunking and vector storage
- 🤖 LLM-powered query answering using context
- 🌐 FastAPI backend
- 🧠 HuggingFace Transformers and LangChain integration

## 🛠️ Tech Stack

- Python
- LangChain
- HuggingFace Transformers
- FAISS (or Weaviate)
- FastAPI
- Streamlit (optional for UI)
- PyMuPDF / pdfplumber (PDF handling)

## 🧩 How It Works

1. Upload a document
2. The text is extracted and chunked
3. Chunks are embedded and stored in a vector store
4. User asks a question → matched relevant chunks are retrieved
5. LLM generates a response using retrieved context

## 📦 Installation

```bash
git clone https://github.com/yourusername/XYZ-chatbot.git
cd XYZ-chatbot
pip install -r requirements.txt
