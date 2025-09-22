---
title: "Driving Analytics with Open Source: Airbyte, dbt, Airflow & Metabase"
slug: driving-analytics
speakers:
 - Ayoade Adegbite
time_start: 2025-10-16 17:00:00
time_end: 2025-10-16 17:30:00
room: Online
track: Airflow & ...
day: 20255
timeslot: 15
gridarea: 7/2/8/3
images: 
slides:
video:
---

In this talk, I’ll walk through how we built an end-to-end analytics pipeline using open-source tools ( Airbyte, dbt, Airflow, and Metabase). At WirePick, we extract data from multiple sources using Airbyte OSS into PostgreSQL, transform it into business-specific data marts with dbt, and automate the entire workflow using Airflow. Our Metabase dashboards provide real-time insights, and we integrate Slack notifications to alert stakeholders when key business metrics change.

This session will cover:
- Data extraction: Using Airbyte OSS to pull data from multiple sources
- Transformation & Modeling: How dbt helps create reusable data marts
- Automation & Orchestration: Managing the workflow with Airflow
- Data-driven decision-making: Delivering insights through Metabase & Slack alerts