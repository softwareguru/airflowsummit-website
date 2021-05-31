---
id: h5-6
title: "Customizing Xcom to enhance data sharing between tasks"
url: /sessions/2021/customizing-xcom-to-enhance-data-sharing-between-tasks
speakers:
 - Vikram Koka
 - Ephraim Anierobi
time_start: 2021-07-16T18:00:00.000Z
time_end: 2021-07-16T18:50:00.000Z
block: h
slot: 5-
---

In Apache Airflow, Xcom is the default mechanism for passing data between tasks in a DAG. In practice, this has been restricted to small data elements, since the Xcom data is persisted in the Airflow metadatabase and is constrained by database and performance limitations. 
 
 With the new TaskFlow API introduced in Airflow 2.0, it is seamless to pass data between tasks and the use of Xcom is invisible. However, the ability to pass data is restricted to a relatively small set of data types which can be natively converted in JSON. 
 
 This tutorial describes how to go beyond these limitations by developing and deploying a Custom Xcom backend within Airflow to enable the sharing of large and varied data elements such as Pandas data frames between tasks in a data pipeline, using a cloud storage such as Google Storage or Amazon S3.