# 🚀 Multi-Document Advanced RAG System (GenAI)

> 🔥 Retrieval-Augmented Generation (RAG) redefined: Handle **multiple document types**, maintain **chat memory**, and get **source-cited answers** in a **sleek UI**.

---

## ✨ The "Wow" Factor

Unlike basic Q&A bots, this system is built for **real-world enterprise use cases**:

- 📂 Works with **PDFs, PPTs, and TXT** files  
- 🧠 Maintains **conversational memory**  
- 🔎 Provides **source citations** for each response  
- 🎨 Fully polished **modern UI** (Next.js + Tailwind)  

---


## 🎯 Use Cases

- 📚 Academic Research – Upload papers & chat with citations

- 🏢 Enterprise Knowledge Base – Centralize documents for employees

- ⚖️ Legal & Compliance – Search through contracts, cite sources

- 💡 Personal Knowledge Assistant – Your second brain powered by GenAI



## 🖼️ Demo Screenshots

<p align="center">
  <img src="screenshots/upload.png" alt="Document Upload" width="800"/>
  <br/>
  <em>📂 Upload multiple document types seamlessly</em>
</p>

<p align="center">
  <img src="screenshots/chat.png" alt="Chat Interface" width="800"/>
  <br/>
  <em>💬 Conversational AI with memory + citations</em>
</p>

<p align="center">
  <img src="screenshots/results.png" alt="Cited Answer" width="800"/>
  <br/>
  <em>🔎 Responses grounded in your documents</em>
</p>

---

## 🏗️ Tech Stack

| Layer         | Technology |
|---------------|------------|
| **Frontend**  | Next.js (React 18), Tailwind CSS |
| **Backend**   | FastAPI (Python 3.11), Docker |
| **AI Core**   | LangChain, OpenAI LLMs & Embeddings |
| **Vector DB** | Pinecone |
| **Deployment**| Vercel (Frontend), AWS EC2/Lightsail (Backend) |

---

## ⚡ Key Features

✅ **Multi-Format Document Support** → PDFs, PPTs, TXT  
✅ **Memory-Aware Conversations** → Context stays consistent across turns  
✅ **Source-Cited Answers** → Traceable, reliable responses  
✅ **High-Performance Backend** → Powered by **FastAPI** + Dockerized services  
✅ **Modern Deployment** → Scalable setup with Vercel + AWS  

---

## 🔧 Installation & Setup

### 1. Clone the repo
```bash
git clone https://github.com/your-username/multi-doc-rag.git
cd multi-doc-rag
```

### 2. Backend Setup (FastAPI + LangChain) 
```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```
### 3. Frontend Setup (Next.js)
```bash
cd frontend
npm install
npm run dev
```
### 4. Environment Variables
```bash
OPENAI_API_KEY=your_api_key
PINECONE_API_KEY=your_api_key
PINECONE_ENVIRONMENT=your_env

```
---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---


## ⭐ Show Your Support

If you like this project, please give it a ⭐ on GitHub and share it with others! 🚀



---

📬 Connect

👨‍💻 Author: Yuvraj Tayal

Portfolio : [Link](https://yuvraj-portfolio-seven.vercel.app/)

🔗 LinkedIn: [linkedin.com/in/yuvraj-tayal](https://www.linkedin.com/in/yuvraj-tayal-7a3a48356)

🐦 Twitter: [twitter.com/yuvrajtayal](https://x.com/YuvrajTayal)