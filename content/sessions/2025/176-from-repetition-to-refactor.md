---
title: "From Repetition to Refactor: Smarter DAG Design in Airflow 3"
slug: from-repetition-to-refactor
speakers:
 - Steven Woods
topics:
 - Best practices
time_start: 2025-10-09 15:45:00
time_end: 2025-10-09 16:10:00
room: Beckler
track: Best practices
day: 20253
timeslot: 176
gridarea: 15/5/16/6
slides: 2025/from-repetition-to-refactor_-smarter-dag-design-in-airflow-3.pdf
video:
images:
 - /images/sessions/2025/from-repetition-to-refactor.png
---

We will explore how Apache Airflow 3 unlocks new possibilities for smarter, more flexible DAG design. We’ll start by breaking down common anti-patterns in early DAG implementations, such as hardcoded operators, duplicated task logic, and rigid sequencing, that lead to brittle, unscalable workflows. From there, we’ll show how refactoring with the D.R.Y. (Don’t Repeat Yourself) principle, using techniques like task factories, parameterization, dynamic task mapping, and modular DAG construction, transforms these workflows into clean, reusable patterns.

With Airflow 3, these strategies go further: enabling DAGs that are reusable across both batch pipelines and streaming/event-driven workloads, while also supporting ad-hoc runs for testing, one-off jobs, or backfills. The result is not just more concise code, but workflows that can flexibly serve different data processing modes without duplication. Attendees will leave with concrete patterns and best practices for building maintainable, production-grade DAGs that are scalable, observable, and aligned with modern data engineering standards.