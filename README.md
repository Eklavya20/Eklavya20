# Eklavya Jumnani

Data Scientist · Germany  
I build production ML systems that are honest about their own failures.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eklavya-jumnani)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat&logo=pypi&logoColor=white)](https://pypi.org/user/EklavyaJ/)
[![diagnost](https://img.shields.io/pypi/v/diagnost?label=diagnost)](https://pypi.org/project/diagnost/)

---

## 🔧 Projects

### [`contract-analyst`](https://github.com/Eklavya20/contract-analyst)

Reviewing contracts is a chore. This makes it less of one — ask a question in plain English, get a cited answer in seconds, without reading 50 pages yourself.

- LangGraph ReAct agent with four tools: semantic search, clause extraction, risk flagging, cross-contract comparison
- Fully local LLM via Ollama (Mistral 7B) — no API keys, no data leaves the machine
- FAISS vector store with sentence-transformers embeddings
- Every answer cites the exact contract and chunk it came from
- Interactive UI built with Streamlit

---

### [`ml-guardian`](https://github.com/Eklavya20/ml-guardian) · [![CI](https://github.com/Eklavya20/ml-guardian/actions/workflows/ml-guardian.yml/badge.svg)](https://github.com/Eklavya20/ml-guardian/actions/workflows/ml-guardian.yml)

A retrained model that quietly got worse is harder to catch than one that obviously broke. ML Guardian catches it before it reaches production — comparing every new model against the live one and blocking deployment if something regressed.

- Checks accuracy, F1, ROC-AUC, calibration, and feature drift against the current production model
- Configurable thresholds — tighten or loosen gates per use case
- Auto-promotes to Production on pass, hard blocks with a full report on failure
- GitHub Actions native — no extra infrastructure needed

Built on top of `diagnost` and `ml-production-template`.

---

### [`ml-production-template`](https://github.com/Eklavya20/ml-production-template) · [![CI](https://github.com/Eklavya20/ml-production-template/actions/workflows/ci.yml/badge.svg)](https://github.com/Eklavya20/ml-production-template/actions/workflows/ci.yml)

Most ML tutorials end at `model.fit()`. This one doesn't — it covers everything from training pipeline to served API, so the next project starts from a solid foundation instead of from scratch.

| Layer | Tool |
|---|---|
| Experiment tracking | MLflow |
| Training pipeline | Prefect |
| Model serving | FastAPI |
| Containerisation | Docker + Docker Compose |
| CI/CD | GitHub Actions |
| Quality gates | ml-guardian |

---

### [`diagnost`](https://github.com/Eklavya20/diagnost) · [![PyPI version](https://img.shields.io/pypi/v/diagnost)](https://pypi.org/project/diagnost/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Accuracy on a test set is one number. It doesn't tell you whether your model is overconfident, whether your data has drifted, or whether it performs equally across groups. Diagnost asks those questions so you don't have to remember to.

| Pillar | What it covers |
|---|---|
| Performance | Classification, regression, clustering metrics |
| Calibration | Reliability curves, ECE, Brier score |
| Drift Detection | KS and Chi-Square tests per feature |
| Dataset Diagnostics | Class imbalance, missing data, outliers, correlation |
| Model Comparison | Side-by-side benchmarking with winner declaration |

```python
pip install diagnost
```

---

## 🧪 Master Thesis

**Dimensionality Reduction and Feature Extraction for High-Dimensional Datasets**  
*FAU Erlangen-Nürnberg · 2025*

---

## 🛠 Stack

**ML & Modeling**  
Python · scikit-learn · XGBoost · PyTorch · Hugging Face

**LLM & RAG**  
LangChain · LangGraph · FAISS · sentence-transformers · Ollama

**MLOps & Infrastructure**  
MLflow · Prefect · FastAPI · Streamlit · Docker · GitHub Actions

**Evaluation & Diagnostics**  
diagnost · calibration · drift detection · ECE · model comparison

**Data**  
pandas · numpy · SQL · AWS

---

## 💼 Experience

**Junior Data Scientist**  
LINO Consulting and Research · Munich · Nov 2025 – Present

**Data Analytics and Reporting · Werkstudent**  
Loyalty Partner Solutions GmbH · Munich · Jul 2023 – Oct 2025

**Artificial Intelligence Student Assistant**  
Pattern Recognition Lab, FAU Erlangen-Nürnberg · Aug – Dec 2023

**Senior Operations Executive**  
Infosys Limited · Pune · Dec 2020 – Aug 2022

---

## 🎓 Education

**M.Sc. Data Science** — Major: AI & Machine Learning  
FAU Erlangen-Nürnberg · 2025

**Diploma in Data Analytics and Econometrics**  
Pune University · 2021

**Bachelor of Business and Computer Applications**  
MIT World Peace University · 2020