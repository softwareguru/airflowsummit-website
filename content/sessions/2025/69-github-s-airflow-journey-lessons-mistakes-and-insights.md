---
title: "GitHub's Airflow Journey: Lessons, Mistakes, and Insights"
slug: github-s-airflow-journey-lessons-mistakes-and-insights
speakers:
 - Oleksandr Slynko
topics:
 - Use cases
time_start: 2025-10-08 14:00:00
time_end: 2025-10-08 14:25:00
room: Columbia A
track: Use cases
day: 20252
timeslot: 69
gridarea: 9/2/10/3
slides:
video:
---

This session explores how GitHub uses Apache Airflow for efficient data engineering. We will share nearly 9 years of experiences, including lessons learnt, mistakes made, and the ways we reduced our on-call and engineering burden. We'll demonstrate how we keep data flowing smoothly while continuously evolving Airflow and other components of our data platform, ensuring safety and reliability. The session will touch on how we migrate Airflow between cloud without user impact. We'll also cover how we cut down the time from idea to running a DAG in production, despite our Airflow repo being among the top 15 by number of PRs within GitHub.

We'll dive into specific techniques such as testing connections and operators, relying on dag-sync, providing short-lived development environments to let developers test their DAG runs, and creating reusable patterns for DAGs. By the end of this session, you will gain practical insights and actionable strategies to improve your own data engineering processes.
