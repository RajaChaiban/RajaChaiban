# Hi, I'm Raja Chaiban 👋

**Finance × AI · New York**

I'm an engineer in New York building where finance and AI meet. Most of what I make starts with a workflow that's slow or manual and ends as a system that actually runs: an agent loop doing the work, a FastAPI/Node.js backend behind it, a Next.js front end on top, deployed on Vercel. I like owning the whole thing end to end, and I keep a human in the loop at the steps that can't be undone. And since I can't help rooting for my teams, a few of my repos are ML models trying to call games before they happen. ⚽ 🏀 🏈

---

## 🛠️ What I've Been Building

- **Agentic CRM** — multi-agent sourcing, enrichment, and outreach over a live Postgres CRM, with every model result re-validated before it touches the database.
- **Voice Agent** — real-time phone agent (streaming speech-to-text → LLM → text-to-speech) that qualifies callers, escalates emergencies, and books the appointment in under a second per turn.
- **KYC copilot** — parallel screening across dozens of public registries over MCP, rolled into one auditable risk score with a human gate on low-confidence cases.
- **Derivatives copilot** — multi-agent structuring that hands the pricing to QuantLib and Monte Carlo instead of trusting the model with the math.
- **MCP servers** — custom tools and data connectors (sports, finance, registries) that any AI assistant can call.
- **Predictive models** — XGBoost, logistic regression, and Monte Carlo for the World Cup, NBA Finals, Super Bowl, and college basketball.
- **Full-stack delivery** — Postgres and FastAPI behind, Next.js in front, and a Vercel preview URL for every branch so a change is clicked through before it merges.

---

## 💻 Tech Stack

**Core stack** — what I reach for most:

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

<details>
<summary><b>Full toolbox</b> — languages, AI/RAG, APIs, ML, backend, data, frontend, tooling</summary>

<br>

- **Languages** — `Python` · `TypeScript` · `JavaScript` · `Dart / Flutter` · `SQL` · `Jupyter` · `HTML/CSS`
- **AI / LLM & RAG** — `anthropic` · `openai` · `google-genai` · `langchain` · `mcp` · `sentence-transformers` · `chromadb` · `pinecone`
- **APIs & Integrations** — Anthropic · OpenAI · Gemini · VAPI (voice) · Telegram · Yahoo Finance · ESPN / sportsdataverse · X · Instagram · LinkedIn · YouTube · Pinecone — often wired together behind custom MCP servers
- **Machine Learning** — `numpy` · `pandas` · `scipy` · `scikit-learn` · `xgboost` · `lightgbm` · `pytorch` · `matplotlib` · `seaborn` · `plotly` · `joblib` · Monte Carlo simulation
- **Quant Finance** — `QuantLib` · `yfinance` · `nfl_data_py` · `sportsdataverse` · `cbbpy` — Black-Scholes, Greeks, barrier/knockout pricing
- **Backends & APIs** — `fastapi` · `uvicorn` · `flask` · `pydantic` · `sqlalchemy` · `sqlmodel` · `alembic` · `express` · `websockets`
- **Data & Infra** — `postgresql` · `asyncpg` · `redis` · `mongodb` · `docker`
- **Scraping & Automation** — `playwright` · `selenium` · `puppeteer` · `beautifulsoup4` · `httpx` · `aiohttp` · `requests`
- **Frontend & Deploy** — `next.js` · `react` · `vite` · `three.js` · `framer-motion` · `vercel` · `railway`
- **Dev Tooling** — `pytest` · `ruff` · `black` · `mypy` · `git` · `loguru` · `structlog`

</details>

---

## 🕸️ My Projects, as a Map

I turned everything below into an **interactive graph** — projects naturally cluster around the tools and models they share. Click a project to see what went into it, drag things around, or filter by area. It's the most fun way to get a feel for how my work connects.

