---
title: "Enhancing DAG Management with DMS: A Scalable Solution for Airflow"
slug: enhancing-dag-management-with-dms-a-scalable-solution-for-airflow
speakers:
 - Sungji Yang
 - DaeHoon Song
topics:
 - Best practices
time_start: 2025-10-07 12:15:00
time_end: 2025-10-07 12:55:00
room: Beckler
track: Best practices
day: 20251
timeslot: 11
gridarea: 5/5/6/6
images: 
slides:
video:
---

In this talk, we will introduce the DAG Management Service (DMS), developed to address critical challenges in managing Airflow clusters. With over 10,000 active DAGs, a single Airflow cluster faces scaling limits and noisy neighbor issues, impacting task scheduling SLAs. DMS enhances reliability by distributing DAGs across multiple clusters and enforcing proper configurations.

We will also discuss how DMS streamlines Airflow version upgrades. Upgrading from an old Airflow version to the latest requires sequential updates and code modifications for over 10,000 DAGs. DMS proposes an efficient upgrade method, reducing dependency on users.

Key functions of DMS include:
1. DAG Deployment: Selectively deploys DAG files from GitHub to Airflow clusters via an event-driven pipeline.
2. DAG Migration: Facilitates seamless DAG migration between clusters, supporting both cluster upgrades and team-specific deployments.
3. Connections and Variables Management: Centralizes management of connection IDs and variables, ensuring consistency and smooth migrations.

Join us to explore how DMS can revolutionize your Airflow DAG management, enhancing scalability, reliability, and efficiency.