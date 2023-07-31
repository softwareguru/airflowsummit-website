---
title: "Airflow at Reddit: How we migrated from Airflow 1 to Airflow 2"
slug: airflow-at-reddit-how-we-migrated-from-airflow-1-to-airflow-2
speakers:
 - Dave Milmont
 - Branden West
time_start: 2023-09-19T14:00:00-04:00
time_end: 2023-09-19T14:25:00-04:00
day: 1
timeslot: 9
timeorder: 1
room: Ballroom C-D
track: Use cases
images:
 - /images/sessions/2023/Dave+Branden.jpg

---

We would love to speak about our experience upgrading our old airflow 1 infrastructure to airflow 2 on kubernetes and how we orchestrated the migration of approximately 1500 DAGs that were owned by multiple teams in our organization. We had some interesting challenges along the way and can speak about our solutions.
 
Points we can talk about:  
 1. Old airflow 1 infrastructure and why we decided to move to kubernetes for airflow 2.    
 2. Possible migration paths we thought of and why we chose the route we did.   
 
 Things we did to make the migration easier to achieve:  
 1. Implementing dag factories - used some neat programmatic approaches to make a great factory interface for our users.
 2. Custom cross airflow instance dag dependency solution. 
 3. DAG audits - how we programmatically determined which dags were actually still being used to reduce migration load.
 
 Problems that we faced: 
 1. DAG ownership
 2. Backfilling in airflow 2 k8s
 3. DAG dependencies