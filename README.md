<div align="center">

# Vishal Kumar Kashyap

**AI Engineer** — building production-grade RAG pipelines, multi-agent orchestration systems, and LLM-powered APIs that work at scale.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishal-kumar-kashyap/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vishal-kumar-kashyap.vercel.app)
[![Email](https://img.shields.io/badge/Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kumarvikash10351@gmail.com)

</div>

---

```yaml
name: Vishal Kumar Kashyap
role: AI Engineer · RAG Specialist · Agentic Systems Builder
focus:
  - Multi-agent orchestration with dynamic task routing & memory
  - Retrieval-augmented generation — chunking, indexing, re-ranking, grounding
  - LLM serving & API design — structured outputs, latency optimization
  - Semantic search infrastructure — dense embeddings, vector indexing
  - ML pipeline engineering — training, evaluation, deployment
currently_building: production RAG systems with sub-200ms retrieval latency
open_to: AI Engineer · ML Engineer · GenAI Engineer · Applied AI roles
```

---

## Featured Projects

> Each project below is a full-stack AI system — designed, architected, and shipped end-to-end.

<table>
<tr><td>

### [ARIA v2 — Adaptive Reasoning Intelligence Agent](https://github.com/kumarvishal10351/ARIA-V2)

A multi-agent AI assistant with dynamic reasoning across conversational, retrieval, and tool-execution modules. Routes queries intelligently between live chat, document retrieval via vector search, and system-level command execution.

**Architecture:** Modular multi-agent design with central orchestrator for task delegation and context-aware routing.

| Metric | Value |
|---|---|
| Agent Modules | 3+ (chat, retrieval, tool-exec) |
| Retrieval | Vector embedding pipeline with semantic re-ranking |
| API | FastAPI REST endpoints, low-latency real-time interaction |
| Interface | Voice-based I/O with session continuity |

`Multi-Agent` `RAG` `FastAPI` `Vector Embeddings` `LLMs` `Voice Interface`

</td></tr>
</table>

---

<table>
<tr><td>

### [AI Career Copilot — Resume Intelligence Platform](https://github.com/kumarvishal10351/AI-Career-Copilot)

End-to-end resume intelligence platform: parses resumes, scores against ATS criteria, matches job descriptions, and generates structured interview preparation — all powered by an LLM backbone with structured JSON outputs.

**Architecture:** Modular pipeline separating LLM inference, PDF parsing, scoring engine, and caching layers.

| Metric | Value |
|---|---|
| LLM Backend | Mistral AI with structured JSON outputs |
| Features | ATS scoring, resume rewriting, job matching, interview Q&A |
| Resilience | Retry logic + session-based state for multi-user stability |
| Interface | Streamlit with real-time scoring dashboard |

`Mistral AI` `Streamlit` `NLP` `ATS Scoring` `PDF Parsing` `LLMs`

</td></tr>
</table>

---

<table>
<tr><td>

### [AURA — Adaptive Unified Retrieval Assistant](https://github.com/kumarvishal10351/-AURA-Adaptive-Unified-Retrieval-Assistant)

A retrieval-augmented QA system engineered to minimize hallucinations by grounding every LLM response in semantically retrieved source documents. Designed for enterprise-grade document Q&A reliability.

**Architecture:** Dense vector search → semantic re-ranking → LLM reasoning with source attribution.

| Metric | Value |
|---|---|
| Retrieval | Dense vector search with semantic re-ranking |
| Pipeline | Scalable ingestion → chunking → indexing → query |
| Grounding | Source-attributed responses, hallucination reduction |
| Target | Enterprise document Q&A with high precision |

`RAG` `Vector DB` `Semantic Search` `NLP` `Knowledge Grounding`

</td></tr>
</table>

---

<table>
<tr><td>

### [AI Research Multi-Agent System](https://github.com/kumarvishal10351/AI-Research-Multi-Agent-System)

Multi-agent research system where specialized agents collaborate on complex research tasks — from literature review and data synthesis to insight generation — with coordinated tool use and shared memory.

**Architecture:** Agent swarm with role specialization, shared context store, and orchestrated task decomposition.

`Multi-Agent` `Research Automation` `LLMs` `Tool Use` `Memory Management`

</td></tr>
</table>

---

<table>
<tr><td>

### [FluentCoach — AI Language Learning](https://github.com/kumarvishal10351/FluentCoach)

AI-powered language learning coach that provides real-time conversational practice, pronunciation feedback, and adaptive difficulty scaling using LLMs and speech processing.

**Architecture:** Speech-to-text → LLM conversation engine → text-to-speech with feedback loop.

`Speech Processing` `LLMs` `NLP` `Adaptive Learning` `Python`

</td></tr>
</table>

---

## System Architecture

> How I design RAG & multi-agent systems — from ingestion to inference.

```mermaid
graph LR
    subgraph Ingestion
        A[Documents] --> B[Chunking Engine]
        B --> C[Embedding Model]
        C --> D[(Vector Store)]
    end

    subgraph Retrieval
        E[User Query] --> F[Query Embedding]
        F --> G[Semantic Search]
        D --> G
        G --> H[Re-Ranking]
    end

    subgraph Reasoning
        H --> I[Context Assembly]
        I --> J[LLM Inference]
        J --> K[Source Attribution]
        K --> L[Grounded Response]
    end

    subgraph Agent Layer
        M[Orchestrator] --> N[Chat Agent]
        M --> O[Retrieval Agent]
        M --> P[Tool Agent]
        O --> G
    end

    style A fill:#1a1f35,stroke:#4de8c2,color:#fff
    style D fill:#1a1f35,stroke:#4de8c2,color:#fff
    style J fill:#1a1f35,stroke:#4de8c2,color:#fff
    style M fill:#1a1f35,stroke:#4de8c2,color:#fff
    style L fill:#0d1117,stroke:#4de8c2,color:#4de8c2
```

---

## Tech Stack

**AI / ML / GenAI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Vector & Search**

![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Data & Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## GitHub Activity

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=kumarvishal10351&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&bg_color=0d1117&title_color=4de8c2&icon_color=4de8c2&text_color=9aa0b8" />
&nbsp;&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kumarvishal10351&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0d1117&title_color=4de8c2&text_color=9aa0b8" />

</div>

---

## Writing & Talks

> *Coming soon — technical deep-dives on RAG pipeline optimization, multi-agent design patterns, and LLM evaluation.*

<!-- Uncomment as you publish:
- 📝 [Designing RAG Pipelines That Don't Hallucinate](#) — How I built AURA's retrieval + grounding system
- 📝 [Multi-Agent Architecture: Lessons from ARIA](#) — Orchestration patterns for production agents
- 📝 [LLM Evaluation Beyond BLEU: A Practical Framework](#) — Metrics that actually matter
-->

---

## Education

| Degree | Institution | Year |
|---|---|---|
| **B.Tech**, Computer Science | Rajiv Gandhi Proudyogiki Vishwavidyalaya | 2023 – 2026 |
| **Diploma**, Computer Science | Jharkhand University of Technology | 2020 – 2023 |

---

<div align="center">

*I build AI systems that work in production — not just in notebooks.*

<sub>If you're working on interesting AI problems, let's talk → <a href="mailto:kumarvikash10351@gmail.com">kumarvikash10351@gmail.com</a></sub>

</div>
