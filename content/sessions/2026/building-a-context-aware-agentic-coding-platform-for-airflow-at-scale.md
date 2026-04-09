---
title: "Building a Context-Aware Agentic Coding Platform for Airflow at Scale"
slug: building-a-context-aware-agentic-coding-platform-for-airflow-at-scale
speakers:
 - Yarden Wolf
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Generic AI coding assistants like Cursor and Claude code are powerful, but they struggle with proprietary infrastructures. At Wix, managing 7,500 active DAGs across 120 Data Engineers, we found that standard AI tools lacked the context to be truly effective - they didn't know our custom operators, DWH modeling patterns, or strict governance rules.
In this session, we introduce our internal "Agentic IDE Configuration Manager" that bridges this gap. We will demonstrate how we leverage MCPs to inject deep Airflow context into our AI agents. 
You will learn how we enabled our coding agents to:
Generate compliant code by utilizing custom Cursor rules to ensure every DAG meets production standards and naming conventions.
Interact with Airflow by using our custom MCPs to run DAGs locally, parse error logs, and autonomously fix pipeline failures.
Understand data by accessing our Data Catalog and Trino engine to validate schema logic in real-time.
Whether you are trying to optimize your team's workflows or simply curious how far can coding agents go in the current age, join us in this exciting talk.