---
title: "Common provider abstractions: Key for multi-cloud data handling"
slug: common-provider-abstractions-key-for-multi-cloud-data-handling
speakers:
 - Vikram Koka
topics:
 - Best practices
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

Enterprises want the flexibility to operate across multiple clouds, whether to optimize costs, improve resiliency, to avoid vendor lock-in, or for data sovereignty. But for developers, that flexibility usually comes at the cost of extra complexity and redundant code. The goal here is simple: write once, run anywhere, with minimum boilerplate. 
In Apache Airflow, we’ve already begun tackling this problem with abstractions like Common-SQL, which lets you write database queries once and run them on 20+ databases, from Snowflake to Postgres to SQLite to SAP HANA. Similarly, Common-IO standardizes cloud blob storage interactions across all public clouds. 
With Airflow 3.0, we are pushing this further by introducing a Common Message Bus provider, which is an abstraction, initially supporting Amazon SQS and expanding to Google PubSub and Apache Kafka soon after. We expect additional implementations such as Amazon Kinesis and Managed Kafka over time.

This talk will dive into why these abstractions matter, how they reduce friction for developers while giving enterprises true multi-cloud optionality, and what’s next for Airflow’s evolving provider ecosystem. 