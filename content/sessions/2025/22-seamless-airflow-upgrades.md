---
title: "Seamless Airflow Upgrades: Migrating from 2.x to 3"
slug: seamless-airflow-upgrades
speakers:
 - Ankit Chaurasia
topics:
 - Best practices
time_start: 2025-10-07 15:00:00
time_end: 2025-10-07 15:25:00
room: Columbia C
track: Best practices
day: 20251
timeslot: 22
gridarea: 9/3/10/4
images: 
 - /images/sessions/2025/seamless-airflow-upgrades.png
slides: 2025/seamless-airflow-upgrades-migrating-from-2_x-to-3.pdf
video: https://youtu.be/u-Ce_VWumoA
summary: "Join this session for live demos and practical examples that will empower you to confidently upgrade from Airflow 2, minimise downtime, and achieve optimal performance in Airflow 3."
---

Airflow 3 has officially arrived! In this session, we’ll start by discussing prerequisites for a smooth upgrade from Airflow 2.x to Airflow 3, including airflow version requirements, removing deprecated SubDAGs, and backing up and cleaning your metadata database prior to migration. We'll then explore the new CLI utility: airflow config update [—-fix] for auto-applying configuration changes. We’ll demo cleaning old XCom data to speed up schema migration.

During this session, attendees will learn to verify and adapt their pipelines for Airflow 3 using a Ruff-based upgrade utility. I will demo run ruff check dag/ --select AIR301 to surface scheduling issues, inspect fixes via ruff check dag/ --select AIR301 --show-fixes, and apply corrections with ruff check dag/ --select AIR301 --fix. We'll also examine rules AIR302 for deprecated config and AIR303 for provider package migrations. By the end, your DAGs will pass all AIR3xx checks error-free. 

Join this session for live demos and practical examples that will empower you to confidently upgrade, minimise downtime, and achieve optimal performance in Airflow 3.