---
title: "Beyond Containers: Securely Orchestrating AI Agents with Strong Isolation in Airflow"
slug: beyond-containers-securely-orchestrating-ai-agents-with-strong-isolation-in-airflow
speakers:
 - Uriel Munoz
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

AI agents break the traditional Airflow trust model. While standard tasks are deterministic, agents execute dynamic logic and invoke external tools, meaning untrusted code is suddenly running inside standard containers sharing your host kernel.
This session demonstrates how to secure AI workloads in Airflow without rewriting the orchestrator or building custom executors. We will introduce a custom, policy-driven @agent TaskFlow abstraction that leverages Kubernetes executor_config overrides (like runtimeClassName) to isolate workloads on the fly.

Key Takeaways for Attendees:
- The Threat Model: Why containers are not a strong enough security boundary for AI agents.
- The Implementation: How to build an @agent decorator that routes tasks to sandboxed environments (gVisor, Kata, Peer Pods) while keeping the KubernetesExecutor unchanged.
- Kubernetes in Production: How to achieve a VM-per-pod pattern using open-source tools without requiring nested node virtualization.
- Operational Realities: A candid look at execution flow, pod spec mutation, and the latency/cost trade-offs of runtime isolation.