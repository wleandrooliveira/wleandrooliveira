<h1 align="center">Wanderson Leandro de Oliveira</h1>

<p align="center">
  <b>Senior Security Engineer</b> &middot; Application Security &middot; Offensive Security &middot; AI Security
</p>
<p align="center">
  Security Engineer @ <a href="https://github.com/dewtech-technologies">Dewtech</a> &middot; Brazil (UTC&minus;3) &middot; Remote
</p>

<p align="center">
  <a href="mailto:wleandro.oliveira@gmail.com"><img src="https://img.shields.io/badge/email-wleandro.oliveira%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/wleandrooliveira"><img src="https://img.shields.io/badge/GitHub-wleandrooliveira-181717?style=flat-square&logo=github"/></a>
</p>

---

## 👋 About

**Senior Security Engineer** with 10+ years of software engineering experience, specializing in **Application Security (AppSec), Secure SDLC, Offensive Security, DevSecOps and AI Security** across enterprise telecom, retail, e-commerce and IoT environments.

I work across **SAST, DAST, vulnerability remediation, threat modeling, secure architecture, security automation and cloud-native security**, with hands-on engineering in Rust, Python and modern application stacks. My AI security work covers LLM applications, MCP, agentic systems, prompt injection, authorization and policy validation, RASP, RAG/GraphRAG and secure tool use.

I also build production-grade security tooling and AI systems with security-by-design: OWASP controls, AES-256-GCM encryption, SSRF guards, audit logging, multi-provider LLM routing (OpenAI, Anthropic, Gemini), Kubernetes and GitOps. I am the author of **2 MCP servers listed on Anthropic's official registry**.

