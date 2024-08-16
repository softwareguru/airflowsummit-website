---
title: "Empowering business analysts with DAG authoring IDE running 8000 workflows"
slug: empowering-business-analysts-with-dag-authoring-ide-running-8000-workflows
speakers:
 - Daniil Dubin
time_start: 2024-09-12 14:00:00
time_end: 2024-09-12 14:25:00
room: California East
track: Use cases
day: 20243
timeslot: 98
gridarea: "11/2/12/3"
images: 
 - /images/sessions/2024/empowering-business.jpg
---

At Wix more often than not business analysts build workflows themselves to avoid data engineers being a bottleneck. But how do you enable them to create SQL ETLs starting when dependencies are ready and sending emails or refreshing Tableau reports when the work is done? One simple answer may be to use Airflow. The problem is every BA cannot be expected to know Python and Git so well that they will create thousands of DAGs easily.
 
 
 
 To bridge this gap we have built a web-based IDE, called Quix, that allows simple notebook-like development of Trino SQL workflows and converts them to Airflow DAGs when a user hits the “schedule” button.
 
 
 
 During the talk we will go through the problems of building a reliable and extendable DAG generating tool, why we preferred Airflow over Apache Oozie and also tricks (sharding, HA-mode, etc) allowing Airflow to run 8000 active DAGs on a single cluster in k8s.