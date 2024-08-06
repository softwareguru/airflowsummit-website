---
title: "Comparing Airflow Executors and Custom Environments"
slug: comparing-airflow-executors-and-custom-environments
speakers:
 - Mikhail Epikhin
time_start: 2024-09-11 11:30:00
time_end: 2024-09-11 11:55:00
room: Elizabethan A+B
track: Airflow & ...
day: 20242
timeslot: 51
gridarea: "6/4/7/5"
images: 
 - /images/sessions/2024/comparing-executors.jpg
---

With recent works in the direction of Executor Decoupling and interest in Hybrid Execution, we find it's still quite common for Airflow users to use the old-time rule of thumbs like "Don't Use Airflow with LocalExecutor in production", "If your scheduler lags, split your DAGs over two separate Airflow Clusters", and so on. In our talk, we will show a deep dive comparison between various Execution models Airflow support and hopefully update understanding of their efficiency and limitations.