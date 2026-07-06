# Multi-Agent-System

A Python-based Multi-Agent AI system that automates the research process using multiple AI agents. Each agent is assigned a specific responsibility, allowing the system to gather, analyze, and present information efficiently.

---

## 🚀 Features

- 🔍 Automated web research
- 🤖 Multiple AI agents working together
- 📄 Summarizes research findings
- 🌐 Retrieves real-time information
- 📊 Generates structured reports
- ⚡ Fast and efficient workflow
- 🔑 Secure API key management using `.env`

---

## 🛠️ Technologies Used

- Python 3.9+
- LangGraph
- LangChain
- OpenAI / Google Gemini
- Tavily Search API
- python-dotenv
- Rich
- Requests

---

## 📁 Project Structure

```
multi-agent-research-system/
│
├── agents.py
├── tools.py
├── state.py
├── graph.py
├── main.py
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/multi-agent-research-system.git
cd multi-agent-research-system
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the environment

Windows

```bash
.venv\Scripts\activate
```

Mac/Linux

```bash
source .venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

Example:

```env
OPENAI_API_KEY=your_openai_api_key
GOOGLE_API_KEY=your_google_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 📌 Workflow

1. User enters a research topic.
2. Research Agent gathers information.
3. Analysis Agent processes collected data.
4. Report Agent generates a structured summary.
5. Final report is displayed to the user.

---

## 📸 Sample Output

```
Topic:
Artificial Intelligence in Healthcare

------------------------------------

Research Summary

• Current AI applications
• Benefits and challenges
• Future trends
• References
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Multi-Agent AI Architecture
- LangGraph Workflows
- LLM Integration
- Prompt Engineering
- API Integration
- State Management
- AI Automation
- Python Project Organization

---

## 🔮 Future Improvements

- PDF report generation
- Streamlit web interface
- Voice input
- Multi-language support
- Research history
- Export to Word/PDF
- Citation support

---

## 👩‍💻 Author

**Priya Naik**

Aspiring AI / Generative AI Engineer

GitHub: https://github.com/your-username

---

## ⭐ If you found this project useful, consider giving it a Star!
