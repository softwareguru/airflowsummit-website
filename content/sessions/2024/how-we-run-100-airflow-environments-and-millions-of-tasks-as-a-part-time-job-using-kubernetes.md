---
title: "How we run 100 Airflow environments and millions of Tasks as a Part Time job using Kubernetes"
slug: how-we-run-100-airflow-environments-and-millions-of-tasks-as-a-part-time-job-using-kubernetes
speakers:
 - Michael Juster
track:
 - Use cases
images:
 - /images/sessions/2024/100-airflow-environments.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Balyasny Asset Management (BAM) is a diversified global investment firm founded in 2001 with over $20 billion in assets under management.  We have more than 100 teams who run a variety of workloads that benefit from Orchestration and parallelization.

Platform Engineers working for companies with K8s ecosystems can use their Kubernetes knowledge and leverage their platform to run Airflow and troubleshoot problems successfully.  BAM’s Kubernetes Platform provides production-ready Airflow environments that automatically get Logging, Metrics, Alerting, Scalability, Storage from a range of File Systems, Authentication, Dashboards, Secrets Management, and specialized compute including GPU, CPU Optimized, Memory Optimized and even Windows.  If you can run thousands of Pods on your Kubernetes Cluster then you can run thousands of Tasks without needing to do anything!  The intention of this talk is to cover:
-	Why K8s and Airflow work so well together 
-	How a team of Platform Engineers can leverage their Kubernetes Platform and knowledge to run millions of Tasks without Airflow being their primary focus
-	Examples of where this model can start to fall apart at extreme scale
