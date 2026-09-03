# Hi, I'm Tian Yang 👋

Senior Software Engineer building **correctness-critical systems** — money movement, data pipelines, and the boring infrastructure that has to be right when it's 3am and a customer is watching.

I care about the unglamorous parts: invariants enforced at the boundary, writes that are idempotent under retry, and systems you can actually reason about under failure.

---

## 🔭 What I'm working toward

Designing and shipping distributed backend systems where **data integrity is non-negotiable** — payments/ledgers, billing, and event-driven platforms. I like problems where "eventually consistent" has to be paired with "provably never wrong."

## 🌱 Currently

- Deepening **TypeScript/Node** and **Python** across the full stack.
- Writing about ledger/accounting-system design (the hard part isn't the code, it's the invariants).
- Reading about distributed-systems correctness, DB internals, and event sourcing.

## 🧰 Tech I reach for

| Area | Tools |
|---|---|
| Languages | TypeScript, Python, SQL |
| Backend | Node, Fastify, Postgres (and its triggers — my favorite lint rule) |
| Data | DuckDB, GRIB2, Postgres |
| Testing | Vitest, pytest, property/fuzz testing |
| Infra | Docker, GitHub Actions, CI/CD-as-a-citizen |

## 💼 Open to

**Senior / Staff Software Engineer** roles — backend, platform, or payments. Remote or San Francisco Bay Area. If you're building systems where correctness matters, let's talk.

---

## 📌 Pinned work

<!-- The repositories below are auto-pinned via GitHub; these are the ones to feature: -->

- **`ledger-ts`** — a double-entry ledger with database-enforced invariants: append-only log, idempotent writes, deferred constraint triggers, transactional outbox. 40 tests including a 400-op concurrency fuzz, running on embedded Postgres (PGlite) *and* real Postgres in CI.
- **`resilient-fetcher`** — concurrency resilience in pure stdlib Python: token-bucket rate limiting, backoff with jitter, a circuit breaker, and a batch-level retry budget. 27 deterministic tests (fake clock, injected transport — never touches a socket or sleeps a real second).

## 📫 How to reach me

- GitHub: [@ellen333712](https://github.com/ellen333712)
- LinkedIn: [tian-y-17397b60](https://www.linkedin.com/in/tian-y-17397b60/)
- Email: use the GitHub profile email (reply via issues on my repos works too)

> *"The log is the truth; everything else is a projection."*
