# RagChatBot

# 💡 WhatsApp AI Agent SaaS Platform RAG Chatbot

This project implements a **Retrieval-Augmented Generation (RAG)** system using **LlamaIndex** to build a query engine over internal project documentation. The RAG system is designed to power an AI Agent SaaS platform targeting Small to Medium Businesses (SMBs) for automating lead conversion, onboarding, and helpdesk functions via WhatsApp.

The project demonstrates document loading, indexing using OpenAI embeddings, querying, and the setup for persistent storage using a **PostgreSQL** database with the **pgvector** extension.

---

## ✨ Features

- **RAG Implementation:** Uses LlamaIndex for efficient retrieval and generation.  
- **Data Ingestion:** Loads documents from a local `data` directory using `SimpleDirectoryReader`.  
- **Vector Indexing:** Creates a vector store index using OpenAI embeddings.  
- **Query Engine:** Sets up a query engine with custom retrieval parameters (`similarity_top_k` and `similarity_cutoff`) for precision.  
- **Persistent Storage (Planned/Setup):** Includes code to configure and use PostgreSQL with PGVectorStore for persistent vector storage.  
- **Local Development Setup:** Uses `dotenv` for secure management of API keys and database credentials.  

---

## 🛠️ Technology Stack

- **RAG Framework:** LlamaIndex (including `llama-index-vector-stores-postgres`)  
- **Language Model (LLM) & Embeddings:** OpenAI (via API key)  
- **Programming Language:** Python  
- **Environment Management:** `venv` or `conda`  
- **Database:** PostgreSQL with `pgvector` extension  

---

## 🚀 Setup and Installation

### 1. Prerequisites

Ensure you have the following installed:

- **Python 3.8+** (Notebook uses Python 3.13.7)  
- **PostgreSQL** with `pgvector` extension enabled  
- **OpenAI API Key**  

### 2. Clone the Repository

```bash
git clone https://github.com/Ujjawal-Singh/RagChatBot2
cd RagChatBot2
