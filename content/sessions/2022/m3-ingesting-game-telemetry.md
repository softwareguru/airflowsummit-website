---
id: m3
title: "Ingesting Game Telemetry in near Real-time dynamically into Redshift with Airflow (WB Games)"
url: /sessions/2022/ingesting-game-telemetry
speakers:
 - Karthik Kadiyam
time_start: 2022-05-27T17:00:00.000Z
time_end: 2022-05-27T17:50:00.000Z
session_type: "Presentation"
hosted_by: Online
presence: remote
block: m
slot: 3
video: https://youtu.be/l5lX_Qvav6k
slides: 2022/m3-IngestingGameTelemetry-Karthik.pdf
---

We the Data Engineering Team here at WB Games implemented an internal Redshift Loader DAG(s) on Airflow that allow us to ingest data in near real-time at scale into Redshift, taking into account variable load on the DB and been able to quickly catch up data loads in case of various DB outages or high usage scenarios.
  
Highlights:
  * Handle any type of Redshift outages and system delays dynamically between multiple sources(S3) to sinks(Redshift).
  * Auto tuning data copies for faster data backfill in case of delay without overwhelming commit queue.
  * Supports schema evolution on Game data dynamically.
  * Maintain data quality to ensure we do not create data gaps or dupes.
  * Provide embedded custom metrics for deeper insights and anomaly detection.
  * Airflow config based Declarative Dag implementation.

