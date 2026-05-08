---
title: "SLIP Through the Cracks: Semantic Leakage from ID Patterns in Vector Database Similarity Queries"
collection: publications
category: manuscripts
# permalink: /publication/slip-vector-database-id-leakage
excerpt: "A semantic leakage attack showing that returned ID lists from vector database similarity queries can reveal query labels."
# date: 2026-05-06
venue: "NDSS submission"
status: "Under review"
# paperurl: ""
code: ""
slides: ""
# citation: "<strong>Yang Zhang</strong> et al. &quot;SLIP Through the Cracks: Semantic Leakage from ID Patterns in Vector Database Similarity Queries.&quot; Submitted."
tags:
  - vector-database
  - database-security
  - leakage-abuse
---

This work identifies a structural privacy leakage channel in vector database similarity search. We show that an attacker who observes only returned top-k ID lists can recover the semantic class labels of user queries, without seeing query vectors, database embeddings, or coordinate values.

SLIP exploits the fact that semantically similar queries tend to return overlapping nearest-neighbor ID sets. It constructs a shadow graph from pairwise Jaccard similarity between returned ID lists, recovers unlabeled semantic groups through spectral clustering, and assigns semantic labels using either class-size priors or a small number of anchor queries.

I led this project as first author, including attack pipeline design, shadow graph construction, spectral clustering, label assignment strategies, threat model analysis, experiments, and defense evaluation.
