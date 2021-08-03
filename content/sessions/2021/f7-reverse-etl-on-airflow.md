---
id: f7
title: "Reverse ETL on Airflow"
url: /sessions/2021/reverse-etl-on-airflow
speakers:
 - Russell Dervay
time_start: 2021-07-15T19:00:00.000Z
time_end: 2021-07-15T19:25:00.000Z
block: f
slot: 7
format: presentation
crowdcast_id: 42
slides: 2021/ReverseETL.pdf
video: https://youtu.be/NGkh8Ql3m5I
---

At Snowflake you can imagine we do a lot of data pipelines and tables curating metrics metrics for all parts of the business. These are the lifeline of Snowflake’s business decisions. We also have a lot of source systems that display and make these metrics accessible to end users. So
 what happens when your data model does not match your system? For example your bookings numbers in salesforce do not match your data model that curates bookings metrics. At snowflake we continued to run into this problem over and over again.

 Having this problem we set out to build an infrastructure that would allow users to effortlessly sync the results of their data pipelines with any downstream / upstream system. Allowing us to have a central source of truth in our warehouse. This infrastructure was built on snowflake using airflow and allows a user to begin syncing data with a few details such as model and system to update.

 In this presentation we will show you how using airflow and snowflake we are able to use our data pipelines as the source of truth for all systems involved in the business. With this infrastructure we are able to use snowflake models as a central source of truth for all applications used throughout the company. This ensures that any number synced in this way seen by two users is always the same.
