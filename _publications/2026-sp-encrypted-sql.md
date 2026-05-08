---
title: "Can I Get More? An Incremental Inference Attack on Encrypted SQL"
collection: publications
category: conferences
permalink: /publication/sp2026-incremental-inference-encrypted-sql
excerpt: "An incremental leakage-abuse attack on encrypted SQL systems using anchors, joint distribution leakage, and optimal transport."
date: 2026-05-01
venue: "IEEE Symposium on Security and Privacy (S&P/Oakland)"
paperurl: ""
code: ""
slides: ""
citation: "Xiaoqian Sun*, Ruiqi He*, <strong>Yang Zhang</strong>, Siyi Lv, Guiyun Qin, Fangzhou Yi, Zheli Liu, and Xiaofeng Chen. &quot;Can I Get More? An Incremental Inference Attack on Encrypted SQL.&quot; <i>IEEE Symposium on Security and Privacy (S&P/Oakland)</i>, 2026."
tags:
  - database-security
  - searchable-encryption
  - leakage-abuse
---

This work studies plaintext recovery attacks against encrypted SQL query systems. Existing leakage-abuse attacks mainly exploit column equality leakage or cross-column equality leakage, but often fail to fully leverage joint distribution leakage revealed by multi-attribute queries.

We propose Anchor-Joint Attack, an incremental inference framework that first extracts high-confidence ciphertext-plaintext mappings as anchors and then gradually incorporates joint distribution information to expand plaintext recovery. The framework formulates frequency inference as an optimal transport problem, uses Earth Mover's Distance and Sinkhorn-style matching, and supports conflict resolution and error correction during iterative mapping refinement.

My contributions include implementing core attack algorithms and the experimental pipeline, participating in the design and implementation of FIOT, EMD/Sinkhorn-based matching, and Anchor-Joint Attack, and organizing experiments across multiple datasets and baselines.
