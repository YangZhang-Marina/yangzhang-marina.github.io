---
title: "Dynamic Searchable Encryption Prototype in openGauss"
collection: projects
permalink: /projects/opengauss-dynamic-sse
excerpt: "A Fides/Sophos-style dynamic searchable encryption prototype integrated into openGauss query paths."
tags:
  - database-security
  - searchable-encryption
---

This project integrates a dynamic searchable encryption prototype into openGauss. It modifies the client-side and SQL execution workflow to support custom Fides commands, encrypted-index maintenance, token generation, deletion handling, and two-stage search.

The implementation adds Fides-style interfaces for insertion, search, and deletion; intercepts Fides-specific SQL commands in the libpq query submission path; rewrites high-level commands into encrypted-index update and search operations; maintains local SSE state through persistent client metadata files; and implements PL/pgSQL helper functions for batched index insertion and search over `fides_datatable` and `fides_indextable`.

This work gave me hands-on experience with database internals, query rewriting, secure index maintenance, and systems-level security prototyping.
