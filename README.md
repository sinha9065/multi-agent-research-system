# 🤖 Multi-Agent Research System

An AI-powered multi-agent system that automates topic research and analysis. Give it a topic, and specialized agents work together to search, gather, and analyze information for you.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green?logo=chainlink)
![OpenAI](https://img.shields.io/badge/OpenAI-API-black?logo=openai)
![Tavily](https://img.shields.io/badge/Tavily-Search-orange)

## ✨ Features

- 🔍 **Automated Research** — pass any topic and get researched, structured output
- 🤝 **Multi-Agent Architecture** — specialized agents handle search, scraping, and analysis separately
- 🌐 **Web Search Integration** — powered by Tavily Search for real-time information
- 📊 **Data Processing** — cleans and structures scraped/searched data using BeautifulSoup & Pandas
- ⚡ **Async Support** — faster and more efficient agent execution
- 🔐 **Environment-based Config** — API keys managed securely via `.env`

## 🛠️ Tech Stack

- **Language:** Python
- **AI Framework:** LangChain, LangChain-OpenAI
- **LLM Provider:** OpenAI
- **Search Tool:** Tavily
- **Web Scraping:** BeautifulSoup4, Requests, lxml
- **Utilities:** Pydantic, Tenacity, Rich, orjson, tiktoken

## 🚀 Installation

1. **Clone the repository**
```bash
   git clone https://github.com/sinha9065/multi-agent-research-system.git
   cd multi-agent-research-system
```

2. **Create a virtual environment** (recommended)
```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS/Linux
   source .venv/bin/activate
```

3. **Install dependencies**
```bash
   pip install -r requirements.txt
```

4. **Set up environment variables**
   Create a `.env` file in the root directory and add your API keys:

OPENAI_API_KEY=your_openai_api_key_here
TAVILY_API_KEY=your_tavily_api_key_here

## ▶️ How to Run

```bash
python app.py
```

## 📁 Project Structure
multi-agent-research-system/
├── agents.py # Agent definitions and logic
├── app.py # Main application entry point
├── pipeline.py # Research pipeline orchestration
├── tools.py # Custom tools used by agents
├── requirements.txt # Project dependencies
└── README.md


## 👤 Author

**Shubham Sinha**
📧 sinhashubham540@gmail.com
