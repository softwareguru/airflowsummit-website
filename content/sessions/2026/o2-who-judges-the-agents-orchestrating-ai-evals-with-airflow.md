---
title: "Who Judges the Agents? Orchestrating AI Evals with Airflow"
slug: who-judges-the-agents-orchestrating-ai-evals-with-airflow
speakers:
 - Rafael Pierre
track: Data & AI Applications
room: Online
day: 2026o1
time_start: 2026-11-04 15:30:00
time_end: 2026-11-04 16:00:00
timeslot: 3
gridarea: 4/2/5/8
slides: 
video:
---

Agentic AI systems are difficult to ship safely: their behavior is non-deterministic, traditional assertions only cover part of the problem, and manual evaluation quickly becomes a release bottleneck.

In this talk, I’ll share how we built Pegasus, an automated evaluation platform for agentic applications, and used Apache Airflow as its orchestration backbone. The platform combines deterministic tests with LLM-as-a-Judge and Agents-as-Judges evaluations. Airflow coordinates the evaluation harness across scheduled and on-demand runs. a DAG checks the commit currently deployed across different environments, determines whether that version has already been evaluated, and runs the required test suites only when needed. The same workflow can also be triggered asynchronously during development and release processes.

This approach automated roughly 80% of tests that previously required manual execution and helped move our production release cadence from about once a month to twice or more a week.

Attendees will leave with a practical architecture for orchestrating AI evaluations with Airflow, patterns for combining scheduled and on-demand evaluation workflows, and lessons for making agentic AI testing repeatable, observable, and useful as part of a production release process.