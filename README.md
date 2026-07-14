<div align="center">

# Hi, I'm Vinit Metange 👋

### AI Product Manager · 6 AI Products Shipped · Agentic AI · LLMs · 5G/Telecom
### Building production-grade AI systems that engineering teams ship and customers use

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vinit--metange-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/vinit-metange)
[![Location](https://img.shields.io/badge/Bengaluru%2C_India-FF6B35?style=for-the-badge&logo=google-maps&logoColor=white)](https://linkedin.com/in/vinit-metange)
[![Virasat](https://img.shields.io/badge/🏦_Virasat-Live-00C896?style=for-the-badge)](https://virasat.co.in)
[![ObsrvAI](https://img.shields.io/badge/🔍_ObsrvAI-Live-4F9EFF?style=for-the-badge)](https://obsrvai.com)
[![Arthavit](https://img.shields.io/badge/💬_Arthavit-Live-A855F7?style=for-the-badge)](https://arthavit.in)
[![Open to Work](https://img.shields.io/badge/Open%20to-AI%20PM%20Roles-00C851?style=for-the-badge)](https://linkedin.com/in/vinit-metange)

</div>

---

## About Me

AI PM with **18+ years** across Nokia, Netcracker, and IBM — and 6 AI products shipped in the last 18 months. I work at the intersection that is genuinely rare: deep enough in 5G/O-RAN/3GPP to design AI-native network functions AND deep enough in LLM architecture to own evals, agentic pipelines, and production cost strategy.

- Shipped 3 live production AI products (Virasat, ObsrvAI, Arthavit) solo — each in under a month
- Designed a 20-agent AI operating team running a company on shared state, zero headcount
- Published an npm SDK (`obsrvai-sdk`) tracking tokens, cost, and latency across 50 LLM models
- Built the AI-Telecom Brief — a practitioner newsletter covering 5G, O-RAN, and agentic NOC at spec depth
- **30%+ cost reduction** through AI automation at Netcracker
- **40% revenue growth** via platform modernization at Nokia
- **4x consecutive quarterly awards** for customer value delivery

> *"I translate technical complexity into scalable products that engineering teams can build and customers love."*

---

## 6 AI Products Shipped

### 🏦 [Virasat](https://virasat.co.in) — Financial Intelligence Platform for Indian Families
> `Next.js 14` · `TypeScript` · `Supabase` · `Anthropic Claude` · `Vercel` · `Razorpay`

| Metric | Value |
|---|---|
| Tests Passing | **4,591** |
| AI Specialist Agents | **11** |
| RLS-Protected DB Tables | **54** |
| AI Golden Evals | **52** |
| Asset Classes | **9** |
| Feature Flags | **34** |
| Live Cron Jobs | **6** |
| TypeScript / ESLint Errors | **0** |

- Full agentic loop: intent classification → RAG → tool execution → 4-stage eval pipeline (PII guard, injection guard, SEBI compliance, factual accuracy)
- CAS PDF parser built from scratch (CDSL, NSDL, CAMS, KFintech) — 100% local, zero financial data sent externally
- WhatsApp agent with 20 intent classifiers sharing the same 11 specialist agents
- Razorpay 4-tier subscription billing, invite-only beta, full growth instrumentation

---

### 🔍 [ObsrvAI](https://obsrvai.com) — AI Observability & BI Platform · Published npm SDK
> `Turborepo` · `Fastify` · `TimescaleDB` · `Redis` · `Next.js 14` · `Anthropic Claude`

- Published npm SDK (`obsrvai-sdk`) — wraps Anthropic + OpenAI for auto-capture of tokens, cost, latency, quality, and hallucinations. **50 models** supported
- Full agent session tracing: tool calls, RAG retrieval, memory reads/writes, multi-agent coordination
- Multi-tenant architecture with monthly-partitioned TimescaleDB, SHA-256 API key auth
- 11 PDF report types including founder and investor reports. Self-hostable via Docker Compose

---

### 💬 [Arthavit](https://arthavit.in) — WhatsApp-Native Expense Tracking & Group Events
> `FastAPI` · `LangGraph` · `GPT-4o` · `Next.js 14` · `Supabase` · `Twilio` · `Razorpay`

- LangGraph state machine with **18 tools**, 20-message conversation memory, dynamic prompt injection per user
- Group event RBAC: **5 roles, 9 permissions** — designed upfront, not retrofitted
- Receipt OCR via GPT-4o vision — WhatsApp image → expense logged automatically
- **427 tests** (338 backend + 89 frontend), debt-minimisation splitting algorithm

---

### 📈 AlphaScreener — Multi-Signal AI Trading Agent
> `LangChain` · `Python` · `TA-Lib` · `FastAPI`

- 500-stock screener with multi-signal AI analysis: momentum, fundamentals, sentiment, technicals
- Automated trade execution pipeline with risk controls and position sizing logic

---

### 🏗️ [AI Product Blueprint](https://github.com/VinitMetange/ai-product-blueprint) — AI Operating System for Product Teams
> `Docs` · `Python` · `Claude Code`

- 62 slash commands covering engineering, product, ops, customer, marketing, and sales functions
- 20-agent team running on shared state files: `TICKETS.md` · `AGENTLOG.md` · `ESCALATIONS.md`
- Battle-tested patterns from building the three production products above

---

### 🎬 [n8n Content Creation Pipeline](https://github.com/VinitMetange/n8n-content-creation-pipeline)
> `n8n` · `Perplexity` · `HeyGen` · `YouTube API`

- End-to-end AI content pipeline: research → scripting → video generation → YouTube upload — fully automated

---

## 🤖 20-Agent AI Operating Team

A complete AI product company operating system — zero headcount, one slash command away:

| Division | Agents |
|---|---|
| Engineering | `/tech-lead` · `/qa` · `/investigate` · `/security` · `/test-architect` · `/performance` |
| Operations | `/devops` · `/error-monitor` · `/data-analyst` |
| Product | `/triage` · `/product` · `/growth` |
| Customer | `/handle-support` · `/crm` · `/customer-success` |
| Marketing | `/content` · `/email-campaign` · `/social` |
| Sales | `/leads` · `/conversion` |

Shared state: `TICKETS.md` · `AGENTLOG.md` · `ESCALATIONS.md` · `WEEKLYDIGEST.md` · `DAILYREPORT.md`

---

## 📚 Field Guides & Reference (Public Knowledge Base)

Practitioner-level reference guides built for AI PMs, engineers, and telecom architects:

| Guide | Description | Link |
|---|---|---|
| 📡 Telecom 5G/OSS/BSS Field Guide | Complete reference: OSS/BSS, 5G Core, O-RAN, AI-native network functions, agentic NOC | [Repo](https://github.com/VinitMetange/Telecom_5G_OSS_BSS_Field_Guide) |
| 🏗️ Production Agentic Blueprint | Stack-agnostic 8-layer blueprint for production agentic AI (AWS/GCP/Azure/Anthropic/OpenAI) | [Repo](https://github.com/VinitMetange/The-Production-Agentic-Blueprint) |
| 🤖 AI PM Field Guide | Every skill, framework, template, and tool an AI PM needs — strategy to shipping | [Repo](https://github.com/VinitMetange/The_AI_PM_Field_Guide) |
| 📦 AI Production Readiness Guide | 9 disciplines for production AI: cost governance, evals, observability, safety, RAG, LLMOps | [Repo](https://github.com/VinitMetange/The_AI_Production_Readiness_Guide) |
| ⚡ Agentic Optimization Strategies | Token reduction, cost cutting, and latency engineering in LLM-powered agentic systems | [Repo](https://github.com/VinitMetange/Agentic_Optimization_Strategies_Guide) |
| 🧠 Agentic AI Context Engineering | 5-layer context architecture, compression pipelines, memory tiers, multi-agent handoff | [Repo](https://github.com/VinitMetange/agentic-ai-context-engineering) |
| 🪙 Token Intelligence Guide | Complete reference for token usage, cost, and optimization across LLM architectures | [Repo](https://github.com/VinitMetange/token-intelligence-guide) |
| ☁️ Cloud Platforms Field Guide | AWS, Azure, GCP — every service explained, every trade-off quantified | [Repo](https://github.com/VinitMetange/The_Cloud_Platforms_Field_Guide) |
| 📋 Product Management Full Guide | Zero to senior PM: frameworks, mental models, case studies — with GitHub Pages | [Repo](https://github.com/VinitMetange/Product-Management-Full_Guide) · [Site](https://vinitmetange.github.io/Product-Management-Full_Guide/) |
| 🤖 Agentic AI Guide | 24-topic field guide for building production agent systems, cost calculators, launch checklists | [Repo](https://github.com/VinitMetange/Agentic_Ai_Guide) |

---

## 🏗️ Full Repository Portfolio

| Repository | Description | Stack | Status |
|---|---|---|---|
| [Virasat](https://github.com/VinitMetange/Virasat) | Financial intelligence platform — 11 AI agents, 4,591 tests, WhatsApp agent | Next.js 14, Claude | 🟢 Live |
| [ObsrvAI](https://github.com/VinitMetange/obsrvai) | AI observability platform, published npm SDK, 50 models | Turborepo, Fastify, TimescaleDB | 🟢 Live |
| [Arthavit](https://github.com/VinitMetange/spendwise-ai-agent) | WhatsApp expense tracking, LangGraph state machine, 427 tests | FastAPI, LangGraph, GPT-4o | 🟢 Live |
| [ai-product-blueprint](https://github.com/VinitMetange/ai-product-blueprint) | 62 slash commands + 20-agent operating team patterns | Docs, Claude Code | 🟢 Active |
| [Telecom_5G_OSS_BSS_Field_Guide](https://github.com/VinitMetange/Telecom_5G_OSS_BSS_Field_Guide) | OSS/BSS/5G Core/O-RAN/AI-in-Telecom practitioner reference | HTML | 🆕 New |
| [The-Production-Agentic-Blueprint](https://github.com/VinitMetange/The-Production-Agentic-Blueprint) | Stack-agnostic 8-layer production agentic AI blueprint | HTML | 🆕 New |
| [The_AI_PM_Field_Guide](https://github.com/VinitMetange/The_AI_PM_Field_Guide) | AI PM skills, frameworks, and templates from strategy to shipping | HTML | 🆕 New |
| [The_AI_Production_Readiness_Guide](https://github.com/VinitMetange/The_AI_Production_Readiness_Guide) | 9 disciplines for shipping production AI systems | HTML | 🆕 New |
| [Agentic_Optimization_Strategies_Guide](https://github.com/VinitMetange/Agentic_Optimization_Strategies_Guide) | Token, cost, and latency optimization for agentic systems | HTML | 🆕 New |
| [agentic-ai-context-engineering](https://github.com/VinitMetange/agentic-ai-context-engineering) | Context architecture, memory tiers, multi-agent handoff protocols | Python, LangGraph | ✅ Public |
| [ai-insurance-claims-agent](https://github.com/VinitMetange/ai-insurance-claims-agent) | ISB Capstone: multi-agent claims processing, 40% manual review reduction | LangChain, Python | ✅ Public |
| [rag-knowledge-assistant](https://github.com/VinitMetange/rag-knowledge-assistant) | RAG enterprise knowledge assistant, 20% support cost reduction | LangChain, FastAPI | ✅ Public |
| [n8n-content-creation-pipeline](https://github.com/VinitMetange/n8n-content-creation-pipeline) | End-to-end AI video/content pipeline (Perplexity + HeyGen + YouTube) | n8n, AI APIs | ✅ Public |

---

## 🏗️ Technical Stack

- **AI / Agents:** Claude Code, LangGraph, LangChain, GPT-4o, AWS Bedrock, Anthropic Claude, Strands
- **Data & Search:** pgvector, FAISS, OpenSearch, TimescaleDB, Vector Databases
- **Full-Stack:** Next.js 14, TypeScript strict, FastAPI, Python, Node.js, Turborepo
- **Infrastructure:** Supabase, Vercel, Railway, Docker, Kubernetes, GitHub Actions CI
- **Telecom:** 3GPP TS 23.288 (NWDAF), O-RAN WG2 (A1/E2 interfaces), OSS/BSS, 5G Core NFs
- **Cloud:** AWS Certified, GCP, Azure
- **Automation:** n8n, 62+ slash commands, 20-agent operating team
- **Security:** AES-256-GCM, RLS, CSP nonce, SECURITY DEFINER, Upstash rate limiting

---

## 🏆 Professional Experience

| Company | Role | Impact |
|---|---|---|
| **Netcracker Technology** (2023–Present) | PM / Senior PO | Multi-agent AI architecture, SAFe governance, 4x on-time delivery, AI Webex assistant |
| **Nokia** (2021–2023) | Technical PM — Shared Data Layer | 40% revenue growth, RAG assistant (30% productivity gain), Nokia Leadership Award |
| **Nokia** (2017–2021) | RD Product Owner / PM | Cloud-native migration, 100M subscribers, Performer of the Year |
| **IBM India** (2010–2014) | Senior RD Developer | Data privacy & encryption, 99% breach risk reduction |

---

## 🎓 Education & Certifications

- **Post Graduate Certificate in Product Management** — Kellogg School of Management, Northwestern University (2023)
- **Leadership with Artificial Intelligence** — Indian School of Business (ISB), 2025
- **Claude Code in Action** — Anthropic Certified
- **AWS Certified Cloud Practitioner**
- **SAFe Certified Agilist**
- **56+ total certifications** across AI, Cloud, Product, and Telecom — [view all](https://github.com/VinitMetange/professional-certifications)

---

## 📣 Content & Recognition

| Category | Description | Link |
|---|---|---|
| **AI-Telecom Brief** | Practitioner newsletter: 5G/O-RAN/agentic network ops at spec level | [LinkedIn](https://linkedin.com/in/vinit-metange) |
| **Articles** | AI PM, RAG, agentic AI, and product strategy — 50+ published pieces | [linkedin-articles](https://github.com/VinitMetange/linkedin-articles-and-insights) |
| **Presentations** | Eduinx webinar: *Building AI Products from Idea to Deployment*, industry talks | [presentations](https://github.com/VinitMetange/presentations-and-talks) |
| **Awards** | Netcracker Above & Beyond (2024, 2025), Nokia Leadership Award (2022) | [awards](https://github.com/VinitMetange/awards-and-recognition) |
| **Certifications** | 56+ professional certifications in AI, Cloud, Product, and Telecom | [certifications](https://github.com/VinitMetange/professional-certifications) |

---

## 🤝 Connect

- **LinkedIn:** [linkedin.com/in/vinit-metange](https://linkedin.com/in/vinit-metange)
- **Email:** vinit.metange30@gmail.com
- **Virasat:** [virasat.co.in](https://virasat.co.in)
- **ObsrvAI:** [obsrvai.com](https://obsrvai.com)
- **Arthavit:** [arthavit.in](https://arthavit.in)

---

*"Building at the intersection of AI systems and product thinking — where specs meet shipping."*
