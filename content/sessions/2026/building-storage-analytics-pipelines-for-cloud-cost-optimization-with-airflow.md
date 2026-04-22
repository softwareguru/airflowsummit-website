---
title: "Building storage analytics pipelines for cloud cost optimization with Airflow"
slug: building-storage-analytics-pipelines-for-cloud-cost-optimization-with-airflow
speakers:
 - Bao Nguyen
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Storage usage is a major driver of infrastructure cost for media collaboration platforms. Understanding how storage grows across accounts, assets, and workflows requires analytics pipelines that combine product data with infrastructure metrics.

In this talk, I'll share how we built storage analytics pipelines that model storage usage across accounts and plan tiers to help leadership understand infrastructure cost drivers. Using warehouse data models orchestrated with Airflow, we developed pipelines that track storage usage over time, identify discrepancies in legacy storage calculations, and resolve edge-cases. 

These pipelines enabled deeper analysis of storage growth and informed changes to asset lifecycle policies that significantly reduced cloud storage costs. 

What attendees will learn:
- How to design analytics pipelines for infrastructure usage data
- Modeling storage usage across accounts and assets
- Using Airflow to orchestrate infrastructure analytics workflows 
- Turning analytics insights into infrastructure cost optimization