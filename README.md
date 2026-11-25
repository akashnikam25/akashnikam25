# Hi there 👋, I'm Akash Nikam

### AI Engineer · Agentic AI, RAG & MCP

> I build AI agents that engineers and technicians use every day, and the evaluation that keeps them honest.

Senior Software Engineer at **John Deere** (Pune, India). Open to AI Engineer and Forward Deployed roles.

[🌐 akashnikam.in](https://www.akashnikam.in) · [💼 LinkedIn](https://www.linkedin.com/in/akash-nikam-profile/) · [📄 Resume](https://www.akashnikam.in/Akash_Nikam_Resume.pdf) · [✉️ akashvnikam@gmail.com](mailto:akashvnikam@gmail.com)

![Profile views](https://komarev.com/ghpvc/?username=akashnikam25&label=Profile%20views&color=1d4ed8&style=flat)

---

### 📊 In production

| | |
|---|---|
| **500+** | engineers use the multi-agent developer assistant |
| **200+** | MCP tools that act as the signed-in user |
| **76% → 92%** | retrieval recall@10 on the maintenance copilot |
| **85% → 99%** | safety pass rate under a zero-failure release gate |

---

### 🏭 Work at John Deere

Described without internal names, data or code. Full write-ups are on my site.

**Multi-agent developer assistant** · 500+ engineers · [case study →](https://www.akashnikam.in/work/developer-assistant/)
One governed assistant in Slack, the CLI, VS Code and the web, on AWS Bedrock. A cheap hybrid router sends most requests to one specialist agent, 40 agents are built on reusable skills, and 200+ MCP tools act with the user's own permissions. An LLM-as-judge eval gate runs on every model, prompt and tool change.

**Plant-maintenance RAG copilot** · 30+ technicians · [case study →](https://www.akashnikam.in/work/maintenance-copilot/)
Grounded answers on shop-floor tablets from 500+ SOPs and 3,000+ work orders a year. Filter-first hybrid search and reranking on PostgreSQL + pgvector raised recall@10 from 76% to 92%. Guardrails run in code, and a release gate with zero safety failures took the safety pass rate from 85% to 99%. It says "no approved procedure found" instead of guessing.

**AI-assisted SDLC** · 30+ teams · [case study →](https://www.akashnikam.in/work/ai-assisted-sdlc/)
A governed VS Code extension that ships custom Copilot and Claude Code agents for business and technical context, epics, stories, plans, diff-scoped review and bug reports, with 3 MCP servers into Jira, Confluence and GitHub Enterprise.

---

### 🚀 Open source

| Project | What it is | Stack |
|---|---|---|
| **[Arken AI](https://github.com/Arken-AI)** · [case study](https://www.akashnikam.in/work/arken-ai/) | Turns plain-English requirements into audited heat-exchanger designs. Claude drives a 16-step engineering pipeline through YAML-defined tools and reviews each step, but deterministic math and hard engineering rules always win. Live progress streams over Redis Streams SSE. Co-built with [@PranitDhane](https://github.com/PranitDhane). | Python, FastAPI, Claude, Redis, MongoDB, React |
| **[ZapBridge](https://github.com/akashnikam25/zapbridge)** | GitHub-to-Slack event bridge: HMAC-verified webhooks, Redis idempotency so retries never double-post, an RQ queue with retries and a failed-job window, OAuth with Fernet-encrypted tokens, and Claude summaries. | Python, FastAPI, PostgreSQL, Redis, Claude |
| **[Personal Agent](https://github.com/akashnikam25/personal-agent)** | A schema that lets a coding agent (Claude Code, Copilot or Codex) maintain an interlinked Markdown knowledge base from dropped documents, using content hashes to detect changes. | Markdown, Bash, Python |

---

### 🛠️ Tech stack

| Area | Tools |
|---|---|
| **AI & agents** | Agentic AI, multi-agent systems, RAG, MCP, LLM evaluation (LLM-as-judge), context engineering, agent memory, guardrails, LangGraph, Strands SDK, AWS Bedrock, Claude Code |
| **Retrieval** | Hybrid search (BM25 + RRF), reranking, pgvector |
| **Backend** | Python, FastAPI, Go, REST, OpenAPI, microservices, Redis Streams, RQ |
| **Frontend** | React, TypeScript, JavaScript, SSE streaming |
| **Data** | PostgreSQL + pgvector, MySQL, MongoDB, Redis, CouchDB, SingleStore, FalkorDB |
| **Infra & ops** | Docker, Kubernetes, CI/CD, GitHub Actions, Langfuse |

---

### 💼 Experience

**Senior Software Engineer · John Deere** · *Oct 2023 – present · Pune*
AI agents and backend: the three systems above. Worked on site with technicians at a plant in Germany.

**Graduate Engineer → Member of Technical Staff I · Mavenir** · *Mar 2021 – Oct 2023*
Go microservices on Kubernetes for telecom analytics (NWDAF): a notification service polling every 100 ms with goroutines and channels, versioned OpenAPI specs, SingleStore for distributed storage.

**Education:** PG-DAC, Advanced Computing · B.Tech, Electronics & Telecommunication

---

### 🏆 Certifications

- **Claude with the Anthropic API** · Anthropic · 2026
- **Agent Skills** · Anthropic · 2026
- **Sub-Agents** · Anthropic · 2026

---

### 📈 GitHub activity

![GitHub stats](https://github-readme-stats.vercel.app/api?username=akashnikam25&show_icons=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=akashnikam25&layout=compact&hide_border=true)

---

### 💬 Ask me about

- Taking AI agents from demo to production, with real users and real permissions
- Evals and release gates that decide whether a change ships
- RAG that says "not found" instead of guessing
- MCP tools, tool calling and multi-agent routing

*I measure before I claim, and I'd rather say "I haven't built that yet" and go build it than fake my way through.*
