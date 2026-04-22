---
title: "From Experiments to Production: How We Built a Lightweight ML Platform on Airflow"
slug: from-experiments-to-production-how-we-built-a-lightweight-ml-platform-on-airflow
speakers:
 - Marion Azoulai
topics:
 - 
room: 
time_start: 2026-07-31 9:00:00
time_end: 2026-07-31 9:45:00
---

Many data teams can build machine learning models, but operationalizing them reliably remains a challenge.

At Astronomer, our data team recently moved from exploratory modeling to running multiple production ML models powering go-to-market analytics and workflows. Rather than introducing heavy MLOps infrastructure, we integrated the full ML lifecycle directly into our Airflow-based data platform.

In this talk, we’ll share how we use Airflow to orchestrate production ML end-to-end: from feature pipelines in Snowflake, to model training and artifact promotion, to batch scoring and prediction delivery.

We’ll also show how reusable Airflow task groups and a declarative DAG framework allowed us to standardize model deployment, monitoring, and retraining across models.

This approach enabled us to go from zero to several production ML models in just a few months while keeping the system simple, scalable, and fully integrated with our existing data workflows.

Attendees will leave with practical patterns for operationalizing ML using Airflow without building a complex MLOps stack.