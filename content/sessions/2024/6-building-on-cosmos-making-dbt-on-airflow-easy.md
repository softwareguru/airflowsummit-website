---
title: "Building on Cosmos: Making dbt on Airflow Easy"
slug: building-on-cosmos-making-dbt-on-airflow-easy
speakers:
 - Lewis Macdonald
 - Ethan Stone
time_start: 2024-09-10 11:00:00
time_end: 2024-09-10 11:45:00
room: California West
track: Airflow & ...
day: 20241
timeslot: 6
gridarea: "5/3/6/4"

images: 
 - /images/sessions/2024/building-cosmos.jpg
---

Balyasny Asset Management (BAM) is a diversified global investment firm founded in 2001 with over $20 billion in assets under management. 
 
As dbt took hold at BAM, we had multiple teams building dbt projects against Snowflake, Redshift, and SQL Server. The common question was: How can we quickly and easily productionise our projects? 
 
Airflow is the orchestrator of choice at BAM, but our dbt users ranged from Airflow power users to people who’d never heard of Airflow before. We built a single solution on top of Cosmos that allowed us to: 
 
 - Decouple the dbt project from the Airflow repository  
 - Have each dbt node run as a separate Airflow task 
 - Allow users to run dbt with little to no Airflow knowledge 
 - Enable users to have fine-grained control over how dbt is run and to combine it with other Airflow tasks 
 - Provide observability, monitoring, and alerting.