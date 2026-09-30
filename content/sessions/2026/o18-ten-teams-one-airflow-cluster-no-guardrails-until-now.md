---
title: "Ten Teams, One Airflow Cluster, No Guardrails. Until Now."
slug: ten-teams-one-airflow-cluster-no-guardrails-until-now
speakers:
 - Vinod Jayendra
 - Sean Bjurstrom
 - Abdul Majid Mohammed
track: Data Strategy
room: Online
day: 2026o2
time_start: 2026-11-05 15:00:00
time_end: 2026-11-05 15:30:00
timeslot: 9
gridarea: 11/2/12/8
slides: 
video:
---

Your Airflow environment started as one team's orchestrator. Now three teams share it, each wants their own connections, variables, and execution roles. Your security review flagged that every DAG runs with the same permissions. Sound familiar?

We'll tackle multi-tenancy head-on. Most Airflow deployments have a single execution context, one DAGs folder, and limited native isolation between teams. Here are the patterns that work in production.

Runtime resource isolation: per-task credential scoping so each team's DAGs only access their own data stores and APIs. DAG-level access control with automated tag-based RBAC that syncs identity attributes to Airflow roles on a schedule, so new DAGs inherit the right permissions without manual work. And the deployment tradeoff: single shared instance with RBAC guardrails vs. separate environments per team.

We'll show how AI agents speed up multi-team operations. Using Airflow 3's task.agent decorator, we built an automated onboarding workflow that scans a team's DAG repo, infers required connections and permissions, generates scoped access policies, and configures RBAC. All as auditable, retryable Airflow tasks instead of manual runbooks.

We'll preview Airflow 3.2's experimental multi-team support: separate DAGs, connections, variables, pools, and executors per team in a single instance.

You'll leave with a blueprint for operating Airflow as an internal platform. Self-service onboarding, cost allocation per team, and security guardrails that don't slow developers down.