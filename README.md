<h1 align="center">Wanderson Leandro de Oliveira</h1>

<p align="center">
  <b>Senior Security Engineer</b> &middot; Application Security (AppSec) &middot; Product Security &middot; AI Security &middot; DevSecOps
</p>
<p align="center">
  Security Engineer @ <a href="https://github.com/dewtech-technologies">Dewtech</a> &middot; Belo Horizonte, MG, Brazil (UTC&minus;3) &middot; Remote
</p>

<p align="center">
  <a href="mailto:wleandro.oliveira@gmail.com"><img src="https://img.shields.io/badge/email-wleandro.oliveira%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/wleandrooliveira"><img src="https://img.shields.io/badge/GitHub-wleandrooliveira-181717?style=flat-square&logo=github"/></a>
</p>

---

## 👋 About

**Senior Security Engineer** with 10+ years of software engineering experience, specializing in **Application Security (AppSec), Product Security, Secure SDLC, Offensive Security, DevSecOps and AI Security** across enterprise telecom, retail, e-commerce, IoT, banking, fintech and PCI-regulated environments.

I work across the full application-security lifecycle: **SAST, DAST, SCA, secure code review, threat modeling, vulnerability management, remediation guidance, risk-based security gates, secure architecture and CI/CD security**. My work includes detecting and classifying vulnerabilities, helping engineering teams remediate findings, prioritizing Critical/High risk, producing actionable security reporting and enforcing security controls across delivery pipelines.

Hands-on enterprise AppSec tooling includes **GitLab Security Pipelines, Veracode and Checkmarx**, with additional evaluation/POC experience using **Snyk and Black Duck**. I also build security automation and security tooling in Rust and Python.

My AI security work covers **LLM applications, MCP, agentic systems, prompt injection, authorization and policy validation, RASP, RAG/GraphRAG and secure tool use**. I build production-grade security tooling and AI systems with security-by-design, including OWASP controls, AES-256-GCM encryption, SSRF guards, audit logging, multi-provider LLM routing, Kubernetes and GitOps. I am the author of **2 MCP servers listed in the official MCP Registry**.

