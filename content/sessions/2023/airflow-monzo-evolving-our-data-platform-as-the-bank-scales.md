---
title: "Airflow @ Monzo - Evolving Our Data Platform As The Bank Scales"
slug: airflow-monzo-evolving-our-data-platform-as-the-bank-scales
speakers:
 - Jonathan Rainer
 - Ed Sparkes
time_start: 2023-09-19T09:00:00-05:00
time_end: 2023-09-19T10:00:00-05:00
track: Use cases
---

As a bank Monzo has seen exponential growth in active users, from 1.6 million in 2019 to 5.8 million in 2022. At the same time the number of data users and analysts has expanded from an initial team of 4 to 132. Alongside this growth, our infrastructure and tooling have had to evolve to deliver the same value at a new scale. From an Airflow installation deployed on a single monolithic instance we now deploy atop Kubernetes and have integrated our Airflow setup into the bank's backend systems. This talk charts the story of that expansion and the growing pains we've faced, as well as looking to the future of our use of Airflow. We'll first discuss how data at Monzo works, from event capture to arrival in our Data Warehouse, before assessing the challenges of our Airflow setup. We'll then dive into the re-platforming that was required to meet our growing data needs, and some of the unique challenges that come with serving an ever growing user base and need for analysis and insight.