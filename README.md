<h1 align="center">Harsh Vardhan Sahu</h1>
<p align="center"><b>Data Science Undergrad — building full-stack ML systems, not notebooks</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
</p>

---

Most student portfolios stop at model.fit() in a Jupyter notebook. Mine don't — every project below has a real API layer, a real database, and a reason it would survive contact with actual users.

## Projects

### `CustomerIQ` — AI-driven customer intelligence platform
An end-to-end ML system for customer analytics: churn/segmentation models (XGBoost, KMeans) served behind a FastAPI backend, with SHAP-based explainability so predictions aren't a black box.
- **NL-to-SQL + GraphRAG** layer — ask questions in plain English, get answers grounded in the actual data graph, not hallucinated
- **MLflow** for experiment tracking, **Evidently AI** for live model drift detection, **Celery** for async training jobs
- Frontend redesigned with a Bloomberg-Terminal-inspired dark UI
- `FastAPI · Supabase/PostgreSQL · XGBoost · SHAP · MLflow · Evidently AI · Celery`

### `ResumePro` — ATS resume optimization engine
A scoring engine that evaluates resumes against weighted, ATS-relevant categories, then rewrites weak sections using a **locally-hosted LLM** (Ollama/Phi3.5) — no OpenAI API key, no data leaving the machine.
- Semantic matching via SentenceTransformers + spaCy NLP pipeline
- Before/After rewrite view so the improvement is visible, not just a score
- `FastAPI · spaCy · SentenceTransformers · Ollama/Phi3.5 · React/Vite`

### `5th Element Fitness Club` — gym management platform
Full production backend, built solo: JWT auth with role-based access (Admin/Trainer/User), Razorpay payment integration, Redis-backed Celery task queue, structured logging.
- `Next.js · FastAPI · PostgreSQL (Neon) · Redis · Celery · JWT · Razorpay`

### `ResearchRelay` *(in progress)* — multi-agent research system
A planner agent breaks a query into sub-tasks, researcher agents gather sources in parallel over MCP tool servers, a critic agent checks claims against sources, a writer agent compiles the final report. Built to go deep on agentic architecture, not just call an agent framework and stop.

---

## Stack

| | |
|---|---|
| **Languages** | Python, C++, Java, SQL |
| **ML / DL** | PyTorch, TensorFlow, Scikit-learn, NLP |
| **Data** | PostgreSQL, MongoDB, Redis, Pandas, NumPy |
| **Backend** | FastAPI, Celery, JWT/RBAC |
| **Frontend** | React, Next.js |
| **Tooling** | Git, MLflow, Docker |

---

<p align="center">
📫 Open to Data Science / ML internship opportunities — <a href="https://www.linkedin.com/in/harsh-vardhan-sahu-6a4391294/">LinkedIn</a>
</p>
