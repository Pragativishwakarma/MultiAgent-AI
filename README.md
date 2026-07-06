# 🤖 MultiAgent-AI

A modular Multi-Agent AI system built using the OpenAI Agents SDK, where specialized AI agents collaborate to solve different tasks efficiently. Each agent is responsible for a specific domain, such as weather information, web search, and coding assistance, while the orchestrator routes user requests to the appropriate expert.

---

## 🚀 Features

- 🤖 Multi-Agent Architecture
- 🌦️ Weather Agent for real-time weather information
- 🔍 Web Search Agent for up-to-date internet research
- 💻 Coding Agent for programming assistance
- 🎯 Intelligent task routing through an Orchestrator
- 🛠️ Tool Calling using the OpenAI Agents SDK
- 🔒 Secure environment variables using `.env`
- 📦 Modular and scalable project structure

---

## 🏗️ Architecture

```
                    User
                      │
                      ▼
             🎯 Orchestrator Agent
            /          |           \
           /           |            \
          ▼            ▼             ▼
 🌦️ Weather     🔍 Web Search     💻 Coding
     Agent          Agent            Agent
          \           |             /
           └──────────┴────────────┘
                  External Tools
```

---

## 🛠️ Tech Stack

- Python 3.x
- OpenAI Agents SDK
- Pydantic
- Python Dotenv
- Weather API
- Web Search Tools
- Git & GitHub

---

## 📂 Project Structure

```
MultiAgent-AI/
│
├── main.py               # Entry point
├── runner.py             # Agent runner
├── agent.py              # Orchestrator Agent
├── weather_agent.py      # Weather Specialist
├── coding_agent.py       # Coding Specialist
├── tool.py               # Tool implementations
├── requirements.txt
├── .gitignore
├── README.md
└── .env (not included)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Pragativishwakarma/MultiAgent-AI.git
```

### 2. Navigate to the project

```bash
cd MultiAgent-AI
```

### 3. Create a virtual environment

**Mac/Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
OPENAI_API_KEY=your_openai_api_key
OPENAI_BASE_URL=your_base_url
GROQ_API_KEY=your_groq_api_key
```

> **Note:** Never commit your `.env` file or API keys to GitHub.

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 💡 Example Queries

```
What's the weather in London?
```

```
Search the web for the latest AI trends.
```

```
Write a Python function to reverse a linked list.
```

```
Explain the difference between REST and GraphQL.
```

---

## 📌 Agents

### 🎯 Orchestrator Agent
Routes user requests to the appropriate specialized agent.

### 🌦️ Weather Agent
Provides accurate real-time weather information.

### 🔍 Web Search Agent
Searches the web and summarizes relevant information.

### 💻 Coding Agent
Assists with programming, debugging, and code generation.

---

## 📚 Learning Outcomes

This project demonstrates:

- Multi-Agent Systems
- Agent Routing
- Tool Calling
- Function Calling
- Prompt Engineering
- Modular Python Development
- AI Workflow Design

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## ⭐ Show Your Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

---

## 👩‍💻 Author

**Pragati Vishwakarma**

- GitHub: https://github.com/Pragativishwakarma
- LinkedIn: https://www.linkedin.com/in/pragativishwakarma/

---

## 📄 License

This project is licensed under the MIT License.
