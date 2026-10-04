
<div align="center">

# Prateek Bala

**Backend Engineer · Distributed Systems · AI Infrastructure**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-prateekbala-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/prateekbala)
[![Twitter](https://img.shields.io/badge/Twitter-@prateek__bala28-1DA1F2?style=flat-square&logo=x)](https://twitter.com/prateek_bala28)
[![Email](https://img.shields.io/badge/Email-prateekbala28%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:prateekbala28@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Prateekbala-181717?style=flat-square&logo=github)](https://github.com/Prateekbala)

</div>

I'm a final year CSE undergraduate at LNMIIT  and a Founding Engineer at Flexzistay, where I build and scale backend systems in production.

I enjoy working on systems where the engineering gets interesting under the hood: distributed coordination, concurrency, networking, storage, low-latency execution, and performance.

Lately, I've been exploring AI infrastructure, LLM inference, autonomous coding agents, and cloud-native systems. I also contribute to open-source projects in the Kubernetes ecosystem.

I learn best by building things from scratch, measuring how they perform, and understanding why they work.

---

## What I'm working on

- **Backend engineering:** Scalable APIs, PostgreSQL, Redis, concurrency-safe workflows, and event-driven architectures.
- **Distributed systems:** Message brokers, consensus, replication, fault tolerance, and high-throughput processing.
- **AI infrastructure:** LLM inference routing, observability, agent orchestration, and production AI systems.
- **Cloud-native engineering:** Kubernetes, KServe, Kubeflow, Docker, CI/CD, and production deployments.
- **Systems programming:** Go, modern C++, networking, asynchronous I/O, and performance optimization.

## Projects

### 1. Codewatch — Autonomous GitHub PR Review Agent

[**Repository**](https://github.com/Prateekbala/Codewatch)

**TypeScript · LangGraph · Node.js · Hono · OpenAI API · GitHub Apps · Docker**

An LLM-powered code review agent designed to identify actionable issues in pull requests.

- Built a modular review engine supporting CLI execution and GitHub App webhooks.
- Implemented multi-stage review workflows, parallel diff analysis, and line-level source grounding.
- Added severity-based filtering, confidence scoring, and a secondary verification pass to reduce false positives.
- Built repository-specific review policies, token budgets, cost controls, and an evaluation framework measuring precision, recall, and F1.

### 2. RiftMQ — Distributed Messaging System

[**Repository**](https://github.com/Prateekbala/Distributed-system)

**Go · Raft · WAL · Docker · Distributed Systems**

A Kafka-inspired distributed message broker built from scratch.

- Achieved approximately 18K messages/sec with 200 concurrent producers.
- Implemented Raft consensus, leader election, and message replication.
- Built persistent message storage using a write-ahead log (WAL).
- Implemented consumer groups, offset tracking, partition assignment, and recovery mechanisms.

### 3. FIX Protocol Trading Gateway

[**Repository**](https://github.com/Prateekbala/Fix-Protocol-Tranding-Engine)

**C++20 · FIX 4.4 · Lock-Free Queues · Async I/O**

A low-latency trading gateway implementing order-management and execution workflows.

- Built a FIX 4.4 gateway with asynchronous networking and lock-free queues.
- Optimized the order-processing pipeline for high-throughput execution.
- Benchmarked performance at 250K orders/sec, with reported P50 latency of 350µs and P99 latency of 633µs.

### 4. Distributed LLM Inference Router

[**Repository**](https://github.com/Prateekbala/Distributed-LLM-Router)

**Python · FastAPI · vLLM · Docker · Prometheus · Grafana**

An OpenAI-compatible gateway that routes inference requests across multiple vLLM workers.

- Implemented round-robin, least-loaded, latency-aware, and inference-aware routing.
- Built health checks, automatic retries, failover, and backpressure controls.
- Added per-node TTFT, token-throughput, active-request, error-rate, and queue-depth metrics.
- Created a reproducible benchmark harness to compare latency and throughput across routing strategies.

### 5. Flexzistay — Hotel Marketplace

[**Live Link**](https://www.flexzistay.in/)

**Node.js · TypeScript · PostgreSQL · Prisma · Redis · GCP · Pub/Sub**

Production backend engineering for a hotel marketplace, built from the ground up.

- Designed and shipped 100+ REST APIs covering search, availability, inventory, reservations, pricing, payments, and wallets.
- Integrated HyperGuest for hotel catalog synchronization, availability, booking, cancellation, and webhook reconciliation across 10K+ hotels.
- Built concurrency-safe booking workflows using transactions, row-level locking, idempotency, and atomic inventory updates.
- Reduced API P95 latency by 50% to under 150ms through query optimization, indexing, connection pooling, and caching.
- Deployed and scaled production services on Google Cloud Run, serving 10K+ users.

### 6. Voice AI Backend

**Python/Backend Systems · SIP · Streaming Audio · STT · LLM · TTS · MCP**

- Optimized a real-time voice pipeline, reducing perceived latency from 1.4 seconds to 900ms.
- Built provider-agnostic telephony workflows with SIP integration, call orchestration, and provider failover.
- Integrated Model Context Protocol (MCP) tools so voice agents could discover and execute external API operations.

---

## Open Source

### KServe / Kubeflow — CNCF Ecosystem

Contributing to Kubernetes-native model serving and cloud-native AI infrastructure.

- [PR #142 — Namespace-scoped resource filtering](https://github.com/kserve/models-web-app/pull/142)  
  Implemented namespace-aware resource filtering using environment variables, backend API changes, and Kubernetes RBAC to support multi-tenant deployments.

- [PR #161 — InferenceGraph support](https://github.com/kserve/models-web-app/pull/161)  
  Added InferenceGraph custom-resource support, including schema integration, backend APIs, and UI resource lifecycle management for multi-model inference pipelines.

I enjoy contributing to projects where improvements in APIs, resource management, and infrastructure make the developer experience better for everyone.

---

## Tech Stack

**Languages:** Go, TypeScript, JavaScript, Python, C/C++, SQL

**Backend:** Node.js, Express.js, FastAPI, Hono, REST APIs, Microservices, Event-Driven Architecture

**Databases & Messaging:** PostgreSQL, MySQL, MongoDB, Redis, Kafka, Google Cloud Pub/Sub

**Distributed Systems:** Raft Consensus, Leader Election, Replication, WAL, Partitioning, Fault Tolerance, Concurrency

**AI Infrastructure:** vLLM, OpenAI-Compatible APIs, LLM Inference Routing, LangGraph, MCP, Prometheus, Grafana

**Cloud & DevOps:** Kubernetes, Docker, GCP, AWS, GitHub Actions, CI/CD

---

## A few more things

- **Competitive programming:** LeetCode Knight, contest rating 1856, ranked in the top 6.13% globally.
- **Problem solving:** 500+ coding problems solved across platforms.
- **Education:** B.Tech in Computer Science and Engineering, LNMIIT.

I'm always interested in backend engineering, distributed systems, AI infrastructure, and meaningful open-source work.

Feel free to reach out if you're building something interesting in these areas.

---

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prateekbala&layout=compact&hide_border=true&theme=default" />
<img height="150" src="https://github-readme-streak-stats.herokuapp.com/?user=prateekbala&hide_border=true" />

</div>
