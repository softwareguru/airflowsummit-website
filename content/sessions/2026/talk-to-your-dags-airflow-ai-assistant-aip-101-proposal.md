---
title: "Talk to your Dags: Airflow AI Assistant (AIP-101 proposal)"
slug: talk-to-your-dags-airflow-ai-assistant-aip-101-proposal
speakers:
 - Shahar Epstein
topics:
 - Data & AI Applications
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Airflow runs the pipelines that matter. When a task breaks, the workflow is fragmented: you copy an error, ask your favorite LLM in another tab, and still end up back in the Grid, scrolling logs.
AIP-101 proposes a better way: an opt-in AI assistant, natively integrated into Apache Airflow. Ask about your Dags, runs, and logs, and get grounded answers based on what you can already see. Built with a safety-first mindset, it respects your existing access, keeps sensitive details out of responses, and makes its help transparent. In this initial phase, the assistant explains, not executes. This talk highlights the user experience, the key design decisions, suggested high-level architecture, and what comes next for AI in Airflow.