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
📁 Project StructurePlaintextdevpath-ai-agent/
│
├── 📄 main.py               ← Production Core: FastAPI Backend + Unified HTML5 Dashboard UI
├── 📄 requirements.txt      ← Dependency specifications (fastapi, uvicorn, google-generativeai)
└── 📄 LICENSE               ← MIT Open Source Permission License
🛠️ Tech StackTechnologyRolePython 3.10+Core development language platformFastAPIHigh-performance asynchronous backend & API routing frameworkUvicornLightning-fast ASGI web server production engineGoogle Gemini APIAdvanced LLM reasoning layer for real-time dynamic path computingHTML5 / CSS3 / JSUnified frontpage visualization layer with interactive loading scripts📊 Pipeline OverviewUser inputs a GitHub profile link and selects a target track (e.g., AI/ML Specialist).The asynchronous FastAPI endpoint /api/analyze triggers the agent orchestrator.The Gemini API maps out the strict technology delta matrix between current skillsets and industry demands.An interactive UI instantly renders custom 3-day roadmap cards with explicit action items.🗂️ File SummaryFileRoleUsed Bymain.pyRuns backend router, agent logic, and UI viewEnd-to-end execution (uvicorn)requirements.txtLists environment tracking setupsPackage installer (pip install)LICENSESets open-source usage policiesLegal & community distributions⭐ If you found this project helpful, give it a star! ⭐