Technical work spans [**dewtech-technologies**](https://github.com/dewtech-technologies), [**darelabs-tech**](https://github.com/darelabs-tech) and [**fermio-technologies**](https://github.com/fermio-technologies), including enterprise AppSec, security tooling, applied AI security research and production systems.

---

## 🛡️ Enterprise Application Security

- **SAST / DAST / SCA** — vulnerability detection across source code, applications, dependencies and CI/CD pipelines
- **End-to-end vulnerability management** — detection, triage, risk classification, reporting, remediation guidance and follow-up with engineering teams
- **Risk-based security gates** — prioritization and enforcement focused on Critical and High severity findings
- **Secure code review** — security-focused review of application code, APIs and remediation changes
- **Threat modeling & secure architecture** — attack-surface analysis, trust boundaries, authorization risks and security-by-design decisions
- **Enterprise tooling** — GitLab Security Pipelines, Veracode and Checkmarx; security-tool evaluation/POCs with Snyk and Black Duck
- **Regulated environments** — engineering experience across banking, fintech and customer environments operating under PCI requirements

---

## 🧠 Focus Areas

- **Application Security (AppSec)** — SAST, DAST, SCA, Secure SDLC, secure code review, vulnerability remediation, threat modeling, OWASP Top 10, API and web security
- **Security Engineering** — security automation, secure architecture, CI/CD security, deterministic validation, auditability and policy enforcement
- **Offensive Security** — penetration testing, adversarial testing, red teaming, attack-path analysis and exploit-oriented validation
- **AI Security** — MCP secure design, OWASP LLM / Agentic Security, prompt injection, tool-use security, authorization, RASP and audit logging
- **DevSecOps & Cloud Security** — Kubernetes, GitOps, CI/CD, AWS, OCI, GCP, Cloud Run and OKE
- **Systems in Rust** — security tooling, agent runtimes and CLIs: static analysis with taint tracking, native AST parsing, embedded graph databases and DAG schedulers
- **LLM Applications** — agents, RAG, GraphRAG, tool calling, structured outputs and production observability
- **Agentic Engineering** — author of the **DARE Method** (Design, Architect, Review, Execute) &middot; community at [darelabs.tech](https://darelabs.tech)

---

## 🚀 Featured Security Projects

### 🔹 DARE Agent Security — Rust
**Deterministic adversarial validation and security conformance testing for AI agents and MCP systems.** Evidence-first by design: conclusions are backed by reproducible test vectors, deterministic expectations and machine-readable evidence for CI/CD — **not by an LLM acting as the final security judge**.

Scope includes MCP server/tool discovery, security baseline generation, **authorization and policy validation**, **AuthZEN / COAZ-MCP conformance vectors**, mappings to **OWASP Agentic Security**, controlled adversarial validation and agent/tool/resource attack-path modeling.

→ [github.com/darelabs-tech/dare-agent-security](https://github.com/darelabs-tech/dare-agent-security)

### 🔹 Fermio Sec CLI — Rust
Open-source **static analysis CLI written in Rust** for PHP codebases (Laravel, Symfony, WordPress). Taint analysis for command injection, SQL injection and XSS, deterministic findings with stable fingerprints, declarative rulepacks, **SARIF** output and baselines for CI adoption.

→ [github.com/fermio-technologies/fermio-sec-cli](https://github.com/fermio-technologies/fermio-sec-cli)

### 🔹 Nexora — AI-Assisted Offensive Security
Pentest platform with a **human pentester in the loop**. Automated red-teaming against the **OWASP LLM Top 10**, including prompt injection, jailbreak fuzzing and tool-call exploitation, with evidence-oriented security reporting. Python, Ruby and Rust.

### 🔹 AI Runtime Security (RASP)
**Runtime Application Self-Protection** for AI workloads in production. Rust core with Python and JavaScript instrumentation.

### 🔹 tubemind-secure-mcp
Open-source **Model Context Protocol** server bringing YouTube intelligence into Claude Desktop. Secure by design with **OAuth2, AES-256-GCM token encryption at rest, SSRF protection, rate limiting, audit logging and Zod-validated inputs**, mapped to OWASP Top 10 controls. Listed in the official MCP Registry.

→ [tubemind.dewtech.tech](https://tubemind.dewtech.tech) · [GitHub](https://github.com/dewtech-technologies/tubemind-secure-mcp) · [npm](https://www.npmjs.com/package/tubemind-secure-mcp)

### 🔹 obsidian-mcp-secure
Open-source MCP bridge for Obsidian with path traversal protection, input sanitization, localhost-only enforcement, API-key isolation, size limits and audit logging. Listed in the official MCP Registry.

→ [GitHub](https://github.com/dewtech-technologies/obsidian-mcp-secure) · [npm](https://www.npmjs.com/package/obsidian-mcp-secure)

---

## ⚙️ Software, AI & Systems Engineering

My security work is backed by hands-on software engineering rather than security tooling alone.

- **DARE Agent Coding Run Time — Rust** — agent execution runtime and evaluation harness with containerized sandboxes, verification tests and calibrated CI baselines
- **DARE Framework / DARE CLI** — agentic engineering toolkit with parallel DAG execution, deterministic build/test/lint verification, GraphRAG and MCP integration
- **DARE Swarm** — research on evolving multi-agent SLM topologies using deterministic engineering fitness functions instead of LLM-as-judge
- **DARE Synapse — C++ / CUDA** — Transformer architectures, training and inference runtimes built from first principles
- **Fermio Platform** — multi-tenant AI agents platform using NestJS, Nuxt, FastAPI and multi-provider LLM routing
- **Fermio Engineering Copilot** — GraphRAG + parametric CAD + FEA/CFD pipelines for mechanical engineering
- **Document Quality Scoring API** — production rewrite from Python to Rust/Axum/Tokio

---

## 🛠️ Stack

**Security:** SAST · DAST · SCA · Secure Code Review · Threat Modeling · Vulnerability Management · Secure SDLC · OWASP Top 10 · OWASP LLM / Agentic Security · Penetration Testing · Security Gates

**AppSec tooling:** GitLab Security Pipelines · Veracode · Checkmarx · Snyk (POC) · Black Duck (POC)

**Languages & frameworks:** Rust · Python · TypeScript · Node.js · NestJS · FastAPI · Nuxt · Ruby on Rails · Java · .NET

**AI / Agentic:** OpenAI · Anthropic · Gemini · MCP · RAG · GraphRAG · LangChain · Hugging Face · Qdrant · Neo4j

**Cloud & platform:** Kubernetes · Docker · GitOps · AWS · GCP · Oracle Cloud · PostgreSQL · Redis · Kafka

---

## 🏛️ Proof of Work

<p>
  <a href="https://registry.modelcontextprotocol.io/v0/servers?search=obsidian-mcp-secure">
    <img src="https://img.shields.io/badge/Official_MCP_Registry-obsidian--mcp--secure-5A67D8?style=for-the-badge" alt="Listed on official MCP Registry"/>
  </a>
  <a href="https://registry.modelcontextprotocol.io/v0/servers?search=tubemind-secure-mcp">
    <img src="https://img.shields.io/badge/Official_MCP_Registry-tubemind--secure--mcp-5A67D8?style=for-the-badge" alt="tubemind-secure-mcp on MCP Registry"/>
  </a>
  <a href="https://www.npmjs.com/package/@dewtech/dare-cli">
    <img src="https://img.shields.io/npm/dt/@dewtech/dare-cli?style=for-the-badge&label=%40dewtech%2Fdare-cli%20downloads&color=CB3837&logo=npm" alt="Total npm downloads dare-cli"/>
  </a>
</p>

### Selected public work

- [DARE Agent Security](https://github.com/darelabs-tech/dare-agent-security) — adversarial validation and security conformance for AI agents and MCP systems
- [Fermio Sec CLI](https://github.com/fermio-technologies/fermio-sec-cli) — Rust static analysis and taint-tracking CLI
- [tubemind-secure-mcp](https://github.com/dewtech-technologies/tubemind-secure-mcp) — production MCP server with security-by-design controls
- [obsidian-mcp-secure](https://github.com/dewtech-technologies/obsidian-mcp-secure) — secure local MCP integration
- [DARE CLI](https://github.com/darelabs-tech/dare-cli) — Rust-native agentic engineering CLI

---

## 📫 Let's talk

Open to selected opportunities in **Senior/Staff Security Engineering, Application Security (AppSec), Product Security, AI Security, AI/Agentic Security and Security Architecture**.

- 📧 wleandro.oliveira@gmail.com
- 🌎 Belo Horizonte, MG, Brazil (UTC-3 / BRT) · Remote
- 💼 Senior Security Engineer @ Dewtech
