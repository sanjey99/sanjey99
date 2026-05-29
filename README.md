# Hi, I'm Sanjeyan Chrysharnthan 👋

**Computer Engineering @ NTU** · ML Systems · GenAI · Quant Finance · Full-Stack

I build production-grade ML systems, quantitative backends, and multimodal AI pipelines. Currently interning at **Panasonic R&D Centre** (ML & GenAI Engineer) and incoming **Data Science Intern at Vertex Holdings**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sanjey99-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/sanjey99)
[![Portfolio](https://img.shields.io/badge/Portfolio-sanjey.vercel.app-000000?style=flat&logo=vercel)](https://sanjey.vercel.app)
[![Email](https://img.shields.io/badge/Email-sanjeyan001@e.ntu.edu.sg-EA4335?style=flat&logo=gmail)](mailto:sanjeyan001@e.ntu.edu.sg)

---

## 🏢 Experience

| Role | Company | Period |
|---|---|---|
| ML & GenAI Intern | Panasonic R&D Centre | Current |
| Data Science Intern *(incoming)* | Vertex Holdings | Upcoming |
| Software Development Engineer Intern | Rohde & Schwarz Asia | May – Jul 2025 |
| Freelance Coding & Robotics Instructor | Empire Code (MOE registered) | Mar 2024 – May 2025 |
| Artillery Sergeant (3SG) | National Service — 23 SA | Mar 2022 – Feb 2024 |

---

## 🚀 Featured Projects

### 🧠 LLM Fine-Tuning & Alignment Lab
`PyTorch` `HuggingFace TRL` `vLLM` `Triton` `Qdrant` `FastAPI` `Docker`

- Fine-tuned **Qwen-2.5-7B-Instruct** on code generation using **QLoRA (4-bit NF4)** with GRPO & DPO post-training alignment
- Implemented **LoRA from scratch** in NumPy/PyTorch (W = W₀ + αBA/r) with manual backprop
- Authored **Triton fused softmax kernel** reducing HBM passes 3→2; benchmarked HumanEval pass@1 & MBPP
- Built end-to-end **RAG pipeline** (bge-small-en-v1.5 + Qdrant + MMR retrieval); deployed vLLM + FastAPI on Docker Compose with Prometheus TTFT/P95 monitoring

---

### 🤖 Multi-Agent Technical Intelligence System
`LangGraph` `Qwen-2.5-7B` `vLLM` `RAGAS` `mem0` `Qdrant` `Celery` `Redis` `Prometheus` `Grafana`

- Engineered a **5-agent LangGraph StateGraph** with human-in-the-loop checkpointing and conditional routing
- A/B tested zero-shot vs CoT vs few-shot across 20 benchmark queries — **CoT achieved RAGAS faithfulness 0.83** (+0.12 over zero-shot)
- Deployed async production serving via **FastAPI + Celery + Redis** (30–120s job queue); **94% citation accuracy**, 88% tool-selection accuracy
- Instrumented per-agent **Prometheus + Grafana P95 histograms** with GPT-4o-mini LLM-as-judge evaluation

---

### 🎬 Multimodal Video Recommendation System
`PyTorch` `CLIP ViT-L/14` `Whisper` `DeepFM` `MMoE` `FAISS` `HuggingFace` `Celery` `C++`

- Fused **CLIP ViT-L/14** visual embeddings (mean+max temporal pooling → 1536-dim) with **Whisper-base ASR** transcripts; late-fusion MLP achieved **mAP 0.67** on 20-class topic tagging and **F1-macro 0.74** on safety filtering
- Deployed two-stage pipeline: **two-tower retrieval** (InfoNCE, FAISS) + **DeepFM ranker** (AUC 0.77) + **MMoE multi-task scorer** (AUC 0.73, watch-time/like/share gating)
- Implemented MMR re-ranking (λ=0.3) with FAISS cold-start fallback (**NDCG@10 +0.19** delta)
- Accelerated frame extraction **3.1× via C++/OpenCV pybind11** binding

---

### 📈 Portfolio Risk Analytics Platform
`Python` `FastAPI` `Apache Kafka` `TimescaleDB` `Redis` `Docker`

- Production quant engine: **Monte Carlo VaR** (10k paths), CVaR/Expected Shortfall, **Markowitz Efficient Frontier** via SLSQP optimisation
- Event-driven market data pipeline via **Kafka (KRaft)** → TimescaleDB with Redis caching at **<5ms hit latency**
- **Fama-French 3-Factor OLS** regression with rolling 126-day factor exposures and **CCAR-style stress tests** (2008 GFC, COVID, rate shock, stagflation)

---

### 🚌 PRISM — Real-Time Transport Monitoring Backend
`TypeScript` `Node.js` `WebSockets` `Swagger` `React` `Vite`
> 🥈 **2nd Place — Hacx! Hackathon** (HTX × Microsoft)

- Built a TypeScript/Express backend with modular controllers, services, and Swagger documentation for transport monitoring across 15+ endpoints
- Implemented deterministic telematics and vital-sign simulation with threshold-based alerting for critical safety events
- Designed audit and session tracking workflows with structured logging and in-memory state management

---

### ⛓️ HarvestChain — Contract Settlement & Risk Backend
`Solidity` `Ethers.js` `Hardhat` `Flask` `MongoDB`
> 🌏 **Global 5th Place — APRU × Google Tech Policy Hackathon** (Bangkok)

- Built Flask REST backend supporting marketplace, futures, contract, and insurance workflows with MongoDB persistence
- Integrated backend services with **Solidity smart contracts** and TypeChain bindings for auditable on-chain/off-chain settlements

---

### 🏠 HomeCast — Real Estate Data & Search Backend
`TypeScript` `Node.js` `React` `SQL` `Prisma ORM` `OneMap API`
> Academic Project — Software Engineering (SC2006)

- Built Node.js/Express backend with REST APIs for property discovery, geospatial search, and favourites
- Engineered **ETL pipelines** to ingest, geocode, and normalise large public datasets into analytics-ready MySQL tables via Prisma ORM

---

### 🛡️ Sentinel — Real-Time Governance & Risk Platform
`PyTorch` `Node.js` `FastAPI` `PostgreSQL` `Docker`
> 🥉 **3rd Place — Deep Learning Week Hackathon** (NTU × Jane Street × Microsoft × OpenAI)

- Built a containerised Node.js backend exposing REST APIs for real-time governance and risk evaluation
- Implemented a **policy + ML fusion engine** combining rule-based checks with PyTorch outputs to generate auditable risk verdicts

---

## 🛠 Technical Skills

**Languages**
`Python` `TypeScript` `C++` `Java` `C#` `SQL` `Solidity` `CUDA`

**ML / AI**
`PyTorch` `HuggingFace (TRL, PEFT, Transformers)` `LangGraph` `LangChain` `vLLM` `FAISS` `Qdrant` `Triton` `W&B` `RAGAS`

**Backend & Infra**
`FastAPI` `Node.js` `Express` `Celery` `Redis` `Apache Kafka` `TimescaleDB` `PostgreSQL` `Docker` `REST API` `WebSocket`

**Frontend**
`React` `Vite` `Next.js`

**Data & Analysis**
`Pandas` `NumPy` `Matplotlib`

---

## 🎓 Education

**Nanyang Technological University (NTU), Singapore** — Aug 2024 – May 2028
Bachelor of Engineering (Honours), Computer Engineering

*Relevant Coursework: Data Structures & Algorithms, Linear Algebra, Probability & Statistics, Discrete Mathematics, Software Engineering, Computer Networks, OOP, Algorithm Design & Analysis*

