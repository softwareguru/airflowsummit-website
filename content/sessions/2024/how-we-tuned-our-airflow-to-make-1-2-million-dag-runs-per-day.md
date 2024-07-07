---
title: "How we tuned our Airflow to make 1.2 million DAG runs - per day!"
slug: how-we-tuned-our-airflow-to-make-1-2-million-dag-runs-per-day
speakers:
 - Jens Scheffler
track:
 - Use cases
images:
 - /images/sessions/2024/tuned-airflow.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

As we deployed Airflow in our enterprise connected to various event sources to implement our data-driven pipelines we were faced with event storms a couple of times. As of such event storms happened often unplanned and with increased load waves we iteratively tuned the setup in multiple iterations. We were in panic and also needed to add some quick workarounds sometime.

Starting from a peak of 1000 triggers in a hour we were happy that workload just queued. But at a certain point we started tuning the setup. With about 10-20 iterations which we would like to share as best practice we started tuning standard parameters, increased resources, changed integration strategies as well and developed patches to core scheduler.

This talk is a retro of the steps we did to share about options to tune and strategies to scale. Being afraid of a queue which degraded performance when having 10000 runs to a peak event reception of 400k runs in an hour it was a long way. You also might hear about some anti-patterns as learning.