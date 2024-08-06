---
title: "Evolution of Airflow at Uber"
slug: evolution-of-airflow-at-uber
speakers:
 - Shobhit Shah
 - Sumit Maheshwari
time_start: 2024-09-12 12:30:00
time_end: 2024-09-12 13:15:00
room: Georgian
track: Use cases
day: 20243
timeslot: 96
gridarea: "8/5/9/6"
images: 
 - /images/sessions/2024/uber.jpg
---

Up until a few years ago, teams at Uber used multiple data workflow systems, with some based on open source projects such as Apache Oozie, Apache Airflow, and Jenkins while others were custom built solutions written in Python and Clojure. 
 
 
 
 Every user who needed to move data around had to learn about and choose from these systems, depending on the specific task they needed to accomplish. Each system required additional maintenance and operational burdens to keep it running, troubleshoot issues, fix bugs, and educate users. 
 
 
 
 After this evaluation, and with the goal in mind of converging on a single workflow system capable of supporting Uber's scale, we settled on an Airflow-based system. The Airflow-based DSL provided the best trade-off of flexibility, expressiveness, and ease of use while being accessible for our broad range of users, which includes data scientists, developers, machine learning experts, and operations employees.
 
 
 
 This talk will focus on scaling Airflow to Uber's scale and providing a no-code seamless user experience