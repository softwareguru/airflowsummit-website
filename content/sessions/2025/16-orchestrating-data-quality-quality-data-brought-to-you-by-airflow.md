---
title: "Orchestrating Data Quality - Quality Data Brought To You By Airflow"
slug: orchestrating-data-quality-quality-data-brought-to-you-by-airflow
speakers:
 - Maggie Stark

topics:
 - Best practices
time_start: 2025-10-07 14:00:00
time_end: 2025-10-07 14:25:00
room: Beckler
track: Best practices
day: 20251
timeslot: 16
gridarea: 7/5/8/6
images: 
slides:
video: https://youtu.be/Y4xM5TpF7lo
summary: "We’ll explore how the Astronomer data team leverages Airflow to uphold data quality across complex pipelines; minimizing firefighting and maximizing confidence in reported metrics."
---

Ensuring high-quality data is essential for building user trust and enabling data teams to work efficiently. In this talk, we’ll explore how the Astronomer data team leverages Airflow to uphold data quality across complex pipelines; minimizing firefighting and maximizing confidence in reported metrics.

Maintaining data quality requires a multi-faceted approach: safeguarding the integrity of source data, orchestrating pipelines reliably, writing robust code, and maintaining consistency in outputs. We’ve embedded data quality into the DevEx experience, so it’s always at the forefront instead of in the backlog of tech debt.

We’ll share how we’ve operationalized:

- Implementing data contracts to define and enforce expectations
- Differentiating between critical (pipeline-blocking) and non-critical (soft) failures
- Exposing upstream data issues to domain owners
- Tracking metrics to measure overall data quality of our team

Join us to learn practical strategies for building scalable, trustworthy data systems powered by Airflow.