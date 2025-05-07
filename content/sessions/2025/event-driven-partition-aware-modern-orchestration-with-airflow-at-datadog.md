---
title: "Event-Driven, Partition-Aware: Modern Orchestration with Airflow at Datadog"
slug: event-driven-partition-aware-modern-orchestration-with-airflow-at-datadog
speakers:
 - Julien Le Dem
topics:
 - Use cases
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

Datadog is a world-class data platform ingesting more than a 100 trillion events a day, providing real-time insights.

Before Airflow’s prominence, we built batch processing on Luigi, Spotify’s open-source orchestrator. As Airflow gained wide adoption, we evaluated adopting the major improvements of release 2.0, but opted for building our own orchestrator instead to realize our dataset-centric, event-driven vision.

Meanwhile, the 3.0 release aligned Airflow with the same vision we pursued internally, as a modern asset-driven orchestrator. It showed how futile it is to build our own compared to the momentum of the community. We evaluated several orchestrators and decided to join forces with the Airflow project.

This talk follows our journey from building a custom orchestrator to adopting and contributing to Airflow 3. We’ll share our thought process, our asset partitions use case, and how we’re working with the community to materialize the Data Awareness (AIP-73) vision. Partition-based incremental scheduling is core to our orchestration model, enabling scalable, observable pipelines thanks to Datadog’s Data Observability product providing visibility into pipeline health.