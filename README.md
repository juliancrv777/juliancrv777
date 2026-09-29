# Hi, I'm Julian Carvalho

**Software Engineer · Full-Stack TypeScript · React · Next.js · Angular · Node.js/NestJS**

I build production-oriented web applications, APIs and distributed workflows with a focus on **reliability, data consistency, concurrency, security and automated testing**.

I'm currently open to **Software Engineer** and **Frontend Engineer** opportunities.

## Core stack

**Frontend:** TypeScript, React, Next.js, Angular, RxJS, HTML5, CSS3  
**Backend:** Node.js, NestJS, REST APIs, WebSockets, Socket.IO, JWT, RBAC  
**Data & infrastructure:** PostgreSQL, Prisma, Redis, BullMQ, Docker, GitHub Actions, Neon, Upstash, Railway, Render, Vercel  
**Testing:** Jest, Vitest, Playwright, integration and E2E testing

## Featured projects

### [LedgerX — production-minded payment systems engineering](https://github.com/juliancrv777/ledgerx)

[![LedgerX CI](https://github.com/juliancrv777/ledgerx/actions/workflows/ci.yml/badge.svg)](https://github.com/juliancrv777/ledgerx/actions/workflows/ci.yml)

A simulated payment platform built around financial correctness, concurrency and event-driven delivery.

- Double-entry ledger with PostgreSQL **SERIALIZABLE** transactions and idempotent transfers.
- Transactional outbox, Redis/BullMQ processing, signed HMAC webhooks, retries and DLQ.
- Rotating refresh sessions, SSRF defenses, rate limiting, structured logs and Prometheus metrics.
- Financial E2E stress test fires **100 concurrent transfer attempts**, validating 50 successful postings, 50 insufficient-funds rejections and a final balance of zero.
- **Stack:** TypeScript, Next.js, React, NestJS, PostgreSQL, Prisma, Redis, BullMQ, Jest, Docker and GitHub Actions.

[Live demo](https://ledgerx-seven.vercel.app) · [Repository](https://github.com/juliancrv777/ledgerx)

---

### [PulseChat — real-time collaboration platform](https://github.com/juliancrv777/pulsechat)

[![PulseChat CI](https://github.com/juliancrv777/pulsechat/actions/workflows/ci.yml/badge.svg)](https://github.com/juliancrv777/pulsechat/actions/workflows/ci.yml)

A deployed multi-user collaboration app with persistent messaging and distributed realtime delivery.

- JWT authentication, workspaces/roles, channels, persistent history, presence and typing indicators.
- Socket.IO with Redis adapter for multi-instance realtime fan-out.
- PostgreSQL/Prisma persistence with Neon as the production database.
- Automated testing and CI around authenticated multi-user flows.
- **Stack:** Next.js, React, TypeScript, NestJS, PostgreSQL, Prisma, Redis, Socket.IO, Docker and GitHub Actions.

[Live demo](https://web-production-b634e.up.railway.app) · [Repository](https://github.com/juliancrv777/pulsechat)

---

### [OpsBoard — full-stack operations platform](https://github.com/juliancrv777/opsboard)

A production-oriented workspace for projects, tasks, ownership and team visibility.

- Angular architecture with Signals/RxJS and a NestJS REST API.
- PostgreSQL/Prisma persistence with JWT, RBAC and server-side authorization.
- Dockerized web/API delivery, Nginx and GitHub Actions validation.
- **Stack:** Angular, TypeScript, NestJS, PostgreSQL, Prisma, JWT/RBAC, Docker and GitHub Actions.

[Live demo](https://web-production-29b16.up.railway.app) · [Repository](https://github.com/juliancrv777/opsboard)

---

### [ReserveFlow — concurrency-safe reservation API](https://github.com/juliancrv777/reserveflow)

A backend for limited-capacity bookings designed to prevent overselling and duplicate reservations under concurrent requests and retries.

- Transactional reservation rules, idempotency, API keys, ownership and audit records.
- Concurrency tests use independent database connections to exercise real contention.
- OpenAPI documentation, Docker setup and GitHub Actions CI.
- **Stack:** Node.js, REST, SQLite, OpenAPI, Docker and GitHub Actions.

[Repository](https://github.com/juliancrv777/reserveflow)

## Engineering focus

- Reliable full-stack TypeScript systems and clean API boundaries.
- React, Next.js and Angular interfaces with explicit loading, error and empty states.
- SQL transactions, concurrency control, idempotency and safe retries.
- Realtime systems with WebSockets/Socket.IO and Redis.
- Authentication, authorization and practical application security.
- Automated unit, integration and E2E testing.
- Dockerized deployment and CI/CD with GitHub Actions.

---

**Português:** Engenheiro de software com foco em aplicações web Full Stack, APIs, concorrência, confiabilidade e testes automatizados. Busco oportunidades como Software Engineer ou Frontend Engineer.
