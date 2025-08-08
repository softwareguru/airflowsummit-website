---
title: "Enabling SQL testing in Airflow workflows using Pydantic types"
slug: enabling-sql-testing-in-airflow-workflows-using-pydantic-types
speakers:
 - Gurmeet Saran
 - Kushal Thakkar
topics:
 - Airflow & ...
time_start: 2025-10-09 15:45:00
time_end: 2025-10-09 16:10:00
room: Columbia D
track: Airflow & ...
day: 20253
timeslot: 175
gridarea: 15/4/16/5
slides:
video:
---

This session explores how to bring unit testing to SQL pipelines using Airflow. I’ll walk through the development of a SQL testing library that allows isolated testing of SQL logic by injecting mock data into base tables. To support this, we built a type system for AWS Glue tables using Pydantic, enabling schema validation and mock data generation. Over time, this type system also powered production data quality checks via a custom Airflow operator. Learn how this approach improves reliability, accelerates development, and scales testing across data workflows.