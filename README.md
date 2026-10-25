# Alhassan Alfarran

Full-stack and Python developer in Moscow, building web products and AI-backed search systems.

**Portfolio:** [alhassan-portfolio-sigma.vercel.app](https://alhassan-portfolio-sigma.vercel.app) — case studies, CV and contact (EN / RU / AR) · mirror for networks that block vercel.app: [kyan9400.github.io/alhassan_portfolio](https://kyan9400.github.io/alhassan_portfolio/)

## Now

**Python / Full-Stack Developer at Elektroservis, Moscow** (since January 2026) — search over engineering documentation: PDF, Word, Excel and scanned files, OCR, hybrid keyword + semantic retrieval (sentence-transformers + FAISS), and FastAPI ingestion and query pipelines. [Lumen Search](https://github.com/kyan9400/lumen-search) shows the same techniques on public documents.

Before that:

- **Chief Full-Stack Developer, Avenue Group** (2025) — built the OKKP operations platform from scratch: React + TypeScript, Node.js / Express, PostgreSQL and MongoDB, role-based access, audit logs, Excel exports.
- **Full-Stack Developer, Junzi Tech** (2024–2025) — cut a critical endpoint's average response time by about 60% through query refactoring and caching, with the response contract unchanged.
- **Freelance** since 2020 — web applications and sites for clients.

**Languages:** Python, TypeScript, JavaScript, SQL, Go, PHP, C, C++.
**Stack:** FastAPI, React, Next.js, Node.js / Express, PostgreSQL, MongoDB, Redis, sentence-transformers, FAISS, Docker.
**Spoken:** Arabic, English, Russian.

## Featured projects

| Project | What it is | Live |
| --- | --- | --- |
| [Lumen Search](https://github.com/kyan9400/lumen-search) | Hybrid document search with citations over PDF, Word, Excel and scanned pages in English and Russian: BM25 + multilingual embeddings in FAISS, rank fusion, cross-encoder reranking, Tesseract OCR, FastAPI, Redis. Measured on 62 labelled questions. | [demo](https://kyan9400.github.io/lumen-search/) (runs in the browser) |
| [Pulseboard](https://github.com/kyan9400/pulseboard) | A compact, self-hosted HTTP uptime monitor with incident history, SLO error-budget analysis, an operations dashboard, a public status page, and a small deployment footprint. | [demo](https://pulseboard-five-tau.vercel.app/) |
| [DeployLedger](https://github.com/kyan9400/deployledger) | A self-hosted release-operations control plane: ingests deployment events, computes DORA metrics, exposes Prometheus health signals, and gives engineers a small dashboard for deciding whether the next release is safe to ship. | [dashboard](https://deployledger.vercel.app/) |
| [Gatehouse](https://github.com/kyan9400/gatehouse) | A self-hosted access request and approval control plane: engineers request narrowly-scoped, short-lived access, approvers see the risk and policy context, and every decision is recorded in a verifiable, tenant-scoped audit chain. | [dashboard](https://gatehouse-nine.vercel.app/) · [API docs](https://gatehouse-api.vercel.app/docs) |
| [Webhook Workbench](https://github.com/kyan9400/webhook-workbench) | A private, self-hosted workbench for capturing and inspecting webhook requests — signature verification for GitHub, Stripe and generic HMAC-SHA-256, and safe replay — shipped as one dependency-free Go binary with the UI embedded. | [demo](https://webhook-workbench.vercel.app/) |

## Skills and where to see them

| Area | Skills | Public code |
| --- | --- | --- |
| Search and AI | RAG, hybrid search (BM25 + embeddings), sentence-transformers, FAISS, cross-encoder reranking, cited answers from an LLM, retrieval evaluation | [Lumen Search](https://github.com/kyan9400/lumen-search), [OpsMind](https://github.com/kyan9400/opsmind) |
| Document processing | OCR (Tesseract), PDF, Word and Excel parsing, structure-aware chunking | [Lumen Search](https://github.com/kyan9400/lumen-search) |
| Machine learning | PyTorch, NumPy, transformers and autograd from first principles | [Mini GPT Workbench](https://github.com/kyan9400/my-gpt), [micrograd-plus](https://github.com/kyan9400/micrograd-plus), [makemore-namegen](https://github.com/kyan9400/makemore-namegen) |
| Data | Pandas, Matplotlib, Hugging Face pipelines, Excel export | [oktoberfest-ai](https://github.com/kyan9400/oktoberfest-ai) |
| Python backend | FastAPI, Pydantic, async SQLAlchemy, background jobs, idempotent writes | [Lumen Search](https://github.com/kyan9400/lumen-search), [DeployLedger](https://github.com/kyan9400/deployledger), [Gatehouse](https://github.com/kyan9400/gatehouse), [LeaseQueue](https://github.com/kyan9400/leasequeue), [Stockroom Ledger](https://github.com/kyan9400/stockroom-ledger) |
| Node.js | Node.js, Express, JWT login, Prisma | [sehati-server](https://github.com/kyan9400/sehati-server), [resto-pro](https://github.com/kyan9400/resto-pro), [OpsMind](https://github.com/kyan9400/opsmind) |
| Frontend | React, TypeScript, Next.js, Tailwind CSS, Vite | [OpsMind](https://github.com/kyan9400/opsmind), [Access Verdict](https://github.com/kyan9400/access-verdict), [Incident Canvas](https://github.com/kyan9400/incident-canvas), [portfolio](https://github.com/kyan9400/alhassan_portfolio) |
| 3D on the web | Three.js, React Three Fiber, GLSL, performance budgets | [Orbit Voyages](https://github.com/kyan9400/orbit-voyages-3d) and ten more in [hassan-webdesign](https://github.com/kyan9400/hassan-webdesign), [Apex](https://github.com/kyan9400/apex-3d-site) |
| Databases | PostgreSQL (with pgvector), MongoDB, Redis, SQLite, safe SQL migrations | [OpsMind](https://github.com/kyan9400/opsmind), [DeployLedger](https://github.com/kyan9400/deployledger), [sehati-server](https://github.com/kyan9400/sehati-server), [Lumen Search](https://github.com/kyan9400/lumen-search), [SchemaSentry](https://github.com/kyan9400/schema-sentry) |
| Security and audit | Role-based access, policy evaluation, tamper-evident audit trails, signed webhooks | [Gatehouse](https://github.com/kyan9400/gatehouse), [Access Verdict](https://github.com/kyan9400/access-verdict), [Tampertrail](https://github.com/kyan9400/tampertrail), [Webhook Workbench](https://github.com/kyan9400/webhook-workbench) |
| Go | CLIs and single-binary services | [SLO Forge](https://github.com/kyan9400/slo-forge), [Webhook Workbench](https://github.com/kyan9400/webhook-workbench), [git-hotspots](https://github.com/kyan9400/git-hotspots), [Tampertrail](https://github.com/kyan9400/tampertrail) |
| DevOps | Docker, GitHub Actions, Kubernetes, Helm, Terraform, Prometheus | [Platform Blueprint](https://github.com/kyan9400/platform-blueprint), [DeployLedger](https://github.com/kyan9400/deployledger), [OpsMind](https://github.com/kyan9400/opsmind), [Lumen Search](https://github.com/kyan9400/lumen-search) |
| PHP | Web application on an external API | [Cinema-Russia](https://github.com/kyan9400/Cinema-Russia) |
| C and C++ | Single-threaded HTTP server in C for microcontrollers (select() event loop, fixed buffers, path-traversal protection); C++ socket server | [test-mdo](https://github.com/kyan9400/test-mdo), [final](https://github.com/kyan9400/final) |

Also used in team and client work, without public code yet: Angular, Solidity, Figma, JIRA and Agile delivery, Cloudinary.

## More work

- **AI and search:** [Lumen Search](https://github.com/kyan9400/lumen-search), [OpsMind](https://github.com/kyan9400/opsmind), [Mini GPT Workbench](https://github.com/kyan9400/my-gpt), [micrograd-plus](https://github.com/kyan9400/micrograd-plus), [File Finder MCP](https://github.com/kyan9400/file-finder-mcp)
- **Backend and reliability:** [LeaseQueue](https://github.com/kyan9400/leasequeue), [Stockroom Ledger](https://github.com/kyan9400/stockroom-ledger), [SLO Forge](https://github.com/kyan9400/slo-forge), [Platform Blueprint](https://github.com/kyan9400/platform-blueprint)
- **Developer tools:** [SchemaSentry](https://github.com/kyan9400/schema-sentry), [OpenAPI Impact](https://github.com/kyan9400/openapi-impact), [git-hotspots](https://github.com/kyan9400/git-hotspots), [Tampertrail](https://github.com/kyan9400/tampertrail)

The full, curated list with screenshots is on the [portfolio](https://alhassan-portfolio-sigma.vercel.app) ([mirror](https://kyan9400.github.io/alhassan_portfolio/)).
