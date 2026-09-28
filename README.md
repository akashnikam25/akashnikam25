# Hi there 👋, I'm Akash Nikam

## AI Engineer · Agentic AI, RAG & LLM Platforms

> Building production AI agents, RAG pipelines, and the backend platforms that ship them.

![Profile views](https://komarev.com/ghpvc/?username=akashnikam25&label=Profile%20views&color=0e75b6&style=flat)

---

### 🚀 What I'm Building

| Project | Description | Stack |
|---|---|---|
| **[Arken-AI](https://github.com/Arken-AI)** | Conversational AI engineering platform: orchestration routes natural language to Claude via a YAML tool registry, a bounded 4-layer pipeline (deterministic calculation, hard-rule validation, Claude review, state accumulation), and real-time SSE over Redis Streams to a React UI | Python, FastAPI, React/TS, Claude |
| **[ZapBridge](https://github.com/akashnikam25/zapbridge)** | Event-driven GitHub-to-Slack agent platform: OAuth 2.0 (Fernet-encrypted), HMAC-SHA256 timing-safe webhook validation, Redis SETNX idempotency, an RQ async worker with retry/dead-letter handling, and a Claude summarization agent | Python, FastAPI, Redis, Claude |
| **[Personal Agent](https://github.com/akashnikam25/personal-agent)** | Self-hosted AI assistant built on agentic patterns and MCP tooling — an LLM-maintained knowledge base that ingests dropped documents into an interlinked, cross-referenced wiki | Python, MCP, Claude |

---

### 🛠️ Tech Stack

| Domain | Skills / Tools |
|---|---|
| **AI & Agents** | Agentic AI, Agentic RAG, Multi-Agent Systems, RAG, MCP, LLM-as-Judge Evaluation, LangGraph, LangChain, AWS Bedrock, Hybrid Search (BM25 + RRF), Vector Search (Qdrant / OpenSearch), Context & Prompt Engineering, AI Agent Governance |
| **Backend** | Python, FastAPI, Go, gRPC, Protocol Buffers, REST APIs, Microservices |
| **Frontend** | TypeScript, React + Vite, JavaScript, WebRTC, SSE / Streaming |
| **Databases** | Postgres, MongoDB, Redis, DynamoDB, CouchDB, Singlestore |
| **DevOps & Infra** | Docker, Kubernetes, Nginx, CI/CD, GitHub Actions |

---

### 📈 GitHub Activity

![Akash's GitHub stats](https://github-readme-stats.vercel.app/api?username=akashnikam25&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=akashnikam25&layout=compact&hide_border=true)

---

### 💼 Experience

**Senior Software Engineer @ John Deere India Pvt. Ltd.** *(Oct 2023 - Present, Pune, Hybrid)*

**EmbAI-ASCENT** — governed VS Code extension for the engineering SDLC:
- Built a governed extension distributing vetted "agent packs" via a custom CLI (Agent Package Manager), with 3 **MCP servers** (JIRA, Confluence, GitHub Enterprise) and 4 custom LM tools wired into Copilot Chat.
- Designed a **13-phase context-engineering** webview with keyword-scoring context assembly and session-state continuity, so engineers can resume multi-day planning threads without losing context.

**PlantIQ (Plant Brain)** — RAG copilot for plant-floor maintenance:
- Built an access-controlled **RAG copilot** for maintenance technicians: hybrid BM25 + dense retrieval fused via **Reciprocal Rank Fusion** over Docling-chunked SOPs, serving at **P95 268ms**.
- Hardened it with deterministic fail-closed guardrails (confidence gating), JWT-derived access scoping, and a CI-gated evaluation harness with dual **LLM-as-Judge** scoring (Claude Opus + GPT-4o).

**AI Developer Assistant Platform** — multi-agent agentic RAG on AWS Bedrock:
- Migrated a single-PDF chatbot into a **ReAct-based agentic RAG** system on **AWS Bedrock** across 7 knowledge bases.
- Built a **FalkorDB code knowledge graph** over 9 repositories and a multi-agent orchestration layer (Supervisor / Researcher / Coder / Writer).
- Shipped an **MCP server** exposing 40+ tools across Slack, CLI, web, and n8n, deployed on **EKS**.

**Member of Technical Staff @ Mavenir** *(Mar 2022 - Oct 2023)*

- Built a high-frequency **Go** service: polls CouchDB every 100ms, matches epoch-time triggers, dispatches notifications, and auto-expires entries using goroutines and channels for concurrent, non-blocking delivery at telecom scale.
- Used **Singlestore** for distributed data storage across Go microservices in production.
- Designed versioned **OpenAPI** specs in Go, cutting migration effort across API versions.
- Contributed to **NWDAF** on a Go microservice architecture deployed on **Kubernetes**.

---

### 🏆 Certifications

- 🤖 **Claude with the Anthropic API** · Anthropic *(2026)*
- 🤖 **Sub-Agent Skill** · Anthropic *(2026)*
- 🤖 **Agent Skill** · Anthropic *(2026)*

---

### 💬 Ask me about

- Building and shipping AI agents in production (not just prototypes)
- Agentic systems with Claude, MCP, and sub-agents
- RAG, vector search, and evals that prove it works
- Go microservices, gRPC, and event-driven backends

---

### 🤝 Connect with Me

- 🌐 Portfolio: [akashnikam25.github.io](https://akashnikam25.github.io)
- 💼 LinkedIn: [akash-nikam-profile](https://linkedin.com/in/akash-nikam-profile)
- 🐙 GitHub: [akashnikam25](https://github.com/akashnikam25)

---

*"I work at the intersection of backend engineering and applied AI: not as a researcher, but as someone who ships things and then builds the tooling that makes shipping faster."*
