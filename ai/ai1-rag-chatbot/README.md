# AI Project 1: RAG Chatbot with Vector Search

> AI-powered chatbot using MongoDB Atlas Vector Search

## 🎯 Overview

An intelligent chatbot that answers questions from a custom document corpus using Retrieval Augmented Generation (RAG).

## 🏗️ Architecture

```
┌─────────────────┐
│   User Query    │
└────────┬────────┘
         │
         ▼
┌─────────────────┐     ┌─────────────────┐
│  Embedding API  │────▶│  MongoDB Atlas  │
│  (OpenAI/Gemini)│     │  Vector Search  │
└─────────────────┘     └─────────────────┘
         │                      │
         │              ┌───────┘
         ▼              ▼
┌─────────────────────────────┐
│      Context + Query        │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────┐     ┌─────────────────┐
│    LLM API      │────▶│   Response      │
│  (Gemini/GPT)   │     │   to User       │
└─────────────────┘     └─────────────────┘
```

## 🛠️ Technologies Used

- **Database:** MongoDB Atlas (M10 cluster)
- **Vector Search:** Atlas Vector Search
- **Backend:** Python, FastAPI
- **AI/LLM:** Gemini API / OpenAI
- **Hosting:** Cloud Run (GCP)
- **Embeddings:** text-embedding-ada-002

## 📊 Key Features

- [ ] Document ingestion pipeline
- [ ] Vector embedding storage
- [ ] Semantic similarity search
- [ ] Context-aware responses
- [ ] Conversation history

## 📈 Results

*To be updated after completion*

- Response time: < 500ms
- Accuracy: To be measured

---

*Status: 🔲 Not Started*
