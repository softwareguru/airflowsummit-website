---
title: "Testing Airflow DAGs with Dagtest"
slug: testing-airflow-dags-with-dagtest
speakers:
 - Victor Chiapaikeo
 - Aldo Orozco Gomez
time_start: 2023-09-19T17:15:00-04:00
time_end: 2023-09-19T17:40:00-04:00
room: York
track: Airflow basics
day: 1
timeslot: 16
images:
 - /images/sessions/2023/VictorChiapaikeo.jpg
video: https://youtu.be/wkAb8mDDHMs
slides: 2023/1-York-1715-Testing-Airflow-DAGs-with-Dagtest.pdf
---

For the dag owner, testing Airflow DAGs can be complicated and tedious. Kubectl cp your dag from local to pod, exec into the pod, and run a command? Install breeze? Why pull the Airflow image and start up the webserver / scheduler / triggerer if all we want is to test the addition of a new task?
 
 
 
 It doesn't have to be this hard. At Etsy, we've simplified testing dags for the dag owner with dagtest. Dagtest is a Python package that we house on our internal PyPi. It is a small client binary that makes HTTP requests to a test API. The test API is a simple Flask server that receives these requests and builds pods to run `airflow dags backfill` commands based on the options provided via dagtest. The simplest of these is a dry-run. Typically, users run test runs where the dag executes E2E for a single ds.
 
 
 
 Equally important is the environment setup. We use an adhoc Airflow instance in a separate GCP environment with an SA that cannot write to Production buckets. This talk will discuss both.