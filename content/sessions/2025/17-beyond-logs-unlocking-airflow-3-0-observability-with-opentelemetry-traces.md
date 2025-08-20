---
title: "Beyond Logs: Unlocking Airflow 3.0 Observability with OpenTelemetry Traces"
slug: beyond-logs-unlocking-airflow-3-0-observability-with-opentelemetry-traces
speakers:
 - Christos Bisias
topics:
 - Airflow 3
time_start: 2025-10-07 14:30:00
time_end: 2025-10-07 14:55:00
room: Columbia A
track: Airflow 3
day: 20251
timeslot: 17
gridarea: 8/2/9/3
images: 
 - /images/sessions/2025/beyond-logs-unlocking-airflow-3-0-observability-with-opentelemetry-traces.png
slides:
video:
---

Using OpenTelemetry tracing, users can gain full visibility into tasks and calls to outside services. This is an increasingly important skill, especially as tasks in an Airflow DAG involve multiple complex computations which take hours or days to complete. Airflow allows users to easily monitor how long entire DAG runs or individual tasks take, but preserves the anonymity of internal actions. OpenTelemetry gives users much more operational awareness and metrics they can use to improve operations.

This presentation will explain the basics: what OpenTelemetry is and how it works – perfect for someone with no prior familiarity with tracing or with the use of OpenTelemetry. It will demonstrate how Airflow users can leverage the new tracing support to achieve deeper observability into DAG runs.