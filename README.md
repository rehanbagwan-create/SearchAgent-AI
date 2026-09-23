# 🤖 SearchAgent AI

An AI-powered web search assistant built with **Python, LangChain, Groq, Google Serper, LangGraph, and Streamlit**.

SearchAgent AI can answer questions using an LLM and perform Google searches when current or up-to-date information is required.

## 🚀 Live Demo

🔗 https://searchagent-rehan.streamlit.app/

## ✨ Features

- 🤖 AI-powered question answering
- 🌐 Google Search integration
- ⚡ Streaming AI responses
- 🧠 Conversation history
- 🔗 LangChain agent architecture
- 🚀 Groq-powered LLM
- 💻 Interactive Streamlit interface
- 🔐 Secure API key management using environment variables and Streamlit Secrets

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Application development |
| LangChain | LLM and agent framework |
| LangGraph | Agent state and memory |
| Groq | LLM inference |
| Google Serper | Web search |
| Streamlit | Web interface |
| python-dotenv | Environment configuration |

## 🏗️ Architecture

```text
                    User
                     │
                     ▼
              Streamlit UI
                     │
                     ▼
             LangChain Agent
                     │
              ┌──────┴──────┐
              │             │
              ▼             ▼
           Groq LLM    Google Search
              │             │
              └──────┬──────┘
                     ▼
              Process Results
                     │
                     ▼
            Streaming Response
                     │
                     ▼
                   User
