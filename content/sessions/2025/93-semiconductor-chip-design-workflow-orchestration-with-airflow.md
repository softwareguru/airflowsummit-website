---
title: "Semiconductor (Chip) Design Workflow Orchestration with Airflow"
slug: semiconductor-chip-design-workflow-orchestration-with-airflow
speakers:
 - Dheeraj Turaga
 - Nicholas Redd
topics:
 - Use cases
time_start: 2025-10-08 15:45:00
time_end: 2025-10-08 16:10:00
room: Columbia D
track: Use cases
day: 20252
timeslot: 93
gridarea: 13/4/14/5
slides: 2025/semiconductor-(chip)-design-workflow-orchestration-with-airflow.pdf
video:
---

The design of Qualcomm's Snapdragon System-On-Chip (SoCs) involves several hundred complex workflows orchestrated across multiple data centers, taking the design from RTL to GDS. In the Snapdragon Oryon Custom CPU team, we introduced Airflow about 2 years ago to orchestrate design, verification, emulation, CI/CD, and physical implementation of our CPUs.

Use Case:
	• Standardization and Templatization: We standardize and templatize common workflows, allowing designers to verify their designs by customizing YAML parameters.
	• Custom Shell Operators: We created custom shell operators (tcshrc) to source project environments and work with internal tooling.
	• Smart Retries: We use pre/post-execute hooks to trigger smart retries on failure.
	• Dynamic Celery Workers: We auto-create Celery workers on the fly on our High-Performance Compute (HPC) clusters to launch and manage Electronic Design Automation (EDA) workloads.
	• Hybrid Executor Strategy: We use a hybrid executor strategy (CeleryExecutor and EdgeExecutor) to orchestrate tasks across multiple data centers.
	• EdgeExecutor for Remote Testing: We leverage EdgeExecutor to access post-silicon hardware in remote locations.