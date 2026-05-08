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
* M.S. in Cybersecurity, College of Cryptography and Security, Nankai University, 2025.6 - Present
  * Advisor: Prof. Zheli Liu
  * Research interests: vector databases and AI security
* B.S. in Information Security, College of Cryptography and Security, Nankai University, 2021.9 - 2025.6
  * Rank: 7/50; GPA: 3.7/4.0; weighted score: 89.01/100
  * Outstanding Graduate, Nankai University, 2025

Work experience
======
* Security R&D Intern, 360 Enterprise Security Group
  * Maintained and updated enterprise vulnerability scanning strategies.
  * Scanned and analyzed common vulnerabilities including SQL injection, XSS, and SSRF.
  * Developed efficient proof-of-concept exploits for specific logic vulnerabilities.
  
Skills
======
* Programming: C/C++ including multithreading and memory management; Python for data processing and automation; Java.
* Databases and storage: openGauss database kernel development; relational database internals; vector database and indexing principles.
* Security: Searchable Symmetric Encryption (SSE), symmetric and asymmetric cryptographic protocols, vulnerability scanning, and POC development.
* Engineering tools: Git, Docker, Linux development environments, code quality, and open-source collaboration.

Projects
======
* Web Situational Awareness and User Interaction Behavior Analysis
  * Led analysis of the security posture of global Top 500 websites.
  * Developed high-concurrency Python crawlers to collect and analyze Web interface elements and user interaction data.
  * Modeled anomalous interaction behavior to identify potential security threats and interface spoofing risks.
* Searchable Symmetric Encryption (SSE) Integration for openGauss
  * Implemented SSE encryption operators in the openGauss database kernel with C++.
  * Supported transparent field-level encryption and optimized encrypted index query logic.
  * Submitted code to the open-source community for efficient exact match and range queries over sensitive data.
* RAG Data Extraction Attack Defense Framework
  * Designed a defense framework against external data extraction attacks in RAG systems.
  * Monitored frozen LLM hidden-state representations before generation to identify attack intent and avoid token leakage.
  * Ranked 22nd in the Datacon RAG track; paper under submission.
* Android Application, Nankai University President's Cup
  * Developed an Android app integrating database storage, LLM API calls, and UI design.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards and honors
======
* Outstanding Graduate, Nankai University, 2025
* Postgraduate Recommendation Scholarship and Gongneng Scholarship, Nankai University, 2024-2025
* Honorable Mention, Mathematical Contest in Modeling (MCM/ICM), 2024
* Academic Excellence Scholarship, Nankai University, 2023-2024
* Silver Medal, China International College Students' "Internet+" Innovation and Entrepreneurship Competition, 2023
* Gongneng Scholarship and Merit Student Honor, Nankai University, 2022-2023
* Academic Excellence Scholarship, Nankai University, 2021-2022

Download
======
* [Download CV as PDF](/files/cv.pdf)
