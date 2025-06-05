---
title: "From Oops to Secure Ops: Self-Hosted AI for Airflow Failure Diagnosis"
slug: from-oops-to-secure-ops-self-hosted-ai-for-airflow-failure-diagnosis
speakers:
 - Nathan Hadfield
topics:
 - Airflow & ...
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
images:
 - /images/sessions/2025/from-oops-to-secure-ops.png
---

Last year, 'From Oops to Ops' showed how AI-powered failure analysis could help diagnose why Airflow tasks fail. But do we really need large, expensive cloud-based AI models to answer simple diagnostic questions? Relying on external AI APIs introduces privacy risks, unpredictable costs, and latency, often without clear benefits for this use case.

With the rise of distilled, open-source models, self-hosted failure analysis is now a practical alternative. This talk will explore how to deploy an AI service on infrastructure you control, compare cost, speed, and accuracy between OpenAI’s API and self-hosted models, and showcase a live demo of AI-powered task failure diagnosis using DeepSeek and Llama—running without external dependencies to keep data private and costs predictable.