# Nishitha Singh 👋
**Applied AI Engineer | Backend Systems | LLM Infrastructure**

I build production-grade backend systems that power AI applications — designing scalable APIs, implementing hybrid retrieval pipelines, orchestrating agentic workflows, and architecting high-performance inference backends using modern async frameworks.

---

## 🎯 Backend Engineering Focus

- ⚡ **Production FastAPI Backends** — Building scalable REST & WebSocket APIs with async/await, dependency injection, and structured request handling
- 🧠 **Retrieval Infrastructure** — Designing hybrid RAG systems with vector databases, reranking pipelines, and semantic search at scale
- 🤖 **Agentic Orchestration** — Implementing multi-tool workflows, agent state management, and LLM-driven decision systems
- 📊 **Evaluation & Observability** — Building evaluation frameworks (RAGAS), logging, and metrics for AI system quality
- 🔄 **Async Architecture** — Designing event-driven systems with WebSockets, Redis pub/sub, message queues, and real-time streaming
- 🗄️ **Data Persistence** — Working with PostgreSQL, MongoDB, vector databases (Qdrant, FAISS), and caching layers
- ☁️ **Cloud Deployment** — Containerizing with Docker, deploying on AWS/GCP, managing scalability and zero-downtime releases

---

## 🚀 Featured Projects

### 🟣 **DocuMind** — Production Hybrid RAG System
**Retrieval Infrastructure | Evaluation Pipeline | Enterprise Scale**

Built a sophisticated RAG backend for financial and compliance document analysis:
- **Hybrid Retrieval**: Implemented BM25 lexical search + semantic embeddings with Reciprocal Rank Fusion (RRF) for optimal result ranking
- **Smart Reranking**: Integrated Cohere reranking to filter top-K results before LLM generation, reducing hallucinations
- **Grounded Generation**: Built LLM integration with retrieval-augmented context for fact-grounded responses
- **Quality Metrics**: Designed RAGAS evaluation suite measuring Faithfulness (0.90), Recall (1.00), and answer relevance
- **Vector Database**: Deployed Qdrant for efficient semantic search across long-form enterprise documents
- **Architecture**: Scalable FastAPI backend with document chunking, embedding pipelines, and async retrieval workflows

