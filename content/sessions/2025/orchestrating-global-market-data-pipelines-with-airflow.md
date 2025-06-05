---
title: "Orchestrating Global Market Data Pipelines with Airflow"
slug: orchestrating-global-market-data-pipelines-with-airflow
speakers:
 - Di Wu
topics:
 - Use cases
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
images:
 - /images/sessions/2025/orchestrating-global.png
---

In this presentation, I will highlight how Apache Airflow addresses key data management challenges for Exchange-Traded Funds (ETFs) in the global financial market. ETFs, which combine features of mutual funds and stocks, track indexes, commodities, or baskets of assets and trade on major stock exchanges. Because they operate around the clock across multiple time zones, ETF managers must navigate diverse regulations, coordinate complex operational constraints, and ensure accurate valuations. This often requires integrating data from vendors for pricing and reference details. These data sets arrive at different times, can conflict, and must pass rigorous quality checks before being published for global investors. Managing updates, orchestrating workflows, and maintaining high data quality present significant hurdles. Apache Airflow tackles these issues by scheduling repetitive tasks and enabling event-triggered job runs for immediate data checks. It offers monitoring and alerting, thus reducing manual intervention and errors. Using DAGs, Airflow scales efficiently, streamlining complex data ingestion, validation, and publication processes.