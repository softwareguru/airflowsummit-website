---
title: "Graphs of AI Coding: Orchestrating Agentic MapReduce with Airflow's New Sandboxes"
slug: graphs-of-ai-coding
speakers:
 - Yossi Eliaz
topics:
 - Data & AI Applications
time_start: 2026-09-01 17:30:00
time_end: 2026-09-01 18:00:00
track: Data & AI Applications
room: Texas Ballroom 6
day: 20262
timeslot: 66
gridarea: 18/4/19/5
slides: 
video:
draft: false
---

AI coding has evolved from single prompts to complex, graph-based workflows. Today's systems plan, map refactoring tasks across codebases, test code viability, and reduce results into a single pull request. This "Agentic MapReduce" requires an orchestrator built for stateful dependencies and untrusted execution.

Enter Apache Airflow. With recent moves toward sandboxed execution (like PR #68847 and the SandboxExecutor), Airflow is perfectly positioned to orchestrate AI coding workflows.

This session explores modeling AI software engineering as an Airflow DAG. We will cover:

-The AI Coding Graph: Breaking down agentic refactoring into MapReduce DAGs.
-The Sandbox Imperative: Why ephemeral containers fail AI agents, and how Airflow's sandboxed execution secures untrusted model code.
-State and Caching: Managing unified caching and persistent state for massive agent-driven build tasks.

Leave with a blueprint for using Airflow as the central nervous system for autonomous software engineering.