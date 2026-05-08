---
title: "SLIP: Vector Database ID-Pattern Leakage Attack"
collection: projects
permalink: /projects/vector-db-slip
excerpt: "A vector database leakage attack showing that returned top-k ID lists can reveal semantic query labels."
tags:
  - vector-database
  - database-security
  - leakage-abuse
---

SLIP studies a new leakage surface in vector database systems: returned top-k ID lists. The attack shows that an observer of returned IDs can recover semantic query labels by analyzing ID overlap patterns, even without access to embeddings or query vectors.

SLIP treats each returned ID list as a set and constructs a query-query shadow graph using pairwise Jaccard similarity. Spectral clustering is then used to recover semantic groups, and labels are assigned through either class-size priors or a small number of anchors. The project highlights that ID lists, although commonly treated as harmless metadata, can encode sensitive semantic information in high-dimensional retrieval systems.
