---
title: "Debugging the Undebuggable: Lessons from Real Airflow Incidents"
slug: debugging-the-undebuggable-lessons-from-real-airflow-incidents
speakers:
 - Pankaj Singh
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Debugging Airflow failures in production can be harder than building the pipelines themselves. Engineers often encounter issues such as disappearing DAGs, hanging tasks, missing logs, zombie tasks, or sudden performance degradation, often with little visibility into the root cause.

Over the past year, while supporting multiple Airflow deployments and integrations, we investigated several such incidents across different teams and environments. This session shares lessons from these real debugging cases and explains how the issues were diagnosed and resolved.

We will walk through incidents involving scheduler behaviour, concurrency limits, memory pressure, and process-level failures. For each case, we highlight the symptoms, the investigation approach, and the root cause.

Attendees will learn
- How to systematically debug complex Airflow failures
- Which components commonly hide the root cause
- Practical signals to watch in logs and metrics