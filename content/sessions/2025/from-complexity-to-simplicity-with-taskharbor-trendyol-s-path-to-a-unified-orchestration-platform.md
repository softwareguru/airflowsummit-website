---
title: "From Complexity to Simplicity with TaskHarbor: Trendyol's Path to a Unified Orchestration Platform"
slug: from-complexity-to-simplicity-with-taskharbor-trendyol-s-path-to-a-unified-orchestration-platform
speakers:
 - Salih Goktug Kose
 - Burak Ozdemir
topics:
 - Airflow & ...
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

At Trendyol, Turkey's leading e-commerce company, Apache Airflow powers our task orchestration, handling DAGs with 500+ tasks, complex interdependencies, and diverse environments. Managing on-prem Airflow instances posed challenges in scalability, maintenance, and deployment. To address these, we built TaskHarbor, a fully managed orchestration platform with a hybrid architecture—combining Airflow on GKE with on-prem resources for optimal performance and efficiency.

This talk covers how we:

- Enabled seamless DAG synchronization across environments using GCS Fuse.
- Optimized workload distribution via GCP’s HTTPS & TCP Load Balancers.
- Automated infrastructure provisioning (GKE, CloudSQL, Kubernetes) using Terraform.
- Simplified Airflow deployments by replacing Helm YAML files with a custom templating tool, reducing configurations to 10-15 lines.
- Built a fully automated deployment pipeline, ensuring zero developer intervention.

We enhanced efficiency, reliability, and automation in hybrid orchestration by embracing a scalable, maintainable, and cloud-native strategy. Attendees will obtain practical insights into architecting Airflow at scale and optimizing deployments.