Technical work spans [**dewtech-technologies**](https://github.com/dewtech-technologies), [**darelabs-tech**](https://github.com/darelabs-tech) and [**fermio-technologies**](https://github.com/fermio-technologies), including security tooling, applied AI security research and production systems.

---

## 🧠 Focus Areas

- **Application Security (AppSec)** — SAST, DAST, Secure SDLC, vulnerability remediation, threat modeling, OWASP Top 10, API and web security
- **Security Engineering** — security automation, secure architecture, CI/CD security, deterministic validation, auditability and policy enforcement
- **Offensive Security** — penetration testing, adversarial testing, red teaming, attack-path analysis and exploit-oriented validation
- **AI Security** — MCP secure design, OWASP LLM / Agentic Security, prompt injection, tool-use security, authorization, RASP and audit logging
- **DevSecOps & Cloud Security** — Kubernetes, GitOps, CI/CD, AWS, OCI, GCP, Cloud Run and OKE
- **Systems in Rust** — security tooling, agent runtimes and CLIs: static analysis with taint tracking, native AST parsing, embedded graph databases and DAG schedulers
- **LLM Applications** — agents, RAG, GraphRAG, tool calling, structured outputs and production observability
- **Agentic Engineering** — author of the **DARE Method** (Design, Architect, Review, Execute) &middot; community at [darelabs.tech](https://darelabs.tech)

---

## 🚀 Featured Projects

### 🔹 dare-agent-security — Rust
**Deterministic adversarial validation and security conformance testing for AI agents and MCP systems.** Evidence-first by design: conclusions are backed by reproducible test vectors, deterministic expectations and machine-readable evidence for CI/CD — **not by an LLM acting as the final security judge**. Scope: MCP server and tool discovery, security baseline generation, **authorization and policy validation**, **AuthZEN / COAZ-MCP conformance vectors**, mappings to **OWASP Agentic Security**, and agent/tool/resource attack-path modeling. → [github.com/darelabs-tech/dare-agent-security](https://github.com/darelabs-tech/dare-agent-security)

### 🔹 Fermio Sec CLI — Rust
Open-source **static analysis CLI written in Rust** for PHP codebases (Laravel, Symfony, WordPress). Taint analysis for command injection, SQL and XSS, **deterministic findings with stable fingerprints**, declarative rulepacks, **SARIF** output and baselines for CI adoption. Local-first — no application execution required. AGPL-3.0. → [github.com/fermio-technologies/fermio-sec-cli](https://github.com/fermio-technologies/fermio-sec-cli)

### 🔹 Dare Agent Coding Run Time — 100% Rust
Agent execution runtime and **evaluation harness**. Containerized sandboxes isolated from the harness, tasks defined as instruction + repository + verification test, calibrated baselines running in CI.

### 🔹 Nexora — AI-Assisted Offensive Security
Pentest platform with a **human pentester in the loop**. Automated red-teaming against the **OWASP LLM Top 10** — prompt injection, jailbreak fuzzing, tool-call exploitation — producing compliance-accepted reports. Python, Ruby and Rust.

### 🔹 AI Runtime Security (RASP)
**Runtime Application Self-Protection** for AI workloads in production. Rust core with Python and JavaScript instrumentation.

### 🔹 DARE Swarm — Applied Research
Automatic evolution of orchestration topologies for swarms of specialized SLMs (3B–14B). The distinguishing choice: the **fitness function is deterministic engineering verification** (build → test → lint → audit), **not an LLM-as-judge**. NSGA-II multi-objective search over quality, token cost and wall time. Systematic review of 21+ papers.

### 🔹 Dare Synapse — C++ / CUDA
Research and development of **scalable Transformer architectures, training and inference runtimes, and domain-specific language models built from first principles** in C++ and CUDA. Not my day-to-day area, but it is why I reason about models at the level of what training data actually does to them, not only how to call an API.

### 🔹 DARE Framework [![npm](https://img.shields.io/npm/v/@dewtech/dare-cli?style=flat-square&color=CB3837&logo=npm&label=npm)](https://www.npmjs.com/package/@dewtech/dare-cli)
Open-source toolkit for **Agentic Engineering** implementing the DARE Method (Design, Architect, Review, Execute). Single-package CLI with **official-scaffold bootstrap** (Composer, NestJS, Vite, Cargo, FastAPI, Go) — optionally via **Docker images** when the host has no toolchain — **parallel DAG Task Runner** (Kahn's algorithm + live canvas), **mandatory Ralph Loop** (build/test/lint runs per task before DONE), embedded **GraphRAG engine** (SQLite/JSON/Neo4j HTTP) and an **MCP Server** for deep IDE integration (Cursor, Claude Code, Antigravity). 8 stacks supported: Rust/Axum, Node/NestJS, Python/FastAPI, PHP/Laravel, Go/Gin, Go/stdlib, React, Vue + MCP servers (TS/Python). Now with a **Rust-native rewrite** at [darelabs-tech/dare-cli](https://github.com/darelabs-tech/dare-cli). → [github.com/dewtech-technologies/dare-method](https://github.com/dewtech-technologies/dare-method)

### 🔹 tubemind-secure-mcp [![npm](https://img.shields.io/npm/v/tubemind-secure-mcp?style=flat-square&color=CB3837&logo=npm)](https://www.npmjs.com/package/tubemind-secure-mcp) [![downloads](https://img.shields.io/npm/dm/tubemind-secure-mcp?style=flat-square)](https://www.npmjs.com/package/tubemind-secure-mcp)
Open-source **Model Context Protocol** server bringing **YouTube intelligence** into Claude Desktop — **18 production tools** across search, video, channel analytics, benchmark, competitor research and content heuristics (CTR potential, retention signals, hook angles, content calendar). Backed by the official **YouTube Data API v3 + YouTube Analytics API** with **OAuth2** (Brand Account support). Secure by design: **AES-256-GCM** token encryption at rest, SSRF guard, rate limiting, audit logging, Zod-validated inputs — all mapped to **OWASP Top 10**. **Listed on the [official Anthropic MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=tubemind)** as `io.github.dewtech-technologies/tubemind-secure-mcp`. Install with `npx tubemind-secure-mcp`. → [tubemind.dewtech.tech](https://tubemind.dewtech.tech) · [github.com/dewtech-technologies/tubemind-secure-mcp](https://github.com/dewtech-technologies/tubemind-secure-mcp)

### 🔹 obsidian-mcp-secure [![npm](https://img.shields.io/npm/v/obsidian-mcp-secure?style=flat-square&color=CB3837&logo=npm)](https://www.npmjs.com/package/obsidian-mcp-secure) [![downloads](https://img.shields.io/npm/dm/obsidian-mcp-secure?style=flat-square)](https://www.npmjs.com/package/obsidian-mcp-secure) [![Smithery](https://smithery.ai/badge/wleandro-oliveira/obsidian-mcp-secure)](https://smithery.ai/servers/wleandro-oliveira/obsidian-mcp-secure)
Open-source **Model Context Protocol** server connecting Claude Desktop to Obsidian — 6 tools (read/list/create/edit/delete/search notes) with Zod validation and winston audit logging. Built from scratch with **OWASP Top 10 controls**: path traversal protection, input sanitization, API key via `.env` only, localhost-only enforcement, size limits. **Listed on the [official Anthropic MCP Registry](https://registry.modelcontextprotocol.io)** as `io.github.dewtech-technologies/obsidian-mcp-secure`. Install with `npx obsidian-mcp-secure`. → [github.com/dewtech-technologies/obsidian-mcp-secure](https://github.com/dewtech-technologies/obsidian-mcp-secure)

### 🔹 Fermio Platform
Multi-tenant AI agents platform (monorepo pnpm, NestJS 11 + Nuxt 3). Multi-provider routing across OpenAI, Anthropic Claude and Gemini. Apps: `api-agent-ai`, `orchestrator-api`, `chatbot-builder`, `atendimento-omnichannel`, `video-translator`, `synapse-process-audio` (FastAPI) and `code-assistant-vscode`.

### 🔹 Fermio Engineering Copilot
Generative AI for mechanical engineering. **GraphRAG** (Neo4j + Qdrant) over technical standards, parametric CAD generation with CadQuery/OpenCascade (STEP/STL), FEA (CalculiX) and CFD (OpenFOAM) pipelines. FastAPI + Nuxt 3 + Three.js (JWT-authenticated STL viewer).

### 🔹 DARE Labs — [darelabs.tech](https://darelabs.tech)
Official community platform for the DARE Method, built in **Ruby on Rails** and shipped to production. Technical libraries, hands-on labs, and verified engineering projects — the "how to build software with method, AI and security" hub for the DARE community. → [darelabs.tech](https://darelabs.tech)

### 🔹 Document Quality Scoring API (Python to Rust)
Rewrote a Python scoring API in **Rust (Axum/Tokio)** with six heuristic modules — no heavy deps (no OpenCV/NumPy). Major throughput gain and memory reduction in production.

---

### 🔹 fermio-gitops
Dedicated GitOps repo with Kubernetes manifests for **Oracle Kubernetes Engine (OKE)** — 12+ production apps, namespaces, secrets, Ingress Nginx, and infra (Postgres/Redis/Qdrant/Neo4j/RabbitMQ).

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
| Aug 2026 | **darelabs-tech/dare-agent-security** — deterministic adversarial validation and security conformance testing for AI agents and MCP systems, in **Rust**. Authorization and policy validation, AuthZEN / COAZ-MCP conformance vectors, OWASP Agentic Security mappings, machine-readable evidence for CI/CD. | [GitHub](https://github.com/darelabs-tech/dare-agent-security) |
| Aug 2026 | **darelabs-tech/dare-swarm** — applied research on evolving multi-agent SLM topologies with a **deterministic engineering fitness function** (build → test → lint → audit) instead of an LLM-as-judge. NSGA-II over quality, token cost and wall time. | private |
| Aug 2026 | **darelabs-tech/dare-agent-coding-run-time** — agent execution runtime and evaluation harness, **100% Rust**. Containerized sandboxes isolated from the harness, tasks as instruction + repository + verification test, calibrated baselines in CI. | private |
| Aug 2026 | **fermio-technologies/ai-runtime-security-rasp** — Runtime Application Self-Protection for AI workloads in production. **Rust** core with Python and JavaScript instrumentation. | private |
| Aug 2026 | **dewtech-technologies/nexora-ai-offensive-security** — AI-assisted pentest platform with a human pentester in the loop. Automated red-teaming against the OWASP LLM Top 10, compliance-accepted reports. | private |
| Aug 2026 | **darelabs-tech/dare-synapse** — Transformer architectures, training and inference runtimes built from first principles in **C++ / CUDA**. | private |
| 2026 | **darelabs.tech** — DARE Method community platform, shipped to production. Ruby on Rails backend + tailored front-end. | [darelabs.tech](https://darelabs.tech) |
| 2026 | **darelabs-tech/dare-cli** — Rust-native rewrite of the DARE CLI. | [GitHub](https://github.com/darelabs-tech/dare-cli) |
| Jul 2026 | **fermio-technologies/fermio-sec-cli v0.1.0-rc.1** — static analysis CLI in **Rust** for PHP (Laravel, Symfony, WordPress). Taint analysis for command injection, SQL and XSS, deterministic findings with stable fingerprints, SARIF output and CI baselines. | [GitHub](https://github.com/fermio-technologies/fermio-sec-cli) |
| May 2026 | **tubemind-secure-mcp v0.1.3** — Secure MCP server for YouTube intelligence: 18 tools (search, analytics, benchmark, heuristics, competitor research) for Claude Desktop, OAuth2 with Brand Account support, AES-256-GCM token encryption at rest, OWASP Top 10 controls. Listed on the official Anthropic MCP Registry as `io.github.dewtech-technologies/tubemind-secure-mcp`. | [npm](https://www.npmjs.com/package/tubemind-secure-mcp) · [MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=tubemind) · [GitHub](https://github.com/dewtech-technologies/tubemind-secure-mcp) |
| May 2026 | **@dewtech/dare-cli v2.9.0** — single-package CLI for the DARE Method: official-scaffold bootstrap (native or Docker), parallel DAG Task Runner with live canvas, mandatory Ralph Loop per task, GraphRAG (SQLite/JSON/Neo4j) and MCP Server. 8 backend/frontend stacks supported. | [npm](https://www.npmjs.com/package/@dewtech/dare-cli) · [GitHub](https://github.com/dewtech-technologies/dare-method) |
| Apr 2026 | **obsidian-mcp-secure v1.0.4** — secure MCP bridge for Obsidian | [npm](https://www.npmjs.com/package/obsidian-mcp-secure) · [MCP Registry](https://registry.modelcontextprotocol.io) · [GitHub](https://github.com/dewtech-technologies/obsidian-mcp-secure) |
| Mar 2026 | **Fermio Engineering Copilot** — GraphRAG + CAD generation for mechanical engineering | private |
| 2025-2026 | **Fermio Platform** — multi-tenant AI agents platform (NestJS + Nuxt 3) | private |
| 2024 | **Document Quality Scoring API** — Python to Rust rewrite (Axum/Tokio) | private |

---

## 📫 Let's talk

Open to selected opportunities in **Security Engineering, Application Security (AppSec), Product Security, Offensive Security and AI Security**.

- 📧 wleandro.oliveira@gmail.com
- 🌎 Brazil (UTC-3 / BRT) · Remote
- 💼 Senior Security Engineer @ Dewtech