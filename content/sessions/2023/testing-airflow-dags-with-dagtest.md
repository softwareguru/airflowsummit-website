---
title: "Testing Airflow DAGs with Dagtest"
slug: testing-airflow-dags-with-dagtest
speakers:
 - Victor Chiapaikeo
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
summary: "Victor Chiapaikeo will showcase Dagtest, a Python package developed at Etsy that greatly facilitatest testing dags."
---

For the dag owner, testing Airflow DAGs can be complicated and tedious. Kubectl cp your dag from local to pod, exec into the pod, and run a command? Install breeze? Why pull the Airflow image and start up the webserver / scheduler / triggerer if all we want is to test the addition of a new task?

It doesn't have to be this hard. At Etsy, we've simplified testing dags for the dag owner with dagtest. Dagtest is a Python package that we house on our internal PyPi. It is a small client binary that makes HTTP requests to a test API. The test API is a simple Flask server that receives these requests and builds pods to run `airflow dags backfill` commands based on the options provided via dagtest. The simplest of these is a dry-run. Typically, users run test runs where the dag executes E2E for a single ds.
  
Equally important is the environment setup. We use an adhoc Airflow instance in a separate GCP environment with an SA that cannot write to Production buckets. This talk will discuss both.