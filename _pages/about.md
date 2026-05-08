---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an M.S. student in Cyberspace Security at [Nankai University](https://www.nankai.edu.cn/), advised by **Prof. Zheli Liu**. My research focuses on security and privacy problems at the intersection of AI systems, databases, and cryptography, including vector database leakage, RAG security, encrypted SQL inference attacks, and searchable encryption.

I am particularly interested in understanding how seemingly harmless operational traces, such as returned document IDs, encrypted query access patterns, or hidden representations of large language models, can reveal sensitive semantic or plaintext information. My recent work studies semantic leakage from vector database similarity search, leakage-abuse attacks on encrypted SQL systems, and representation-based defenses against external data extraction attacks in RAG systems.

I have worked on research projects submitted to or accepted by top security and data mining venues, including IEEE Symposium on Security and Privacy (S&P/Oakland), NDSS, and KDD. I also have engineering experience with openGauss database internals, dynamic searchable encryption prototypes, and security vulnerability analysis.

## Research Interests

- AI Security
- RAG Security
- Vector Database Security
- Database Security
- Encrypted SQL
- Leakage-Abuse Attacks
- Searchable Encryption
- Secure Query Processing
- Privacy Leakage from Retrieval Systems
- Hidden Representation Probing
- Security Evaluation of AI Infrastructure

## News

- **May 2026:** Submitted a first-author manuscript, "SLIP Through the Cracks: Semantic Leakage from ID Patterns in Vector Database Similarity Queries," to NDSS.
- **May 2026:** Submitted "You Shouldn't Have Taken It: Detecting Extraction from Retrieval-Augmented Generation via Hidden Representations" to KDD as a co-first author.
- **2026:** Our paper "Can I Get More? An Incremental Inference Attack on Encrypted SQL" was accepted by IEEE Symposium on Security and Privacy (S&P/Oakland) 2026.
- **2025:** Ranked 22nd in the AI Security track of DataCon2025 Big Data Security Analysis Competition.
- **2025:** Started M.S. study in Cyberspace Security at Nankai University, advised by Prof. Zheli Liu.

## Selected Publications

1. **Can I Get More? An Incremental Inference Attack on Encrypted SQL**
   Xiaoqian Sun*, Ruiqi He*, **Yang Zhang**, Siyi Lv, Guiyun Qin, Fangzhou Yi, Zheli Liu, Xiaofeng Chen.
   *IEEE Symposium on Security and Privacy (S&P/Oakland), 2026.*

2. **SLIP Through the Cracks: Semantic Leakage from ID Patterns in Vector Database Similarity Queries**
   **Yang Zhang** et al.
   *Submitted to NDSS.*

3. **You Shouldn't Have Taken It: Detecting Extraction from Retrieval-Augmented Generation via Hidden Representations**
   **Yang Zhang** et al.
   *Submitted to KDD. Co-first author.*

## Research Projects

- **Vector Database ID-Pattern Leakage.** Studying how returned top-k ID lists from vector database similarity search can leak semantic query labels.
- **RAG Extraction Defense via Hidden Representations.** Detecting external data extraction attacks before generation using hidden states of frozen language models.
- **Encrypted SQL Inference Attacks.** Exploiting joint distribution leakage in encrypted SQL systems using optimal transport and anchor-based incremental recovery.
- **Dynamic Searchable Encryption in openGauss.** Building a Fides/Sophos-style prototype inside openGauss query paths.

## Contact

Please feel free to contact me at **yangz@mail.nankai.edu.cn**.
