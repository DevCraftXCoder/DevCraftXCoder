<div align="center">

# DevCraftXCoder

**Full-stack engineer building AI-powered systems, cloud infrastructure, and security tooling.**

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)](https://workers.cloudflare.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Anthropic](https://img.shields.io/badge/Claude_API-D97706?style=flat&logo=anthropic&logoColor=white)](https://www.anthropic.com/)

</div>

---

## What I Build

Edge-first backends, AI integrations, and security tooling — designed to run at scale without traditional server infrastructure.

- **Cloud systems** — Cloudflare Workers, D1, R2, Durable Objects. No cold starts, globally distributed, no Kubernetes.
- **AI automation** — Claude API with extended thinking, prompt caching, streaming, and tool use. Production-grade, not demos.
- **Security tooling** — MCP-compatible pentesting framework, attack surface mapping, IP-allowlisted admin ops.
- **Creator infrastructure** — Full-stack platforms for independent creators: content pipelines, analytics, media processing.

---

## Featured Projects

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Underground Social](https://github.com/DevCraftXCoder/Underground-Social) | Edge-native social platform — 150+ API routes, real-time DMs via Durable Objects, AI moderation, Stripe subscriptions | TypeScript · Hono · CF Workers · D1 · R2 |
| [SIC — Security Intelligence Center](https://github.com/DevCraftXCoder/SIC) | AI-powered pentesting MCP framework — 150+ security tools, 12+ autonomous agents, local-first zero-trust design | Python · MCP · REST API |
| [AttackMap](https://github.com/DevCraftXCoder/AttackMap) | Attack surface mapper and threat modeling framework — MCP-compatible, structured threat reports, IP-allowlisted | Python · MCP · REST API |
| [EV Betta](https://github.com/DevCraftXCoder/EV-Betta) | Sports analytics pipeline — odds scraper, EV engine, React picks board, edge-cached API | TypeScript · Hono · CF Workers · D1 · React |
| [Growth Report AI](https://github.com/DevCraftXCoder/Growth-Report-AI) | AI analytics dashboard — streaming Claude reports, prompt caching, sub-2s load, period-over-period comparisons | Next.js · Anthropic SDK · SSE |
| [Biggest Bro](https://github.com/DevCraftXCoder/Biggest-Bro) | Domain-expert AI agent — Claude Opus 4.7 extended thinking, tool use, prompt caching, SSE streaming | Next.js · Anthropic SDK · Claude API |
| [Admin Dashboard](https://github.com/DevCraftXCoder/Admin-Dashboard) | Multi-panel admin console with embedded Security Intelligence Center — AI-powered vulnerability analysis | Next.js · TypeScript · Claude API |
| [Mizzy Tools](https://github.com/DevCraftXCoder/Mizzy-Toolz) | Self-hosted creator dashboard — streaming media downloads, analytics, Cloudflare Named Tunnel (zero port exposure) | Next.js · Docker · Cloudflare Tunnel |
| [Influnx Calc](https://github.com/DevCraftXCoder/Influnx-Calc) | Influencer scoring engine — 100-point multi-metric system, sub-100ms at 1,000 req/s, pure TypeScript | TypeScript · React · Vitest |
| [Prompt Library](https://github.com/DevCraftXCoder/Prompt-Library) | 1,000+ production-ready prompts — Quick/Combo/Paragraph tiers, 33 sections, JSON + TypeScript format | — |

---

## Technical Focus

```
Edge Architecture     │  Cloudflare Workers · D1 · R2 · Durable Objects · KV
AI Integration        │  Claude API · extended thinking · tool use · prompt caching · SSE streaming
Security Engineering  │  MCP pentesting · attack surface mapping · zero-trust IP allowlisting · OWASP
Backend               │  TypeScript · Hono · Python · FastAPI · SQL · Zod validation
Frontend              │  Next.js 15 · App Router · React · Vite · Server Actions
Infrastructure        │  Docker · PM2 · Cloudflare Named Tunnels · Workers Rate Limiting
```

---

## How I Work

Solo full-stack — I own the entire stack from D1 schema to React component. Architecture decisions skew toward:

- **Edge-first**: If it can run on a Worker, it does. Durable Objects for stateful real-time, D1 for relational, R2 for binary. No traditional servers.
- **Security-aware by default**: Rate limiting at the edge, timing-safe auth, CSRF guards, IDOR prevention, Zod on every boundary.
- **AI as infrastructure**: Not bolted on — Claude API integrations are first-class with prompt caching, structured tool use, and streaming built in from the start.
- **Single-pass delivery**: No MVP iterations. Features ship production-ready with error handling, validation, and observability.

---

## Recent Additions

- **SIC v6.0.0** — 38 tool routes patched for shell injection safety, per-service API tokens, rate limiting, hardened error handling
- **MizzyTools** — AI insights streaming via Ollama-first/OpenRouter-fallback, PrismaticBurst WebGL backdrop, mobile bottom nav bar
- **francois-landing** — PanelLearn visual overhaul (glassmorphism, XP strip, animated rings), SystemsTab Clear buttons, Space Grotesk typography
- **EV Betta** — single CF native cron driver, job telemetry, Discord threshold-delta notifications removed
- **Infrastructure** — PM2 popup watchdog hardening, autodeploy hook `[skip-deploy]` token, orphaned pythonw cleanup

---

<div align="center">

[Underground Social](https://github.com/DevCraftXCoder/Underground-Social) · [SIC](https://github.com/DevCraftXCoder/SIC) · [AttackMap](https://github.com/DevCraftXCoder/AttackMap) · [EV Betta](https://github.com/DevCraftXCoder/EV-Betta)

</div>
