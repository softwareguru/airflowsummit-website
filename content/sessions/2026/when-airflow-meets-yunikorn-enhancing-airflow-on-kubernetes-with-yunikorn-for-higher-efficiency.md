---
title: "When Airflow Meets Yunikorn: Enhancing Airflow on Kubernetes with Yunikorn for Higher Efficiency"
slug: when-airflow-meets-yunikorn-enhancing-airflow-on-kubernetes-with-yunikorn-for-higher-efficiency
speakers:
 - Xiaodong Deng
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Apache Airflow’s Kubernetes integration enables flexible workload execution on Kubernetes but lacks advanced resource management features including application queueing, tenant isolation and gang scheduling. These features are increasingly critical for data engineering as well as AI/ML use cases, particularly GPU utilization optimization. For example, gang scheduling ensures all required resources for a job are allocated atomically, preventing partial allocations that waste resources. Apache Yunikorn, a Kubernetes-native scheduler, addresses these gaps by offering a high-performance alternative to Kubernetes default scheduler. In this talk, we'll demonstrate how to conveniently leverage Yunikorn's power in Airflow, along with practical use cases and examples.