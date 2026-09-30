---
title: "Cross-Deployment Monitoring and Dag Dependencies with the Kafka Event Producer Plugin"
slug: cross-deployment-monitoring-and-dag-dependencies-with-the-kafka-event-producer-plugin
speakers:
 - Christos Bisias
track: Builder
room: Online
day: 2026o2
time_start: 2026-11-05 7:00:00
time_end: 2026-11-05 7:30:00
timeslot: 3
gridarea: 4/2/5/8
slides: 
video:
---

Organizations can have multiple Airflow instances running on separate hardware, each with its own database, and sometimes in different geographical regions. How can we monitor these instances and get updates on their state without polling their databases or APIs? Is there a way to coordinate Dags from different Airflow instances?

This session answers the above questions by presenting a newly released plugin in the Apache Kafka Provider, which publishes a message to a configured Kafka topic for every Dag run or task instance state change event.

It will cover:
- what the plugin does
- what the published messages look like
- how to enable and configure it
- how to consume the messages
- some use cases