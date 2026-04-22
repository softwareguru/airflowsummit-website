---
title: "Gleaming the Cube: Exploring the limits of Airflow through the Rubik's Cube"
slug: gleaming-the-cube-exploring-the-limits-of-airflow-through-the-rubik-s-cube
speakers:
 - Jonathan Leek
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

What does solving a Rubik’s Cube have to do with Apache Airflow? More than you’d think.

In this talk, I’ll walk through a project where Airflow orchestrates the process of solving a Rubik’s Cube — not as a gimmick, but as a framework for exploring cyclic workflows, state management, and iterative computation in a system designed for DAGs. Cube-solving algorithms naturally require feedback loops, evolving state, and conditional branching — all things that challenge Airflow’s acyclic model.

We’ll explore how to model “cycles” without breaking DAG semantics, manage cube state across tasks, handle convergence and termination conditions, and avoid common anti-patterns. Along the way, I’ll share practical lessons about idempotency, XCom design, task explosion, and when to rethink orchestration boundaries.

If you’ve ever tried to push Airflow beyond straightforward ETL, this session will give you concrete patterns for safely orchestrating iterative, stateful workflows in production.