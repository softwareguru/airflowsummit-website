---
title: "Architecting Multi-Tenant ML Governance & Privacy in Airflow"
slug: architecting-multi-tenant-ml-governance-privacy-in-airflow
speakers:
 - Serjesh Sharma
 - John MacMillan
track: Data & AI Applications
room: Online
day: 2026o1
time_start: 2026-11-04 21:00:00
time_end: 2026-11-04 21:30:00
timeslot: 9
gridarea: 11/2/12/8
slides: 
video:
---

In enterprise SaaS, orchestrating ML models on sensitive workforce data requires zero compromise on data privacy and multi-tenant isolation. Workday's Scheduling & Labor Optimization product uses Airflow to power predictive workforce forecasts across thousands of customer tenants—where each customer strictly owns their data and model artifacts.   This session demonstrates how Workday leverages Airflow for multi-tenant ML pipeline orchestration. 
We cover how Airflow dynamically materializes isolated ML DAGs per tenant, enforces strict execution boundaries via TENANT_KEY metadata, and automates lifecycle operations for customer opt-in and opt-out workflows, including mandatory 14-day data/model purges.   
Key Problems Solved:   
1. Strict Data & Model Privacy: Isolating tenant data and training models exclusively on tenant-owned datasets.  
2.  Lifecycle Compliance: Triggering DAG creation on opt-in and managing grace periods with enforced 14-day purges on opt-out.   3. Operational Efficiency: Scaling thousands of dynamic DAGs using VPA/Scaleops autoscaling without scheduler overhead.

Session Outline :   
1. Overview & Challenge 
2.  Multi-tenant ML privacy in SaaS.   
3. Dynamic DAG Architecture  
4. Event-driven materialization and TENANT_KEY isolation.   
5. Lifecycle Compliance 
6. Dynamic enrollment and automated 14-day deletion pipelines.   Scaling & Infrastructure 
7. Resource optimization with ScaleOps/VPA

Takeaways: 
1.   Design patterns for dynamic per-tenant DAG generation.   
2. Enforcing tenant isolation, security boundaries, and model governance in Airflow.   
3. Building compliance workflows for dynamic opt-in/opt-out retention policies.   
