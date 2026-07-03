<h1 align="center">Suntharalingam Kugarathan</h1>
<p align="center">AI Product Engineer</p>

<p align="center">
  I ship AI products end-to-end — LLM pipeline to production UI — solo when the team is just me, leading when it isn't.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kugarathan-suntharalingam"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn"></a>
  <a href="mailto:skugarathan2@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About

Three years in. Right now, I'm the only engineer on [OwnStory](https://ownstory.com) — a live product that turns photos, videos, and voice notes into a private story page people unlock with one QR scan, for gifts, weddings, memorials, birthdays. Real users, real traffic, no app required. I report straight to the founder, no BA or PM layer between an idea and shipped code. I lean on AI-native workflows to cover ground that would normally take a small team.

Before that, I led a five-engineer team rebuilding an insurance platform's policy, finance, and claims systems from scratch — turning what the business side actually needed into a system with 30+ controllers, 40+ models, and 50+ endpoints, not just writing code to a spec someone else finished. So I've run both ends of it: sole engineer with no safety net, and the person other engineers were relying on.

The AI work is where I go deepest, in either mode. Multi-provider LLM orchestration across Claude, OpenAI, and Gemini with forced tool-use and structured generation. RAG pipelines that don't rely on vector search alone — BM25 keyword search fused in via Reciprocal Rank Fusion, then cross-encoder reranking on top, because pure semantic similarity misses exact names, codes, and version numbers. Per-account and global AI budget guards so a bad prompt loop can't burn the budget. Eval harnesses that catch regressions before users do. This isn't theory — it's what's running behind a live NDA'd platform, and it's the whole point of [llmframe](https://github.com/rathan-skr/llmframe), a RAG + multi-LLM framework I built and open-sourced.

I pick the tool that fits the constraint, not the one that's trending, and I'd rather ship something real and imperfect than something perfect and theoretical. If there's no team, I'm the whole team. If there is one, I fit into it fast.

---

## Selected work

**[llmframe](https://github.com/rathan-skr/llmframe)** — production-grade RAG + multi-LLM framework
Three-stage retrieval: vector search + BM25 fused via Reciprocal Rank Fusion, then cross-encoder reranking. Streaming FastAPI API, swappable LLM providers (Claude / GPT-4o), swappable embeddings (OpenAI or local, zero-cost). 25 tests, Docker-ready.
`RAG` `hybrid search` `FastAPI` `Claude` `ChromaDB` `Docker`

**Stealth AI Site-Mirroring & Localization Platform** — *under NDA*
Multi-provider LLM pipeline (Claude / OpenAI / Gemini) with forced tool-use, large-context chunking, per-account and global AI budget guards, and an evals harness for output quality. Type-safe monorepo, Stripe billing, Bunny CDN delivery.
`AI orchestration` `evals` `cost control` `tRPC` `Drizzle` `TypeScript`

**[OwnStory](https://ownstory.com)** — multi-tenant consumer SaaS, sole engineer
Private, QR-linked story pages for gifts and life moments — photos, videos, and voice notes on one page, unlocked with a scan, no app or public feed. Next.js 15 Turborepo: 4 apps + 3 background workers, a Fastify API with auto-generated OpenAPI docs, Postgres via Drizzle (migrated off a legacy MySQL system), BullMQ/Redis for resumable media pipelines, and Claude + OpenAI content workflows. 417k+ stories served. Built and run solo, reporting directly to the founder.
`Next.js 15` `Fastify` `PostgreSQL` `BullMQ` `Claude/OpenAI` `Better Auth`

**[elitevaran.com](https://elitevaran.com)** — solo-built matrimony SaaS
Multi-tenant platform, zero to production, alone: schema-per-tenant PostgreSQL, 100+ routes, Better Auth with KYC, load-tested to 500 concurrent users.
`Next.js` `PostgreSQL` `multi-tenancy` `Better Auth`

**Envoy Policy Platform** — insurance system, Apptimus, team lead
Django/DRF + MySQL platform covering the full policy lifecycle, financials, and claims. Built a registry-driven incentive engine with a recursive logic-tree evaluator and a dynamic SQL query builder, plus a double-entry accounting engine. 30+ controllers, 40+ models, 50+ endpoints. Led a five-engineer team.
`Django` `systems design` `double-entry accounting` `JWT/RBAC` `Docker/K8s`

---

## Stack

**Languages** — TypeScript · Python · JavaScript · SQL
**AI / LLM** — Claude · OpenAI · Gemini · Vercel AI SDK · evals & observability
**Frontend** — Next.js 15 · React · Tailwind · TanStack Query
**Backend & data** — tRPC · Fastify · Node.js · Django/DRF · Drizzle · PostgreSQL · MySQL · Redis · BullMQ · Inngest
**Infra** — Docker · Kubernetes · Turborepo · Stripe · Cloudflare R2

---

## Contact

skugarathan2@gmail.com · [LinkedIn](https://www.linkedin.com/in/kugarathan-suntharalingam)