🔗 [GitHub: DocuMind](https://github.com/nishithaNsingh/DocuMind)

---

### 🔴 **Call Audit** — AI Voice Failure Analysis Backend
**LLM Orchestration | Structured Workflows | Pattern Detection**

Engineered an end-to-end system for analyzing voice agent interactions and detecting failure patterns:
- **Transcript Pipeline**: Built async processing backend for ingesting and parsing call transcripts
- **Failure Detection**: Implemented multi-agent workflow to identify conversational failures (user confusion, dead ends, broken promises)
- **Severity Scoring**: Designed risk classification system with automated severity levels
- **Prompt Remediation**: Created LLM-driven agent to generate actionable prompt fixes from failure patterns
- **API Architecture**: Designed FastAPI endpoints for transcript submission, analysis, and results retrieval
- **Compatible APIs**: Built abstraction layer supporting Anthropic and OpenAI-compatible model endpoints
- **Workflow Orchestration**: Implemented structured LLM calls with tool use, memory, and sequential processing

🔗 [GitHub: Call Audit](https://github.com/nishithaNsingh/call-audit)

---

### 🟠 **Financial Audit Ledger** — Enterprise Audit Trail System
**Database Architecture | API Design | Data Integrity**

Developed a robust backend system for financial record auditing and compliance tracking:
- **Data Persistence**: Designed PostgreSQL schema for immutable audit logs with timestamps and change tracking
- **REST API**: Built FastAPI endpoints for ledger queries, transaction audits, and compliance reporting
- **Transaction Integrity**: Implemented mechanisms to ensure audit trail accuracy and non-repudiation
- **Query Optimization**: Designed efficient indexing and query patterns for large-scale financial datasets
- **Compliance Ready**: Structured backend to support regulatory requirements and audit workflows

🔗 [GitHub: Financial Audit Ledger](https://github.com/nishithaNsingh/Financial-Audit-Ledger)

---

### 🔵 **Real-Time Anomaly Detection Pipeline** — Streaming ML Backend
**Async Processing | WebSockets | Low-Latency Inference**

Built a high-performance streaming inference system for real-time data analysis:
- **FastAPI Streaming**: Implemented WebSocket endpoints for continuous data ingestion and result streaming
- **Async Processing**: Designed fully asynchronous processing pipeline for non-blocking computations
- **Redis Integration**: Built caching layer and in-memory data structures for sub-100ms inference latency
- **ML Pipeline**: Integrated anomaly detection models with real-time feature extraction
- **Scalability**: Designed architecture supporting concurrent connections and horizontal scaling
- **Production-Ready**: Implemented error handling, graceful degradation, and connection management

🔗 [GitHub: Real-Time Anomaly Detection](https://github.com/nishithaNsingh/realtime-anomaly-detection)

---

### 🟢 **MiningBot** — LLM-Powered Backend API
**Domain-Specific API | Inference Pipeline | FastAPI Architecture**

Developed a production backend for AI-assisted domain-specific queries:
- **REST API Design**: Built scalable FastAPI routes for structured AI inference workflows
- **LLM Integration**: Integrated DeepSeek and compatible API endpoints with error handling and retry logic
- **Request Pipeline**: Designed validation, preprocessing, and response formatting for consistent API contracts
- **Performance**: Optimized for latency with async request handling and efficient resource utilization
- **API Documentation**: Implemented OpenAPI/Swagger for developer-friendly API exploration

🔗 [GitHub: MiningBot](https://github.com/nishithaNsingh/mine_bot_new)

---

### ⚪ **Scalable Real-Time Chat Backend** — WebSocket Infrastructure
**Real-Time Messaging | Session Management | Data Persistence**

Architected a production chat backend with real-time capabilities and fault tolerance:
- **WebSocket Architecture**: Built bi-directional WebSocket connections for real-time message delivery
- **Redis Pub/Sub**: Implemented distributed messaging layer for horizontal scaling and multi-instance communication
- **Offline Queueing**: Designed message persistence for users offline, with retry mechanisms on reconnection
- **Database Layer**: Built PostgreSQL schema for message history, user sessions, and state management
- **Authentication**: Implemented JWT-based auth with token refresh and session lifecycle management
- **Scalability**: Designed stateless API server pattern for easy horizontal scaling
- **Resilience**: Built graceful connection handling, automatic reconnection, and data consistency guarantees

🔗 [GitHub: Chat App Backend](https://github.com/nishithaNsingh/chat-app)

---

## 🛠️ Backend Technology Stack

**Frameworks & APIs**
- FastAPI, REST APIs, WebSocket, gRPC patterns

**Async & Concurrency**
- Python async/await, asyncio, concurrent task processing

**Data & Storage**
- PostgreSQL (relational), MongoDB (document), MySQL (legacy)
- Vector Databases: Qdrant, FAISS
- Redis (caching, pub/sub, session store)

**AI/ML Backend**
- LangChain, RAG pipelines, LLM integrations
- Embeddings, reranking (Cohere), semantic search
- RAGAS evaluation frameworks, agentic workflows

**Infrastructure & DevOps**
- Docker containerization
- Cloud Platforms: AWS, GCP, Firebase, Render
- Database migration and optimization
- API monitoring and logging

**Languages**
- Python (primary), SQL, Shell scripting

---

## 💪 Core Backend Strengths

✅ Building fault-tolerant, production-grade APIs  
✅ Designing scalable database schemas and query optimization  
✅ Implementing async/concurrent request handling  
✅ Real-time systems (WebSockets, message queues, streaming)  
✅ API design, versioning, and documentation  
✅ Integration with AI/LLM systems and evaluation pipelines  
✅ Cloud deployment, containerization, and infrastructure  
✅ Building observable, maintainable codebases with testing  

---

## 📫 Get In Touch

📧 **Email**: nishithasingh777@gmail.com  
💼 **LinkedIn**: https://www.linkedin.com/in/nishitha-singh-n-a68b71256/  
🐙 **GitHub**: https://github.com/nishithaNsingh

---

*Building robust backend infrastructure that enables AI at scale* ✨
