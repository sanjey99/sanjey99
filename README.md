# Hi, I'm Sanjeyan Chrysharnthan 👋

**Data Science · Machine Learning · ML Systems**

I turn messy data and model outputs into tested experiments, reliable pipelines, and useful products. I'm a Computer Engineering student at **Nanyang Technological University (NTU)** and currently a **Data Scientist Intern at Vertex Holdings**, working on applied data science and AI-enabled internal tools.

Previously, as a **Machine Learning & GenAI Engineer Intern at Panasonic R&D Centre Singapore**, I built local computer-vision and vision-language systems for GPU-constrained environments.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sanjey99-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/sanjey99)
[![Portfolio](https://img.shields.io/badge/Portfolio-sanjey.vercel.app-000000?style=flat&logo=vercel)](https://sanjey.vercel.app)
[![Email](https://img.shields.io/badge/Email-sanjeyan001%40e.ntu.edu.sg-EA4335?style=flat&logo=gmail)](mailto:sanjeyan001@e.ntu.edu.sg)

---

## Experience

| Role | Organisation | Period |
|---|---|---|
| Data Scientist Intern | Vertex Holdings | Jul 2026 – Present |
| Machine Learning & GenAI Engineer Intern | Panasonic R&D Centre Singapore | May – Jul 2026 |
| Software Development Engineer Intern | Rohde & Schwarz Asia | May – Jul 2025 |

---

## Selected Work

### Data Drift Detection & Adaptation
`Python` `LightGBM` `scikit-learn` `pandas` `SciPy` · Private team submission · [early public prototype](https://github.com/sanjey99/singtel_datadrift)

- Co-built the original NAISC 2026 Singtel Challenge pipeline for telco churn, combining PSI/KS drift tests, adversarial validation, feature engineering, and reweighting under fixed-hyperparameter and CPU-only constraints.
- Built a self-contained drift dashboard and report generator; the final private team repository records **0.787 public-test AU-PRC**.

### [Multimodal Video Recommendation](https://github.com/sanjey99/multimodal-video-recommendation)
`PyTorch` `CLIP` `Whisper` `FAISS` `FastAPI` `Celery`

- Implemented and trained fusion, two-tower retrieval, DeepFM ranking, and MMoE multi-task ranking components, then wired their checkpoints into an asynchronous serving path.
- Evaluated retrieval against content-similarity and popularity baselines, diagnosed where personalization underperformed, and fixed a hand-rolled AUC implementation using a known-answer regression test.

### [Algorithmic Backtesting & Data Quality](https://github.com/sanjey99/algo-backtesting)
`Python` `pandas` `SciPy` `SQLAlchemy` `FastAPI` `pytest`

- Built an event-driven research backtester with next-bar execution, persistent orders, walk-forward analysis, and finite-sample-corrected permutation tests.
- Added quality-gated market-data ingestion, immutable data generations, and 11 SQL analytics/integrity queries; the public system passes **712 tests**, Ruff, and strict mypy.

### [Quantum-Enhanced Fraud Detection](https://github.com/sanjey99/quantum_hackathon)
`Qiskit` `scikit-learn` `Python` `Spring Boot`

- Primary repository author in a two-person hackathon team, building a simulator-verified QSVM with quantum-kernel feature encoding over an imbalanced credit-card fraud dataset.
- Added precision/recall, F1, ROC-AUC, average-precision, and confusion-matrix evaluation, plus a typed Spring Boot service layer.

---

## Open Source

- **[FinancePy PR #249](https://github.com/domokane/FinancePy/pull/249)** — fixed Python 3.10/3.11 compatibility errors in bond YTM/OAS pricing code, including a second latent instance beyond the original report; merged upstream in August 2026.

---

## Toolkit

**Data & ML:** `Python` `SQL` `PyTorch` `scikit-learn` `LightGBM` `pandas` `NumPy` `SciPy` `FAISS`

**Evaluation:** experiment design, baseline comparison, imbalanced classification, drift detection, walk-forward validation, permutation testing

**ML Systems:** `FastAPI` `Docker` `Celery` `Redis` `Prometheus` `MLflow` `PostgreSQL`

**Engineering:** `Git` `pytest` `Ruff` `mypy` `C++` `Java` `TypeScript`

---

## Education

**Nanyang Technological University, Singapore** · Bachelor of Engineering (Honours), Computer Engineering · 2024–2028
