---
id: g3
title: "How DAG Became a Test - Airflow System Tests Redefined"
url: /sessions/2022/how-dag-became-a-test
speakers:
 - Bartłomiej Hirsz
 - Eugene Kosteev
 - Mateusz Nojek
time_start: 2022-05-25T16:30:00.000Z
time_end: 2022-05-25T16:50:00.000Z
format: "Presentation"
hosted_by: "Warsaw"
presence: "onsite"
block: g
slot: 3
---

Nothing is perfect, but it doesn’t mean we shouldn’t seek perfection. After some time spent with Airflow system tests, we have recognized numerous places in which we can make significant improvements. We decided to rediscover them. The new design started with the establishment of goals.
 
 
 
 Tests need to:
 
 - be easy to write, read, run and maintain,
 
 - be as close as possible to how Airflow runs in practice,
 
 - be fast, reliable and verifiable,
 
 - assure high quality of Airflow Operators.
 
 
 
 With these principles in mind, we prepared an Airflow Improvement Proposal (AIP-47) and after it’s confirmed, we started the implementation. The results of our work were better than we expected when we started this initiative.
 
 
 
 This session will walk you through the story of how we struggled to run system tests before, how we came up with the improvements, and how we put them into a working solution.