[![Interactive Project Map](https://img.shields.io/badge/%F0%9F%97%BA%EF%B8%8F_Open_the_Interactive_Project_Map-2646D4?style=for-the-badge&labelColor=2646D4&color=2646D4)](https://rajachaiban.github.io/RajaChaiban/)

> 🔗 **Live:** https://rajachaiban.github.io/RajaChaiban/ — hosted free via GitHub Pages from the `/docs` folder of this repo.

---

## 🚀 A Few Things I've Built

A closer look at some of my favorite projects — click any repo to dig in.

| Project | What it does | Stack |
|---|---|---|
| [Finance_Agentic_Platform_Argo](https://github.com/RajaChaiban/Finance_Agentic_Platform_Argo) | S&P 500 knockout option pricer — Black-Scholes, Greeks, QuantLib validation | `Python` `QuantLib` `FastAPI` `NumPy` `Gemini` |
| [Predicting_WorldCup_2026](https://github.com/RajaChaiban/Predicting_WorldCup_2026) | XGBoost + logistic regression + Monte Carlo simulation to predict every World Cup game | `Python` `XGBoost` `scikit-learn` `pandas` |
| [CBB_Predictive_Dashboard](https://github.com/RajaChaiban/CBB_Predictive_Dashboard) | Dashboard powered by an MCP server and ML models to predict college basketball games | `Python` `MCP` `XGBoost` `Dash` `Plotly` |
| [MCP_College_Basketball](https://github.com/RajaChaiban/MCP_College_Basketball) | MCP server exposing college basketball data to AI models | `Python` `MCP` `aiohttp` `pandas` `ESPN API` |
| [SketchMotion](https://github.com/RajaChaiban/SketchMotion) | Turns prompts into hand-drawn animations and stylized sketches | `Python` `FastAPI` `Gemini` `Pillow` `Redis` |
| [Resume_Builder](https://github.com/RajaChaiban/Resume_Builder) | End-to-end platform that turns your resume into a visual | `TypeScript` `React` `Three.js` `Vite` |
| [Conversation_Transcription](https://github.com/RajaChaiban/Conversation_Transcription) | Mobile app for real-time transcription with on-device storage and AI summaries | `Dart` `Flutter` |
| [Finance_AI_Podcast](https://github.com/RajaChaiban/Finance_AI_Podcast) | Pipeline that fetches financial & AI news and turns it into a podcast | `Python` `Gemini` `PyTorch` `FastAPI` `Telegram` |
| [VoiceAgent](https://github.com/RajaChaiban/VoiceAgent) | AI voice agent for automated phone conversations | `Python` `VAPI` `websockets` |
| Agentic CRM System | AI agents that enrich contacts, prioritize outreach, and surface the next best action | `Python` `Claude` `MCP` `RAG` |
| Agentic KYC & Entity Search | Autonomously gathers and verifies public data, scores risk, human-in-the-loop review | `Python` `Gemini` `RAG` `Pinecone` |
| Agentic Automation Workflows | Agentic AI running business processes end-to-end with human-in-the-loop checkpoints | `Python` `Claude` `MCP` |

---

## 🔁 Loops

The "loop" is the heart of any agentic system — the logic that decides what the AI does next. Here are six I've designed and built, each one broken down in the showcase (including the parts that broke and how I fixed them).

**▶ [Walk through all six in the interactive showcase](https://claude.ai/code/artifact/78c9134d-a230-45e9-9473-5ea53d839c33)**

| # | Loop | Pattern | Stack |
|---|---|---|---|
| 1 | **Candidate Search** | Autonomous Claude tool-use loop over a live Postgres CRM — 6-turn cap, 200K-token budget, every returned ID re-validated server-side against the DB | `Claude Sonnet` `Postgres + pgvector` `Vercel` |
| 2 | **KYC Verification** | Orchestrator-worker fan-out — 26 parallel calls across 37 data sources, human-in-the-loop gate below 0.85 confidence, deterministic 100-point risk engine | `asyncio` `FastMCP` `Claude` |
| 3 | **ArgoPilot Structuring** | 7-agent derivatives pipeline as an explicit finite state machine with human gates and a $0.50/session cost ceiling, QuantLib-grounded across 18 product types | `QuantLib` `SSE` `Pydantic` |
| 4 | **Voice Pipeline** | Streaming STT → LLM → TTS with generation-ID barge-in, targeting sub-1s perceived latency on Twilio Media Streams | `Deepgram` `Cartesia` `Twilio` |
| 5 | **CBB MCP Server** | 18-tool FastMCP server with a resolver that capability-routes each call across 4 upstream sources under one MCP surface | `FastMCP` `Railway` |
| 6 | **DealFlow Analysis** | Sequential-then-parallel multi-agent PE document analysis → deterministic IC-memo synthesis with rule-based upgrades/downgrades | `Vision + text` `multi-agent` |

---

## 📫 Reach Me

- GitHub: [@RajaChaiban](https://github.com/RajaChaiban)
- LinkedIn: https://www.linkedin.com/in/rajachaiban
- Email: rajachaiban@gmail.com
