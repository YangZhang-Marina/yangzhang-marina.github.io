---
title: "You Shouldn't Have Taken It: Detecting Extraction from Retrieval-Augmented Generation via Hidden Representations"
collection: publications
category: manuscripts
permalink: /publication/diver-rag-extraction-hidden-representations
excerpt: "A representation-based detector for external data extraction attacks in RAG systems using pre-generation hidden states."
date: 2026-05-01
venue: "KDD submission"
paperurl: ""
code: ""
slides: ""
citation: "<strong>Yang Zhang</strong> et al. &quot;You Shouldn't Have Taken It: Detecting Extraction from Retrieval-Augmented Generation via Hidden Representations.&quot; Submitted."
tags:
  - ai-security
  - rag-security
---

This work studies defenses against External Data Extraction Attacks in Retrieval-Augmented Generation systems. These attacks craft user queries that induce a RAG system to output retrieved private context verbatim.

We propose DIVER, a lightweight representation-based detector that identifies extraction intent from pre-generation hidden representations of a frozen LLM, allowing intervention before any output token is produced. The method does not require fine-tuning or modifying the underlying LLM and is designed to improve prompt-wrapper generalization.

My contributions include algorithm implementation, experimental pipeline construction, attack and defense sample construction, hidden-state extraction, lightweight probe training, and evaluation across LLM backbones and RAG prompt settings.
