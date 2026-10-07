# Avri Barzel

**Applied AI Engineer | Agentic Systems, RAG & Voice AI | Production AI**

I build and operate AI systems that turn models into reliable products, agents and workflows. My work spans architecture, Python/TypeScript engineering, retrieval, evaluation, real-time voice, APIs, databases, cloud deployment and production reliability.

I care about what happens around the model: **grounding, evals, provenance, permissions, observability, latency/cost, fail-closed behavior and human approval where it matters.**

## Selected systems

| System | What it demonstrates | Evidence |
|---|---|---|
| **Legal Eye** | Production Hebrew legal RAG, source-grounded retrieval, verbatim citations, abstention and public evals | Public canonical eval: **0% fabricated citations**, **100% out-of-scope rejection (5/5)** and **0 FAIL** on the latest 50-question run |
| **[OrgState](case-studies/orgstate.md)** | Multi-tenant operational intelligence, evidence trails, decision queues and production SaaS engineering | Tested pilot: **precision 1.0**, **recall 0.917**, **mean +4.5 days lead time** vs. a naive 3-sigma dashboard baseline |
| **[Real-Time Agentic Voice AI](case-studies/voice-ai.md)** | Telephony, streaming audio, speech processing, LLM reasoning, grounded business knowledge and controlled tool execution | Production preflight and authorization gates; representative commerce read improved from ~103.6 ms cold to ~13 ms warm |
| **[GYRO Core / Oracle](case-studies/gyro-core.md)** | AI control under uncertainty, evidence acquisition, risk/abstention, service orchestration and production infrastructure | Oracle-hosted production/canary services with Docker, Linux, CI/CD, health gates, backups and fail-closed release controls |
| **[Lecture Intelligence](case-studies/lecture-intelligence.md)** | Long-form speech AI, transcription, segmentation, worker orchestration, selective repair and quality gates | Production-oriented lecture pipeline with benchmarked segmentation/transcription and targeted reprocessing of weak spans |

## Public proof of work

### Legal Eye — evaluation harness
A public, reproducible evaluation repository for the production Legal Eye system.

- Real production API, not mocks
- Canonical legal questions + adversarial out-of-scope cases
- Raw results and scoring logic
- Scheduled GitHub Actions regression runs
- Explicit abstention over unsupported citation

**Repository:** [GreenCycle2025/legal-eye-eval](https://github.com/GreenCycle2025/legal-eye-eval)  
**Live product:** [legal-eye.1bigfam.com](https://legal-eye.1bigfam.com)

### OrgState — operational intelligence
Production system for detecting operational drift, explaining evidence and surfacing decision queues.

**Stack:** React/Vite, FastAPI, PostgreSQL, Docker, ingestion connectors, SSO/API auth, audit, retention, usage/billing, status and load testing.

**Live demo:** [orgstate.1bigfam.com](https://orgstate.1bigfam.com)

## Engineering focus

- **Applied / Agentic AI:** LLM systems, agents, tool use, workflows, approvals
- **RAG & retrieval:** BM25, dense/hybrid retrieval, reranking, grounding, attribution, retrieval evaluation
- **Voice & speech:** real-time audio, telephony, speech pipelines, long-form transcription
- **Evaluation & reliability:** public evals, regression gates, provenance, auditability, uncertainty and fail-closed behavior
- **Backend & product engineering:** Python, TypeScript, FastAPI, React/Next.js, REST APIs, workers/queues
- **Data & infrastructure:** PostgreSQL, Supabase, Docker, Linux, Oracle Cloud, Vercel, GitHub Actions, CI/CD

## Background

I founded **i-group** in 2023 as an independent Applied AI studio and build products from problem definition through architecture, implementation, evaluation, deployment and production debugging.

Before focusing full-time on AI, I founded and ran a legal practice and served as **VP & Chief Legal Officer** at a digital-health company. That background is useful when AI systems have to work with real users, regulated environments, ambiguous requirements and high-stakes decisions.

I completed a **210-academic-hour AI Engineering / Machine Learning professional program at the Hebrew University of Jerusalem**.

## Current role targets

Applied AI Engineer · Agentic AI Engineer · Forward Deployed AI Engineer · AI Product Engineer · AI Solutions Engineer · RAG / LLM Systems · Voice AI · AI Systems

---

[LinkedIn](https://www.linkedin.com/in/avri-barzel/) · [Legal Eye Eval](https://github.com/GreenCycle2025/legal-eye-eval) · **Israel — Jerusalem & Central Israel**
