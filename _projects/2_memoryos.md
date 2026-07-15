---
layout: page
title: MemoryOS
description: Three-tier memory backend for LLM agents
importance: 2
category: work
github: https://github.com/Auntara12/memoryos
---

**MemoryOS** is a production-grade three-tier memory backend for LLM agents, combining Redis, PostgreSQL, and FAISS with importance-scored promotion between tiers so agents can persist and recall context across sessions.

**Highlights:**
- 8 REST endpoints; 3 MCP tools exposed for native Claude integration
- 384-dim FAISS retrieval; nightly Celery pipeline clusters and LLM-summarizes episodic memories per agent
- Containerized 5-service Docker stack with Alembic migrations and CI
- Sub-100ms end-to-end semantic query latency

**Stack:** Python, FastAPI, PostgreSQL, Redis, FAISS, MCP

Code on [GitHub](https://github.com/Auntara12/memoryos).
