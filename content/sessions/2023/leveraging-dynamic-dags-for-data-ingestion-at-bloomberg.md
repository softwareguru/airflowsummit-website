---
title: "Leveraging Dynamic DAGs for Data Ingestion at Bloomberg"
slug: leveraging-dynamic-dags-for-data-ingestion-at-bloomberg
speakers:
 - Ivan Sayapin
 - Yenny Su
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
---

Bloomberg's Data Platform Engineering team powers some of the most valuable business and financial data on which Bloomberg clients rely. We recently built a configuration-driven system that allows non-engineers to onboard alternative datasets into the company's ecosystem. This system uses Apache Airflow to orchestrate the data flow across different applications and Bloomberg Terminal functions. We are unique in that we have over 1500 dynamic DAGs tailored for each dataset's needs (which very few Airflow users have). In this talk, we will review our high-level Airflow architecture, how we leverage the dynamic DAGs in our ETL pipeline, as well as review some of the challenges we faced.