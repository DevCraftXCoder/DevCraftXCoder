<div align="center">

# DevCraftXCoder

**Full-stack engineer building security systems, edge infrastructure, automation, and music platforms.**

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)](https://workers.cloudflare.com/)
[![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Tauri](https://img.shields.io/badge/Tauri_2-FFC131?style=flat&logo=tauri&logoColor=black)](https://tauri.app/)

</div>

---

## What I Build

Production security tooling, globally distributed edge systems, automation, and social platforms — architected for environments where uptime, data integrity, and threat resilience are baseline requirements.

- **Security engineering** — Pentesting frameworks with 85 MCP tools, attack surface mapping, zero-trust access controls, and MCP-compatible tooling for integration into existing security workflows.
- **Edge-native infrastructure** — Serverless backends on Cloudflare Workers with D1, R2, Durable Objects, and Workers Rate Limiting. Globally distributed, no cold starts, no traditional server management.
- **Automation systems** — Workflow automation, scheduled job pipelines, webhook systems, and real-time reporting. Built for security automation, continuous operations, and monitoring at scale.
- **Full-stack product delivery** — End-to-end ownership from database schema to deployed frontend. Every system ships with hardened auth, input validation, error handling, and observability from day one.

---

## Projects

### Security Engineering

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Security Intelligence Center](https://github.com/DevCraftXCoder/Security-Intelligence-Center) | Pentesting MCP framework — 85 security tools, 12+ specialized agents, local-first zero-trust design | Python · MCP · REST API |
| [AttackMap](https://github.com/DevCraftXCoder/AttackMap) | Attack surface mapper — MCP-compatible, structured threat reports, IP-allowlisted, local-first | Python · MCP · REST API |
| [SOC Handoff](https://github.com/DevCraftXCoder/soc-handoff) | Security operations handoff and audit reporting system — NIST SP 800-61, MITRE ATT&CK, OWASP, CIS Controls v8. Integrates with SIC for automated finding ingestion | Python · TypeScript · SIC |

### Platform Engineering

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Underground Social](https://github.com/DevCraftXCoder/Underground-Social) | Social music platform for independent artists — real-time DMs via Durable Objects, HLS multi-bitrate streaming, Stripe subscriptions, 42-route edge API | TypeScript · Hono · CF Workers · D1 · R2 |
| [Finos](https://github.com/DevCraftXCoder/Finos) | Financial OS — Next.js web + Tauri 2 desktop + edge API, real-time dashboards, typed SQL bridge | Next.js 15 · Tauri 2.x · Hono · CF Workers · Supabase |

### Infrastructure & Developer Tools

| Project | What It Is | Stack |
|---------|-----------|-------|
| [AI Infrastructure](https://github.com/DevCraftXCoder/AI-Infrastructure) | OpenAI-compatible LLM gateway + service health control plane — OpenRouter cascade, input/output safety, D1 cost ledger, 5-min health sweeps, prompt cache auto-injection | TypeScript · Hono · CF Workers · D1 · Workers Rate Limiting |
| [Admin Dashboard](https://github.com/DevCraftXCoder/Admin-Dashboard) | Security ops console with embedded SIC — automated vulnerability analysis, dependency health SCA, uptime monitoring | Next.js · TypeScript |
| [Ops App](https://github.com/DevCraftXCoder/Ops-App) | Workflow automation, monitoring, alerting and ticketing dashboard — drag-and-drop workflow builder, real-time metrics, PM2/CF cron migration | Next.js 15 · React Flow · CF Workers · R2 |
| [Claude Hermes Bridge](https://github.com/DevCraftXCoder/claude-hermes-bridge) | Coding assistant to autonomous agent bridge — auto-syncs agents/hooks/skills to WSL2, multi-provider fallback, Discord gateway bot | Node.js · WSL2 · Ollama |
| [Autodeploy](https://github.com/DevCraftXCoder/Autodeploy) | Non-blocking CF Workers autodeploy hook system — git-triggered builds, detached wrangler deploy, concurrent pipelines | Node.js · Cloudflare Workers · Git Hooks |
| [snap](https://github.com/DevCraftXCoder/snap) | Screenshot vision + visual alias manager — analyzes Windows screenshots, correlates to repo source files and CSS layers, persists as reusable aliases | Node.js · pnpm |
| [ai-alias-system](https://github.com/DevCraftXCoder/ai-alias-system) | Symbol-shorthand alias vocabulary for coding assistants — `pnpm dlx ai-alias-system install` wires `@`, `$`, `#`, `&`, `%`, `~` into your workflow | Node.js · pnpm CLI |
| [Hook Recovery](https://github.com/DevCraftXCoder/hook-recovery) | Coding assistant hook hardening kit — fixes re-read loops, silent write failures, post-compact blocks. 23-test suite, one-line install | Node.js |
| [PDF Report Engine](https://github.com/DevCraftXCoder/PDF-Report-Engine) | Enterprise PDF generation — Python ReportLab engine, Next.js API routes, React 4-step wizard, live preview | Python · Node.js · Next.js · ReportLab |
| [Mode](https://github.com/DevCraftXCoder/Mode) | System resource optimizer — auto-pauses Docker, WSL, background pollers; freezes idle Chrome tabs to reclaim RAM/CPU/GPU | Node.js · PowerShell · PM2 |
| [PM2 Popup Guard](https://github.com/DevCraftXCoder/pm2-popup-guard) | Windows PM2 process cleanup — kills stale popups, heals port bindings, resets crash counters | PowerShell · Node.js · PM2 |
| [CrossWindow](https://github.com/DevCraftXCoder/CrossWindow) | Windows desktop utility — move and swap windows across monitors with directional hotkeys | C# · Windows |

### Automation Systems

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Swarm Orchestrator](https://github.com/DevCraftXCoder/swarm-orchestrator) | Meta-orchestrator for distributed task execution — analyzes tasks, picks workers, dispatches swarms, collects handoffs | Node.js · Agent Framework |
| [Biggest Bro](https://github.com/DevCraftXCoder/Biggest-Bro) | Domain-expert reporting agent — tool use, SSE streaming, structured output | Next.js · SSE |
| [Growth Report AI](https://github.com/DevCraftXCoder/Growth-Report-AI) | Analytics automation dashboard — streaming reports, sub-2s load, period-over-period comparisons | Next.js · SSE |

### Analytics & Data

| Project | What It Is | Stack |
|---------|-----------|-------|
| [EV Betta](https://github.com/DevCraftXCoder/EV-Betta) | Sports analytics pipeline — multi-source odds scraper, EV scoring engine, React picks board, edge-cached API, Discord alerts | TypeScript · Hono · CF Workers · D1 · React |
| [Influnx Calc](https://github.com/DevCraftXCoder/Influnx-Calc) | Influencer scoring engine — 100-point multi-metric system, sub-100ms at 1,000 req/s, pure TypeScript | TypeScript · React · Vitest |

### Creator & Content Tools

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Focus App](https://github.com/DevCraftXCoder/focus-app) | Timed writing sessions with automated scoring — 5-phase flow (splash → setup → write → score → history), countdown or open timer, 5 graded dimensions, cross-window controls, week streak tracking, daily prompts | Tauri 2 · React 19 · Vite |
| [dropstream](https://github.com/DevCraftXCoder/dropstream) | Live media and control wall for streamers — drop any stream, video, chat, timer, or widget link into freeform panes, arrange them, and export a clean OBS browser source. Room state serialized to URL; safety model drops unsafe schemes and sandboxes iframes without `allow-same-origin` | TanStack Start · React 19 · Vite · CF Workers |
| [Prompt Library](https://github.com/DevCraftXCoder/Prompt-Library) | 3,900+ production-ready prompts — Quick/Combo/Paragraph tiers, 33 sections, JSON + TypeScript + MCP plugin | JSON · TypeScript · MCP |
| [BelieveIt](https://github.com/DevCraftXCoder/BelieveIt) | Visual concept social platform — portfolio and discovery for generated images, brand concepts, and creative campaigns | Vite · React · Cloudflare Pages |
| [Mizzy Tools](https://github.com/DevCraftXCoder/Mizzy-Toolz) | Self-hosted creator dashboard — streaming media downloads, analytics, dev app launcher; zero port exposure via CF Tunnel | Next.js · Docker · Cloudflare Tunnel |

---

## Technical Focus

```
Security              |  Pentesting frameworks · attack surface mapping · OWASP · zero-trust · MCP tooling
Automation            |  Webhook pipelines · scheduled jobs · worker orchestration · streaming · SSE
Cloud & Edge          |  Cloudflare Workers · D1 · R2 · Durable Objects · KV · Vectorize · Named Tunnels
Backend               |  TypeScript · Hono · Python · FastAPI · PostgreSQL · SQLite (D1) · Zod · JWT · Web Crypto
Frontend              |  Next.js 15 · React 19 · Tauri 2.x · Vite · App Router · Server Actions
DevOps                |  Docker · PM2 · Wrangler · Git hooks · WSL2 · automated deploy pipelines
```

---

## How I Work

End-to-end ownership — from threat model and database schema through deployed edge infrastructure. I architect, implement, harden, and ship.

- **Security by design** — Every system is built with hardened auth, input validation, rate limiting, and CSRF protection from the first commit. Security is a design constraint, not a follow-up ticket.
- **Offensive and defensive** — I build the pentesting frameworks and the production systems they're designed to test. Understanding both sides produces better engineering on each.
- **Edge-native architecture** — Cloudflare Workers, D1, R2, and Durable Objects as the default runtime. Globally distributed, zero cold starts, no server management overhead.
- **Automated workflows** — Multi-provider integrations with structured tool use, streaming, and worker orchestration for security automation and reporting at scale.
- **Production-grade standards** — Every feature includes structured error handling, observability, input validation, and deployment configuration. Nothing ships incomplete.

---

<div align="center">

[Security Intelligence Center](https://github.com/DevCraftXCoder/Security-Intelligence-Center) · [Finos](https://github.com/DevCraftXCoder/Finos) · [Underground Social](https://github.com/DevCraftXCoder/Underground-Social) · [EV Betta](https://github.com/DevCraftXCoder/EV-Betta) · [Claude Hermes Bridge](https://github.com/DevCraftXCoder/claude-hermes-bridge)

</div>
