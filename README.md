<h1 align="center">Wanderson Leandro de Oliveira</h1>

<p align="center">
  <b>AI Security Engineer</b> &middot; LLM Application Security &middot; Agentic Systems &middot; Backend &amp; Cloud
</p>
<p align="center">
  Founder @ <a href="https://github.com/dewtech-technologies">Dewtech</a> &middot; Author of <a href="https://darelabs.tech">DARE Method</a> &middot; Belo Horizonte/MG &middot; Open to remote
</p>

<p align="center">
  <a href="mailto:wleandro.oliveira@gmail.com"><img src="https://img.shields.io/badge/email-wleandro.oliveira%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/wleandrooliveira"><img src="https://img.shields.io/badge/GitHub-wleandrooliveira-181717?style=flat-square&logo=github"/></a>
  <a href="https://darelabs.tech"><img src="https://img.shields.io/badge/darelabs.tech-5A67D8?style=flat-square"/></a>
  <a href="https://dewtech.tech"><img src="https://img.shields.io/badge/dewtech.tech-0070f3?style=flat-square"/></a>
</p>

---

## 👋 About

**AI Security Engineer** building production-grade security tooling for LLM applications and agentic systems. Author of **2 MCP servers on Anthropic's official registry**. 15+ years of backend, cloud and security engineering across enterprise telecom, retail, e-commerce and IoT.

I take **AI prototypes from notebook to production** with security-by-design: OWASP Top 10 controls, AES-256-GCM encryption, SSRF guards, audit logging. Multi-provider LLM routing (OpenAI, Anthropic, Gemini), **RAG** and **GraphRAG** (Neo4j + Qdrant), Kubernetes (OKE/GCP Cloud Run) — things ship with observability and controlled cost.

