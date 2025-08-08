---
title: "Navigating Secure and Cost-Efficient Flink Batch on Kubernetes with Airflow"
slug: navigating-secure-and-cost-efficient-flink-batch-on-kubernetes-with-airflow
speakers:
 - Purshotam Shah
 - Prakash Nandha Mukunthan
topics:
 - Use cases
time_start: 2025-10-09 14:30:00
time_end: 2025-10-09 14:55:00
room: Beckler
track: Use cases
day: 20253
timeslot: 161
gridarea: 11/5/12/6
slides:
video:
---

At Yahoo, we built a secure, scalable, and cost-efficient batch processing platform using Amazon MWAA to orchestrate Apache Flink jobs on EKS, managed by the Flink Kubernetes Operator. This setup enables dynamic job orchestration while meeting strict enterprise compliance standards.

In this session, we’ll share how Airflow DAGs:

* Dynamically launch, monitor, and clean up isolated Flink clusters per batch job, improving resource efficiency.

* Securely fetch EKS kubeconfig, submit FlinkDeployment CRDs using FlinkKubernetesOperator, and poll job status using Airflow sensors.

* Integrate IAM for access control and meet Yahoo’s security requirements, including mutual TLS (mTLS) with Athenz.

* Optimize for cost and resilience through automated cleanup of jobs and the operator, and handle job failures and retries.

Join us for practical strategies and lessons from Yahoo’s production-scale Flink workflows in a Kubernetes environment.