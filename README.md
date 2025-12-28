# RAG Chatbot 

A Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF documents and ask questions about their content. Built with FastAPI, PostgreSQL + pgvector, OpenAI, and a modern React frontend.

## Features

- 📄 **PDF Upload**: Upload PDF documents for analysis
- 🤖 **RAG Chat**: Ask questions about uploaded PDFs using OpenAI GPT-4o-mini
- 🔍 **Vector Search**: Uses pgvector for efficient similarity search
- 💾 **Chat History**: Persistent conversation history stored in PostgreSQL
- 🐳 **Dockerized**: Complete containerized setup with docker-compose
- ⚛️ **Modern UI**: Clean, responsive React frontend with component-based architecture



## Tech Stack

### Backend
- **FastAPI**: Modern Python web framework
- **PostgreSQL + pgvector**: Vector database for embeddings storage
- **OpenAI**: GPT-4o-mini for chat completions and text-embedding-3-small for embeddings
- **PyPDF2**: PDF text extraction
- **LangChain**: RAG pipeline components

### Frontend
- **React 18**: Modern component-based UI framework
- **Webpack**: Module bundler with hot reloading
- **Responsive Design**: Mobile-friendly interface
- **File Upload**: Drag-and-drop PDF upload functionality

### Infrastructure
- **Docker**: Containerized backend application
- **docker-compose**: Multi-service orchestration

## Prerequisites

- Docker and Docker Compose
- OpenAI API key
License.
