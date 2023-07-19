---
title: "A New SQLAlchemyCollector and OpenLineageAdapter for Emitting Airflow Lineage Metadata as DAGs Run"
slug: a-new-sqlalchemycollector-and-openlineageadapter-for-emitting-airflow-lineage-metadata-as-dags-run
speakers:
 - Michael Robinson
time_start: 2023-09-20T15:00:00-04:00
time_end: 2023-09-20T15:30:00-04:00
room: York
track: Lineage & Quality
day: 2
timeslot: 11
---

Airflow uses SQLAlchemy under the hood but up to this point has not exploited the tool’s capacity to produce detailed metadata about queries, tables, columns, and more. In fact, SQLAlchemy ships with an event listener that, in conjunction with OpenLineage, offers tantalizing possibilities for enhancing the development process – specifically in the areas of monitoring and debugging. 
 
SQLAlchemy’s event system features a Session object and ORMExecuteState mapped class that can be used to intercept statement executions and emit OpenLineage RunEvents as executions occur. In this talk, Michael Robinson from the community team at Astronomer will provide an overview and demo of new SQLAlchemyCollector and OpenLineageAdapter classes for leveraging SQLAlchemy’s event system to emit OpenLineage events as DAGs run.