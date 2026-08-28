# Alhassan Alfarran

Platform-minded full-stack engineer based in Moscow. I build reliable web products, backend services, and the delivery systems around them—from transactional APIs and observability to GitOps, SLOs, and safe releases.

**Core stack:** Go, Python, TypeScript, React, Node.js, PostgreSQL, Redis, Docker, Kubernetes, Terraform, Prometheus, and GitHub Actions. Languages: Arabic, English, and Russian.

## Flagship projects

- **[Gatehouse](https://github.com/kyan9400/gatehouse)** ([live dashboard](https://gatehouse-nine.vercel.app/), [API docs](https://gatehouse-api.vercel.app/docs)) — A policy-first access operations control plane with tenant-scoped requests, role-aware approvals, idempotent writes, optimistic concurrency, a hash-linked audit trail, Prometheus metrics, a React review desk, Docker, Kubernetes, Terraform, and GHCR release automation.
- **[DeployLedger](https://github.com/kyan9400/deployledger)** ([live dashboard](https://deployledger.vercel.app/)) — A self-hosted release-operations control plane with DORA metrics, idempotent deployment ingestion, signed GitHub webhooks, a hash-linked audit trail, Prometheus health signals, a React dashboard, Docker Compose, Kubernetes, Terraform, and release automation.
- **[SLO Forge](https://github.com/kyan9400/slo-forge)** ([v1.0.0](https://github.com/kyan9400/slo-forge/releases/tag/v1.0.0)) — A Go CLI and HTTP API that compiles one SLO definition into Prometheus recording rules, multi-window burn-rate alerts, a Prometheus Operator resource, a Grafana dashboard, and a reviewable error-budget explanation. CI verifies race safety, generated drift, PromQL, the static non-root container, and high/critical vulnerabilities.
- **[Platform Blueprint](https://github.com/kyan9400/platform-blueprint)** ([v1.0.0](https://github.com/kyan9400/platform-blueprint/releases/tag/v1.0.0)) — A reproducible GitOps reference platform with Flux reconciliation, metric-gated Flagger canaries, CEL admission controls, Prometheus SLOs, kind smoke tests, and an EKS Terraform path.
- **[Stockroom Ledger](https://github.com/kyan9400/stockroom-ledger)** ([live demo](https://stockroom-ledger.vercel.app/)) — A full-stack inventory operations console with audited cycle counts, atomic location transfers, idempotent writes, optimistic concurrency, and a hardened container deployment.
- **[LeaseQueue](https://github.com/kyan9400/leasequeue)** ([live demo](https://leasequeue.vercel.app/)) — A durable background-job service with atomic leases, crash recovery, idempotent submission, bounded retries, dead-letter redrive, and Prometheus metrics.
- **[SchemaSentry](https://github.com/kyan9400/schema-sentry)** — A PostgreSQL migration safety analyzer with changed-migration pull-request scans, SARIF reporting, justified suppressions, and a reusable GitHub Action.
- **[Mini GPT Workbench](https://github.com/kyan9400/my-gpt)** ([live demo](https://kyan9400.github.io/my-gpt/)) — A readable character-level transformer with vectorized causal attention, deterministic training, safe checkpoints, controlled sampling, and an interactive transformer explorer.
- **[Pathwise](https://github.com/kyan9400/pathwise-client)** ([live app](https://pathwise-client.vercel.app/)) — An explainable university-program discovery and comparison product with a polished Next.js interface, search and filtering flows, and a public production deployment.

## Live systems

| Product | Demo | What to inspect |
| --- | --- | --- |
| [Gatehouse](https://github.com/kyan9400/gatehouse) | [Open dashboard](https://gatehouse-nine.vercel.app/) | Tenant-scoped access requests, policy decisions, approvals, and audit evidence. |
| Gatehouse API | [OpenAPI / Swagger](https://gatehouse-api.vercel.app/docs) | Live FastAPI service with health/readiness probes, OpenAPI, metrics, and auditable access workflows. |
| [DeployLedger](https://github.com/kyan9400/deployledger) | [Open dashboard](https://deployledger.vercel.app/) | Release ingestion, DORA metrics, deployment history, and health signals. |
| [Pathwise](https://github.com/kyan9400/pathwise-client) | [Open app](https://pathwise-client.vercel.app/) | Search, compare, and explain university-program choices in a polished product flow. |
| [LeaseQueue](https://github.com/kyan9400/leasequeue) | [Open console](https://leasequeue.vercel.app/) | Queue operations, retry behavior, leases, and dead-letter recovery. |
| [Stockroom Ledger](https://github.com/kyan9400/stockroom-ledger) | [Open console](https://stockroom-ledger.vercel.app/) | Inventory transfers, cycle counts, idempotency, and optimistic concurrency. |
| [Webhook Workbench](https://github.com/kyan9400/webhook-workbench) | [Open workbench](https://webhook-workbench.vercel.app/) | Signature verification, event capture, and guarded replay. |
| [Pulseboard](https://github.com/kyan9400/pulseboard) | [Open status page](https://pulseboard-five-tau.vercel.app/) | Uptime checks, incidents, SLO budgets, and operational metrics. |

## Where to start

| Hiring signal | Project | Evidence |
| --- | --- | --- |
| DevOps / platform engineering | [Platform Blueprint](https://github.com/kyan9400/platform-blueprint) | Flux GitOps, Flagger canaries, Kyverno policy, Prometheus SLOs, kind smoke tests, and Terraform for EKS. |
| Backend engineering | [DeployLedger](https://github.com/kyan9400/deployledger) | FastAPI services, signed webhooks, idempotent ingestion, DORA metrics, audit history, and production deployment paths. |
| Full-stack product engineering | [Gatehouse](https://github.com/kyan9400/gatehouse) | React review console, tenant-scoped API, optimistic concurrency, policy evaluation, audit evidence, and a live demo. |
| Reliability / SRE | [SLO Forge](https://github.com/kyan9400/slo-forge) | SLO-as-code compilation into burn-rate alerts, dashboards, Prometheus resources, and reviewable error budgets. |

## More engineering work

- **Reliability and distributed systems:** [Pulseboard](https://github.com/kyan9400/pulseboard), [Retry Lab](https://github.com/kyan9400/retry-lab), [Incident Canvas](https://github.com/kyan9400/incident-canvas), and [Webhook Workbench](https://github.com/kyan9400/webhook-workbench).
- **Policy and delivery tooling:** [Access Verdict](https://github.com/kyan9400/access-verdict), [ToggleBench](https://github.com/kyan9400/togglebench), and [OpenAPI Impact](https://github.com/kyan9400/openapi-impact).
- **Developer tools:** [Tampertrail](https://github.com/kyan9400/tampertrail), [git-hotspots](https://github.com/kyan9400/git-hotspots), [File Finder MCP](https://github.com/kyan9400/file-finder-mcp), and [RepoVitals](https://github.com/kyan9400/repo-vitals).

## Engineering focus

I care about correctness under failure, secure delivery, useful observability, deterministic automation, and documentation that lets another engineer run and evaluate a project without guesswork.

