# 🧠 projwt — Enterprise Multi-Agent Operating System (MAOS)

> A distributed AI operating system where specialized agents collaborate 
> to plan, execute, audit, and optimize enterprise tasks.

![Status](https://img.shields.io/badge/status-active-success)
![Python](https://img.shields.io/badge/python-3.10+-blue)
![React](https://img.shields.io/badge/react-18-61DAFB)
![License](https://img.shields.io/badge/license-MIT-green)

## 🎯 What is projwt?

**projwt** is a practice-grade **Multi-Agent Operating System** that orchestrates 
6 specialized AI agents working together as a team to solve complex tasks.

Instead of one LLM doing everything, each agent has a **specific role** — 
just like a real company has different departments.

## 🤖 The 6 Agents

| Agent | Role |
|-------|------|
| 🧭 **Planner** | Breaks down the task into subtasks |
| 🎯 **Coordinator** | Assigns subtasks to right agents |
| ⚡ **Executor** | Performs the actual work |
| 🔍 **Auditor** | Verifies output quality & correctness |
| 🚀 **Optimizer** | Improves & refines the result |
| 👁️ **Observer** | Monitors, logs & reports everything |

## 🔄 Workflow



## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React 18 + Vite + TailwindCSS + Framer Motion |
| **Backend** | Python 3.10 + FastAPI |
| **Agent Framework** | LangGraph |
| **LLM** | Google Gemini API (gemini-1.5-flash) |
| **Database** | SQLite + SQLAlchemy |
| **Vector Memory** | ChromaDB |
| **Charts** | Recharts |
| **Workflow Viz** | React Flow |

## ✨ Features

- ✅ Multi-agent orchestration with LangGraph
- ✅ Real-time task monitoring dashboard
- ✅ Live agent status tracking
- ✅ Audit & optimization reports
- ✅ Workflow visualization graph
- ✅ Beautiful glassmorphism UI (dark theme)
- ✅ Task timeline & execution logs
- ✅ CPU-friendly (no GPU needed)
- ✅ Free tier Gemini API

## 🚀 Quick Start

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env           # Add your GEMINI_API_KEY
python main.py