---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Cyberspace Security, College of Cyber Science, Nankai University, 2025.06 - Present
  * Advisor: Prof. Zheli Liu
  * Research direction: vector database security, AI security, encrypted database leakage, and RAG security.
* B.S. in Information Security, College of Cyber Science, Nankai University, 2021.09 - 2025.06
  * GPA: 3.7/4.0
  * Ranking: 7/50
  * Weighted score: 89.01/100

Research Identity
======
I study privacy leakage and defense mechanisms in AI-driven data systems, especially vector databases, RAG pipelines, and encrypted database query systems.

Publications and Manuscripts
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research and Engineering Projects
======
* Dynamic Searchable Encryption Prototype in openGauss
  * Implemented a Fides/Sophos-style dynamic searchable encryption prototype on openGauss.
  * Modified client-side query submission, result handling, and SQL helper functions for custom searchable-encryption commands.
  * Built encrypted-index update/search operations, token derivation logic, deletion-marker filtering, and two-stage search.
* Data Extraction Attack Framework for RAG Systems - DataCon2025
  * Designed a RAG extraction framework under a limited query budget.
  * Combined instruction injection, BFS exploration, semantic query fusion, duplicate filtering, checkpointing, and retry logic.
  * Ranked 22nd in the AI Security track of DataCon2025 Big Data Security Analysis Competition.
* SLIP: Vector Database ID-Pattern Leakage Attack
  * Studied semantic leakage from returned top-k ID lists in vector database similarity search.
  * Built a shadow graph from Jaccard overlap and used spectral clustering plus label assignment to recover semantic groups.
* Encrypted SQL Inference Attack with Anchor-Joint Recovery
  * Studied plaintext recovery attacks against encrypted SQL systems supporting boolean and join queries.
  * Used anchors, joint distribution leakage, and optimal transport for incremental ciphertext-plaintext recovery.

Security Practice
======
* Security Development / Vulnerability Analysis Training, 360 Enterprise Security Group
  * Reproduced and analyzed high-risk vulnerabilities, including Apache bRPC RCE and VMware vCenter Server RCE (CVE-2021-21972).
  * Built vulnerability reproduction environments and documented trigger conditions, affected versions, exploit paths, and remediation suggestions.
  * Wrote Python POC scripts and organized automated verification procedures.
  * Completed web security testing tasks involving SQL injection, file upload, file parsing, information leakage, and WAF attack log analysis.

Honors and Awards
======
* IEEE Symposium on Security and Privacy (S&P/Oakland) 2026 paper accepted.
* Submitted first-author manuscript to NDSS on vector database semantic leakage.
* Submitted co-first-author manuscript to KDD on RAG extraction detection.
* DataCon2025 Big Data Security Analysis Competition, AI Security track, ranked 22nd.
* National College Students' Innovation and Entrepreneurship Competition, Silver Award.
* MCM/ICM 2024, Honorable Mention.
* Nankai University Outstanding Graduate, 2025.
* Nankai University Academic Excellence Scholarship, 2021-2022.
* Nankai University Gongneng Scholarship and Merit Student Honor, 2022-2023.
* Nankai University Academic Excellence Scholarship, 2023-2024.
* Nankai University Graduate Recommendation Scholarship and Gongneng Scholarship, 2024-2025.

Skills
======
* Programming: C/C++, Python, Java, SQL, Shell scripting.
* AI / Machine Learning: PyTorch basics, scikit-learn, XGBoost, representation probing, hidden-state extraction, LLM API usage, RAG pipeline evaluation.
* Database and Systems: openGauss, relational database internals, query rewriting, searchable encryption prototype development, Linux, Docker, Git.
* Security: encrypted database leakage analysis, searchable encryption, leakage-abuse attacks, RAG extraction attacks, vulnerability reproduction, POC writing, web security testing.
* Research Tools: LaTeX, Python scientific stack, experiment automation, paper reading and writing, technical figure preparation.
