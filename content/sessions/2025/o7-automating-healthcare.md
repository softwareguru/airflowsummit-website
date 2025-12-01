---
title: "Automating Healthcare Triage with Airflow and Large Language Models"
slug: automating-healthcare
speakers:
 - Milcah Mbithi
time_start: 2025-10-15 18:30:00
time_end: 2025-10-15 19:00:00
room: Online
track: Use cases
day: 20254
timeslot: 7
gridarea: 8/2/9/3
slides:
video: https://youtu.be/BgKrX3UGP-0
---

I will talk about how Apache Airflow is used in the healthcare sector with the integration of LLMs to enhance efficiency.

Healthcare generates vast volumes of unstructured data daily, from clinical notes and patient intake forms to chatbot conversations and telehealth reports. Medical teams struggle to keep up, leading to delays in triage and missed critical symptoms. This session explores how Apache Airflow can be the backbone of an automated healthcare triage system powered by Large Language Models (LLMs).

I’ll demonstrate how I designed and implemented an Airflow DAG orchestration pipeline that automates the ingestion, processing, and analysis of patient data from diverse sources in real-time. Airflow schedules and coordinates data extraction, preprocessing, LLM-based symptom extraction, and urgency classification, and finally routes actionable insights to healthcare professionals.

The session will focus on the following;
 - Managing complex workflows in healthcare data pipelines
 - Safely integrating LLM inference calls into Airflow tasks
 - Designing human-in-the-loop checkpoints for ethical AI usage
 - Monitoring workflow health and data quality with Airflow.