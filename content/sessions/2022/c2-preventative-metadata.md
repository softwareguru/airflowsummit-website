---
id: c2
title: "Preventative Metadata: Building for data reliability with DataHub, Airflow, & Great Expectations"
url: /sessions/2022/preventative-metadata
speakers:
 - John Joyce
 - Tamás Németh
time_start: 2022-05-23T14:00:00.000Z
time_end: 2022-05-23T14:40:00.000Z
format: "Technical deep dive / tutorial"
hosted_by: "Tokyo"
presence: "remote"
block: c
slot: 2
---

Recently there has been much discussion around data monitoring, particularly in regards to reducing time to mitigate data quality problems once they've been detected. The problem with reactive or periodic monitoring as the de-facto standard for maintaining data quality is that it's expensive. By the time a data problem has been identified, it's effects may have been amplified across a myriad of downstream consumers, leaving you (a data engineer) with a big mess to clean-up. 
 
 
 
 In this talk, we will present an approach for proactively addressing data quality problems using orchestration based on a central metadata graph. Specifically, we will walk through use cases highlighting how the open source metadata platform DataHub can enable proactive pipeline circuit-breaking by serving as the source of truth for both technical & semantic health status for a pipeline's data dependencies. We’ll share practical recipes for how three powerful open source projects can be combined to build reliable data pipelines: Great Expectations for generating technical health signals in the form of assertion results on datasets, DataHub for providing a semantic identity for a dataset, including ownership, compliance, & lineage, and Airflow for orchestration.