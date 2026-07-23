# Nishitha Singh N 👋
**Backend Developer | AI/LLM Systems**

Sole backend engineer on a live social commerce app shipped to App Store and Play Store — built entirely from scratch. I build production backend systems: REST APIs, real-time infrastructure, payment reliability pipelines, and hybrid RAG systems.

---

## 💼 Production Experience

**Zatch — Sole Backend Engineer** *(Sep 2025 – May 2026)*
Live social commerce platform, built end-to-end:
- Node.js/Express backend with MongoDB, Redis, BullMQ, WebSockets, Agora live video, Bunny CDN
- Razorpay payment flows with full webhook reliability — persist-first on receipt, async retry with exponential backoff, dead-letter queue for permanently failed events
- Optimized MongoDB aggregation pipelines across 9 collections with 38 indexes, parallel `Promise.all` execution — reduced query latency on feed/product listing endpoints

**Terabit Global Solutions — Backend Developer** *(Aug 2024 – May 2025)*
- Built REST APIs handling 10,000+ requests/day at sub-150ms latency; JWT auth + RBAC, 40% response time reduction
- Delivered 3+ features/sprint with end-to-end ownership

---

## 🚀 Featured Projects

### 🎟️ Turnstile — Concurrency-Safe Ticket Booking Backend
Eliminated double-booking race conditions using PostgreSQL row-level locks (`SELECT ... FOR UPDATE`) instead of app-level mutex/Redis lock — proved correctness with 10 simultaneous hold requests on one seat (1 confirmed, 9 correctly rejected, 0 double-bookings).
- TTL-based seat holds, idempotency-key-protected booking confirmation, signed webhook payment verification
- Stack: Node.js, Express, PostgreSQL (Supabase), JWT
🔗 [GitHub](https://github.com/nishithaNsingh/Turnstile)

### 📊 AgentOps — AI Evaluation & Observability Platform
*In active development.* Backend for evaluating and monitoring AI agent behavior — dashboard, playground, evaluations, knowledge base.

### 🟣 DocuMind — Hybrid RAG System
Production-grade RAG for financial/legal Q&A across loan agreements, compliance docs, SEC filings.
- Qdrant + BM25 + Cohere reranking
- **0.90 Faithfulness / 1.00 Context Recall** on RAGAS evaluation
- Dockerized and deployed
🔗 [GitHub](https://github.com/nishithaNsingh/DocuMind)

### 🔴 Call Audit — Voice Call Failure Detection
FastAPI service analyzing sales/support call transcripts to detect failure patterns — undeliverable commitments, unresolved user blocks, repeated clarification loops — with per-pattern severity scoring and actionable prompt fixes.
🔗 [GitHub](https://github.com/nishithaNsingh/call-audit) | [Live](https://oximy-demo.onrender.com)

---

## 🛠️ Tech Stack

**Languages:** Python, JavaScript, SQL
**Backend:** FastAPI, Node.js, Express, REST APIs, WebSockets, BullMQ, Celery, OAuth2, JWT, RBAC, Event-Driven Architecture
**Data:** PostgreSQL, MongoDB, Redis, MySQL, Qdrant, FAISS, SQLAlchemy
**AI/LLM:** LangChain, RAG, Hybrid Retrieval, BM25, Cohere Reranking, RAGAS Evaluation
**DevOps:** Docker, Google Cloud, Render, Git

---

## 📫 Contact
📧 nishithasinghn11@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/nishitha-singh-n-a68b71256/)

---

*Building robust backend infrastructure that enables AI at scale* ✨
