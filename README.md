# PDF Q&A Chat Application

A powerful web application that allows users to upload PDF documents and ask questions about their content using Generative AI. Built with RAG (Retrieval-Augmented Generation) architecture for accurate, context-aware responses.

![AI PDF Chat](https://img.shields.io/badge/AI-PDF%20Chat-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-lightgrey)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-orange)

## 🚀 Features

### Core Features
- **📄 PDF Upload** - Support for large PDF documents (500+ pages)
- **🤖 Intelligent Q&A** - Ask questions about uploaded PDF content
- **🔍 RAG Architecture** - Uses similarity search for accurate responses
- **💬 Chat Interface** - Conversational, chat-like user experience
- **🧠 OpenAI Integration** - Powered by GPT models for intelligent responses

### Advanced Features
- **📊 Large Document Support** - Efficiently processes 500+ page PDFs
- **✂️ Smart Chunking** - Intelligent text segmentation with overlap
- **🔢 Vector Search** - FAISS-based similarity search for context retrieval
- **💾 Session Management** - Maintains conversation history per document
- **📱 Responsive UI** - Clean, modern interface that works on all devices

## 🛠️ Technology Stack

### Backend
- **Python**
- **LangChain** for RAG pipeline
- **OpenAI GPT-4** for text generation
- **FAISS** for vector similarity search
- **PyPDF2** for PDF text extraction
- **Sentence Transformers** for embeddings

### Frontend
- **Streamlit**

## 📦 Installation

### Prerequisites
- Python 3.8+
- OpenAI API key

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/bhosaleparas/AI_Assignment.git
cd AI_Assignment


### 1. Clone the Repository
```bash
git clone https://github.com/bhosaleparas/Blood-Bank.git
cd bloodbank

```
### 2.Create a Virtual Environment (Windows)
```bash
python -m venv venv
venv\Scripts\activate

```
### 3.Install Dependencies
```bash
pip install -r requirements.txt

```
### 4. Run the app
```bash
python streamlit run app.py 



