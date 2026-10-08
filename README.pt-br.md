<!-- cv-source: pt-br/cv-pt-br.md -->
<p align="right"><sub><a href="README.md">English</a> | <b>Português</b></sub></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Rafael Nobre" width="100%" height="80">
</picture>

<!-- cv:headline -->
**Desenvolvedor Full-Stack** • TypeScript • React • Node.js • PostgreSQL • IA aplicada
<!-- /cv:headline -->

Sou desenvolvedor full-stack no Brasil e trabalho com aplicações SaaS e IA em produção na [Meteora Digital](https://github.com/meteora-digital): agentes de IA, RAG e integrações SaaS, de design a deploy, com testes automatizados, CI com verificações de segurança e decisões arquiteturais documentadas.

[Currículo (PDF)](https://github.com/RNobre1/RNobre1/raw/main/cv-pt-br.pdf) | [Resume in English (PDF)](https://github.com/RNobre1/RNobre1/raw/main/cv-en.pdf) | [LinkedIn](https://www.linkedin.com/in/rafaelnobre-dev/) | [rafael@rnobre.dev](mailto:rafael@rnobre.dev)

Disponível para trabalho remoto e realocação.

## No que trabalho

Plataformas de IA da Meteora Digital e de clientes.

- **Cérebro AI-first de uma incorporadora, em produção.** Ingestão de 8 fontes (WhatsApp, reuniões transcritas e diarizadas, Drive, ERP, ponto), RAG sobre 180 mil+ chunks e resposta em linguagem natural com fonte rastreável e liberação por perfil.
- **Plataforma interna de agentes de IA no-code.** Arquitetura multi-tenant com templates, agendamento cron, jobs duráveis e chat no-code, além de agentes stateful com estado persistido e modo dry-run.
- **Integrações SaaS com OAuth por usuário.** Gmail, Slack e WhatsApp, com isolamento cross-tenant em dupla camada, tokens cifrados (AES-256-GCM) e classificação de sigilo por dado.
- **Hub de observability e custo de LLM cross-aplicação.** Custo por modelo e por app, traces, taxa de erro e catálogo de capacidades de IA de 3 sistemas instrumentados.
- **O Agente, anteriormente.** Agentes conversacionais que atenderam clientes pagantes via WhatsApp, Instagram e Web. Mantive o pipeline RAG híbrido (pgvector, busca BM25 + vetorial, rerank) e a integração WhatsApp com pipeline de visão e takeover humano, sobre gateway LLM multi-provider unificado.

## Como trabalho

Testes primeiro: as suítes dos projetos somam 11.000+ testes (unit, integração, E2E Playwright, contrato). CI com gates de SAST e lint de RLS. Decisões arquiteturais ficam registradas em ADRs, 40+ até aqui, com pesquisa formal de stack e trade-offs quantificados.

## Stack

<!-- cv:stack -->
<table>
<tr><td><b>Linguagens</b></td><td>TypeScript, JavaScript, SQL</td></tr>
<tr><td><b>Frontend</b></td><td>React 19, Next.js 16 (App Router), Vite, Tailwind, shadcn/ui, TanStack Query, React Hook Form + Zod</td></tr>
<tr><td><b>Backend</b></td><td>Node.js, Supabase, Drizzle ORM, jobs event-driven e duráveis (Inngest), REST/OpenAPI</td></tr>
<tr><td><b>Banco / IA</b></td><td>PostgreSQL, Row-Level Security, agentes de IA, RAG híbrido (pgvector, BM25 + vetorial, rerank), gateway LLM multi-provider, observability e custo de LLM, eval LLM-as-judge</td></tr>
<tr><td><b>Segurança &amp; DevOps</b></td><td>LGPD e classificação de sigilo, GitHub Actions (CI/CD com gates de SAST e eval), Docker, Vercel, Sentry, Vitest, Testing Library, Playwright</td></tr>
</table>
<!-- /cv:stack -->
