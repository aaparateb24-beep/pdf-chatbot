# 🤖 AI Document Analyzer (PDF Chatbot)

An AI-powered web application that allows users to upload PDF documents and ask questions based on their content.

---

## 🚀 Features

* 📄 Upload PDF files
* 🔍 Extract text from documents
* 🧠 Semantic search using FAISS
* 🤖 Ask questions about the document
* ⚡ FastAPI backend

---

## 🛠️ Tech Stack

* Python
* FastAPI
* FAISS (Vector Database)
* Sentence Transformers (Embeddings)
* LangChain (Text Splitting)

---

## 📂 Project Structure

```
pdf-chatbot/
├── app.py            
├── qa_system.py        # AI logic (embeddings + FAISS)
├── requirements.txt
├── README.md
```

---

## ⚙️ Setup Instructions

```bash
pip install -r requirements.txt
python -m uvicorn app:app --reload
```

---

## 🧪 Usage

1. Open: http://127.0.0.1:8000/docs
2. Upload a PDF
3. Ask questions

---

## 🔥 Current Status

✅ PDF Upload
✅ Text Extraction
✅ Vector Search (FAISS)
✅ QnA System

🚧 Next: LLM-based answers, summarization

---

## 📌 Author

Aarya Parate
