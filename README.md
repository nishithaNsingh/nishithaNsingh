# Nishitha Singh

**I build AI systems that work in production — not demos.**

RAG pipelines with measurable retrieval quality. Voice agent failure detectors catching real compliance violations. Backends handling real traffic. If it doesn't solve a concrete problem, I don't ship it.

Currently: open to Forward Deployed / Applied AI Engineering roles at early-stage startups.

---

## What I've built

### Call Audit — Voice Agent Failure Detector
Most voice AI teams find out their agent is broken when a customer complains. Call Audit catches it first.

Analyzes voice transcripts and classifies failures into `PROMISE_RISK`, `DEAD_END`, and `USER_CONFUSION` — then generates specific prompt fixes, not just flags. Built with an LLM-as-judge pattern, structured outputs, and a FastAPI backend.

→ [github.com/nishithaNsingh/call-audit](https://github.com/nishithaNsingh/call-audit)

---

### DocuMind — Hybrid RAG for Financial & Compliance Documents
Keyword search misses context. Pure vector search misses exact terms. DocuMind uses both — BM25 + dense vector retrieval fused with Reciprocal Rank Fusion, then Cohere reranking on top.

Evaluated end-to-end with RAGAS: **0.90 faithfulness / 1.00 context recall** on financial and compliance document sets. Not self-reported — measured.

→ [github.com/nishithaNsingh/DocuMind](https://github.com/nishithaNsingh/DocuMind)

---

### Real-Time Anomaly Detection Pipeline
WebSocket-based streaming pipeline built for low-latency event monitoring. Redis-backed ingestion, live dashboard support, designed to handle high-frequency event streams without dropping data.

→ [github.com/nishithaNsingh/realtime-anomaly-detection](https://github.com/nishithaNsingh/realtime-anomaly-detection)

---

### Real-Time Chat Backend
Production-grade messaging backend: WebSocket connections, Redis pub/sub for delivery, PostgreSQL for persistence, JWT auth, offline message queuing. The kind of thing that has to work at 2am.

→ [github.com/nishithaNsingh/chat-app](https://github.com/nishithaNsingh/chat-app)

---

## Stack

**AI/ML** — LLM APIs (OpenAI, Anthropic, Cohere), RAG, LangChain, Qdrant, FAISS, RAGAS, Prompt Engineering, Structured Outputs

**Backend** — Python, FastAPI, REST APIs, WebSockets, Async, Redis, MongoDB, PostgreSQL

**Infra** — Docker, Render, AWS, GCP, Firebase

---

## Contact

nishithasinghn11@gmail.com · [LinkedIn](https://www.linkedin.com/in/nishitha-singh-n-a68b71256/)
