---
title: "Beyond XComs - A Deep Dive into Passing Data Between Tasks"
slug: beyond-xcoms-a-deep-dive-into-passing-data-between-tasks
speakers:
 - Jeff Fletcher
time_start: 2023-09-20T17:15:00-04:00
time_end: 2023-09-20T17:40:00-04:00
room: Ballroom A-B
track: Operationalizing Airflow
day: 2
timeslot: 16
images:
 - /images/sessions/2023/JeffFletcher.jpg

---

Passing large amounts of data between tasks in Airflow used to be considered an anti-pattern. This is because of the limitations inherent in the way XComs was initially implemented. However Airflow is both evolving and is very customisable, and these limitations are now easily overcome to make moving of large data between tasks not only possible, but also preferable. 
 
In this talk I will explore different ways of passing data between tasks, and the pros and cons of each.  
 
I will also look at using Airflow with additional tools for passing data between tasks like Spark, Ray, Dask, Pandas and DuckDB to compare them for processing speed and implementation complexity. We will look at what each tool is best suited for and when to consider them.
 
Finally the talk will wrap up with a demo that shows how to do distributed processing using Airflow and DuckDB.