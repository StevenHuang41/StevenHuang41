# 🏊🏻‍♂️ Steven Huang

Hi, I'm Steven Huang 👋

I'm a **junior ML/AI Software Engineer** and **UNSW Master of Information Technology graduate specializing in Artificial Intelligence**. I build practical AI software with **Python, FastAPI, Docker, CI/CD, cloud deployment workflows, and RAG/LLM systems**.

My strongest direction is **AI application engineering**: turning ML/RAG ideas into reproducible, testable software with clean APIs, local/containerized workflows, evaluation, and honest documentation of limitations.

---

## What I Build

- **AI / LLM Applications** — RAG pipelines, embeddings, FAISS retrieval, citation-aware answers, provider abstraction, and evaluation workflows
- **ML-backed Products** — data cleaning, feature engineering, model comparison, Optuna tuning, inference APIs, and user-facing applications
- **Backend AI Systems** — FastAPI services, PostgreSQL-backed workflows, Docker Compose environments, tests, and CI/CD validation
- **Applied ML Experiments** — reinforcement learning, computer vision, model evaluation, and careful baseline comparison

---

## Featured Projects

| Project | What it demonstrates | Stack |
|---|---|---|
| [Salary Prediction Web Application](https://github.com/StevenHuang41/salary_prediction_web_application) | End-to-end ML product: React UI, FastAPI backend, PostgreSQL persistence, model training/inference separation, Docker workflow, CI/CD, and GCP deployment patterns | Python, FastAPI, React, PostgreSQL, scikit-learn, Optuna, Docker, GitHub Actions, GCP |
| [RAG-based Notes Helper](https://github.com/StevenHuang41/RAG-based_notes_helper) | Local-first RAG assistant with document ingestion, embeddings, FAISS retrieval, citation-aware responses, smart re-indexing, provider abstraction, Docker, tests, and RAGAS evaluation | Python, FAISS, SentenceTransformers, OpenAI/Gemini/Ollama, LangChain, RAGAS, Docker, pytest |
| [RL-based Stock Trading Support System](https://github.com/StevenHuang41/RL-based_Stock_Trading_Support_System) | Reinforcement-learning experimentation system for buy/sell/hold policy design, reward shaping, exploration strategies, and historical backtesting caveats | Python, TensorFlow/Keras, Q-learning, SARSA, DQN, Deep SARSA, yfinance, pytest |

---

## Project Highlights

### Salary Prediction Web Application

A full-stack machine-learning web application for salary prediction. The system connects a React frontend, FastAPI backend, PostgreSQL database, model training pipeline, inference workflow, and containerized local development.

**Engineering evidence**

- Built separate **training and inference responsibilities** so model updates do not block the API service design.
- Compared multiple regression models and tuned candidates with **Optuna**.
- Reported model performance with **R² = 0.899**, **MAE = 11,291**, and **RMSE = 16,611**.
- Implemented Docker Compose local development plus GitHub Actions checks and GCP Cloud Run / Cloud Run Jobs deployment patterns.

**Why it matters:** this is my strongest end-to-end ML software project because it combines ML, backend APIs, frontend integration, database workflows, containers, CI/CD, and cloud-oriented architecture.

---

### RAG-based Notes Helper

A local-first Retrieval-Augmented Generation tool for querying personal Markdown, text, PDF, and Python notes through a CLI / REPL workflow.

**Engineering evidence**

- Implemented ingestion, chunking, SentenceTransformer embeddings, and **FAISS IndexFlatIP** retrieval for local personal-notes scale.
- Designed citation-aware answers using source file path, document ID, and chunk ID.
- Added provider abstraction for **OpenAI, Gemini, Ollama, and Hugging Face-style backends**.
- Used JSONL metadata with byte-offset indexing for **O(1) post-retrieval chunk metadata lookup**.
- Reduced repeated index-update work by about **96%** with changed-file smart re-indexing.
- Added tests, Docker support, CI/CD, runtime logs, and RAGAS-based evaluation.

**Why it matters:** this project shows practical LLM application engineering: retrieval design, grounding, configuration, observability, evaluation, and maintainable local-first AI tooling.

---

### RL-based Stock Trading Support System

An experimental reinforcement-learning project for studying trading-policy behavior on historical market data. It is a learning and research system, **not** production trading software or financial advice.

**Engineering / research evidence**

- Implemented Q-learning, SARSA, DQN, and Deep SARSA agents.
- Compared epsilon-greedy and softmax exploration strategies.
- Designed a simplified buy/sell/hold environment with state, action, reward, and portfolio-value evaluation.
- Compared learned policies against a buy-and-hold baseline and saved plots, reports, Q-tables, and model weights.
- Best stored DQN epsilon-greedy historical backtest reached **+855% return** and **2.03x** the buy-and-hold baseline under project assumptions.

**Why it matters:** this project demonstrates reinforcement-learning implementation, experiment design, baseline comparison, and awareness of evaluation limitations such as transaction costs, slippage, and historical backtest constraints.

---

## Academic AI / Computer Vision Work

I also completed postgraduate AI / computer-vision projects at UNSW. These are framed as academic project evidence rather than production systems.

- **MRI Image Style Transformation** — contributed to an academic group project comparing VGG19 neural style transfer with CycleGAN for unpaired Siemens-to-Philips MRI scanner-domain image transformation. The project demonstrated CycleGAN's reusable-generator workflow and measured generator-loss reduction, while avoiding claims of clinical validation.
- **Solar Cell Defect Classification** — contributed to a COMP9517 computer-vision project on ELPV solar-cell defect classification, comparing classical CV/ML methods and CNN architectures such as VGG11, ResNet-18, and MobileNetV3 under class imbalance.

---

## Current Learning Focus

I'm currently deepening my skills in:

- **LLM evaluation** — retrieval quality, grounding, faithfulness, and answer relevance
- **Fine-tuning / steering fundamentals** — efficient adaptation concepts and safe claim boundaries
- **Agentic workflows** — tool use, planning, memory, and multi-step AI-assisted engineering patterns
- **MLOps** — reproducible model workflows, packaging, deployment automation, monitoring, and CI/CD
- **Cloud AI architecture** — clean interfaces for deployable AI services and background ML jobs

---

## Technical Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Basic_Scripting-4EAA25?style=flat&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)

**AI / ML / LLM**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter_Tuning-blue?style=flat)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-Embeddings-purple?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-blue?style=flat)
![RAG](https://img.shields.io/badge/RAG-LLM_Applications-purple?style=flat)
![RAGAS](https://img.shields.io/badge/RAGAS-Evaluation-green?style=flat)

**Backend / Data / Product**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-Settings%20%2F%20Validation-E92063?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)

**DevOps / Cloud / Workflow**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-Local_Dev-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![uv](https://img.shields.io/badge/uv-Python_Packaging-654FF0?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Engineering Mindset

- Build projects so they can be **run, tested, and explained**, not just shown in screenshots.
- Prefer **Dockerized, reproducible workflows** and clear setup documentation.
- Use metrics and baselines, but keep claims scoped to what the project actually proves.
- Treat README files as engineering evidence: architecture, testing, limitations, and honest deployment status matter.

---

## Contact

- LinkedIn: [Yen-Jung Huang](https://www.linkedin.com/in/yen-jung-huang-491a57353/)
- Email: [yenjung178741@gmail.com](mailto:yenjung178741@gmail.com)
