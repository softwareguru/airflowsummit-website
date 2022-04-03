---
id: 
title: "Beyond Testing: How to Build Circuit Breakers with Airflow"
url: /sessions/2022/beyond-testing
speakers:
 - Barr Moses
block: 
slot: 
track: Airflow internals
time_start: 2022-01-01T17:00:00.000Z
time_end: 2022-01-01T18:00:00.000Z

---

Testing is an important part of the DataOps life cycle, giving teams confidence in the integrity of their data as it moves downstream to production systems. But what happens when testing doesn’t catch all of your bad data and “unknown unknown” data quality issues fall through the cracks? Fortunately, data engineers can apply a thing or two from DevOps best practices to tackle data quality at scale with circuit breakers, a novel approach to stopping bad data from actually entering your pipelines in the first place. In this talk, Prateek Chawla, Founding Team Member and Technical Lead at Monte Carlo, will discuss what circuit breakers are, how to integrate them with your Airflow DAGs, and what this looks like in practice. Time permitting, Prateek will also walk through how to build and automate Airflow circuit breakers across multiple cascading pipelines with Python and other common tools.