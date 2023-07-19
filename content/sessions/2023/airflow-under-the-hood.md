---
title: "Airflow: Under the hood"
slug: airflow-under-the-hood
speakers:
 - Utkarsh Sharma
time_start: 2023-09-19T11:30:00-04:00
time_end: 2023-09-19T12:00:00-04:00
day: 1
timeslot: 5
room: York
track: Airflow basics
---

Making a contribution to or becoming a committer on Airflow can be a daunting task, even for experienced Python developers and Airflow users. The sheer size and complexity of the code base may discourage potential contributors from taking the first steps. To help alleviate this issue, this session is designed to provide a better understanding of how Airflow works and build confidence in getting started.
 
During the session, we will introduce the main components of Airflow, including the Web Server, Scheduler, and Workers. We will also cover key concepts such as DAGs, DAG-run objects, Tasks, and Task Instances. Additionally, we will explain how tasks communicate with each other using XComs, and discuss the frequency of DAG runs based on the schedule. To showcase changes in the state of various objects, we will dive into the code level and continuously share the state of the database at every important checkpoint.