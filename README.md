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

## Currently building

- **[rag-eval-lab](https://github.com/smitsohagiya/rag-eval-lab)**: an open eval harness that compares chunking, retrieval and re-ranking strategies for RAG and publishes the results.

## Stack

- **AI:** LangGraph, LangChain, LangSmith, Vercel AI SDK, OpenAI / Anthropic / Gemini APIs, pgvector, Pinecone
- **Backend:** Python (FastAPI), TypeScript (Node.js, NestJS, Express), PostgreSQL, MongoDB, Redis, Elasticsearch, Kafka, RabbitMQ
- **Frontend:** React, Next.js
- **Cloud and DevOps:** AWS, Azure, GCP, Docker, Kubernetes, GitHub Actions
