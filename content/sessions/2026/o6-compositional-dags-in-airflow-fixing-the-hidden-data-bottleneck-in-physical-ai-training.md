---
title: "Compositional DAGs in Airflow: Fixing the Hidden Data Bottleneck in Physical AI Training"
slug: compositional-dags-in-airflow-fixing-the-hidden-data-bottleneck-in-physical-ai-training
speakers:
 - Saket Milind Karve
track: Data & AI Applications
room: Online
day: 2026o1
time_start: 2026-11-04 20:00:00
time_end: 2026-11-04 20:30:00
timeslot: 7
gridarea: 9/2/10/8
slides: 
video:
---

Robot foundation model training is data-bound, not compute-bound. GPUs sit idle while heterogeneous trajectory data, synchronized camera streams, IMU, joint-state, and force/torque signals, waits to be transformed into training-ready tensors. Production teams generate tens of terabytes daily, and generic data-loader patterns don't compose the way this data needs.

This talk shares a compositional DAG architecture built on Airflow for exactly this problem. Each ingestion step declares its own CPU/GPU/memory profile, ships as a versioned container image, fans out across Kubernetes workers using a distribute-wait pattern, and is selectively gated to skip re-execution of unaffected steps when downstream logic changes. Business logic runs off-orchestrator so the scheduler's worker pool never saturates under compute load.

In production, this eliminated over 30% of training slowdown while coordinating an 88 TB cache across 16 H100 nodes.

Attendees will leave with concrete DAG design patterns for per-step resource specification, selective re-execution, and orchestrator/compute separation, applicable to any team running heterogeneous, resource-heavy pipelines on Airflow, not just robotics.