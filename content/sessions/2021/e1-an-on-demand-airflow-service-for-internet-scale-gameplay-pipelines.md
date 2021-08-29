---
id: e1
title: "An On-Demand Airflow Service for Internet Scale Gameplay Pipelines"
url: /sessions/2021/an-on-demand-airflow-service-for-internet-scale-gameplay-pipelines
speakers:
 - Nitish Victor
 - Yuanmeng Zeng
time_start: 2021-07-15T04:00:00.000Z
time_end: 2021-07-15T04:25:00.000Z
block: e
slot: 1
format: adoption
crowdcast_id: 32
video: https://youtu.be/t4BdWuu--io
slides: 2021/e1-OnDemandAirflowService.pdf
---

EA Games have very dynamic and federated needs on their data processing pipelines. Many individual studios within EA build and manage the data pipelines for their games iterating rapidly through game development cycles. Developer productivity around orchestrating these pipelines is as critical as providing a robust production quality orchestration service. With these in mind, we re-engineered our Airflow service ground up to cater to our large internal user base (1000s) and internet scale data processing systems (Petabytes of data). This session details the evolution of the use of Airflow at EA Digital Platform from a monolithic multi-tenant instance to an "On-Demand" system where teams and studios create their own dedicated Airflow instance with all the necessary bells-and-whistles required at the click of a button - and allows them to immediately get their data pipelines running. We also elaborate how Airflow is interwoven into a "Self Serve" model for ETL pipelines within our teams with the objective of truely democratizing data across our games.
