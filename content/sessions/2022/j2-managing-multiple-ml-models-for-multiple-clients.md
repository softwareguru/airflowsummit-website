---
id: j2
title: "Managing Multiple ML Models For Multiple Clients : Steps For Scaling Up"
url: /sessions/2022/managing-multiple-ml-models-for-multiple-clients
speakers:
 - Ori Peri
time_start: 2022-05-26T15:30:00.000Z
time_end: 2022-05-26T15:50:00.000Z
format: "Presentation"
hosted_by: "Tel Aviv"
presence: "onsite"
block: j
slot: 2
---

For most ML-based SaaS companies, the need to fulfill each customer’s KPI will usually be addressed by matching a dedicated model. Along with the benefits of optimizing the model’s performance, a model per customer solution carries a heavy production complexity with it. In this manner, incorporating up-to-date data as well as new features and capabilities as part of a model’s retraining process can become a major production bottleneck. In this talk, we will see how Riskified scaled up modeling operations based on MLOps ideas, and focus on how we used Airflow as our ML pipeline orchestrator. We will dive into how we wrap Airflow as an internal service, the goals we started with, the obstacles along the way and finally - how we solved them. You will receive tools for how to set up your own Airflow-based continuous training ML pipeline, and how we adjusted it such that ML engineers and data scientists would be able to collaborate and work in parallel using the same pipeline.