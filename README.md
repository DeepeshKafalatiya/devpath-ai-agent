# 🎙️ DevPath AI

### Autonomous Multi-Agent Career & Skill Mentor

⚡ **Submitted for Agentic Arena 2026 - Round 2** ⚡

💥 [![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org) [![FastAPI](https://img.shields.io/badge/FastAPI-v0.100+-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com) [![Google Gemini](https://img.shields.io/badge/Google_Gemini-API_Reasoning-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev) [![Status](https://img.shields.io/badge/STATUS-ACTIVE-brightgreen?style=for-the-badge)](https://github.com) 💥

> DevPath AI is a production-grade autonomous multi-agent framework designed to bridge the structural skill gap for engineering students by replacing static learning charts with self-correcting dynamic roadmaps powered by Google Gemini.

---

## 📌 Table of Contents
* [How It Works](#-how-it-works)
* [Project Structure](#-project-structure)
* [Tech Stack](#-tech-stack)
* [Pipeline Overview](#-pipeline-overview)
* [File Summary](#-file-summary)
* [License](#-license)

---

## 🧠 How It Works

```text
┌──────────────────────┐      ┌───────────────────────────┐      ┌───────────────────────────┐
│  User Github URL     │  ▶   │  Profile Evaluation Agent │  ▶   │  Trend Intelligence Agent │
│  & Target Career     │      │  (Parses Core Footprint)  │      │  (Global Industry Bench)  │
└──────────────────────┘      └───────────────────────────┘      └─────────────┬─────────────┘
                                                                               │
                                                                               ▼
                                                                 ┌───────────────────────────┐
                                                                 │ Dynamic Curriculum        │
                                                                 │ Orchestrator (Gemini API) │
                                                                 └─────────────┬─────────────┘
                                                                               │
                                                                               ▼
                                                                 ┌───────────────────────────┐
                                                                 │ Unified Interactive       │
                                                                 │ Responsive Dashboard UI   │
                                                                 └───────────────────────────┘

📁 Project Structure

devpath-ai-agent/
│
├── 📄 main.py               ← Production Core: FastAPI Backend + Unified HTML5 Dashboard UI
├── 📄 requirements.txt      ← Dependency specifications (fastapi, uvicorn, google-generativeai)
└── 📄 LICENSE               ← MIT Open Source Permission License

🛠️ Tech Stack

[Technology]        | [Role]
────────────────────┼───────────────────────────────────────────────────────────────────
Python 3.10+        | Core development language platform
FastAPI             | High-performance asynchronous backend & API routing framework
Uvicorn             | Lightning-fast ASGI web server production engine
Google Gemini API   | Advanced LLM reasoning layer for real-time dynamic path computing
HTML5 / CSS3 / JS   | Unified frontpage visualization layer with interactive loading scripts

📊 Pipeline Overview

1. User inputs a GitHub profile link and selects a target track (e.g., AI/ML Specialist).
2. The asynchronous FastAPI endpoint `/api/analyze` triggers the agent orchestrator.
3. The Gemini API maps out the strict technology delta matrix between current skillsets and industry demands.
4. An interactive UI instantly renders custom 3-day roadmap cards with explicit action items.

🗂️ File Summary

[File]              | [Role]                                | [Used By]
────────────────────┼───────────────────────────────────────┼─────────────────────────────────
main.py             | Runs backend router & agent UI view   | End-to-end execution (uvicorn)
requirements.txt    | Lists environment tracking setups     | Package installer (pip install)
LICENSE             | Sets open-source usage policies       | Legal & community distributions

⭐ If you found this project helpful, give it a star! ⭐
