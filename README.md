<!-- cv-source: en/cv-en.md -->
<p align="right"><sub><b>English</b> | <a href="README.pt-br.md">Português</a></sub></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Rafael Nobre" width="100%" height="80">
</picture>

<!-- cv:headline -->
**Full-Stack Developer** • TypeScript • React • Node.js • PostgreSQL • Applied AI
<!-- /cv:headline -->

I'm a full-stack developer in Brazil working on production SaaS and AI applications at [Meteora Digital](https://github.com/meteora-digital): AI agents, RAG and SaaS integrations, from design to deployment, with automated tests, CI security checks and documented architectural decisions.

[Resume (PDF)](https://github.com/RNobre1/RNobre1/raw/main/cv-en.pdf) | [Currículo em português (PDF)](https://github.com/RNobre1/RNobre1/raw/main/cv-pt-br.pdf) | [LinkedIn](https://www.linkedin.com/in/rafaelnobre-dev/) | [rafael@rnobre.dev](mailto:rafael@rnobre.dev)

Open to fully remote work and relocation.

## What I work on

AI platforms for Meteora Digital and its clients.

- **AI-first knowledge brain for a real-estate developer, in production.** Ingestion from 8 sources (WhatsApp, transcribed and diarized meetings, Drive, ERP, time tracking), RAG over 180k+ chunks, and natural-language answers with traceable sources and per-role clearance.
- **Internal no-code AI agent platform.** Multi-tenant architecture with templates, cron scheduling, durable jobs and no-code chat, plus stateful agents with persisted state and a dry-run mode.
- **SaaS integrations with per-user OAuth.** Gmail, Slack and WhatsApp, with double-layer cross-tenant isolation, encrypted tokens (AES-256-GCM) and per-datum sensitivity classification.
- **Cross-application LLM observability and cost hub.** Per-model and per-app cost, traces, error rates and an AI capability catalog across 3 instrumented systems.
- **O Agente, earlier.** Conversational agents that served paying customers via WhatsApp, Instagram and Web. I maintained its hybrid RAG pipeline (pgvector, BM25 + vector search, reranking) and the WhatsApp integration with a vision pipeline and human takeover, on a unified multi-provider LLM gateway.

## How I work

Test-first, with the projects' suites at 11,000+ tests (unit, integration, Playwright E2E, contract). CI gates on SAST and RLS lint. Architectural decisions are written down as ADRs, 40+ so far, backed by formal stack research with quantified trade-offs.

## Stack

<!-- cv:stack -->
<table>
<tr><td><b>Languages</b></td><td>TypeScript, JavaScript, SQL</td></tr>
<tr><td><b>Frontend</b></td><td>React 19, Next.js 16 (App Router), Vite, Tailwind, shadcn/ui, TanStack Query, React Hook Form + Zod</td></tr>
<tr><td><b>Backend</b></td><td>Node.js, Supabase, Drizzle ORM, event-driven and durable jobs (Inngest), REST/OpenAPI</td></tr>
<tr><td><b>Database / AI</b></td><td>PostgreSQL, Row-Level Security, AI agents, hybrid RAG (pgvector, BM25 + vector, reranking), multi-provider LLM gateway, LLM observability and cost tracking, LLM-as-judge evaluation</td></tr>
<tr><td><b>Security &amp; DevOps</b></td><td>data privacy and sensitivity classification, GitHub Actions (CI/CD with SAST and eval gates), Docker, Vercel, Sentry, Vitest, Testing Library, Playwright</td></tr>
</table>
<!-- /cv:stack -->
