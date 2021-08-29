---
id: h4
title: "Airflow loves Kubernetes"
url: /sessions/2021/airflow-loves-kubernetes
speakers:
 - Jarek Potiuk
 - Kaxil Naik
time_start: 2021-07-16T17:30:00.000Z
time_end: 2021-07-16T17:55:00.000Z
block: h
slot: 4
format: presentation
crowdcast_id: 51
video: https://youtu.be/Xub3mJVtYpc
slides: 2021/h4-AirflowKubernetes.pdf
---

In this talk Jarek and Kaxil will talk about official, community support for running Airflow in the Kubernetes environment.

The full support for Kubernetes deployments was developed by the community for quite a while and in the past users of Airflow had to rely on 3rd-party images and helm-charts to run Airflow on Kubernetes. Over the last year community members made an enormous effort to provide robust, simple and versatile support for those deployments that would respond to all kinds of Airflow users. Starting from official container image, through quick-start docker-compose configuration, culminating in April with release of the official Helm Chart for Airflow.

This talk is aimed for Airflow users who would like to make use of all the effort. The users will learn how to:
* Extend or customize Airflow Official Docker Image to adapt it to their needs
* Run quickstart docker-compose environment where they can quickly verify their images
* Configure and deploy Airflow on Kubernetes using the Official Airflow Helm chart
