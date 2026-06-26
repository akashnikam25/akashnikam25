# Hi there 👋, I'm Akash Nikam

## AI Engineer · Agentic AI, RAG & LLM Platforms

> Building AI agents and the production backends that ship them. Making engineering teams **50-70% faster**.

![Profile views](https://komarev.com/ghpvc/?username=akashnikam25&label=Profile%20views&color=0e75b6&style=flat)

---

### 🚀 What I'm Building

| Project | Description | Stack |
|---|---|---|
| **[Arken-AI](https://github.com/Arken-AI)** | Conversational AI platform for engineering design: Claude orchestration, a bounded multi-layer pipeline, real-time SSE streaming | Python, FastAPI, React/TS, LLMs |
| **[ZapBridge](https://github.com/akashnikam25/zapbridge)** | Event-driven GitHub-to-Slack integration: OAuth 2.0, HMAC webhooks, Redis idempotency, RQ worker, Claude agent | Python, FastAPI, Redis, Claude |
| **[Personal Agent](https://github.com/akashnikam25/personal-agent)** | Self-hosted AI assistant built on agentic patterns and MCP tooling | Python, MCP, Claude |

---

### 🛠️ Tech Stack

| Domain | Skills / Tools |
|---|---|
| **AI & Agents** | Agentic AI, Multi-Agent Systems, LangGraph, LangChain, MCP, RAG, LLM Evals, Prompt Engineering |
| **Retrieval** | Vector DBs (Qdrant), hybrid search (BM25 + dense, RRF), semantic search |
| **Backend** | Python, FastAPI, Go, gRPC, Protocol Buffers, REST, event-driven, microservices |
| **Frontend** | TypeScript, React, Vite |
| **Data** | Postgres, MongoDB, Redis, CouchDB, DynamoDB |
| **DevOps** | Docker, Kubernetes, GitHub Actions, CI/CD |

---

### 📈 Contribution Stats *(as of May 2026)*

| Metric | Count | Notes |
|---|---|---|
| ⭐ Total Stars Earned | 6+ | Public repos |
| 🔁 Total Commits (all time) | 190+ | Public + private org repos |
| 🔀 Total PRs Created | 39+ | Across personal + Arken-AI + SmartHireX |
| ✅ Total PRs Merged | 28+ | hx_design_engine(12), backend(4), frontend(4), SmartHireX(2+), personal(1+) |
| 👁️ Code Reviews Done | 4 | Arken-AI/backend, Arken-AI/frontend, SmartHireX |
| 🏢 Orgs Contributed To | 3 | @Arken-AI · @SmartHireX · @floss-fund |
| 🔥 Current Streak | Active | May 2026 |
| 📅 Total Contributions | 1,025+ | Last year (Aug 2022 - Present) |
| 🗓️ Longest Streak | 56 days | Dec 19, 2025 - Feb 12, 2026 |

---

### 💼 Experience

**Senior Software Engineer @ John Deere India Pvt. Ltd.** *(Oct 2023 - Present)*

- Architected a **12-agent AI platform** automating the full SDLC (epics, user stories, bug triage, code review, infra docs) with specialized agents (planner, developer, reviewer, static-analyzer, link-tester) on a durable **LangGraph** orchestration layer. Deployed across 3-4 teams, cutting engineering time **50-70%**.
- Integrated Azure DevOps and Confluence into GitHub Copilot via **MCP servers**: agents pull live Confluence context and write to ADO (epics, stories, bugs), turning Copilot into a context-aware, backlog-grounded project tool.
- Built a **code knowledge graph** that parses the codebase into a call/dependency graph, ranks the most important nodes with **PageRank**, and renders an interactive dependency visualization.
- Engineered a **graph-based RAG** retriever that grounds agents in real code by blending keyword search, PageRank importance, and graph-neighbor proximity, suppressing hallucination.
- Designed **durable, local-first execution** with a custom LangGraph checkpointer over SQLite: resumable, crash-safe agent runs with no central server.
- Wired agents into **automated quality gates** (lint, type-check, test, smoke-test, duplicate-detection) run by dedicated reviewer, static-analyzer, and link-tester agents as merge blockers.
- Rolled out the platform across 3-4 teams via hands-on KT, shifting engineers from writing to reviewing and validating AI output behind a structured quality-gate process.
- Built a real-time **machine visualization UI** from scratch with GitHub Copilot, delivered ~50% faster than the traditional estimate.
- Built a **production RAG platform**: 3-lane hybrid retrieval (Qdrant BM25 + dense + entity graph, RRF fusion) with correction and outcome boosting synced into the vector payload.
- Hardened it for production: **multi-tenant isolation** (RBAC, prompt-injection defence, append-only audit log), a cross-model **eval harness** (Opus + GPT-4o, >5% regression blocks CI), and a 6-layer fallback with zero silent failures.

**Member of Technical Staff @ Mavenir** *(Mar 2022 - Oct 2023)*

- Built a high-frequency **Go polling service**: polls CouchDB every 100ms, matches epoch-time triggers, dispatches notifications, and auto-expires entries, using goroutines and channels for concurrent, non-blocking delivery at telecom scale.
- Used **SingleStore** for distributed data storage across Go microservices in production: query model, distributed data patterns, and real-time performance.
- Designed versioned **OpenAPI specs** in Go, making APIs configurable across versions and cutting migration effort.
- Contributed to **NWDAF** on a Go microservice architecture deployed on **Kubernetes**: service-to-service APIs and distributed state management.

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
