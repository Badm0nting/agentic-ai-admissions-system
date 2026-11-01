# Agentic AI Admissions System

An intelligent, multi-agent automated university admissions processing system powered by LangChain, LangGraph, and Python.

---

## 📌 Overview

The **Agentic AI Admissions System** automates student applicant routing, qualification assessment, and inquiry handling. Built using state-of-the-art multi-agent workflows, the system evaluates applicant data, verifies prerequisites, manages state transitions, and serves interactive responses via a FastAPI server.

### Key Features
* **Multi-Agent Orchestration:** Structured graph-based workflows using LangGraph and LangChain.
* **FastAPI Backend Server:** Production-ready API endpoints (`api_server.py`) for real-time query resolution.
* **State Management:** Strict typing and state management (`state.py`) tracking applicant interactions.
* **Automated Response Generation:** Context-aware admissions dynamic response agent (`response_generator.py`).
* **Tool Integration:** Extensible tool framework (`tools.py`) for admissions evaluation and database lookup.

---

## 🛠️ Tech Stack & Tools

* **Core Framework:** Python 3.9+, LangChain, LangGraph
* **Backend & API:** FastAPI, Uvicorn
* **State & Data Processing:** Pydantic, Python Dataclasses
* **Version Control:** Git, GitHub

---

## 📁 Project Architecture

```text
agentic-ai-admissions-system/
├── api_server.py           # FastAPI backend server endpoints
├── main.py                 # Multi-agent execution entry point
├── response_generator.py   # Response generation module
├── state.py                # LangGraph state schema definition
├── tools.py                # Custom agent tool definitions
├── test.py                 # Test scripts & workflow validation
├── .gitignore              # Environment & build exclusions
└── README.md               # Repository documentation
```

## 🚀 Getting Started

### 1. Prerequisites

* Python 3.9+
* Active API keys (OpenAI / Anthropic / Groq depending on setup)

### 2. Installation

```bash
# Clone the repository
git clone [https://github.com/Badm0nting/agentic-ai-admissions-system.git](https://github.com/Badm0nting/agentic-ai-admissions-system.git)

# Navigate into the project folder
cd agentic-ai-admissions-system

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```
### 3. Running the Application

```bash
# Start the API Server
python api_server.py

# Or run the main workflow directly
python main.py
```
## 👤 Author & Contact

Indraneal Sajjankar

Role: AI/ML Engineer | Computer Vision | Multi-Agent Systems | Full-Stack AI Development |

GitHub: @Badm0nting

Email: nealann101169@gmail.com
