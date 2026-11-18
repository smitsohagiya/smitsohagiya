# Smit Sohagiya

**Lead Software Engineer · AI Expert**

Technical lead on a healthcare AI product for a US client.
I build LLM apps, RAG pipelines and agent workflows in Python and TypeScript.

[LinkedIn](https://www.linkedin.com/in/smit-sohagiya/) · [X](https://x.com/smit_sohagiya) · [Email](mailto:smitsohagiya81@gmail.com)

## What I work on

- **Agents with a human in the loop.** I built a LangGraph pipeline that reads clinical notes, extracts signals and scores risk. Structured outputs and fixed thresholds keep it predictable, and a human approval step comes before any alert reaches a care team.
- **RAG that is measured, not guessed.** We raised RAG answer accuracy by about 50% by testing prompt, chunking, retrieval and re-ranking changes against an offline eval set of about 100 questions.
- **One layer over many models.** A multi-LLM layer across OpenAI, Anthropic and Gemini with routing, provider fallbacks, streaming, per-tenant token budgets and cost tracking.
- **Backends that hold up.** Earlier, I tuned database hot paths so a SaaS platform handled 3x user growth with no infrastructure changes, and I stopped random outages caused by a flood of WhatsApp delivery callbacks with a Redis buffer and batched inserts.

I lead a team of 10-20 engineers and clinical reviewers, and I have nearly 5 years of professional experience.

## Featured projects

- **[rag-eval-lab](https://github.com/smitsohagiya/rag-eval-lab)**: an eval harness that compares chunking, retrieval and re-ranking for RAG on public docs. The best setup (hybrid search with a cross-encoder re-ranker) finds a relevant chunk in the top 5 for 97 of 100 questions, and re-ranking was the biggest single gain.
- **[ticket-triage-agent](https://github.com/smitsohagiya/ticket-triage-agent)**: a LangGraph agent that triages support tickets, with PII redaction, prompt-injection checks, a human approval step and safety gates in CI. Every security and injection ticket reaches a person, with the rules baseline or a local 3B model.
- **[llm-gateway](https://github.com/smitsohagiya/llm-gateway)**: one OpenAI-compatible API over OpenAI, Anthropic, Gemini and Ollama, with fallbacks, a circuit breaker, per-tenant token budgets, caching, Prometheus metrics and Kubernetes manifests.
- **[docs-mcp](https://github.com/smitsohagiya/docs-mcp)**: an MCP server that gives Claude Code, Claude Desktop or Cursor cited search over any folder of markdown docs. BM25 over heading sections, with no model or API key, in about half a millisecond per query.
- **[til](https://github.com/smitsohagiya/til)**: short notes on things I learn while building.

## Stack

- **AI:** LangGraph, LangChain, LangSmith, Vercel AI SDK, OpenAI / Anthropic / Gemini APIs, MCP, Ollama, pgvector, Pinecone
- **Backend:** Python (FastAPI), TypeScript (Node.js, NestJS, Express), PostgreSQL, MongoDB, Redis, Elasticsearch, Kafka, RabbitMQ
- **Frontend:** React, Next.js
- **Cloud and DevOps:** AWS, Azure, GCP, Docker, Kubernetes, GitHub Actions
