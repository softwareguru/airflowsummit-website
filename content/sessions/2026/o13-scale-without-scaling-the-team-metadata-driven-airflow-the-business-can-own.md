---
title: "Scale Without Scaling the Team: Metadata-Driven Airflow the Business Can Own"
slug: scale-without-scaling-the-team-metadata-driven-airflow-the-business-can-own
speakers:
 - Ramzi Alashabi
track: Data Strategy
room: Online
day: 2026o2
time_start: 2026-11-05 7:30:00
time_end: 2026-11-05 8:00:00
timeslot: 4
gridarea: 5/2/6/8
slides: 
video:
---

Every data team hits the same wall: a handful of engineers writing and maintaining every Airflow DAG, while the business waits in the queue.

We took a different path. Instead of hand-writing pipelines, we generate them from metadata, a declarative description of what each data product needs, compiled straight into asset-scheduled Airflow 3 DAGs. Source dependencies, partitioning, trigger conditions, retries: all derived, not typed. That alone let us stand up hundreds of pipelines without hundreds of hand-maintained files.

But auto-generation only takes you so far. Real orchestration needs human judgment: this product should wait for that one; these steps run in a specific order. So we gave the business a canvas drag-and-drop dependencies on top of the generated graph that compiles back into the same metadata. Analysts compose their own reusable orchestration; engineers stay out of the critical path.

I'll walk through:
    • How to compile metadata into an asset-scheduled Airflow DAG, what to derive automatically, and what to leave configurable.
    • How a visual, drag-and-drop dependency graph maps cleanly back to declarative orchestration, not throwaway clicks.
    • Where auto-generation ends and human-authored orchestration begins and how to let both live in one source of truth.
    • What this does to delivery speed when the people who understand the data can ship the pipeline.

You'll leave with a blueprint for metadata-driven DAG generation plus business-owned orchestration a way to scale pipeline delivery without scaling your DAG-writing team.
