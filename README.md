# 🚀 Simple RAG Application (PDF Question Answering)

An AI-powered **Retrieval-Augmented Generation (RAG)** system that allows users to ask questions from a PDF document and get accurate, context-aware answers.

---

## 📌 Overview

This project demonstrates how to build a **document-based Q&A system** using modern AI tools like LangChain, HuggingFace, and ChromaDB.

Instead of relying only on a language model, this system retrieves relevant information from a PDF and uses it to generate precise answers.

---

## 🎯 Features

* 📄 Upload and process PDF documents
* ✂️ Automatic text chunking
* 🔍 Semantic search using embeddings
* 🧠 Context-aware answer generation
* 💾 Persistent vector storage (ChromaDB)
* ⚡ Lightweight and efficient pipeline

---

## 🏗️ Tech Stack

| Category   | Tools Used                          |
| ---------- | ----------------------------------- |
| Language   | Python                              |
| Framework  | LangChain                           |
| Embeddings | HuggingFace (Sentence Transformers) |
| Vector DB  | ChromaDB                            |
| PDF Loader | PyPDF                               |
| LLM        | TinyLlama / Ollama                  |

---

## ⚙️ How It Works

1. 📄 Load PDF document
2. ✂️ Split text into chunks
3. 🔢 Convert text → embeddings
4. 💾 Store embeddings in vector database
5. ❓ User asks a question
6. 🔍 Retrieve relevant chunks
7. 🧠 LLM generates final answer

---

## 📂 Project Structure

```
Simple RAG/
│
├── Simple RAG Application.ipynb   # Main notebook
├── MapReduce.pdf                 # Sample document
├── README.md                     # Project documentation
└── rag_db/                       # Vector DB (ignored)
```

---

## 🧪 Installation

```bash
pip install langchain langchain-community langchain-huggingface \
langchain-text-splitters langchain-chroma pypdf chromadb \
sentence-transformers transformers accelerate
```

---

## ▶️ Usage

1. Open the notebook in VS Code / Jupyter
2. Run all cells step by step
3. Ask questions like:

```python
print(ask("Explain MapReduce"))
```

---

## 🧠 Example Output

**Question:** What is MapReduce?
**Answer:** MapReduce is a programming model used for processing large datasets in a distributed manner...

---

## ⚠️ Important Notes

* `rag_db/` folder is auto-generated and should not be pushed to GitHub
* First run may download models (~100MB)
* Works best with text-based PDFs

---

## 🚀 Future Improvements

* 🌐 Build a Streamlit web interface
* 📚 Support multiple PDF documents
* 🧠 Use advanced LLMs (Mistral, LLaMA)
* 🔍 Improve retrieval accuracy

---

## 👨‍💻 Author

**Amjath Hussain**

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

---
