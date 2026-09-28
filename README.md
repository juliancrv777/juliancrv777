# Hi, I'm Julian

**Software Engineer · TypeScript · Angular · React · Node.js**

I build web applications and REST APIs with a focus on clear user flows, data consistency and automated tests. I'm focused on Software Engineer and Frontend Engineer opportunities, building production-oriented web applications, APIs and reliable data workflows.

## Featured projects

### [OpsBoard — full-stack operations platform](https://github.com/juliancrv777/opsboard)

A production-oriented operations workspace for projects, tasks, ownership and team visibility, with a public live demo.

- **Implementation:** Angular feature architecture with Signals/RxJS, NestJS REST API, PostgreSQL/Prisma persistence, authentication and role-based authorization.
- **Delivery:** automated frontend/backend tests, Docker images, Nginx, GitHub Actions and a Railway deployment.
- **Validated workflow:** authenticated User → Project → Task flow with owners, assignees, roles and responsive mobile UI.
- **Stack:** Angular, TypeScript, NestJS, PostgreSQL, Prisma, JWT/RBAC, Docker and GitHub Actions.

[Live demo](https://web-production-29b16.up.railway.app) · [Architecture](https://github.com/juliancrv777/opsboard/blob/main/docs/ARCHITECTURE.md) · [Repository](https://github.com/juliancrv777/opsboard)


### [ReserveFlow — transactional reservation API](https://github.com/juliancrv777/reserveflow)

A backend for limited-capacity workshop bookings, designed to prevent overselling and duplicate reservations when requests compete or clients retry.

- **Implementation:** HTTP endpoints, reservation rules, API-key authentication, ownership checks, persistence and integration tests.
- **Key decision:** conditional inventory updates, saved idempotency responses and audit records share a SQLite transaction. Separate database connections test contention beyond one event loop.
- **Try it:** run `npm run demo` to check 20 competing requests for five seats, retries and cancellation against the running API.
- **Stack:** Node.js 24, JavaScript, SQLite, OpenAPI, Docker and GitHub Actions.

[Project case study](https://github.com/juliancrv777/reserveflow/blob/main/docs/CASE-STUDY.md) · [Architecture](https://github.com/juliancrv777/reserveflow/blob/main/docs/ARCHITECTURE.md) · [Tests](https://github.com/juliancrv777/reserveflow/tree/main/test)

### [IssueDesk — ticket management workspace](https://github.com/juliancrv777/issuedesk)

A responsive help desk that takes a request from creation to resolution, with priorities, assignment, comments, search and history.

- **Implementation:** React components and hooks, a typed API client, validated HTTP endpoints, SQL persistence and automated checks.
- **Key decision:** version checks reject stale edits; atomic database batches keep ticket changes and history together. Retry identifiers prevent duplicate creation and comments.
- **Validation:** 13 unit/domain/client tests and three HTTP integration scenarios using the compiled Worker and isolated local D1. GitHub Actions runs tests, type checks and the build.
- **Stack:** React, TypeScript, Zod, Drizzle, SQLite / Cloudflare D1 and GitHub Actions.

[Visual walkthrough](https://github.com/juliancrv777/issuedesk#see-the-workflow) · [Project case study](https://github.com/juliancrv777/issuedesk/blob/main/docs/CASE-STUDY.md) · [Architecture](https://github.com/juliancrv777/issuedesk/blob/main/docs/ARCHITECTURE.md) · [CI](https://github.com/juliancrv777/issuedesk/actions)

## Engineering focus

- Angular and React interfaces with explicit loading, error and empty states.
- Full-stack TypeScript architecture, REST APIs, input validation and SQL transactions.
- Concurrency, safe retries and failure handling.
- Reproducible tests, Git workflows and documented tradeoffs.

These are portfolio projects with documented boundaries. OpsBoard provides the public full-stack demo; ReserveFlow targets a single host; IssueDesk currently uses a shared workspace without application-level login or roles. Its screenshots and walkthrough are public; the hosted app is private.

---

**Português:** desenvolvedor com foco em aplicações web, APIs REST e testes automatizados. Busco oportunidades como Software Engineer ou Frontend Engineer. Nos projetos acima, você encontra demonstrações, código, testes e decisões de arquitetura.
