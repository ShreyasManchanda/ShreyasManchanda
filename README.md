<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=140&section=header&text=Shreyas%20Manchanda&fontSize=42&fontColor=ffffff&fontAlignY=55&animation=fadeIn" width="100%"/>

### AI/ML Engineer · Agentic Systems · RAG · LLM Evaluation

*Building production AI systems that reason, retrieve, and act — not just autocomplete.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shreyas%20Manchanda-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/shreyasmanchanda)
[![Email](https://img.shields.io/badge/Email-reach%20me-D14836?style=flat-square&logo=gmail)](mailto:manchandashreyas24@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ShreyasManchanda-181717?style=flat-square&logo=github)](https://github.com/ShreyasManchanda)

</div>

---

## What I build

I'm a final-year CSE student at **SRM Institute of Science and Technology** (CGPA 9.39/10, graduating May 2027) who ships AI systems end-to-end — agent orchestration, RAG pipelines, evaluation infrastructure, and the production APIs underneath all of it.

My focus is **agentic systems that have to be trusted, not just impressive** — which means the evaluation and failure-handling layer matters to me as much as the agent logic itself. I've spent the last year doing this in production: rebuilding a brittle SQL agent into a supervisor-managed, async-streaming LangGraph pipeline, and running adversarial testing on production LLM agents to surface failure modes before they reached clients.

---

## Experience

**AI Engineer Intern · RMgX Technologies** — *May 2026 – Jul 2026*
Built a domain-agnostic conversational chatbot end-to-end — owned recognition/understanding, response generation, and integration, designed to generalize across use cases rather than a single hardcoded flow. Alongside this, worked on a document/data ingestion pipeline handling messy real-world edge cases, integrating with existing infra and Table Transformer (TATR) for structured extraction, with hands-on experimentation using YOLO for detection tasks.

**AI Engineer Intern · RMgX Technologies** — *Jun 2025 – Jul 2025*
Ran adversarial testing on production LLM agents — engineering edge-case prompts that broke SQL agent query logic and induced hallucinations, surfacing failure modes prior to client deployment. Rebuilt a brittle SQL agent into a supervisor-managed, async-streaming LangGraph agent, eliminating recurring production failures. Shipped 3 production-ready agentic components (RAG, SQL, and internet agents) across 4 sprints in a 5-person cross-functional team.

---

## Featured Projects

| Project | What it does | Stack | Key Result |
|---|---|---|---|
| [**Aletheia**](https://github.com/ShreyasManchanda/Aletheia) · [Live Demo](#) | Self-hosted GraphRAG system reconstructing company events across Slack, Jira & GitHub — two-pass linking (deterministic + IDF-weighted Jaccard + optional LLM pass) with auditable confidence scores on every edge | FastAPI · Neo4j · Qdrant · PostgreSQL · Redis · LangGraph · Gemini | Hybrid retrieval (BM25 + dense RRF → graph expansion → reranking), RBAC-gated end to end |
| [**CMPT**](https://github.com/ShreyasManchanda/CMPTR) · [Live Demo](#) | AI competitive pricing platform — deterministic pricing engine handles rule-based decisions, an Ambiguity Agent resolves edge cases, an Explanation Agent generates auditable rationale | CrewAI · LangGraph · Gemini · Firecrawl · FastAPI · PostgreSQL | ~90% reduction in manual competitor data collection |
| [**Dumb It Down**](https://github.com/ShreyasManchanda/DumbItDown) · [Live Demo](#) | Hybrid RAG pipeline over a ~1,250-paper PubMed corpus, converting dense academic text into accessible summaries | FAISS · Qdrant · Gemini 2.0 Flash · FastAPI · React · SQLite | 3-stage retrieval (rewrite → search → rerank), validated via user testing |

<!-- Replace the (#) placeholders above with your actual Live Demo URLs once you send them -->

---

## Stack

<div align="center">

**LLM & Agents**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6F00?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini%20LLM-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Retrieval & Evaluation**

![FAISS](https://img.shields.io/badge/FAISS-00599C?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-4B0082?style=for-the-badge)

**Backend & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

</div>

---

## Certifications

- 🟠 **AWS Certified AI Practitioner** (2025)
- ☁️ **AWS Certified Cloud Practitioner** (2025)

---

## Research

📄 **CNN & DNN for Alzheimer's Detection via EEG** — Independent research, joint first author. State-of-the-art 69.22% accuracy on BCI Competition III Dataset IV (subject-independent LOSO evaluation); 86.89% under subject-dependent evaluation.

---

## Currently

- 🤝 Open to AI/ML engineering internships — agentic systems, RAG, LLM evaluation. Remote or India-based.

---

<div align="center">

*"The best way to understand a system is to build one."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=80&section=footer" width="100%"/>

</div>
