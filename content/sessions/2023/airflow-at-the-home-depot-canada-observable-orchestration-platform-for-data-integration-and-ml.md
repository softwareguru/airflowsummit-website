---
title: "Airflow at The Home Depot Canada: Observable orchestration platform for data integration and ML"
slug: airflow-at-the-home-depot-canada-observable-orchestration-platform-for-data-integration-and-ml
speakers:
 - Jose Puertos
time_start: 2023-09-19T11:30:00-04:00
time_end: 2023-09-19T12:00:00-04:00
track: Use cases
---

The purpose of this session is to indicate how we leverage airflow in a federated way across all our business units to perform a cost-effective platform that accommodates different patterns of data integration, replication and ML tasks in a flexible way providing DevOps tunning of DAGs across environments that integrate to our open-source observability strategy that allows our SREs to have a consistent metrics, monitoring and alerting of data tasks.
 
 We will share the opinionated way we setup DAGs that include naming and folder structure conventions along coding expectation like the use of XCom specific entries to report processed elements and support for state for DAGs that require it as well as the expected configurable capabilities for tasks such as the type of runner for Apache Beam tasks. Along these ones we will also indicate the “DevOps DAGs” that we deploy in all our environments that take care of specific platform maintenance/support.