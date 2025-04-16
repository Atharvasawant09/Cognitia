# 🧠 Cognitia - Agentic AI Research Assistant

Cognitia is an intelligent research assistant powered by OpenAI-compatible models (like Groq's Mixtral, LLaMA, Gemma) and integrated with live tools such as Wikipedia search, web search via DuckDuckGo, and local text saving. Built using LangChain, it can perform tool-augmented research and return structured, parsable responses.

---

## ✨ Features

- 📚 Tool-augmented research with:
  - Web search (DuckDuckGo)
  - Wikipedia search
  - Save to text file
- 🧠 Agent-based architecture using `langchain`
- 🔍 Structured output using `Pydantic` models
- 🧩 Modular design – easy to add more tools or swap LLMs
- 🔐 `.env` support for API keys and configurations

---

## 📦 Tech Stack

- Python 3.10+
- [LangChain](https://github.com/langchain-ai/langchain)
- [OpenAI/Groq-compatible models](https://console.groq.com/)
- DuckDuckGo Search API
- Wikipedia API
- dotenv
- pydantic

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/cognitia.git

cd cognitia

pip install -r requirements.txt

For .env
OPENAI_API_KEY=your-groq-or-openai-api-key
OPENAI_API_BASE=https://api.groq.com/openai/v1

python main.py
