---
title: "Data-Centric Airflow"
slug: data-centric-airflow
speakers:
 - Tzu-ping Chung
track:
 - New features
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

While Airflow has its roots in ETL workflows, it is now more and more common for people to use it in a variety of ways. A traditional ETL approach thinks mainly in functions, while data being considered a side effect of the functions, and generally do not have a presence at all in user-facing interfaces.

In a data-centric mindset, however, users put data front-and-center instead, and think the operations as a means to create new data from upstream data. This creates a mismatch between the user’s mental model, and how the same thing is represented in Airflow, requiring additional mental overhead to describe how the user wants in Airflow’s design language.