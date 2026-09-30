---
title: "Airflow Across Four Regions and a Fleet of Agents: How Notion Runs Its Data Platform"
slug: airflow-across-four-regions-and-a-fleet-of-agents-how-notion-runs-its-data-platform
speakers:
 - Yunhao Qing
track: Data & AI Applications
room: Online
day: 2026o2
time_start: 2026-11-05 6:00:00
time_end: 2026-11-05 6:30:00
timeslot: 1
gridarea: 2/2/3/8
slides: 
video:
---

Notion runs in four AWS regions today, with more on the way, and every data pipeline has to respect where a customer's data lives. Airflow on Astronomer is the control plane that holds this together: two Astro deployments, 500+ DAGs, and region-aware routing to EMR, EMR Serverless, Ray on Anyscale, Kafka, Snowflake, Databricks, and our vector database.

This talk covers the platform patterns that let a small team operate all of that: a generated cell and region model shared by every DAG, so new regions and retired cells propagate without touching pipeline code; DAG factories that fan one config out per region; and per-environment, per-region compute isolation, including the custom Anyscale operator we built and the cloud migrations we ran from DAG config alone.

We then zoom into one concrete workload: indexing Jira, Slack, Google Drive, GitHub, and a dozen other connectors for Notion AI. Kafka feeds Spark and Ray embedding jobs that write to region-local vector indexes. This workload shows both where our abstractions held up and where they broke down, including the per-region DAG file explosion we are still paying down.

Attendees will leave with practical patterns for designing region-aware Airflow platforms: how to model regions and cells, generate DAGs without duplicating business logic, isolate compute by environment and geography, and evolve infrastructure as regions are added, migrated, or retired.