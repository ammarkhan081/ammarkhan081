<!--
  This file replaces the README in your special profile repo:
  github.com/ammarkhan081/ammarkhan081

  To use it: open that repo on GitHub, edit README.md, paste this in, commit.
  Anything wrapped in an HTML comment like this one is invisible once
  rendered on GitHub — it's just a note for you, safe to leave in place
  until you've filled in the real value, then delete the comment.
-->

# Ammar Ayaz

**AI Engineer · Agentic Systems · RAG · LLM Production Tooling**

I build AI systems that are meant to run in production — not just in demos. Most of what's below ships with tracing, evaluation, and audit logging built in from the start, not added afterward.

🟢 Open to full-time AI Engineer roles (remote or on-site) — available October 2026
🔧 Also taking on select automation projects for businesses — agentic systems, RAG pipelines, on-prem AI

<!-- TODO: once your portfolio site is deployed, add the link here, e.g.:
🌐 Portfolio: https://ammarayaz.dev -->

---

## Featured Projects

### 🤖 [ASHIA — Agentic AIOps Self-Healing Infrastructure](https://github.com/ammarkhan081/Agentic-AIOps-Platform-Self-Healing-Infrastructure-Agent)
A 6-agent closed-loop platform that detects anomalies across 12 live metrics in under 60 seconds, auto-resolves low-risk incidents without paging, and escalates risky changes for human sign-off — across 11 containerized services.
`LangGraph` `FastAPI` `React` `Docker` `PostgreSQL` `Redis` `Prometheus` `Loki` `Jaeger` `ChromaDB`

### 📊 [AI Evaluation & Reliability Platform](https://github.com/ammarkhan081/ai-evaluation-reliability-platform)
LLM observability platform unifying tracing, evaluation, and cost intelligence in one pipeline. A 3-stage hallucination cascade handles most evaluations before an LLM judge is ever invoked, keeping evaluation cost low at scale.
`FastAPI` `TimescaleDB` `OpenTelemetry` `RAGAS` `Celery` `Next.js` `Docker` `Kubernetes`

### 🎬 [YouTube Video Intelligence](https://github.com/ammarkhan081/yt-video-qa-enhanced)
Chrome extension delivering streamed, timestamp-cited answers about any YouTube video — first tokens arrive in under 1 second via Groq, across 12+ languages, without leaving the watch page.
`FastAPI` `Chrome Extension (MV3)` `Pinecone` `Groq (Llama-3.3-70B)` `yt-dlp` `RAGAS`

### 🔎 AI Research Analyst — *Agentic RAG*
Cited, RAGAS-evaluated answers from private document corpora. Routes ~10–15% of queries to an honest "insufficient evidence" response rather than generating from low-quality context.
`LangGraph` `ChromaDB` `BM25 + BGE hybrid retrieval` `Cross-encoder reranking` `Tavily` `MCP` `RAGAS`
> Private repo — happy to walk through the code on request.

### 🔐 Finance Sovereign Assistant — *On-Prem RAG*
Finance Q&A running 100% on-premise — zero cloud calls at runtime. QLoRA fine-tuned Mistral 7B with measurably improved domain faithfulness vs. the base model, and compliance guardrails mapped to specific EU AI Act requirements.
`Mistral 7B (QLoRA)` `Ollama` `FAISS` `LangGraph` `FastAPI` `RAGAS`
> Private repo — happy to walk through the code on request.

### 🧠 GRPO Reasoning Model — *RL Post-Training* `(in progress)`
Applying Group Relative Policy Optimization — the method behind DeepSeek-R1 — to teach a small open model (Qwen2.5-1.5B) to reason step-by-step on GSM8K, trainable on a single free Colab T4.
`GRPO (TRL)` `Unsloth` `Qwen2.5-1.5B` `QLoRA (4-bit)` `GSM8K`
> Training pipeline and reward design complete — base-vs-trained evaluation in progress.

---

## Stack

**AI & Agent Engineering** — LangGraph · LangChain · RAG · GPT-4o · Embeddings & Semantic Search · Function Calling · Prompt Evaluation · RL Post-Training (GRPO)

**Backend** — Python · FastAPI · PostgreSQL · Redis · REST & WebSockets · ChromaDB · FAISS · Pinecone

**Production & Reliability** — Docker · Docker Compose · GitHub Actions · OpenTelemetry · Prometheus · Loki · Jaeger · Grafana

**ML / Data** — PyTorch · TensorFlow · Hugging Face · TRL / Unsloth · scikit-learn · NLP

**Frontend** — React · Next.js · TypeScript · Tailwind CSS · Streamlit

---

## Get in touch

📧 [ammarkhan9903233@gmail.com](mailto:ammarkhan9903233@gmail.com)
<!-- TODO: once you claim your custom LinkedIn URL, update the link below -->
💼 [LinkedIn](https://linkedin.com/in/ammar-ayaz-980a3b375)
