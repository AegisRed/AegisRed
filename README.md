<div align="center">

<img src="./img/ChatGPT%20Image%20May%203%2C%202026%2C%2009_39_20%20PM.png" width="100%" alt="Profile banner" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2600&pause=700&color=FF2D55&center=true&vCenter=true&width=900&lines=I+build+LLM+systems+that+survive+production.;Agents%2C+RAG%2C+streaming%2C+observability%2C+model+runtimes.;My+code+has+long-term+memory.+My+GPU+doesn%27t." alt="Typing introduction" />

<br/>

<a href="https://github.com/AegisRed">
  <img src="https://komarev.com/ghpvc/?username=AegisRed&style=for-the-badge&color=ff2d55&label=PROFILE+VIEWS" alt="Profile views" />
</a>
<a href="https://github.com/AegisRed?tab=followers">
  <img src="https://img.shields.io/github/followers/AegisRed?style=for-the-badge&logo=github&label=FOLLOWERS&color=ff2d55" alt="GitHub followers" />
</a>
<a href="https://github.com/AegisRed?tab=stars">
  <img src="https://img.shields.io/github/stars/AegisRed?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge&logo=github&label=STARS&color=ff2d55" alt="GitHub stars" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/FOCUS-PRODUCTION_LLM_SYSTEMS-111827?style=flat-square&labelColor=ff2d55" alt="Focus: production LLM systems" />
<img src="https://img.shields.io/badge/RUNTIME-RUST_%2B_PYTHON-111827?style=flat-square&labelColor=ff2d55" alt="Runtime: Rust and Python" />
<img src="https://img.shields.io/badge/AGENTS-MCP_%2B_DURABLE_WORKFLOWS-111827?style=flat-square&labelColor=ff2d55" alt="Agents: MCP and durable workflows" />
<img src="https://img.shields.io/badge/MODE-SHIPPING-111827?style=flat-square&labelColor=ff2d55" alt="Mode: shipping" />

</div>

<br/>

## Hey, I'm Vladyslav. I make models behave.

<img align="right" width="190" src="./img/a364360f92cedf34412751286fdd5924.png" alt="Right side character" />

I’m an AI/ML Engineer building production-oriented LLM systems, agent platforms, RAG and memory pipelines, streaming APIs, observability tooling, and model inference infrastructure.

I care about the parts that remain after the demo works: strict schemas, durable state, tool safety, provider fallbacks, latency and token attribution, tests, deployment, and honest failure modes.

<br clear="right"/>

---

## Current hunt

- Building **agent platforms** with provider routing, MCP tools, durable workflow traces, memory, and guarded execution
- Developing **Rust-first inference tooling**, graph execution, planners, bounded model streaming, and CPU decode paths
- Shipping systems around **FastAPI**, **React/TypeScript**, **PostgreSQL**, **Redis**, **Qdrant**, **Kafka**, and **Docker**
- Designing **RAG and multimodal workflows** that know when to answer, clarify, escalate, or stay quiet
- Turning messy human requests into strict JSON, reproducible decisions, queues, metrics, and production logs

> [!NOTE]
> **Current R&D:** MAHT — an experimental Rust-based runtime and memory architecture for running models beyond a simple load-everything-into-VRAM pipeline.

---

## Core stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,rust,ts,js,bash,fastapi,react,docker,linux,nginx,postgres,redis,sqlite,git,github,githubactions,pytorch&theme=dark" alt="Core technology stack" />

<br/><br/>

<img src="https://img.shields.io/badge/LLM_Agents-111827?style=for-the-badge&logoColor=white" alt="LLM agents" />
<img src="https://img.shields.io/badge/MCP-111827?style=for-the-badge&logoColor=white" alt="Model Context Protocol" />
<img src="https://img.shields.io/badge/RAG-111827?style=for-the-badge&logoColor=white" alt="Retrieval augmented generation" />
<img src="https://img.shields.io/badge/Qdrant-111827?style=for-the-badge&logoColor=white" alt="Qdrant" />
<img src="https://img.shields.io/badge/Kafka-111827?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/WebSockets-111827?style=for-the-badge&logo=socketdotio&logoColor=white" alt="WebSockets" />
<img src="https://img.shields.io/badge/vLLM-111827?style=for-the-badge&logoColor=white" alt="vLLM" />
<img src="https://img.shields.io/badge/RunPod-111827?style=for-the-badge&logoColor=white" alt="RunPod" />

</div>

---

## How I build systems

```mermaid
flowchart LR
    A[Product or human input] --> B[API and UI layer]
    B --> C[Validation and policy]
    C --> D[Workflow and tools]
    C --> E[RAG and memory]
    C --> F[LLM API or local runtime]
    D --> G[Grounded result]
    E --> G
    F --> G
    G --> H[Streaming response]
    H --> I[Traces, cost, latency and metrics]
```

---

## Featured engineering work

<table>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/lattice-agent-platform">Lattice Agent Platform</a></h3>

Observable AI-agent platform with runtime OpenAI, Gemini, and DeepSeek routing, executable goal workflows, MCP tools, durable traces, multi-layer memory, and a complete Docker topology.

