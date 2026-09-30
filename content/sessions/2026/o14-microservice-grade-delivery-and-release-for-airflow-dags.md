---
title: "Microservice-Grade Delivery and Release for Airflow DAGs"
slug: microservice-grade-delivery-and-release-for-airflow-dags
speakers:
 - Piyush Maheshwari
 - Sameer Raj
track: Builder
room: Online
day: 2026o2
time_start: 2026-11-05 13:00:00
time_end: 2026-11-05 13:30:00
timeslot: 5
gridarea: 7/2/8/8
slides: 
video:
---

At Uber, preparing Airflow to take on workloads from Piper (our Airflow 1 fork operating at nearly one million daily task runs) requires rethinking both DAG delivery and release. Shipping a multi-GB monorepo artifact to isolated Kubernetes executors for every task is neither fast nor efficient.

We’ll share how dependency-aware slim bundles package only the required DAG code, first-party dependencies and generated artifacts into reproducible bundles. We’ll then cover per-DAG version pinning, which separates code distribution from activation and enables pre-production regression gates, controlled promotion and automated rollback.

Attendees will learn practical patterns and trade-offs for monorepo dependency resolution, bundle granularity, Kubernetes execution and safer DAG releases. We’ll also discuss AIP-109, our proposal to contribute DAG version pinning to Apache Airflow.