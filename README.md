---

# 🤖 AI Agent with Playwright (LangGraph + Ollama)

An intelligent **autonomous AI agent** built using **LangGraph** and **Ollama (Llama 3.1)** that can **browse the web, use tools, and remember conversations** using Playwright-powered browser automation.

---

## 🚀 Features

* 🧠 Local LLM (Llama 3.1 via Ollama) — no API required
* 🌐 Playwright browser automation (real-time web interaction)
* 🔍 Tool-calling AI agent (search, browser, notifications)
* 🧠 Conversational memory using LangGraph
* 🔁 Agent workflow with conditional tool execution
* 💬 Interactive UI using Gradio

---

## 📸 Demo

### 🧠 Chat History

![Chat History](chathistory.png)

---

### 🔁 Agent Flow

![Flow](flow.png)

---

### 🌐 Playwright Tool in Action

![Playwright Tool](playwrighttool.png)

---

## 🛠️ Tech Stack

* Python
* LangGraph
* LangChain
* Ollama (Llama 3.1)
* Playwright
* Gradio
* Google Serper API
* Pushover API

---

## ⚙️ Setup

```bash
# Create virtual environment
python3 -m venv myenv
source myenv/bin/activate

# Install dependencies
pip install langgraph langchain-core langchain-ollama langchain-community playwright gradio python-dotenv

# Install Playwright browsers
playwright install chromium
```

---

## ▶️ Run

```bash
# Start Ollama
ollama run llama3.1

# Run your app
python your_script.py
```

---

## 🧩 How It Works

1. User sends input via Gradio UI
2. LangGraph agent processes the request
3. LLM decides:

   * Answer directly
   * OR call tools (Playwright, search, notification)
4. Tools execute actions (browse, extract, notify)
5. Memory stores conversation context
6. Final response returned to user

---

## 📌 Example Use Cases

* AI agent that browses websites and summarizes content
* Real-time news fetching using browser automation
* Smart assistant with memory and tool usage
* Autonomous web-interacting AI systems

---

## 🧠 Architecture

* **StateGraph** → controls workflow
* **Chatbot Node** → LLM reasoning
* **Tools Node** → executes actions (Playwright, APIs)
* **MemorySaver** → maintains conversation history

---


## ⭐ Author

**Prateek Choudhary**

---

