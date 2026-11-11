<h1 align="center">Hi there 👋, I'm Aayush Rajput</h1>
<h3 align="center">🚀 AI Backend & High-Throughput Distributed Systems Engineer</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=aayushrajputz&style=flat-square&color=00ADD8" alt="Profile Views"/>
  <img src="https://img.shields.io/badge/Focus-High--Throughput%20Distributed%20Systems-blue?style=flat-square&logo=go" alt="Focus"/>
  <img src="https://img.shields.io/badge/Specialization-Production%20Agentic%20AI-orange?style=flat-square&logo=python" alt="Specialization"/>
  <img src="https://img.shields.io/badge/Open%20Source-NPM%20Package%20Author-success?style=flat-square&logo=npm" alt="NPM"/>
</p>

---

### 💻 About Me

I design and build **high-concurrency distributed backends, streaming event pipelines, and production agentic AI architectures**. My core engineering focus lies in mechanical sympathy, low-latency execution engines, sub-millisecond database/caching optimizations, and deterministic AI guardrails.

- 🔭 **Current Focus:** Engineering **FinFlow** (in-memory Go orderbook matching engine) and multi-agent state machines with PostgreSQL checkpointing.
- ⚡ **Engineering DNA:** Go (Goroutines/Channels), Python (FastAPI Async), TypeScript, Apache Kafka, Redis (Lua/Redlock), pgvector (HNSW), Docker, and LangGraph.
- 🎯 **Engineering Principle:** *"Atomicity isn't free concurrency — keep transactional boundaries minimal and verify deterministic contracts statically."*

---

### 🛠️ Core Engineering Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-CC292B?style=flat&logo=postgresql&logoColor=white) |
| **Backend & Concurrency** | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white) ![Goroutines](https://img.shields.io/badge/Go-Goroutines%20%26%20Channels-00ADD8?style=flat&logo=go&logoColor=white) |
| **Distributed Systems & Streaming** | ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-Lua%20%7C%20PubSub%20%7C%20Redlock-DC382D?style=flat&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) |
| **AI, RAG & Vector Search** | ![LangGraph](https://img.shields.io/badge/LangGraph-Multi--Agent%20StateGraph-FF6F00?style=flat) ![pgvector](https://img.shields.io/badge/pgvector-HNSW%20Indexing-4169E1?style=flat&logo=postgresql&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-Hybrid%20Search%20(RRF)-blueviolet?style=flat) ![MCP](https://img.shields.io/badge/Protocol-Model%20Context%20Protocol%20(MCP)-blue?style=flat) |
| **Databases & Cloud** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-AsyncSQLAlchemy-4169E1?style=flat&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) ![Cloudflare R2](https://img.shields.io/badge/Cloudflare-R2%20Storage-F38020?style=flat&logo=cloudflare&logoColor=white) |

---

### 🚀 Flagship Engineering Projects

#### 1. [FinFlow: Distributed Real-Time Trade Ledger & Autonomous AI Co-Pilot](https://github.com/aayushrajputz/Fintech-Real-Time-Trade-Ledger-Wallet-Engine)
* **High-Throughput Concurrency:** Stress-tested via K6 load generator reaching **2,802 Peak RPS (34.39ms avg latency)** with a **0% error rate over 221K+ requests**.
* **Order Engine:** Engineered in-memory Go FIFO orderbook matching engine utilizing Goroutines and channels, processing streaming Kafka trade topics.
* **Invariant Safety:** Atomic balance reservation using Redis Lua scripts & Redlock to eliminate financial race conditions and double-spending.
* **Agentic Workflows:** LangGraph State Machine with PostgreSQL Checkpointing (`PostgresSaver`) for multi-turn session persistence and time-travel trajectory auditing.

#### 2. [AStra CLI: AST-Level Route Impact & Breaking Change Analyzer](https://github.com/aayushrajputz/AStra-AI)
* **Published NPM Package:** Global CLI tool run via `npx astra check --gate`.
* **Sub-200ms Performance:** Scans and resolves static route impact graphs across **3,000+ files in under 164ms** written natively in Go.
* **CI/CD Quality Gate:** Deterministic AST traversal enforcing non-zero exit codes to block breaking API changes (`requiredScope` / caller incompatibilities) before PR merge.

#### 3. [AI Doubt Engine & Course Assistant Microservice](https://github.com/aayushrajputz/AI-Doubt-Engine-Course-Assistant-Microservice)
* **4-Tier Hierarchical Caching:** Redis Exact Match (~2ms) ➔ PostgreSQL English FTS Lexical (~15ms) ➔ pgvector HNSW Cosine Distance (≥85%) ➔ Groq LPU Fallback, reducing repetitive LLM inference costs by up to 95%.
* **Real-Time Streaming:** Sub-200ms Time-To-First-Token (TTFT) via Server-Sent Events (SSE) `StreamingResponse` with client auto-disconnect token cancellation.
* **Video Context-Aware:** 2k-token sliding-window transcript slicing mapped dynamically to user video playback timestamps.

#### 4. [BinaryPDF: High-Concurrency Document SaaS Platform](https://github.com/aayushrajputz/BinaryPDF)
* High-concurrency Golang REST microservices and worker pipelines handling asynchronous document processing, Razorpay webhooks deduplication, and Cloudflare R2 storage.

---

### 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aayushrajputz&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Aayush's GitHub Stats" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aayushrajputz&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="48%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aayushrajputz&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages"/>
</p>

---

### 📫 Connect With Me

- **Email:** [aayushpratapsingh001@gmail.com](mailto:aayushpratapsingh001@gmail.com)
- **LinkedIn:** [Aayush Rajput](https://www.linkedin.com/in/aayush-rajput-38142827b/)
- **LeetCode:** [aayush_rajput](https://leetcode.com/u/aayush_rajput/)
- **Codolio:** [Aayushrajput](https://codolio.com/profile/Aayushrajput)
