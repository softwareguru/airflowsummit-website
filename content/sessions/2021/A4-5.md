---
title: "Pinterest’s Migration Journey"
url: /sessions/Pinterest’s-Migration-Journeyace
speakers:
 - Ace Haidrey
block: 
time_start: 2021-07-18T16:00:00.000Z
time_end: 2021-07-18T16:45:00.000Z
draft: false
---

Last year, we were able to share why we have selected Airflow to be our next generation workflow system. This year, we will dive into the journey of migrating over 3000+ workflows and 45000+ tasks to Airflow. We will discuss the infrastructure additions to support such loads, the partitioning and prioritization of different workflow tiers defined in house, the migration tooling we built to get users to onboard, the translation layers between our old DSLs and the new, our internal k8s executor to leverage Pinterest’s kubernetes fleet, and more. We want to share the challenges both technically and usability wise to get such large migrations over the course of a year, and how we overcame it to successfully migrate 100% of the workflows to our inhouse workflow platform branded Spinner.
