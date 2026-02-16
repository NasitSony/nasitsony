# Hi, I'm Nasit Sony 👋

💡 AI Infrastructure Engineer | Distributed Systems | Consensus Protocols (BFT)  
📍 Building production-grade backend systems for AI and fault-tolerant distributed computing

---

## 🧠 About Me

I design and build **reliable backend systems** where AI meets distributed systems.

My work focuses on:
- Scaling AI pipelines beyond the "happy path"
- Building fault-tolerant, event-driven systems
- Designing and analyzing consensus protocols (Byzantine Fault Tolerance)

---

## 🔥 Featured Projects

### 🚧 SmartSearch — AI-Powered Semantic Search & RAG Backend
Production-oriented AI system built like real backend infrastructure.

**Key Features:**
- Asynchronous document ingestion (Kafka → Workers → DB)
- Embedding-based semantic search (pgvector + OpenAI embeddings)
- Retrieval-Augmented Generation (RAG) pipeline
- Explicit lifecycle tracking (PENDING → PROCESSING → READY/FAILED)

**Reliability Engineering:**
- Idempotent processing (no duplicate chunks)
- Retry + DLQ handling
- Worker crash recovery (offset-safe processing)
- Eventual consistency guarantees

👉 _Focus: Treating AI systems as distributed systems, not simple APIs_

### 🌐 Cloud-Native API Gateway

### 🏗️ Backend Infrastructure & System Design

Designed backend systems as infrastructure components, focusing on security, reliability, and scalability.

- 🌐 Cloud-Native API Gateway  
  - Centralized authentication (JWT) and request handling  
  - Acts as a control layer for backend services  

- ⚙️ Event-Driven Architecture  
  - Kafka-based asynchronous ingestion pipeline (SmartSearch)  
  - Decoupled services with retry and failure handling  

- 🛠️ Reliability Engineering  
  - Idempotency and duplicate-safe processing  
  - Retry, DLQ, and failure recovery strategies  
  - Observability of system behavior under faults  


---

## 🚧 Upcoming Work

### ⚙️ LSM-based KV Store (C++)

Building a single-node storage engine inspired by LSM-tree designs (similar to RocksDB), focusing on durability, write optimization, and compaction.

**Scope:**
- Write-Ahead Log (WAL) for crash recovery
- Memtable + SSTable (LSM-tree architecture)
- Compaction (size-tiered strategy)
- Benchmarks with latency histograms (p50/p95/p99)

**Engineering Focus:**
- Crash safety and recovery guarantees
- Write vs read amplification trade-offs
- Storage efficiency and performance

👉 _Foundation layer for a replicated distributed KV store_

---

### ⚙️ Consensus Protocol Implementation (Rust)

Building a fault-tolerant consensus system inspired by Raft and modern BFT protocols (HotStuff-style ideas), focusing on correctness and failure handling.

**Scope:**
- Leader election and log replication
- Fault recovery under node crashes and network partitions
- Message-driven simulation of distributed nodes
- State machine application and consistency guarantees

**Engineering Focus:**
- Handling partial failures and asynchronous communication
- Ensuring safety and liveness properties
- Performance vs correctness trade-offs

👉 _Extending storage systems into fully replicated distributed systems_


---

## 🧰 Tech Stack

**Languages:**  
Java, Rust (learning), Python

**Backend & Infra:**  
Spring Boot, Kafka, PostgreSQL, pgvector

**AI Stack:**  
Embeddings, RAG pipelines, OpenAI APIs

**Distributed Systems:**  
Event-driven systems, fault tolerance, idempotency, retries

---

## ✍️ Writing

I write about building production-grade AI systems and distributed systems:

- Medium: https://medium.com/@nasitsony96

Recent topics:
- Failure handling in async AI pipelines
- Idempotency and retries in event-driven systems
- Designing RAG systems beyond the "happy path"

---

## 📚 Research

- Google Scholar: https://scholar.google.com/citations?user=mBIQ1-0AAAAJ&hl=en

Selected Work:
- Prioritized-MVBA: Optimal Asynchronous Byzantine Agreement Protocol  
  
---

## 🎯 What I’m Focused On

- Making AI systems **production-ready and reliable**
- Building **fault-tolerant distributed systems**
- Advancing toward **consensus protocol engineering**

---

## 📬 Let’s Connect

- LinkedIn: www.linkedin.com/in/nasitsony
- Open to roles in:
  - AI Infrastructure
  - Backend / Platform Engineering
  - Distributed Systems

---

⭐ *I believe AI systems should be engineered like distributed systems — with correctness, reliability, and failure handling as first-class concerns.*
