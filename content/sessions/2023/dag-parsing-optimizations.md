---
title: "DAG Parsing Optimizations"
slug: dag-parsing-optimizations
speakers:
 - Raphaël Vandon
time_start: 2023-09-19T17:15:00-04:00
time_end: 2023-09-19T17:45:00-04:00
track: New features/roadmap
---

As big Airflow users grow their usage to hundreds of DAGs, parsing them can become a performance bottleneck in the scheduler.
 
 In this talk, we'll explore how this situation was improved by using caching techniques and pre-processing of DAGs to minimize the overhead of parsing them at runtime.
 
 We'll also touch on how the the performance of the existing code was analyzed to find points of improvement.
 
 We may include a section on how to configure airflow to benefit from those recent changes, and some tips on how to make DAGs that are quick to parse, but this will not be the core of the talk.
 
 
 
 The talk is intended for contributors and anyone interested in working on performance improvement in general.