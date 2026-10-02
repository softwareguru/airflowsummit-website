---
title: "How We Taught an Agent Airflow: Building Self-Healing Pipelines with Otto"
slug: how-we-taught-an-agent-airflow-online
speakers:
 - Stephanie Niu
 - Christine Shen
track: Sponsored
room: Online
day: 2026o1
time_start: 2026-11-04 16:30:00
time_end: 2026-11-04 17:00:00
timeslot: 5
gridarea: 6/2/7/8
slides: 
video:
---

Generic AI assistants can read your logs, but that doesn't make them good at diagnosing your pipelines. When a Dag fails, the evidence is scattered across task logs, lineage, code diffs, and upstream data, and Airflow is the only place it all comes together. This session is about what happens when you build an investigation agent there, instead of bolting one onto your logs.

We'll show how Otto, Astronomer's data engineering agent, encodes failure patterns from eight years of running Airflow at enterprise scale and grounds every investigation in the live context of your own environment. We'll share real examples of teams using Otto in production, including one that cut MTTR by 95% in eight weeks and now starts their mornings reviewing proposed fixes instead of firefighting. 

You'll leave with a clear mental model for what makes an agent trustworthy at diagnosis, why investigation belongs at the orchestration layer, and which layer of self-healing is worth building yourself and which one isn't.