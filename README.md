# Hi, I'm Nasit Sony 👋

**Distributed Systems & AI Infrastructure Engineer**

I build correctness-first systems — from storage engines and consensus protocols to fault-tolerant pipelines and orchestration platforms.

I focus on what happens when systems fail:
- crashes
- retries
- duplicate processing
- network delays and reordering
- adversarial behavior (BFT)

---

## 🧠 About Me

I design and implement distributed systems where correctness is a requirement — not a best-effort.

My work spans:

- **Storage systems** (WAL, crash recovery, replication)
- **Consensus protocols** (Raft, asynchronous BFT)
- **Fault-tolerant pipelines** (Kafka, idempotency, retries)
- **Orchestration systems** (workflow + job scheduling)
- **AI infrastructure** (RAG pipelines, inference routing)

I treat AI systems as **distributed systems problems**, not just APIs.

---

## ⚡ Experience Snapshot

### 💰 Production Systems (Fintech)
- Built international money transfer systems handling **$600M+ annual volume**
- Focus: correctness, consistency, and reliability under real-world constraints

### 🔬 Distributed Systems & BFT Research
- Published work in Springer journals and international conferences
- Designed and implemented asynchronous Byzantine fault-tolerant protocols
- Focus: bridging theoretical guarantees with real system behavior

---

## 🚀 What I Build

### 🧱 Storage Layer — VeriStore
Crash-consistent KV engine with WAL durability, snapshotting, and Raft-based replication.

Handles:
- process crashes (kill -9)
- partial/torn writes
- deterministic recovery via WAL replay
- leader failover and log consistency

---

### 🧠 Consensus Layer — Async-BFT Framework
Asynchronous Byzantine fault-tolerant consensus framework (MVBA, ABBA).

Simulates:
- adversarial nodes
- message delays and reordering
- quorum-based agreement under failure

---

### ⚙️ Orchestration Layer — Veriflow
Kubernetes-based job orchestration control plane.

Implements:
- idempotent job submission
- concurrency-safe scheduling (SKIP LOCKED)
- reconciliation-driven execution recovery
- append-only event timeline for auditability

---

### 🔄 Data Pipeline — SmartSearch
Fault-aware async ingestion + semantic retrieval backend.

Handles:
- worker crashes mid-processing
- Kafka replay / duplicate delivery
- idempotent ingestion and deterministic recovery

---

### 🔁 Workflow Orchestration — AgentFlow
Failure-aware workflow execution engine with explicit state transitions.

Features:
- step-level execution and retry
- timeout handling and recovery
- deterministic state reconstruction

---

## 💥 Engineering Philosophy

I design systems for failure, not just success.

I ask:
- What if a worker crashes mid-processing?
- What if a write is partially persisted?
- What if messages are replayed?
- What if nodes behave maliciously?

I build systems that:
- recover deterministically
- enforce explicit state transitions
- prevent duplication and corruption
- remain correct under failure

---

## 🧰 Tech Stack

**Languages:**  
Java, C++, Go, Python

**Backend & Infra:**  
Spring Boot, Kafka, PostgreSQL, Kubernetes, Docker

**Distributed Systems:**  
WAL, replication, consensus (Raft, BFT), idempotency, retries

**AI Infrastructure:**  
Embeddings, RAG pipelines, vector search (pgvector)

---

## 📚 Research

**Prioritized-MVBA — Asynchronous Byzantine Agreement Protocol**  
Published in Springer journals & international conferences  

🔗 https://scholar.google.com/citations?user=mBIQ1-0AAAAJ&hl=en

---

## 🎯 Current Focus

- Distributed systems & storage engines  
- Fault-tolerant AI infrastructure  
- Consensus protocol engineering  

---

## 📬 Connect

🔗 LinkedIn: https://www.linkedin.com/in/nasitsony
