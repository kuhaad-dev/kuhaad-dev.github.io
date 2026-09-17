# Engineering Portfolio — Mayank Kuhaad

> **Live Website:** [https://kuhaad-dev.github.io](https://kuhaad-dev.github.io)  
> **GitHub Profile:** [@kuhaad-dev](https://github.com/kuhaad-dev)  
> **LinkedIn:** [Mayank Kuhaad](https://linkedin.com/in/mayank-kuhaad)  

Senior Backend Software Engineer with 3.5+ years of experience engineering high-concurrency event-driven architectures, transactional database locks, and cloud platforms.

---

## 🚀 Featured Production Architectures

### 1. [Workflow Orchestration Engine](https://github.com/kuhaad-dev/workflow-engine)
- **Stack:** NestJS 11, TypeORM, MySQL, Redis, BullMQ, Docker
- **Highlights:** Configurable Finite State Machine (FSM), strict state transition guards, row-level pessimistic locking (`SELECT ... FOR UPDATE`), cron-driven SLA escalation worker, high-throughput bulk ingestion pipeline.
- **Verification:** Concurrency E2E suite verifying 20 simultaneous writes serialize with 1 success and 19 conflicts.

### 2. [Event-Driven Real-Time Notification Service](https://github.com/kuhaad-dev/realtime-notifications)
- **Stack:** NestJS 11, PostgreSQL 16, Redis 7, Socket.IO with Redis Streams adapter, BullMQ
- **Highlights:** Timing-safe HMAC-SHA256 signature verification (`crypto.timingSafeEqual`), Redis atomic idempotency deduplication (`SETNX`), horizontal WebSocket broadcasting, interactive test console.

### 3. [Production NestJS Platform on GCP](https://github.com/kuhaad-dev/nestjs-platform)
- **Stack:** GKE, Terraform (IaC), Workload Identity Federation (OIDC), Docker Multi-Stage, Prometheus RED Method
- **Highlights:** Zero-trust CI/CD without static service account keys, image size reduction (800MB → 190MB), Kubernetes HPA, and real-time Rate/Errors/Duration observability dashboards.

---

## 🛠️ Tech Stack & Design
- **Frontend:** Semantic HTML5, Tailwind CSS, JetBrains Mono & Outfit typography.
- **Deployment:** GitHub Pages continuous deployment via the `main` branch.
