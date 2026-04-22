---
title: "Breaking the Monolith: Implementing Airflow 3.x Remote Execution for Multi-Team Environments"
slug: breaking-the-monolith-implementing-airflow-3-x-remote-execution-for-multi-team-environments
speakers:
 - Kowsy Narayan
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Problem Statement: As our data platform scaled, our shared Airflow 2.9 deployment became a bottleneck with critical challenges: development friction from shared repositories, custom security workarounds, release coordination complexity, data isolation concerns, and cost attribution opacity. When Airflow 3.x launched with hybrid execution support, we restructured our architecture. Following a successful proof of value, we implemented remote execution - enabling teams to run workloads in isolated Kubernetes clusters while maintaining centralized orchestration. This session shares our journey, architectural decisions, and how we leveraged agentic AI to streamline migration and developer experience.

Presentation Details: Join us for a practitioner's guide to transforming Airflow from a shared bottleneck into scalable execution with multiple Kubernetes clusters. The Journey: Why we moved from Airflow 2.9's monolithic deployment to Airflow 3.x's remote execution. The Architecture: Astronomer orchestrating workloads across team-owned Azure Kubernetes clusters. The Innovation: How agentic AI automates DAG development, from code generation to deployment.