Portfolio operates as three GitHub orgs: [**dewtech-technologies**](https://github.com/dewtech-technologies) (parent), [**darelabs-tech**](https://github.com/darelabs-tech) (community & tooling for DARE Method) and [**fermio-technologies**](https://github.com/fermio-technologies) (AI Security products).

---

## 🧠 Focus Areas

- **AI Security** — MCP secure design, OWASP LLM Top 10, red teaming, RASP (Runtime Application Self-Protection), audit logging
- **LLM Applications** — agents, RAG, GraphRAG, tool calling, structured outputs
- **Vector / Graph Search** — Qdrant, Neo4j, ElasticSearch vector, semantic search
- **Agentic Engineering** — author of the **DARE Method** (Design, Architect, Review, Execute) &middot; community at [darelabs.tech](https://darelabs.tech)
- **Production AI** — multi-tenant, multi-provider routing, observability, cost control
- **Cloud Native** — Kubernetes (OKE), Cloud Run (GCP), GitOps, multi-cloud (AWS, OCI, GCP)

---

## 🚀 Featured Projects

### 🔹 tubemind-secure-mcp [![npm](https://img.shields.io/npm/v/tubemind-secure-mcp?style=flat-square&color=CB3837&logo=npm)](https://www.npmjs.com/package/tubemind-secure-mcp) [![downloads](https://img.shields.io/npm/dm/tubemind-secure-mcp?style=flat-square)](https://www.npmjs.com/package/tubemind-secure-mcp)
Open-source **Model Context Protocol** server bringing **YouTube intelligence** into Claude Desktop — **18 production tools** across search, video, channel analytics, benchmark, competitor research and content heuristics (CTR potential, retention signals, hook angles, content calendar). Backed by the official **YouTube Data API v3 + YouTube Analytics API** with **OAuth2** (Brand Account support). Secure by design: **AES-256-GCM** token encryption at rest, SSRF guard, rate limiting, audit logging, Zod-validated inputs — all mapped to **OWASP Top 10**. **Listed on the [official Anthropic MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=tubemind)** as `io.github.dewtech-technologies/tubemind-secure-mcp`. Install with `npx tubemind-secure-mcp`. → [tubemind.dewtech.tech](https://tubemind.dewtech.tech) · [github.com/dewtech-technologies/tubemind-secure-mcp](https://github.com/dewtech-technologies/tubemind-secure-mcp)

### 🔹 obsidian-mcp-secure [![npm](https://img.shields.io/npm/v/obsidian-mcp-secure?style=flat-square&color=CB3837&logo=npm)](https://www.npmjs.com/package/obsidian-mcp-secure) [![downloads](https://img.shields.io/npm/dm/obsidian-mcp-secure?style=flat-square)](https://www.npmjs.com/package/obsidian-mcp-secure) [![Smithery](https://smithery.ai/badge/wleandro-oliveira/obsidian-mcp-secure)](https://smithery.ai/servers/wleandro-oliveira/obsidian-mcp-secure)
Open-source **Model Context Protocol** server connecting Claude Desktop to Obsidian — 6 tools (read/list/create/edit/delete/search notes) with Zod validation and winston audit logging. Built from scratch with **OWASP Top 10 controls**: path traversal protection, input sanitization, API key via `.env` only, localhost-only enforcement, size limits. **Listed on the [official Anthropic MCP Registry](https://registry.modelcontextprotocol.io)** as `io.github.dewtech-technologies/obsidian-mcp-secure`. Install with `npx obsidian-mcp-secure`. → [github.com/dewtech-technologies/obsidian-mcp-secure](https://github.com/dewtech-technologies/obsidian-mcp-secure)

### 🔹 Fermio Platform
Multi-tenant AI agents platform (monorepo pnpm, NestJS 11 + Nuxt 3). Multi-provider routing across OpenAI, Anthropic Claude and Gemini. Apps: `api-agent-ai`, `orchestrator-api`, `chatbot-builder`, `atendimento-omnichannel`, `video-translator`, `synapse-process-audio` (FastAPI) and `code-assistant-vscode`.

### 🔹 Fermio Engineering Copilot
Generative AI for mechanical engineering. **GraphRAG** (Neo4j + Qdrant) over technical standards, parametric CAD generation with CadQuery/OpenCascade (STEP/STL), FEA (CalculiX) and CFD (OpenFOAM) pipelines. FastAPI + Nuxt 3 + Three.js (JWT-authenticated STL viewer).

### 🔹 Fermio Sec CLI
Open-source security CLI for AI pipelines under the **fermio-technologies** org. Ships alongside internal proprietary modules for **automated red-teaming** (OWASP LLM Top 10 — prompt injection, jailbreak fuzzing, tool-call exploitation) and **RASP** (Runtime Application Self-Protection) for LLM workloads in production. → [github.com/fermio-technologies/fermio-sec-cli](https://github.com/fermio-technologies/fermio-sec-cli)

### 🔹 DARE Framework [![npm](https://img.shields.io/npm/v/@dewtech/dare-cli?style=flat-square&color=CB3837&logo=npm&label=npm)](https://www.npmjs.com/package/@dewtech/dare-cli)
Open-source toolkit for **Agentic Engineering** implementing the DARE Method (Design, Architect, Review, Execute). Single-package CLI with **official-scaffold bootstrap** (Composer, NestJS, Vite, Cargo, FastAPI, Go) — optionally via **Docker images** when the host has no toolchain — **parallel DAG Task Runner** (Kahn's algorithm + live canvas), **mandatory Ralph Loop** (build/test/lint runs per task before DONE), embedded **GraphRAG engine** (SQLite/JSON/Neo4j HTTP) and an **MCP Server** for deep IDE integration (Cursor, Claude Code, Antigravity). 8 stacks supported: Rust/Axum, Node/NestJS, Python/FastAPI, PHP/Laravel, Go/Gin, Go/stdlib, React, Vue + MCP servers (TS/Python). Now with a **Rust-native rewrite** at [darelabs-tech/dare-cli](https://github.com/darelabs-tech/dare-cli). → [github.com/dewtech-technologies/dare-method](https://github.com/dewtech-technologies/dare-method)

### 🔹 DARE Labs — [darelabs.tech](https://darelabs.tech)
Official community platform for the DARE Method, built in **Ruby on Rails** and shipped to production. Technical libraries, hands-on labs, and verified engineering projects — the "how to build software with method, AI and security" hub for the DARE community. → [darelabs.tech](https://darelabs.tech)

### 🔹 fermio-gitops
Dedicated GitOps repo with Kubernetes manifests for **Oracle Kubernetes Engine (OKE)** — 12+ production apps, namespaces, secrets, Ingress Nginx, and infra (Postgres/Redis/Qdrant/Neo4j/RabbitMQ).

### 🔹 Document Quality Scoring API (Python to Rust)
Rewrote a Python scoring API in **Rust (Axum/Tokio)** with six heuristic modules — no heavy deps (no OpenCV/NumPy). Major throughput gain and memory reduction in production.

---

## 🛠️ Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Nuxt](https://img.shields.io/badge/-Nuxt%203-00DC82?style=flat-square&logo=nuxt.js&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Ruby on Rails](https://img.shields.io/badge/-Ruby%20on%20Rails-CC0000?style=flat-square&logo=rubyonrails&logoColor=white)
![.NET](https://img.shields.io/badge/-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)

![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Anthropic%20Claude-D97757?style=flat-square)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square)
![HuggingFace](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square)
![Neo4j](https://img.shields.io/badge/-Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)

![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/-Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

---

## 🏛️ Featured on

<p>
  <a href="https://registry.modelcontextprotocol.io/v0/servers?search=obsidian-mcp-secure">
    <img src="https://img.shields.io/badge/Anthropic_MCP_Registry-obsidian--mcp--secure-5A67D8?style=for-the-badge&logo=anthropic&logoColor=white" alt="Listed on official MCP Registry"/>
  </a>
  <a href="https://www.npmjs.com/package/obsidian-mcp-secure">
    <img src="https://img.shields.io/npm/dt/obsidian-mcp-secure?style=for-the-badge&label=npm%20total%20downloads&color=CB3837&logo=npm" alt="Total npm downloads obsidian-mcp-secure"/>
  </a>
  <a href="https://www.npmjs.com/package/@dewtech/dare-cli">
    <img src="https://img.shields.io/npm/v/@dewtech/dare-cli?style=for-the-badge&label=%40dewtech%2Fdare-cli&color=5A67D8&logo=npm&logoColor=white" alt="@dewtech/dare-cli version"/>
  </a>
  <a href="https://www.npmjs.com/package/@dewtech/dare-cli">
    <img src="https://img.shields.io/npm/dt/@dewtech/dare-cli?style=for-the-badge&label=npm%20total%20downloads&color=CB3837&logo=npm" alt="Total npm downloads dare-cli"/>
  </a>
  <a href="https://registry.modelcontextprotocol.io/v0/servers?search=tubemind-secure-mcp">
    <img src="https://img.shields.io/badge/Anthropic_MCP_Registry-tubemind--secure--mcp-5A67D8?style=for-the-badge&logo=anthropic&logoColor=white" alt="tubemind-secure-mcp on MCP Registry"/>
  </a>
  <a href="https://www.npmjs.com/package/tubemind-secure-mcp">
    <img src="https://img.shields.io/npm/dt/tubemind-secure-mcp?style=for-the-badge&label=npm%20total%20downloads&color=CB3837&logo=npm" alt="Total npm downloads tubemind-secure-mcp"/>
  </a>
</p>

## 📦 Latest shipping

| Date | What | Where |
|------|------|-------|
| 2026 | **darelabs.tech** — DARE Method community platform, shipped to production. Ruby on Rails backend + tailored front-end. | [darelabs.tech](https://darelabs.tech) |
| 2026 | **darelabs-tech/dare-cli** — Rust-native rewrite of the DARE CLI. | [GitHub](https://github.com/darelabs-tech/dare-cli) |
| 2026 | **fermio-technologies/fermio-sec-cli** — Open-source security CLI for AI pipelines. Companion for private modules (red-teaming, RASP) under `fermio-technologies`. | [GitHub](https://github.com/fermio-technologies/fermio-sec-cli) |
| May 2026 | **tubemind-secure-mcp v0.1.3** — Secure MCP server for YouTube intelligence: 18 tools (search, analytics, benchmark, heuristics, competitor research) for Claude Desktop, OAuth2 with Brand Account support, AES-256-GCM token encryption at rest, OWASP Top 10 controls. Listed on the official Anthropic MCP Registry as `io.github.dewtech-technologies/tubemind-secure-mcp`. | [npm](https://www.npmjs.com/package/tubemind-secure-mcp) · [MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=tubemind) · [GitHub](https://github.com/dewtech-technologies/tubemind-secure-mcp) |
| May 2026 | **@dewtech/dare-cli v2.9.0** — single-package CLI for the DARE Method: official-scaffold bootstrap (native or Docker), parallel DAG Task Runner with live canvas, mandatory Ralph Loop per task, GraphRAG (SQLite/JSON/Neo4j) and MCP Server. 8 backend/frontend stacks supported. | [npm](https://www.npmjs.com/package/@dewtech/dare-cli) · [GitHub](https://github.com/dewtech-technologies/dare-method) |
| Apr 2026 | **obsidian-mcp-secure v1.0.4** — secure MCP bridge for Obsidian | [npm](https://www.npmjs.com/package/obsidian-mcp-secure) · [MCP Registry](https://registry.modelcontextprotocol.io) · [GitHub](https://github.com/dewtech-technologies/obsidian-mcp-secure) |
| Mar 2026 | **Fermio Engineering Copilot** — GraphRAG + CAD generation for mechanical engineering | private |
| 2025-2026 | **Fermio Platform** — multi-tenant AI agents platform (NestJS + Nuxt 3) | private |
| 2024 | **Document Quality Scoring API** — Python to Rust rewrite (Axum/Tokio) | private |

---

## 📫 Let's talk

If you're building **LLM-powered products**, **agentic systems** or **RAG/GraphRAG pipelines** and want someone who can ship to production — reach out.

- 📧 wleandro.oliveira@gmail.com
- 🌎 Open to **remote** (global, timezone UTC-3 / BRT)
- 💼 **PJ** contracts via Dewtech or full-time
