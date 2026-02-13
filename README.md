# 🕉️ Gita AI Agent (Agentic RAG System)

An Agentic RAG-based AI system that answers questions from the Bhagavad Gita using Retrieval-Augmented Generation.

## 🚀 Features

- 📚 Document ingestion & chunking
- 🧠 Vector database storage (Qdrant)
- 🔎 Semantic search retriever
- 🤖 LLM-powered response generation
- 🛠 Tool-based agent architecture

## 🏗 Project Architecture

User Query  
 ↓  
Agent  
 ↓  
Retriever (Qdrant Vector DB)  
 ↓  
Context + Prompt  
 ↓  
LLM Response

## 📂 Folder Structure

Gita_Agent/
│
├── app.py
├── requirements.txt
├── db/
│ └── qdrant_client.py
├── src/
│ ├── agent.py
│ ├── retriever.py
│ ├── tools.py
│ ├── prompts.py
│ └── load_texts.py

## 🛠 Tech Stack

- Python
- LangChain
- Qdrant
- OpenAI / Groq
- Agentic Tool Calling

## 📌 Future Improvements

- Add memory module
- Add multi-tool support
- Deploy as API
- Add Streamlit UI
