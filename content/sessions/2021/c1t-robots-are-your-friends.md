---
id: c1t
title: "Robots are your friends - using automation to keep your Airflow operators up to date"
url: /sessions/2021/robots-are-your-friends
speakers:
 - Leah Cole
time_start: 2021-07-13T16:00:00.000Z
time_end: 2021-07-13T16:10:00.000Z
block: c
slot: 1t
---

As part of my role at Google, maintaining samples for Cloud Composer, hosted managed Airflow, is crucial. It's not feasible for me to try out every sample every day to check that it's working. So, how do I do it?
 
 Automation! While I won't let the robots touch everything, they let me know when it's time to pay attention. Here's how:
 
 Step 0: An update for the operators is released
 Step 1: A GitHub bot called Renovate Bot opens up a PR to a special requirements file to make this update
 Step 2: Cloud build runs unit tests to make sure none of my DAGs immediately break
 Step 3: PR is approved and merged to main
 Step 4: Cloud Build updates my dev environment
 Step 5: I look at my DAGs in dev to make sure all is well. If there is a problem, I need to resolve it manually and revert my requirements file. 
 Step 6: I manually update my prod PyPI packages
 
 I'll discuss what automation tools I choose to use and why, and the places where I intentionally leave manual steps to ensure proper oversight.