# 🧠 ContextIQ

### 🚀 AI Document Intelligence Assistant

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4.1--mini-black?style=for-the-badge\&logo=openai)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-orange?style=for-the-badge)
![Gradio](https://img.shields.io/badge/Gradio-UI-red?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Architecture-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-Apache%202.0-green?style=for-the-badge)

</p>

---

## 🌟 Overview

**ContextIQ** is an AI-powered document assistant that enables users to **interact with PDFs using natural language**.

Built using **Retrieval-Augmented Generation (RAG)**, it retrieves relevant context from documents and generates accurate, intelligent responses using LLMs.

---

## ✨ Key Features

* 📄 Upload and process PDF documents
* 💬 Chat with your document (context-aware responses)
* 🧠 **Adaptive Response Modes**:

  * 🟢 **Beginner Mode** → Simple explanations
  * 🟡 **Exam Mode** → Structured, exam-ready answers
  * 🔴 **Strict Mode** → Answers strictly from document (no hallucination)
* 📝 Generate exam-style questions
* 📌 Smart summarization
* ⚡ Fast semantic search using FAISS
* 🎯 Clean and interactive UI using Gradio

---

## 🧠 RAG Architecture

```mermaid
graph TD
A[PDF Upload] --> B[Text Extraction]
B --> C[Chunking]
C --> D[Embeddings]
D --> E[FAISS Vector Store]
E --> F[User Query]
F --> G[Relevant Context Retrieval]
G --> H[OpenAI LLM]
H --> I[Final Answer]
```

---

## 🛠️ Tech Stack

| Layer          | Technology            |
| -------------- | --------------------- |
| Language       | Python                |
| LLM            | OpenAI (GPT-4.1-mini) |
| Embeddings     | Sentence Transformers |
| Vector DB      | FAISS                 |
| UI             | Gradio                |
| PDF Processing | PyPDF                 |

---

## ⚙️ Installation

```bash
git clone https://github.com/gee-46/contextiq.git
cd contextiq
pip install -r requirements.txt
```

---

## 🔑 Setup API Key

```bash
export OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ Run the App

```bash
python app.py
```

---

## 🎥 Demo


```md
![Demo](demo.gif)
```

---

## 🎯 Learning & Takeaways

While building **ContextIQ**, I gained hands-on experience in:

* Designing scalable **Python functions for AI systems**
* Understanding and implementing **Retrieval-Augmented Generation (RAG)**
* Working with **vector embeddings and FAISS search**
* Integrating **LLMs into real-world applications**
* Building interactive AI interfaces using **Gradio**

---

## 🚀 Future Improvements

* 💬 Chat memory (conversation context)
* 🌐 Deployment as a web application
* 📂 Multi-document support
* 🎨 Enhanced UI/UX

---

## 📌 Notes

* Requires a valid OpenAI API key with billing enabled
* Avoid exposing API keys publicly
* Works best with text-based PDFs

---

## 📄 License

This project is licensed under the **Apache License 2.0**.

---

## 🔗 Connect With Me

* 💻 GitHub: https://github.com/gee-46
* 🔗 LinkedIn: https://www.linkedin.com/in/gautam-n-chipkar/

---

## ⭐ Support

If you found this project interesting:

* ⭐ Star the repository
* 🍴 Fork it
* 💡 Use it as inspiration for your own projects

---

<p align="center">
Built and maintained by <b>gee-46</b>
</p>
