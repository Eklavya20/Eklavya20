# Eklavya Jumnani

Data Scientist · Applied AI Engineer · Germany  
I build production ML systems that are honest about their own failures.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eklavya-jumnani)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat&logo=pypi&logoColor=white)](https://pypi.org/user/EklavyaJ/)
[![diagnost](https://img.shields.io/pypi/v/diagnost?label=diagnost)](https://pypi.org/project/diagnost/)

---

## Projects

### [`contract-analyst`](https://github.com/Eklavya20/contract-analyst)

A local agentic RAG system for legal contract analysis. Ask questions in plain English — the agent retrieves relevant clauses, flags risks, and compares terms across documents, with every answer grounded in a source citation.

- LangGraph ReAct agent with four tools: semantic search, clause extraction, risk flagging, cross-contract comparison
- Fully local via Ollama (Mistral 7B) — no API keys, no data leaves the machine, GDPR-compliant by design
- FAISS vector store with sentence-transformers embeddings
- Streamlit interface

---

### [`ml-guardian`](https://github.com/Eklavya20/ml-guardian) · [![CI](https://github.com/Eklavya20/ml-guardian/actions/workflows/ml-guardian.yml/badge.svg)](https://github.com/Eklavya20/ml-guardian/actions/workflows/ml-guardian.yml)

Automated model quality gates for MLflow. Compares every candidate model against the current production version across accuracy, F1, ROC-AUC, calibration, and feature drift — auto-promotes on pass, hard blocks with a structured report on failure.

- Configurable thresholds per use case
- GitHub Actions native — no extra infrastructure required
- Built on top of `diagnost` and `ml-production-template`

---

### [`ml-production-template`](https://github.com/Eklavya20/ml-production-template) · [![CI](https://github.com/Eklavya20/ml-production-template/actions/workflows/ci.yml/badge.svg)](https://github.com/Eklavya20/ml-production-template/actions/workflows/ci.yml)

A full MLOps stack covering training pipeline through served API — experiment tracking, orchestration, containerisation, CI/CD, and quality gates in one composable template.

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

An open-source Python library for end-to-end model diagnostics. Accuracy on a test set is one number — Diagnost covers what it doesn't: overconfidence, data drift, subgroup performance gaps, and dataset quality issues.

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

## Master Thesis

**Dimensionality Reduction and Feature Extraction for High-Dimensional Datasets**  
*FAU Erlangen-Nürnberg · 2026*

*Link coming soon.*

---

## Experience

**Junior Data Scientist**  
LINO Consulting and Research · Munich · Nov 2025 – Present

**Data Analytics and Reporting · Werkstudent**  
Loyalty Partner Solutions GmbH · Munich · Jul 2023 – Oct 2025

**Artificial Intelligence Student Assistant**  
Pattern Recognition Lab, FAU Erlangen-Nürnberg · Aug – Dec 2023

**Senior Operations Executive**  
Infosys Limited · Pune · Dec 2020 – Aug 2022

---

## Education

**M.Sc. Data Science** — Major: AI & Machine Learning  
FAU Erlangen-Nürnberg · 2026

**Diploma in Data Analytics and Econometrics**  
Pune University · 2021

**Bachelor of Business and Computer Applications**  
MIT World Peace University · 2020