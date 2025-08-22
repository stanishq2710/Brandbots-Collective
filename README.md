# 🚀 Brandbots Collective

**Brandbots Collective** is an AI-powered **marketing automation crew** built with [CrewAI](https://github.com/joaomdmoura/crewai).  
It leverages **multi-agent collaboration** to streamline marketing workflows such as campaign planning, content generation, market research, and analytics — all in one automated pipeline.

---

## ✨ Features

- 🤖 **Multi-Agent AI Framework** – specialized agents for research, copywriting, analysis, and strategy.  
- 📊 **Data-Driven Insights** – automatically gathers and analyzes market data.  
- 📝 **Content Generation** – creates blog posts, ad copies, social media posts.  
- 🔄 **Automation Ready** – reduces manual effort in marketing teams.  
- ⚡ **Extensible** – add more agents/tools for custom use cases.  

---

## 🏗️ Tech Stack

- **Python 3.10+**
- [CrewAI](https://github.com/joaomdmoura/crewai) – multi-agent framework  
- [LangChain](https://www.langchain.com/) – LLM orchestration  
- [LiteLLM](https://github.com/BerriAI/litellm) – unified LLM API layer  
- **LLMs** – Google Gemini, OpenAI GPT, or any other supported model  
- **Tools** – Serper, Web scraping, File I/O utilities  

---

---

## ⚙️ Installation & Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/stanishq2710/Brandbots-Collective.git
   cd Brandbots-Collective
   ```

2.**Create a virtual environment**
  ```bash
  python3 -m venv .venv
  source .venv/bin/activate   # Linux/Mac
  .venv\Scripts\activate      # Windows
  ```

3.**Install dependencies**
  ```bash
  uv add langchain crewai crewai[tools] google-generativeai
  ```

4.**Set environment variables**
   ```env
    GEMINI_API_KEY=your_google_api_key
    SERPER_API_KEY=your_serper_api_key
   ```

**Contributions are welcome!**

Fork the repo

Create a feature branch

Submit a Pull Request

