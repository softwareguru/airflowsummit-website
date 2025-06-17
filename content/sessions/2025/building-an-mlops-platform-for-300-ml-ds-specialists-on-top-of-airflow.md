---
title: "Building an MLOps Platform for 300+ ML/DS Specialists on Top of Airflow"
slug: building-an-mlops-platform-for-300-ml-ds-specialists-on-top-of-airflow
speakers:
 - Aleksandr Shirokov
 - Roman Khomenko
 - Tarasov Alexey
topics:
 - Airflow & ...
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

As your organization scales to 20+ data science teams and 300+ DS/ML/DE engineers, you face a critical challenge: how to build a secure, reliable, and scalable orchestration layer that supports both fast experimentation and stable production workflows. We chose Airflow — and didn’t regret it! But to make it truly work at our scale, we had to rethink its architecture from the ground up.

In this talk, we’ll share how we turned Airflow into a powerful MLOps platform through its core capability: running pipelines across multiple K8s GPU clusters from a single UI (!) using per-cluster worker pools. To support ease of use, we developed MLTool — our own library for fast and standardized DAG development, integrated Vault for secure secret management across teams, enabled real-time logging with S3 persistence and built a custom SparkSubmitOperator for Kerberos-authenticated Spark/Hadoop jobs in Kubernetes. We also streamlined the developer experience — users can generate a GitLab repo and deploy a versioned pipeline to prod in under 10 minutes!

We’re proud of what we’ve built — and our users are too. Now we want to share it with the world!