---
title: "Automated Testing and Deployment of DAGs"
slug: automated-testing-and-deployment-of-dags
speakers:
 - Austin Bennett
track:
 - Use cases
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

DAG integrity is critical. So are coding conventions, consistency in standards for the group. In this talk, we will share the various lessons learned in ChartBoost for testing/verifying our DAGs as part of our GitHub workflows [ for testing as part of the pull request process, and for automated deployment - eventually to production - once merged ]. We will dig into how we have unlocked additional efficiencies, catch errors before they get deployed, and generally how we are better off for having both Airflow & plenty of checks in our CI, before we merge/deploy.