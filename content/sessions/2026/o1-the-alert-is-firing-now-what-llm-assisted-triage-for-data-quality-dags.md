---
title: "The Alert Is Firing. Now What? LLM-Assisted Triage for Data Quality DAGs"
slug: the-alert-is-firing-now-what-llm-assisted-triage-for-data-quality-dags
speakers:
 - Ashir Alam
track: Data & AI Applications
room: Online
day: 2026o1
time_start: 2026-11-04 15:00:00
time_end: 2026-11-04 15:30:00
timeslot: 2
gridarea: 3/2/4/8
slides: 
video:
---

At Airflow Summit 2025 we showed how we generate data quality DAGs from YAML using DAGFactory, putting check authoring in the hands of 30+ engineers, analysts, and BI users on Cloud Composer. It worked and it created a new problem. Check coverage grew faster than our ability to respond to it, and on-call was spending a median of one to two hours per alert just deciding whether it was real.

Almost none of that time was judgment. It was gathering: querying historical values for the failing metric, checking upstream task state, looking for schema drift, correlating recent deploys, comparing sibling checks on the same table. All of it was context Airflow already had.

This talk covers how we turned that gathering loop into a triage DAG. A failing check triggers parallel context-assembly tasks, hands the result to an LLM constrained to a strict output schema, and posts a structured verdict to Slack: true positive, false positive, or inconclusive, with confidence, reasoning, and cited evidence. The engineer approves a rerun, suppresses, or escalates with one click - Airflow stays in control of every action taken. Median time to a triage decision dropped from one to two hours to under ten minutes.

We'll walk through the DAG design, the output schema, how the Slack approval loop doubles as a labeled evaluation set, and what we measure to know the model isn't quietly wrong, including false-negative rate and how often engineers override the verdict. We'll also cover what broke along the way: hallucinated root causes, context bloat, cost per triage, and the open question of whether humans keep reviewing carefully once the verdicts start getting good.