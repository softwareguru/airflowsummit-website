---
title: "Better Support for Using Multiple Namespaces with KubernetesExecutor"
slug: better-support-for-using-multiple-namespaces-with-kubernetesexecutor
speakers:
 - Xiaodong Deng
time_start: 2023-09-19T16:15:00-04:00
time_end: 2023-09-19T16:40:00-04:00
room: Ballroom A-B
track: New features/roadmap
day: 1
timeslot: 14
images:
 - /images/sessions/2023/XiaodongDeng.jpg
video: https://youtu.be/TVBHGWD6d2Q
slides: 2023/ab1-1615-BetterSupport.pdf
---

Airflow’s KubernetesExecutor has supported multi_namespace_mode for long time. This feature is great at allowing Airflow jobs to run in different namespaces on the same Kubernetes clusters for better isolation and easier management.

However, this feature requires cluster-role for the Airflow scheduler, which can create security problems or be a blocker for some users.
 
PR https://github.com/apache/airflow/pull/28047 , which will become available in Airflow 2.6.0, resolves this issue by allowing Airflow users to specify multi_namespace_mode_namespace_list when using multi_namespace_mode, so that no cluster-role is needed and user only needs to ensure the Scheduler has permissions to certain namespaces rather than all namespaces on the Kubernetes cluster.
  
This talk aims to help you better understand KubernetesExecutor and how to set it up in a more secure manner.