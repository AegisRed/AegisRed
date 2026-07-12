<div align="center">

<img src="./img/ChatGPT%20Image%20May%203%2C%202026%2C%2009_39_20%20PM.png" width="100%" alt="Profile banner" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2600&pause=700&color=FF2D55&center=true&vCenter=true&width=900&lines=I+build+LLM+systems+that+survive+production.;RAG%2C+streaming%2C+queues%2C+cost+tracking%2C+GPU+deployments.;My+code+has+long-term+memory.+My+GPU+doesn%27t." alt="Typing SVG" />

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
<img src="https://img.shields.io/badge/MODE-SHIPPING-111827?style=flat-square&labelColor=ff2d55" alt="Mode: shipping" />
<img src="https://img.shields.io/badge/MEMORY-LONG_TERM-111827?style=flat-square&labelColor=ff2d55" alt="Memory: long term" />

</div>

<br/>

## Hey, I'm Vladyslav. I make models behave.

<img align="right" width="190" src="./img/a364360f92cedf34412751286fdd5924.png" alt="Right side character" />

I’m an AI/ML Engineer building production LLM systems: backend orchestration, RAG and memory pipelines, multimodal services, streaming APIs, and GPU inference.

I care about the parts demos usually hide — failure modes, observability, latency, cost, strict contracts, and what happens when the model confidently does something stupid.

<br clear="right"/>

---

## Current hunt

- Building **Rust-first model runtimes**, graph execution, planners, and inference tooling
- Shipping AI systems around **FastAPI**, **LLM APIs**, **local inference**, **RAG**, and **semantic memory**
- Deploying models with **Docker**, **RunPod**, **Ollama**, **vLLM**, and OpenAI-compatible APIs
- Designing assistants with **long-term memory**, **streaming responses**, **usage analytics**, and **admin dashboards**
- Turning messy human requests into strict JSON, filters, queues, and production logs
- Slowly making private AI experiments safe enough to drag into the light

> [!NOTE]
> **Current R&D:** MAHT — an experimental Rust-based runtime and memory architecture for working with models beyond a simple load-everything-into-VRAM pipeline.

---

## Languages I actually touch

<div align="center">

<img src="https://skillicons.dev/icons?i=python,rust,ts,js,bash,cs,php,postgres,sqlite&theme=dark" alt="Languages and data technologies" />

</div>

---

## Core stack

<div align="center">

<img src="https://skillicons.dev/icons?i=fastapi,docker,linux,nginx,postgres,redis,sqlite,git,github,githubactions,pytorch,opencv&theme=dark" alt="Core technology stack" />

<br/><br/>

<img src="https://img.shields.io/badge/FastAPI-111827?style=for-the-badge&logo=fastapi&logoColor=00C7B7" alt="FastAPI" />
<img src="https://img.shields.io/badge/aiogram-111827?style=for-the-badge&logo=telegram&logoColor=26A5E4" alt="aiogram" />
<img src="https://img.shields.io/badge/Qdrant-111827?style=for-the-badge&logoColor=white" alt="Qdrant" />
<img src="https://img.shields.io/badge/Ollama-111827?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
<img src="https://img.shields.io/badge/vLLM-111827?style=for-the-badge&logoColor=white" alt="vLLM" />
<img src="https://img.shields.io/badge/RunPod-111827?style=for-the-badge&logoColor=white" alt="RunPod" />
<img src="https://img.shields.io/badge/OpenAI_API-111827?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" />
<img src="https://img.shields.io/badge/RAG-111827?style=for-the-badge&logoColor=white" alt="RAG" />
<img src="https://img.shields.io/badge/WebSockets-111827?style=for-the-badge&logo=socketdotio&logoColor=white" alt="WebSockets" />
<img src="https://img.shields.io/badge/SSE-111827?style=for-the-badge&logoColor=white" alt="Server-Sent Events" />

</div>

---

## How I build AI systems

```mermaid
flowchart LR
    A[Human or product input] --> B[API and bot layer]
    B --> C[Validation and routing]
    C --> D[RAG and memory]
    C --> E[LLM API or local runtime]
    D --> F[Grounded generation]
    E --> F
    F --> G[Streaming output]
    G --> H[Logs, cost and metrics]
```

---

## Featured repos

<table>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/qa_guard_bot">QA Guard Bot</a></h3>

Production-style Telegram bot for continuous website QA. Deterministic checks run first; Gemini is used only for narrow visual and semantic review.

<br/>

<img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" />
<img src="https://img.shields.io/badge/Playwright-111827?style=flat-square&logo=playwright&logoColor=2EAD33" alt="Playwright" />
<img src="https://img.shields.io/badge/aiogram-111827?style=flat-square&logo=telegram&logoColor=26A5E4" alt="aiogram" />

<br/><br/>

<a href="https://github.com/AegisRed/qa_guard_bot"><b>Explore repository →</b></a>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/support_rag_bot">Support RAG Assistant</a></h3>

Grounded first-line support triage with explicit <code>answer</code>, <code>clarify</code>, and <code>handoff</code> decisions instead of confident guessing.

<br/>

<img src="https://img.shields.io/badge/RAG-111827?style=flat-square&logoColor=white" alt="RAG" />
<img src="https://img.shields.io/badge/Gemini-111827?style=flat-square&logo=googlegemini&logoColor=8E75FF" alt="Gemini" />
<img src="https://img.shields.io/badge/SQLite-111827?style=flat-square&logo=sqlite&logoColor=03A9F4" alt="SQLite" />

<br/><br/>

<a href="https://github.com/AegisRed/support_rag_bot"><b>Explore repository →</b></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/TGAI_chatbot">TGAI Chatbot</a></h3>

A lightweight persona chatbot with persistent memory, user profiling, modular memory hooks, and API-key rotation.

<br/>

<img src="https://img.shields.io/badge/Persistent_memory-111827?style=flat-square&logoColor=white" alt="Persistent memory" />
<img src="https://img.shields.io/badge/Gemini_API-111827?style=flat-square&logo=googlegemini&logoColor=8E75FF" alt="Gemini API" />

<br/><br/>

<a href="https://github.com/AegisRed/TGAI_chatbot"><b>Explore repository →</b></a>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/AegisRed/odaba-gemini">ODABA Gemini</a></h3>

A responsive React and TypeScript AI workspace with streaming responses, multi-chat management, themes, search, and exports.

<br/>

<img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
<img src="https://img.shields.io/badge/Streaming-111827?style=flat-square&logoColor=white" alt="Streaming" />

<br/><br/>

<a href="https://github.com/AegisRed/odaba-gemini"><b>Explore repository →</b></a>

</td>
</tr>
</table>

---

## Projects I like building

<table>
<tr>
<td width="50%" valign="top">

### AI backends

LLM orchestration, prompt routing, retry and fallback logic, token accounting, request queues, streaming output, and strict JSON schemas.

</td>
<td width="50%" valign="top">

### RAG & memory

Embeddings, semantic search, long-term memory, Qdrant and PostgreSQL retrieval, KB-grounded answers, and confidence-aware escalation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Multimodal systems

Vision extraction, OCR and caption pipelines, image-context analysis, text-model reasoning, and aggregator APIs.

</td>
<td width="50%" valign="top">

### Telegram AI products

aiogram bots, subscriptions, payments, admin panels, moderation flows, roleplay systems, and analytics dashboards.

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
