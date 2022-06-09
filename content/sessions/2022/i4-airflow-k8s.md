---
id: i4
title: "Airflow / Kubernetes: Running on and using k8s"
url: /sessions/2022/airflow-k8s
speakers:
 - Jed Cunningham
time_start: 2022-05-26T05:30:00.000Z
time_end: 2022-05-26T05:40:00.000Z
session_type: "Presentation"
hosted_by: "Melbourne"
presence: "remote"
block: i
slot: 4
video: https://youtu.be/H8JjhiVGOlg
slides: 
---

Apache Airflow and Kubernetes work well together. Not only does Airflow have native support for running tasks on Kubernetes, there is also an official helm chart that makes it easy to run Airflow itself on Kubernetes!
 
Confused on the differences between KubernetesExecutor and KubernetesPodOperator? What about CeleryKubernetesExecutor? Or the new LocalKubernetesExecutor? After this talk you will understand how they all fit in the ecosystem.
 
We will talk about the ways you can run Airflow on Kubernetes, run tasks on Kubernetes, or do both. We will also cover things you may want to consider doing to have a reliable Airflow instance.