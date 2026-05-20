<div align="center">

# DevCraftXCoder

**Forward-deployed engineer specializing in security systems, edge infrastructure, and AI-driven automation.**

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)](https://workers.cloudflare.com/)
[![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![LLM API](https://img.shields.io/badge/LLM_API-D97706?style=flat&logo=anthropic&logoColor=white)](https://www.anthropic.com/)

</div>

---

## What I Build

Production security tooling, globally distributed edge systems, and AI automation - architected for environments where uptime, data integrity, and threat resilience are baseline requirements.

- **Security engineering** - Pentesting frameworks with 150+ tools and autonomous agents, attack surface mapping, zero-trust access controls, and MCP-compatible tooling for integration into existing security workflows.
- **Edge-native infrastructure** - Serverless backends on Cloudflare Workers with D1, R2, Durable Objects, and Workers Rate Limiting. Globally distributed, no cold starts, no traditional server management.
- **AI systems** - LLM API integrations with extended thinking, prompt caching, structured tool use, and streaming. Built for security automation, intelligent reporting, and autonomous analysis - not prototypes.
- **Full-stack product delivery** - End-to-end ownership from database schema to deployed frontend. Every system ships with hardened auth, input validation, error handling, and observability from day one.

---

## Projects

### Security Engineering

| Project | What It Is | Stack |
|---------|-----------|-------|
| [SIC - Security Intelligence Center](https://github.com/DevCraftXCoder/SIC) | AI-powered pentesting MCP framework - 150+ security tools, 12+ autonomous agents, local-first zero-trust design | Python · MCP · REST API |
| [AttackMap](https://github.com/DevCraftXCoder/AttackMap) | Attack surface mapper - MCP-compatible, structured threat reports, IP-allowlisted, local-first | Python · MCP · REST API |
| [Admin Dashboard](https://github.com/DevCraftXCoder/Admin-Dashboard) | Security ops console with embedded SIC - AI vulnerability analysis, dependency health SCA, uptime monitoring | Next.js · TypeScript · LLM API |

### Platform Engineering

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Underground Social](https://github.com/DevCraftXCoder/Underground-Social) | Artist emerging platform - real-time DMs, social discovery, collaborate with artists, post music; edge-native with 150+ API routes | TypeScript · Hono · CF Workers · D1 · R2 |
| [Finos](https://github.com/DevCraftXCoder/Finos) | Multi-platform workspace app - Next.js web + Tauri desktop + edge API, real-time sync, AI intelligence, typed SQL bridge | Next.js 15 · Tauri 2.x · Hono · CF Workers · Supabase |

### AI Systems

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Biggest Bro](https://github.com/DevCraftXCoder/Biggest-Bro) | Domain-expert AI agent - LLM extended thinking, tool use, prompt caching, SSE streaming | Next.js · LLM SDK · LLM API |
| [Growth Report AI](https://github.com/DevCraftXCoder/Growth-Report-AI) | AI analytics dashboard - streaming LLM reports, prompt caching, sub-2s load, period-over-period comparisons | Next.js · LLM SDK · SSE |
| [Claude Hermes Bridge](https://github.com/DevCraftXCoder/claude-hermes-bridge) | Claude Code to Hermes agent bridge - auto-syncs agents, hooks, skills to WSL2 autonomous agent, memory export, Discord gateway, multi-provider LLM fallback | Node.js · WSL2 · Ollama · Claude Code Hooks |

### Infrastructure & Developer Tools

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Ops App](https://github.com/DevCraftXCoder/Ops-App) | Workflow automation, monitoring, alerting and ticketing dashboard - drag-and-drop workflow builder, real-time metrics, PM2/CF cron migration | Next.js 15 · React Flow · CF Workers · R2 |
| [Autodeploy](https://github.com/DevCraftXCoder/Autodeploy) | Non-blocking CF Workers autodeploy hook system - git-triggered builds, detached wrangler deploy, concurrent pipelines | Node.js · Cloudflare Workers · Git Hooks |
| [Mode](https://github.com/DevCraftXCoder/Mode) | System resource optimizer - auto-pauses Docker, WSL, background pollers; freezes idle Chrome tabs to reclaim RAM/CPU/GPU for Premiere, DaVinci, Blender, local LLMs | Node.js · PowerShell · PM2 |
| [PM2 Popup Guard](https://github.com/DevCraftXCoder/pm2-popup-guard) | Windows PM2 process cleanup - kills stale Playwright/Explorer popups, heals port bindings, resets crash counters | PowerShell · Node.js · PM2 |
| [Hook Recovery](https://github.com/DevCraftXCoder/hook-recovery) | Claude Code hook hardening kit - fixes re-read loops, silent write failures, post-compact blocks. 23-test suite, one-line install | Node.js · Claude Code Hooks |
| [PDF Report Engine](https://github.com/DevCraftXCoder/PDF-Report-Engine) | Enterprise PDF generation - Python ReportLab engine, Next.js API routes, React 4-step wizard, live preview | Python · Node.js · Next.js · ReportLab |

### Analytics & Data

| Project | What It Is | Stack |
|---------|-----------|-------|
| [EV Betta](https://github.com/DevCraftXCoder/EV-Betta) | Sports analytics pipeline - odds scraper, EV engine, React picks board, edge-cached API | TypeScript · Hono · CF Workers · D1 · React |
| [Influnx Calc](https://github.com/DevCraftXCoder/Influnx-Calc) | Influencer scoring engine - 100-point multi-metric system, sub-100ms at 1,000 req/s, pure TypeScript | TypeScript · React · Vitest |

### Creator & Content Tools

| Project | What It Is | Stack |
|---------|-----------|-------|
| [Mizzy Tools](https://github.com/DevCraftXCoder/Mizzy-Toolz) | Self-hosted creator dashboard - streaming media downloads, analytics, dev app launcher; Cloudflare Named Tunnel (zero port exposure) | Next.js · Docker · Cloudflare Tunnel |
| [Prompt Library](https://github.com/DevCraftXCoder/Prompt-Library) | 1,000+ production-ready prompts - Quick/Combo/Paragraph tiers, 33 sections, JSON + TypeScript format | JSON · TypeScript · MCP |

---

## Technical Focus

```
Security              │  Pentesting frameworks · attack surface mapping · OWASP · zero-trust access · MCP tooling
AI & Automation       │  LLM API · autonomous agents · extended thinking · prompt caching · structured tool use · SSE
Cloud & Edge          │  Cloudflare Workers · D1 · R2 · Durable Objects · KV · Workers Rate Limiting · Named Tunnels
Backend               │  TypeScript · Hono · Python · FastAPI · PostgreSQL · SQLite (D1) · Zod · JWT · Web Crypto
Frontend              │  Next.js 15 · React 19 · Tauri 2.x · Vite · App Router · Server Actions
DevOps                │  Docker · PM2 · Wrangler · Git hooks · PowerShell · Automated deploy pipelines
```

---

## How I Work

End-to-end ownership - from threat model and database schema through deployed edge infrastructure. I architect, implement, harden, and ship.

- **Security by design** - Every system is built with hardened auth, input validation, rate limiting, and CSRF protection from the first commit. Security is a design constraint, not a follow-up ticket.
- **Offensive and defensive** - I build the pentesting frameworks and the production systems they're designed to test. Understanding both sides produces better engineering on each.
- **Edge-native architecture** - Cloudflare Workers, D1, R2, and Durable Objects as the default runtime. Globally distributed, zero cold starts, no server management overhead.
- **AI-augmented workflows** - LLM integrations built with prompt caching, structured tool use, and streaming for security automation, intelligent reporting, and autonomous analysis at scale.
- **Production-grade standards** - Every feature includes structured error handling, observability, input validation, and deployment configuration. Nothing ships incomplete.

---

## Recent Additions

- **PM2 Popup Guard** - Windows daemon + daily sweep that kills stale Playwright/Explorer/Terminal popups before they knock PM2 services offline; 5 root-cause kill rules, CimInstance batch fetch for `~66ms` sweep
- **Finos** - web to desktop parity pass: 25 UI improvements, Tax screen, Settings nav, demo gate, CSP — identical dashboard layout across Next.js and Tauri surfaces
- **Resume API** - PDF footer stamping via pdf-lib + P0 security patches (auth bypass, path traversal, input validation)
- **Hermes** - autonomous agent integrated in WSL2 Ubuntu: Ollama provider, brain dump bridge, systemd service, live web dashboard
- **SIC** - standalone billing server with X-Billing-Key machine-to-machine auth; Sentry SDK init; P0 audit fixes
- **Hook Recovery** - Claude Code hook hardening kit: fixes token-guard re-read loops, silent write failures, post-compact blocked reads. 23-test suite, diagnostic CLI, one-line install

---

<div align="center">

[SIC](https://github.com/DevCraftXCoder/SIC) · [Finos](https://github.com/DevCraftXCoder/Finos) · [PDF Report Engine](https://github.com/DevCraftXCoder/PDF-Report-Engine) · [Growth Report AI](https://github.com/DevCraftXCoder/Growth-Report-AI) · [AttackMap](https://github.com/DevCraftXCoder/AttackMap)

</div>
