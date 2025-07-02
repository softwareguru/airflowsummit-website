---
title: "Uses in an on Prem Research Setting"
slug: uses-in-an-on-prem-research-setting
speakers:
 - Lawrence Gerstley
time_start: 2025-10-07 09:10:00
time_end: 2025-10-07 10:05:00
room: 
track: 
topics: Use cases
day: 
timeslot: 
gridarea: 
images: 

slides:
video: 
---

KP Division of Research uses Airflow as a central technology for integrating diverse technologies in an agile setting. We wish to present a set of use-cases for AI/ML workloads, including imaging analysis (tissue segmentation, mammography), NLP (early identification of psychosis), LLM processing (identification of vessel diameter from radiological impressions), and other large data processing tasks. We create these "short-lived" project workflows to accomplish specific aims, and then may never run the job again, so leveraging generalized patterns are crucial to quickly implementing these jobs. Our Advanced Computational Infrastructure is comprised of multiple Kubernetes clusters, and we use Airflow to democratize the use of our batch level resources in those clusters. We use Airflow form-based parameters to deploy pods running R and Python scripts where generalized parameters are injected into scripts that follow internal programming patterns. Finally, we also leverage Airflow to create headless services inside Kubernetes for large computational workloads (Spark & H2O) that subsequent pods consume ephemerally.