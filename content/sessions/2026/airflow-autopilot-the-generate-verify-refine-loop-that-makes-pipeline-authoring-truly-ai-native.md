---
title: "Airflow Autopilot: The Generate-Verify-Refine Loop That Makes Pipeline Authoring Truly AI-Native"
slug: airflow-autopilot-the-generate-verify-refine-loop-that-makes-pipeline-authoring-truly-ai-native
speakers:
 - Yifan Wang
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Today's Pipeline authoring is synchronous: writing code, chasing error - every step blocks the engineer until resolved. You can't step away or parallelize.
Airflow Autopilot reimagines this to be AI-native and asynchronous. Describe your pipeline's intent. The agent takes over - orchestrating two classes of purpose-built tools: tools that generate the DAG code and automate setup, and scorer tools that evaluate it across dimensions: e.g. data discovery, auth, compliance, DAG validation, even end-to-end execution.
Every scorer returns a deterministic result and structured, prioritized hints. The agent runs the generate → verify → refine loop — calling scorers, reading hints, fixing code, re-scoring — until every dimension passes.
You come back to a PR with DAGs that have been iteratively built, tested, and ready for review.
For 10,000+ Airflow users, this shifts the engineer from executor to reviewer: you own the intent and final judgment, the agent owns the execution.
Attendees leave with the architecture for an AI-native authoring experience, the principles behind decomposing work into scorer-sized verification units, and what it takes to scale this in production.