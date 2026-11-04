# Single Agent with Multiple Tools 🤖

An AI-powered agent built using **LangChain, Google Gemini, Tavily Search, and Weather API**. This project demonstrates how a single LLM-powered agent can intelligently interact with multiple external tools to answer user queries.

## 🚀 Overview

This project implements a Single Agent architecture where Google Gemini acts as the reasoning engine and selects the appropriate tools based on the user's query.

Instead of manually calling APIs, the agent decides when to use web search or weather information tools and combines their outputs to generate meaningful responses.

## 🛠️ Technologies Used

- **Python** – Core programming language
- **LangChain** – Agent creation and tool integration
- **Google Gemini (gemini-2.5-flash)** – LLM for reasoning and decision-making
- **Tavily Search API** – Real-time web search
- **Weatherstack API** – Current weather information
- **python-dotenv** – Environment variable management

## ✨ Features

- Intelligent tool selection based on user queries.
- Real-time web search using Tavily.
- Current weather information using Weatherstack.
- Multiple tools integrated into a single AI agent.
- Natural language responses powered by Gemini.
- Handles queries requiring multiple tools.

## ⚙️ How It Works

1. The user submits a query.
2. Gemini analyzes the query and determines which tool is required.
3. The agent invokes Tavily Search for web-related information.
4. The agent invokes Weatherstack for current weather information.
5. Tool outputs are passed back to the LLM.
6. Gemini generates a final response based on the retrieved information.

## 📂 Project Structure

```text
Single-Agent-Multiple-Tools/
│
├── main.py
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

## 🔧 Installation & Setup

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
cd Single-Agent-Multiple-Tools
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Configure API keys**

Create a `.env` file:

```env
GOOGLE_API_KEY=your_google_api_key
TAVILY_API_KEY=your_tavily_api_key
WEATHERSTACK_API_KEY=your_weatherstack_api_key
```

**4. Run the application**

```bash
python main.py
```

## 💡 Example Queries

- What is the capital of India?
- What is the current weather in Delhi?
- What are the latest developments in Artificial Intelligence?
- Tell me about the latest AI developments and the current weather in Mumbai.

## 🧠 Key Learning Outcomes

- Understanding LangChain agents.
- Integrating multiple external tools with an LLM.
- Understanding tool calling and agent decision-making.
- Working with external APIs.
- Building tool-augmented AI applications.

## 🔮 Future Improvements

- Implement a Multi-Agent System using LangGraph.
- Add conversation memory.
- Implement structured outputs.
- Add more specialized tools.
- Develop an interactive user interface.

## 👨‍💻 Author

**Abdul Wazid**

AI/ML Developer | Exploring Agentic AI, LangChain & LangGraph

---

*This project is part of my journey toward building intelligent and autonomous AI systems.*
