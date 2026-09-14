# Senior Systems & Applied AI Engineer

Software Engineer with **7+ years of commercial experience** designing deterministic, high-throughput systems and modern web architectures. Focused on the intersection of **low-level systems engineering (Rust / WASM)**, **Applied AI infrastructure (FastAPI, Qdrant, Local LLMs)**, and **mission-critical data pipelines**.

Anti-hype, anti-vibe-coding. Built on ACID compliance, zero-trust security, and mechanical sympathy.

---

## 🛠️ Core Engineering Stack

* **Systems & Core Logic:** Rust, WebAssembly (WASM), C++, Memory & Concurrency Optimization
* **Applied AI & Data Architecture:** Python (FastAPI, SQLModel), Vector DBs (Qdrant), RAG Pipelines, Text-to-SQL Engines, PostgreSQL, DuckDB
* **Frontend & Visual Computing:** TypeScript, React, Next.js (App Router), Canvas API, High-Density Dashboards
* **Infrastructure & Security:** Docker, Linux, On-Premise/Air-Gapped Deployment, AST Validation, ABAC/RBAC

---

## 🛰️ Selected Architectures & Production Systems

### 🛡️ Enterprise Zero-Trust RAG Gateway
A production-grade, deterministic RAG system engineered for strict corporate compliance and zero data leakage.
* **Granular Security (ABAC):** Enforces deterministic payload filtering at the storage engine level (Qdrant) before context ever reaches the LLM context window.
* **High-Throughput Backend:** Asynchronous FastAPI + SQLModel engine maintaining strict relational integrity in PostgreSQL while serving sub-50ms vector queries.
* **Deterministic Ingestion:** AST-aware chunking pipelines eliminating context fragmentation and token bloat.
* *Stack:* `Python` `FastAPI` `Qdrant` `PostgreSQL` `Docker` `Next.js`

### 📊 Deterministic Text-to-SQL Gateway
An enterprise analytical pipeline enabling non-technical operators to query production databases in natural language without structural or security compromises.
* **AST Validation & Sandboxing:** Validates and parses generated SQL through strict AST filters prior to execution, completely mitigating destructive queries and multi-tenant leaks.
* **Read-Only Infrastructure:** Connection pooling optimized for read-only replicas with hard query timeouts and deterministic schema caching.
* *Stack:* `Python` `PostgreSQL` `SQLGlot` `AST Parsing` `TypeScript`

### ⚙️ High-Performance Physics & Telemetry Engine (`option-engine`)
A lightweight, high-frequency simulation core engineered in Rust to generate, process, and visualize real-time vector telemetry.
* **Zero-Cost Abstractions:** Custom physics pipeline built without bloated simulation frameworks, compiling to native binaries and WebAssembly.
* **Predictive Pipeline:** Real-time data serialization pipe connecting low-level Rust telemetry directly to predictive machine learning models and high-frame-rate Canvas interfaces.
* *Stack:* `Rust` `WASM` `Python` `TypeScript` `Canvas API`

---

## 🏛️ Engineering Principles

> "Make it deterministic first, then optimize the hot path."

* **Reliability Over Hype:** LLMs are probabilistic engines; systems around them must be deterministic.
* **Engine-Level Security:** Access control belongs at the database and memory layer, not inside a conversational prompt.
* **End-to-End Ownership:** From bare-metal resource limits and database transactions up to sub-frame UI rendering.

---

### 🌐 Industrial Studio & Advisory
Founder of **StelCode** — a boutique software studio engineering private, air-gapped AI solutions and high-performance system integrations for enterprise operations.
