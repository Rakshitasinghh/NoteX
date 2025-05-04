# 🧠 NoteX – AI Text Summarizer & Q&A Web App

**NoteX** is a smart Streamlit-based web app that summarizes and answers questions from PDFs, DOCX files, YouTube videos, websites, and raw text using advanced NLP models like **facebook/bart-large-cnn**.

---

## 🚀 Features

- 📄 Summarize PDF and DOCX files  
- 📺 Summarize YouTube video transcripts  
- 🌐 Summarize content from web URLs  
- ✍️ Paste raw text for instant summarization  
- ❓ Ask questions based on provided content  
- ⚡ Clean, interactive Streamlit UI

---

## ⚙️ Setup

### 1. Install Python 3.8+

Make sure Python is installed on your system.

### 2. Install Dependencies & run

```bash
pip install streamlit pdfplumber python-docx youtube-transcript-api requests beautifulsoup4 transformers torch
streamlit run main.py

