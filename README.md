# 📚 Study Buddy Agent

## 🚀 Overview
The **Study Buddy Agent** is an AI-powered assistant designed to make learning easier.  
It helps students by:
- Reading and understanding course PDFs/notes  
- Summarizing study materials into simple explanations  
- Answering student questions in real time  
- Generating practice questions for exam preparation  

This project is part of my **7-day agent-building challenge**.  

---

## ✨ Features
- 📂 **PDF/Notes Loader** → Upload study materials and extract content  
- 🤖 **Question-Answer System** → Ask questions, get context-aware answers  
- 📝 **Summary Generator** → Concise, easy-to-understand notes  
- 🎯 **Practice Question Creator** → Auto-generate quiz-style questions  

---

## 🛠️ Tech Stack
- **Language Model:** OpenAI GPT-4 / GPT-3.5  
- **Framework:** LangChain  
- **Backend:** FastAPI (expose API endpoints)  
- **Vector Store:** FAISS / Pinecone (for retrieval-based QA)  
- **Environment:** Python 3.10+  

---

## ⚙️ Installation & Setup

### 1. Clone the repository

git clone https://github.com/Syed-Imthiaz/study-buddy-agent.git
cd study-buddy-agent

### 2. Create and activate virtual environment

python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

### 3. Install dependencies

pip install -r requirements.txt

### 4. Run the FastAPI app

uvicorn src.main:app --reload

----

### 📋 Roadmap (7 Days)

- [x] Create repo & project plan  
- [ ] Implement FastAPI backend  
- [ ] Add PDF loader + text splitter  
- [ ] Integrate vector database (FAISS)  
- [ ] Connect GPT model for Q&A  
- [ ] Add summarizer & practice question generator  
- [ ] Test with real course materials  

----

📎 Links

🔗 GitHub Repo: [Study Buddy Agent](https://github.com/Syed-Imthiaz/study-buddy-agent)  

#LearnInpublic

----