<br/>

<img src="https://img.shields.io/badge/AI_Agents-111827?style=flat-square&logoColor=white" alt="AI agents" />
<img src="https://img.shields.io/badge/MCP-111827?style=flat-square&logoColor=white" alt="MCP" />
<img src="https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=00C7B7" alt="FastAPI" />
<img src="https://img.shields.io/badge/Qdrant-111827?style=flat-square&logoColor=white" alt="Qdrant" />

<br/><br/>

<a href="https://github.com/AegisRed/lattice-agent-platform"><b>Explore repository →</b></a>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/Flowka">Flowka</a></h3>

Kafka observability platform with realtime cluster health, consumer lag, message inspection, historical metrics, and a live Producer → Topic → Consumer graph.

<br/>

<img src="https://img.shields.io/badge/Kafka-111827?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=00C7B7" alt="FastAPI" />
<img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/WebSockets-111827?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets" />

<br/><br/>

<a href="https://github.com/AegisRed/Flowka"><b>Explore repository →</b></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/qa_guard_bot">QA Guard Bot</a></h3>

Telegram website monitor that runs deterministic Playwright checks first and uses Gemini only for bounded visual and semantic review, with scheduling, history, charts, and conservative alerts.

<br/>

<img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" />
<img src="https://img.shields.io/badge/Playwright-111827?style=flat-square&logo=playwright&logoColor=2EAD33" alt="Playwright" />
<img src="https://img.shields.io/badge/Gemini-111827?style=flat-square&logo=googlegemini&logoColor=8E75FF" alt="Gemini" />

<br/><br/>

<a href="https://github.com/AegisRed/qa_guard_bot"><b>Explore repository →</b></a>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/support_rag_bot">Support RAG Assistant</a></h3>

Grounded support triage with retrieval, server-side safety gates, audit logs, and explicit <code>answer</code>, <code>clarify</code>, or <code>handoff</code> decisions instead of confident guessing.

<br/>

<img src="https://img.shields.io/badge/RAG-111827?style=flat-square&logoColor=white" alt="RAG" />
<img src="https://img.shields.io/badge/Gemini-111827?style=flat-square&logo=googlegemini&logoColor=8E75FF" alt="Gemini" />
<img src="https://img.shields.io/badge/SQLite-111827?style=flat-square&logo=sqlite&logoColor=03A9F4" alt="SQLite" />

<br/><br/>

<a href="https://github.com/AegisRed/support_rag_bot"><b>Explore repository →</b></a>

</td>
</tr>
</table>

---

## More public work

| Project | What it demonstrates |
| --- | --- |
| [Lunaria Atelier](https://github.com/AegisRed/lunaria-patisserie) | FastAPI storefront, transactional SQLite orders, Docker/Nginx deployment, PWA and GitHub Pages demo |
| [Velora Travel](https://github.com/AegisRed/velora-travel) | React/TypeScript product UI, Express API, validation, tests, Docker and static fallback |
| [Travel Planner API](https://github.com/AegisRed/Test_task_Travel_Planning) | FastAPI, SQLAlchemy, external API validation, caching, business rules and pytest |
| [Daily Vibe Check](https://github.com/AegisRed/anvi_test_fullstack_task) | Compact React/Fastify CRUD product with tests and transparent mock analysis |
| [ODABA Gemini](https://github.com/AegisRed/odaba-gemini) | Responsive React/TypeScript Gemini workspace with streaming and local multi-chat state |
| [TGAI Chatbot](https://github.com/AegisRed/TGAI_chatbot) | Lightweight persona chatbot with persistent JSON memory and modular hooks |

Older coursework, game scripts, visual demos, and reference repositories remain public for history, but the projects above are the clearest representation of my current engineering level.

---

## What I like building

<table>
<tr>
<td width="50%" valign="top">

### Agent and LLM backends

Provider routing, durable workflows, tool execution, streaming output, retries, token accounting, strict schemas, and observable failure modes.

</td>
<td width="50%" valign="top">

### RAG and memory

Embeddings, semantic retrieval, long-term memory, grounded answers, confidence-aware escalation, and auditable decisions.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Runtime and infrastructure

Rust data planes, model streaming, CPU inference, Docker topologies, queues, caches, databases, and deployment tooling.

</td>
<td width="50%" valign="top">

### Product interfaces

React/TypeScript dashboards, realtime telemetry, admin tools, responsive layouts, and honest demo fallbacks.

</td>
</tr>
</table>

---

<img align="left" width="120" src="./img/441a4dd902acebc8071391f2a69594a3.png" alt="Left side character" />

<br clear="left"/>

---

## Contact

<div align="center">

<a href="https://www.linkedin.com/in/vladyslavrussu">
  <img src="https://img.shields.io/badge/LinkedIn-vladyslavrussu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://github.com/AegisRed">
  <img src="https://img.shields.io/badge/GitHub-AegisRed-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF2D55,100:0D1117&height=100&section=footer" width="100%" alt="Footer wave" />

</div>
