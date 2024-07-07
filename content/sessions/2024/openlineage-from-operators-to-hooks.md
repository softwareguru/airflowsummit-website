---
title: "OpenLineage: From Operators to Hooks"
slug: openlineage-from-operators-to-hooks
speakers:
 - Maciej Obuchowski
track:
 - New features
images:
 - /images/sessions/2024/open-lineage.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

"More data lineage" has been second most popular feature request in Airflow Survey 2023. However, despite the integration of OpenLineage in Airflow 2.7 through AIP-53, the most popular Operator in Airflow - PythonOperator - isn't covered by lineage support.

With addition of TaskFlow API, Airflow Datasets, Airflow ObjectStore, and many other small changes, writing DAGs without using other operators is easier than ever. And that's why lineage collection in Airflow moves beyond covering specific Operators, to covering Hooks and Object Storage.

In this session, you'll learn how newly added AIP-62 will allow you author DAGs the way you love, while also keeping benefits of a data pipeline well covered by lineage.