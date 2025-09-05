---
title: "Lessons learned from migrating to Airflow @ LI Scale"
slug: lessons-learned-from-migrating-to-airflow-li-scale
speakers:
 - Arthur Chen
 - Trevor DeVore
 - Deng Pan
topics:
 - Airflow & ...
time_start: 2025-10-09 14:00:00
time_end: 2025-10-09 14:25:00
room: Columbia C
track: Airflow & ...
day: 20253
timeslot: 152
gridarea: 10/3/11/4
slides:
video:
images:
 - /images/sessions/2025/lessons-learned-from-migrating-to-airflow.png
---

At LinkedIn, our data pipelines process exabytes of data, with our offline infrastructure executing 300K ETL workflows daily and 10K concurrent executions. Historically, these workloads ran on our legacy system, Azkaban, which faced UX, scalability, and operational challenges. To modernize our infra, we built a managed Airflow service, leveraging its enhanced developer & operator experience, rich feature set, and strong OSS community support. That initiated LinkedIn’s largest-ever infrastructure migration—transitioning thousands of legacy workflows to Airflow.

In this talk, we will share key lessons from migrating massive-scale pipelines with minimal production disruption. We will discuss:
- Overall Migration Strategy
- Custom Tooling Enhancements on testing, deployment, and observability
- Architectural Innovations decoupling orchestration and compute
- GenAI-powered Migration automating code rewrites
- Post-Migration Challenges & Airflow 3.0.

Attendees will walk away with battle-tested strategies for large-scale Airflow adoption and practical insights into scaling Airflow in enterprise environments.