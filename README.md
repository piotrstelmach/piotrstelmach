# Senior Systems & Web Architect

Software Engineer with **7+ years of commercial experience** architecting high-throughput, deterministic systems. Specialized in bridging **low-level numeric cores (Rust / WebAssembly)** with **enterprise application layers (TypeScript, NestJS, DDD)** and **AI-assisted operational intelligence**.

Uncompromising focus on deterministic execution, sub-millisecond latencies, transactional data boundaries, and mechanical sympathy.

---

## 🛠️ Technical Competence & Architecture

* **High-Performance Numeric Cores:** Rust, WebAssembly (`wasm-pack`), Low-Level Optimization, SIMD/Monte Carlo Simulations
* **Enterprise Application Architecture:** TypeScript, NestJS (Modular Monolith, DDD, Transactional Outbox, OCC), Node.js, Python
* **Data Persistence & Concurrency:** PostgreSQL, Prisma (`schema-per-module`), Isolation Levels, ACID, Optimistic Concurrency Control
* **Frontend & High-Density UI:** React, TypeScript, Vite, Real-Time Market Visualizations, Sub-frame Latency Optimization
* **Applied AI & Systems:** Deterministic Narrative Engines, Local LLM Integration (Ollama), Structured Ingestion, Qdrant

---

## 🏛️ Featured Engineering Systems

### ⚡ Options Risk & Analytics Engine (`option-engine`)
A high-performance quantitative simulation and options risk engine engineered as a modular monolith. Integrates an ultra-fast Rust/WASM numeric core directly into a DDD application layer.

* **High-Frequency WASM Core:** Custom Rust numerical engine implementing analytic Black-Scholes, Greeks calculation, and Geometric Brownian Motion (GBM) Monte Carlo paths (~59M paths/sec).
* **Enterprise DDD Architecture:** NestJS modular monolith enforcing strict boundary rules via ports, transactional outbox relays (`FOR UPDATE SKIP LOCKED`), and schema-per-module isolation in PostgreSQL.
* **Deterministic Concurrency & Integrity:** Mutation pipelines guarded by Optimistic Concurrency Control (OCC) rejecting 100% of stale writes under high contention.
* **Full-Spectrum Risk Profiling:** Real-time multi-asset Monte Carlo revaluation generating VaR (95/99), Expected Shortfall (ES), and peak-to-trough drawdown distributions (~30M revaluations/sec).
* **Deterministic-First AI Insights:** Narrative risk synthesis defaulting to sub-millisecond deterministic templates with an automated fallback pipeline for local LLMs (Ollama) guarded by request-hash caching.
* *Stack:* `Rust` `WebAssembly` `NestJS` `TypeScript` `PostgreSQL` `Prisma` `React` `Docker`

---

### 🛡️ Enterprise Zero-Trust RAG Gateway (`company-wiki-ai`)
A production-grade, deterministic RAG system engineered for enterprise authorization boundaries and zero data leakage.

* **Attribute-Based Access Control (ABAC):** Enforces deterministic payload filtering at the storage engine level (Qdrant) before vector context ever reaches the LLM context window.
* **Asynchronous High-Throughput Core:** FastAPI + SQLModel engine maintaining referential integrity across relational entities (PostgreSQL) while serving sub-50ms vector queries.
* **Zero-Hallucination Ingestion:** Paragraph-aware chunking pipeline eliminating fragmentation and the "Lost in the Middle" latency penalty.
* *Stack:* `Python` `FastAPI` `Qdrant` `PostgreSQL` `SQLModel` `Docker` `Next.js`

---

## 📐 Engineering Philosophy

> "Make it deterministic first, optimize the hot path, enforce safety at the storage layer."

* **Determinism Over Probabilism:** Probabilistic engines (LLMs) belong inside strict, sandboxed boundaries. The core business and risk layers must remain mathematically provable.
* **Mechanical Sympathy:** Real performance comes from memory layout, cache efficiency, and zero-cost abstractions—not brute-force cloud resources.
* **Architectural Boundaries:** Microservices add network latency; disciplined modular monoliths with strict DDD ports give you the same isolation with zero RPC overhead.

---

### 🌐 Advisory & Engineering Studio
Founder of **StelCode** — Engineering studio delivering custom, high-performance software systems, numeric analytics engines, and air-gapped AI integrations for enterprise operations.
