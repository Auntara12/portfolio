---
layout: page
title: Protein Intelligence Platform
description: Full-stack bioinformatics platform for protein analysis
importance: 3
category: work
github: https://github.com/Auntara12/protein-intelligence
---

A full-stack platform that aggregates four biomedical databases behind a unified query interface, with a FAISS-backed similarity search over high-dimensional protein embeddings and an interactive React frontend for exploring mutation sites in 3D.

**Highlights:**
- FAISS similarity search over protein embeddings — sub-100ms latency under load
- FastAPI backend integrating ESM2 embeddings, Smith-Waterman alignment, AlphaFold structures, and ClinVar variants
- TypeScript + React frontend with interactive 3D protein visualization for non-technical users
- Rate limiter via sorted sets and an atomic Lua script; degrades gracefully to passthrough on backend failure

**Stack:** Python, FastAPI, React, TypeScript, PostgreSQL, Redis, FAISS

Code on [GitHub](https://github.com/Auntara12/protein-intelligence).
