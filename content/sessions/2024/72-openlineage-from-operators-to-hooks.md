---
title: "OpenLineage: From Operators to Hooks"
slug: openlineage-from-operators-to-hooks
speakers:
 - Maciej Obuchowski
time_start: 2024-09-11 16:30:00
time_end: 2024-09-11 16:55:00
room: Elizabethan A+B
track: New features
day: 20242
timeslot: 72
gridarea: "15/4/16/5"
images: 
 - /images/sessions/2024/open-lineage.jpg
---

"More data lineage" has been second most popular feature request in Airflow Survey 2023. However, despite the integration of OpenLineage in Airflow 2.7 through AIP-53, the most popular Operator in Airflow - PythonOperator - isn't covered by lineage support.
 
 
 
 With addition of TaskFlow API, Airflow Datasets, Airflow ObjectStore, and many other small changes, writing DAGs without using other operators is easier than ever. And that's why lineage collection in Airflow moves beyond covering specific Operators, to covering Hooks and Object Storage.
 
 
 
 In this session, you'll learn how newly added AIP-62 will allow you author DAGs the way you love, while also keeping benefits of a data pipeline well covered by lineage.