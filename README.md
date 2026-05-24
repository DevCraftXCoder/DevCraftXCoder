<div align="center">

# DevCraftXCoder

**Full-stack engineer building security systems, edge infrastructure, automation, and music platforms.**

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)](https://workers.cloudflare.com/)
[![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![LLM API](https://img.shields.io/badge/LLM_API-D97706?style=flat&logo=anthropic&logoColor=white)](https://www.anthropic.com/)
[![Tauri](https://img.shields.io/badge/Tauri_2-FFC131?style=flat&logo=tauri&logoColor=black)](https://tauri.app/)

</div>

---

## What I Build

Production security tooling, globally distributed edge systems, Automation, and a social music platform for independent artists — architected for environments where uptime, data integrity, and threat resilience are baseline requirements.

- **Security engineering** — Pentesting frameworks with 150+ tools and Autonomous agents, attack surface mapping, zero-trust access controls, and MCP-compatible tooling for integration into existing security workflows.
- **Edge-native infrastructure** — Serverless backends on Cloudflare Workers with D1, R2, Durable Objects, and Workers Rate Limiting. Globally distributed, no cold starts, no traditional server management.
- **automation systems** — Multi-provider LLM integrations (Claude, OpenRouter, Ollama) with extended thinking, prompt caching, structured tool use, streaming, and autonomous agent orchestration. Built for security automation, intelligent reporting, and real-time analysis.
- **Full-stack product delivery** — End-to-end ownership from database schema to deployed frontend. Every system ships with hardened auth, input validation, error handling, and observability from day one.

---

## Projects

### Security Engineering

| Project | What It Is | Stack |
|---------|-----------|-------|
| [SIC](https://github.com/DevCraftXCoder/SIC) | Automation-powered pentesting MCP framework — 150+ security tools, 12+ Autonomous agents, local-first zero-trust design | Python · MCP · REST API |
| [AttackMap](https://github.com/DevCraftXCoder/AttackMap) | Attack surface mapper — MCP-compatible, structured threat reports, IP-allowlisted, local-first | Python · MCP · REST API |
| [Admin Dashboard](https://github.com/DevCraftXCoder/Admin-Dashboard) | Security ops console with embedded SIC — Automated vulnerability analysis, dependency health SCA, uptime monitoring | Next.js · TypeScript · LLM API |

### Platform Engineering

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Underground Social](https://github.com/DevCraftXCoder/Underground-Social) | Social music platform for independent artists — 150+ API routes, real-time DMs, Automated recommendations, HLS streaming, Stripe subscriptions | TypeScript · Hono · CF Workers · D1 · R2 |
| [Finos](https://github.com/DevCraftXCoder/Finos) | Financial Automation OS — Next.js web + Tauri 2 desktop + edge API, real-time dashboards, Automated intelligence, typed SQL bridge | Next.js 15 · Tauri 2.x · Hono · CF Workers · Supabase |

### Automation Systems

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Biggest Bro](https://github.com/DevCraftXCoder/Biggest-Bro) | Domain-expert Automation agent — LLM extended thinking, tool use, prompt caching, SSE streaming | Next.js · LLM SDK · LLM API |
| [Growth Report AI](https://github.com/DevCraftXCoder/Growth-Report-AI) | analytics Automation dashboard — streaming LLM reports, prompt caching, sub-2s load, period-over-period comparisons | Next.js · LLM SDK · SSE |
| [Swarm Orchestrator](https://github.com/DevCraftXCoder/swarm-orchestrator) | Meta-orchestrator for coding agents — analyzes tasks, picks agents, dispatches swarms, collects handoffs | Node.js · Claude Code · Agent Framework |

### Infrastructure & Developer Tools

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Ops App](https://github.com/DevCraftXCoder/Ops-App) | Workflow Automation, monitoring, alerting and ticketing dashboard — drag-and-drop workflow builder, real-time metrics, PM2/CF cron migration | Next.js 15 · React Flow · CF Workers · R2 |
| [Autodeploy](https://github.com/DevCraftXCoder/Autodeploy) | Non-blocking CF Workers Autodeploy hook system — git-triggered builds, detached wrangler deploy, concurrent pipelines | Node.js · Cloudflare Workers · Git Hooks |
| [Claude Hermes Bridge](https://github.com/DevCraftXCoder/claude-hermes-bridge) | Claude Code to Hermes agent bridge — auto-syncs agents/hooks/skills to WSL2 autonomous agent, multi-provider LLM fallback (Ollama + OpenRouter), Discord gateway bot | Node.js · WSL2 · Ollama · Claude Code Hooks |
| [ai-alias-system](https://github.com/DevCraftXCoder/ai-alias-system) | Symbol-shorthand alias vocabulary for automation coding assistants — `pnpm dlx ai-alias-system install` wires `@`, `$`, `#`, `&`, `%`, `~` into Claude Code, Codex CLI, and Gemini CLI | Node.js · pnpm CLI · Claude Code · Codex · Gemini |
| [Mode](https://github.com/DevCraftXCoder/Mode) | System resource optimizer — auto-pauses Docker, WSL, background pollers; freezes idle Chrome tabs to reclaim RAM/CPU/GPU | Node.js · PowerShell · PM2 |
| [PM2 Popup Guard](https://github.com/DevCraftXCoder/pm2-popup-guard) | Windows PM2 process cleanup — kills stale popups, heals port bindings, resets crash counters | PowerShell · Node.js · PM2 |
| [Hook Recovery](https://github.com/DevCraftXCoder/hook-recovery) | Claude Code hook hardening kit — fixes re-read loops, silent write failures, post-compact blocks. 23-test suite, one-line install | Node.js · Claude Code Hooks |
| [PDF Report Engine](https://github.com/DevCraftXCoder/PDF-Report-Engine) | Enterprise PDF generation — Python ReportLab engine, Next.js API routes, React 4-step wizard, live preview | Python · Node.js · Next.js · ReportLab |

### Analytics & Data

| Project | What It Is | Stack |
|---------|-----------|-------|
| [EV Betta](https://github.com/DevCraftXCoder/EV-Betta) | Sports analytics pipeline — multi-source odds scraper, EV scoring engine, React picks board, edge-cached API, Discord alerts | TypeScript · Hono · CF Workers · D1 · React |
| [Influnx Calc](https://github.com/DevCraftXCoder/Influnx-Calc) | Influencer scoring engine — 100-point multi-metric system, sub-100ms at 1,000 req/s, pure TypeScript | TypeScript · React · Vitest |

### Creator & Content Tools

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Mizzy Tools](https://github.com/DevCraftXCoder/Mizzy-Toolz) | Self-hosted creator dashboard — streaming media downloads, analytics, dev app launcher; zero port exposure via CF Tunnel | Next.js · Docker · Cloudflare Tunnel |
| [Prompt Library](https://github.com/DevCraftXCoder/Prompt-Library) | 3,900+ production-ready prompts — Quick/Combo/Paragraph tiers, 33 sections, JSON + TypeScript + MCP plugin | JSON · TypeScript · MCP |

---

## Technical Focus

```
Security              |  Pentesting frameworks · attack surface mapping · OWASP · zero-trust · MCP tooling
LLM & Automation       |  Claude API · OpenRouter · Ollama · autonomous agents · tool use · prompt caching · SSE
Cloud & Edge          |  Cloudflare Workers · D1 · R2 · Durable Objects · KV · Vectorize · Named Tunnels
Backend               |  TypeScript · Hono · Python · FastAPI · PostgreSQL · SQLite (D1) · Zod · JWT · Web Crypto
Frontend              |  Next.js 15 · React 19 · Tauri 2.x · Vite · App Router · Server Actions
DevOps                |  Docker · PM2 · Wrangler · Git hooks · WSL2 · Automated deploy pipelines
```

---

## How I Work

End-to-end ownership — from threat model and database schema through deployed edge infrastructure. I architect, implement, harden, and ship.

- **Security by design** — Every system is built with hardened auth, input validation, rate limiting, and CSRF protection from the first commit. Security is a design constraint, not a follow-up ticket.
- **Offensive and defensive** — I build the pentesting frameworks and the production systems they're designed to test. Understanding both sides produces better engineering on each.
- **Edge-native architecture** — Cloudflare Workers, D1, R2, and Durable Objects as the default runtime. Globally distributed, zero cold starts, no server management overhead.
- **automation-augmented workflows** — Multi-provider LLM integrations (Claude, OpenRouter, Ollama) with structured tool use, streaming, and Autonomous agents for security automation and intelligent reporting at scale.
- **Multi-agent orchestration** — 50+ specialized Claude Code agents with model-aware spawning, handoff protocols, and parallel execution. Custom hook system (16 hooks) enforces quality gates across every code change.
- **Production-grade standards** — Every feature includes structured error handling, observability, input validation, and deployment configuration. Nothing ships incomplete.

---

## Recent Work

- **ai-alias-system** — `@$#&%~` symbol shorthand for Claude Code, Codex CLI, Gemini CLI — interactive wizard, per-project vocabulary, validate command
- **Claude Hermes Bridge** — multi-provider LLM fallback (Ollama -> OpenRouter), Discord gateway bot, auth.json credential cache management, provider resolution debugging
- **PM2 Popup Guard** — Windows daemon + daily sweep that kills stale Playwright/Explorer/Terminal popups; 5 root-cause kill rules, CimInstance batch fetch
- **Finos Desktop** — Tauri 2.x with microphone input settings, admin mode bypass, WebView2 mic dialog, STT diagnostics
- **Underground API** — 150+ routes across 41 files, 68 D1 migrations, 30+ tables, HLS multi-bitrate streaming, Web Push notifications
- **EV Betta** — picks engine with player prop scoring, multi-source odds scraper (6 sources), Discord webhook alerts
- **SIC v6** — 150+ security tools, 12+ Autonomous agents, billing server, incident tracking, MCP integration
- **Hook Recovery** — Claude Code hook hardening: token-guard re-read loops, silent write failures, post-compact blocks (23-test suite)

---

<div align="center">

[SIC](https://github.com/DevCraftXCoder/SIC) · [Finos](https://github.com/DevCraftXCoder/Finos) · [Underground Social](https://github.com/DevCraftXCoder/Underground-Social) · [EV Betta](https://github.com/DevCraftXCoder/EV-Betta) · [Claude Hermes Bridge](https://github.com/DevCraftXCoder/claude-hermes-bridge)

</div>
