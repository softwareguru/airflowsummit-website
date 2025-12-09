---
title: "DAGnostics: Shift-Left Airflow Governance with Policy Enforcement Framework"
slug: dagnostics
speakers:
 - Yifan Wang
time_start: 2025-10-09 15:00:00
time_end: 2025-10-09 15:25:00
room: Columbia D
track: Roadmap
day: 20253
timeslot: 167
gridarea: 12/4/13/5
images: 
 - /images/sessions/2025/dagnostics.png
slides: 2025/dagnostics-shift-left-airflow-governance-with-policy-enforcement-framework.pdf
video: https://youtu.be/CwVvEIUcSUs
---

DAGnostics seamlessly integrates Airflow Cluster Policy hooks to enforce governance from local DAG authoring through CI pipelines to production runtime. Learn how it closes validation gaps, collapses feedback loops from hours to seconds, and ensures consistent policies across stages.
We examine current runtime-only enforcement and fractured CI checks, then unveil our architecture: a pluggable policy registry via Airflow entry points, local static analysis for pre-commit validation, GitHub Actions CI integration, and runtime hook enforcement. See real-world use cases: alerting standards, resource quotas, naming conventions, and exemption handling.
Next, dive into implementation: authoring policies in Python, auto-discovery, cross-environment enforcement, upstream contribution, and testing strategies. We share LinkedIn’s metrics—2,000+ DAG repos, 10,000+ daily executions supporting trunk-based development across isolated teams/use-cases, and 78% fewer runtime violations—and lessons learned scaling policy-as-code at enterprise scale.
Leave with a blueprint to adopt DAGnostics and strengthen your Airflow governance while preserving full compatibility with existing systems.

