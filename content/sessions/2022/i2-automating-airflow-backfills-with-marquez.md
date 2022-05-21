---
id: i2
title: "Automating Airflow Backfills with Marquez"
url: /sessions/2022/automating-airflow-backfills-with-marquez
speakers:
 - Willy Lulciuc
time_start: 2022-05-26T04:00:00.000Z
time_end: 2022-05-26T04:45:00.000Z
session_type: "Presentation"
hosted_by: Melbourne
presence: "remote"
block: i
slot: 2
---

As a data engineer, backfilling data is an important part of your day-to-day work. But, backfilling interdependent DAGs is time-consuming and often associated with an unpleasant experience. For example, let's say you were tasked with backfilling a few months worth of data. You’re given the start and end date for the backfill that will be used to run an ad-hoc backfilling script that you have painstakingly crafted locally on your machine. As you sip your morning coffee, you kick off the backfilling script, hoping it’ll work, and think to yourself, there must be a better way. Yes, there is, and collecting DAG lineage metadata would be a great start!
 
In this talk, Willy Lulciuc will briefly introduce you to how backfills are handled in Airflow, then discuss how DAG lineage metadata stored in Marquez can be used to automate backfilling DAGs with complex upstream and downstream dependencies.