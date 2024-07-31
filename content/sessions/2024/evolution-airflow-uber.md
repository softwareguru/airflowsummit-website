---
title: "Evolution of Airflow at Uber"
speakers:
 - Shobhit Shah
 - Sumit Maheshwari
images:
 - /images/sessions/2024/uber.jpg 
track:
 - Use cases
time_start: 2024-09-10T16:00:00.000Z
time_end: 2024-09-10T16:45:00.000Z
draft: false
---

Up until a few years ago, teams at Uber used multiple data workflow systems, with some based on open source projects such as Apache Oozie, Apache Airflow, and Jenkins while others were custom built solutions written in Python and Clojure.

Every user who needed to move data around had to learn about and choose from these systems, depending on the specific task they needed to accomplish. Each system required additional maintenance and operational burdens to keep it running, troubleshoot issues, fix bugs, and educate users.

After this evaluation, and with the goal in mind of converging on a single workflow system capable of supporting Uber's scale, we settled on an Airflow-based system. The Airflow-based DSL provided the best trade-off of flexibility, expressiveness, and ease of use while being accessible for our broad range of users, which includes data scientists, developers, machine learning experts, and operations employees.

This talk will focus on scaling Airflow to Uber's scale and providing a no-code seamless user experience.