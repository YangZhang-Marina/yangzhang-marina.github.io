---
title: "Data Extraction Attack Framework for RAG Systems - DataCon2025"
collection: projects
# permalink: /projects/rag-extraction-datacon
excerpt: "A general-purpose RAG extraction attack framework combining instruction injection, BFS exploration, semantic query fusion, and duplicate filtering."
tags:
  - ai-security
  - rag-security
---

Designed and implemented a general-purpose attack framework for extracting private chunks from RAG systems under a 5000-query limit. The framework combines instruction injection, global-local BFS exploration, semantic query fusion, duplicate filtering, checkpointing, and retry logic to improve extraction fidelity and coverage.

The project used external LLMs to fuse known leaked chunks with random knowledge bias, producing semantically shifted queries that discover new chunks. The team ranked 22nd in the AI Security track of DataCon2025 Big Data Security Analysis Competition.
