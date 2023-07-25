---
title: "Accelerating Data Delivery: How the FT automated its ETL pipelines with Airflow"
slug: accelerating-data-delivery-how-the-ft-automated-its-etl-pipelines-with-airflow
speakers:
 - Vladi Nekolov
 - Zdravko Hvarlingov
time_start: 2023-09-20T17:15:00-04:00
time_end: 2023-09-20T17:40:00-04:00
room: Ballroom C-D
track: Use cases
day: 2
timeslot: 16
---

Inside the Financial Times, we’ve been gradually moving our batching data processing from a custom solution to Airflow. To enable various teams within the company to use Airflow more effectively, we've been working on extending the system's self-service capabilities. This includes giving ownership to teams of their DAGs and separating resources such as connections.

The batch data ingestion processes are the main ETL - like jobs that we run on Airflow. The creation of a new job used to be a manual and repetitive task of receiving the data specification, creating the requisite tables in our data warehouse and writing the DAG that would move the data there. Airflow allowed us to automate this process to a degree that surprised us, completely removing the need to write DAG code.

We will use the talk to describe what the current process of creating a new ETL workflow looks like and our plans for further improvements.