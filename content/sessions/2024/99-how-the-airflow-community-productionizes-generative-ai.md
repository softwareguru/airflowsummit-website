---
title: "How the Airflow Community Productionizes Generative AI"
slug: how-the-airflow-community-productionizes-generative-ai
speakers:
 - Pete Dejoy
time_start: 2024-09-12 14:00:00
time_end: 2024-09-12 14:25:00
room: California West
track: Community
day: 20243
timeslot: 99
gridarea: "11/3/12/4"
images: 
 - /images/sessions/2024/productionize-ai.jpg
---

Every data team out there is being asked from their business stakeholders about Generative AI. Taking LLM centric workloads to production is not a trivial task. At the foundational level, there are a set of challenges around data delivery, data quality, and data ingestion that mirror traditional data engineering problems. Once you’re past those, there’s a set of challenges related to the underlying use case you’re trying to solve. Thankfully, because of how Airflow was already being used at these companies for data engineering and MLOps use cases, it has become the defacto orchestration layer behind many GenAI use cases for startups and Fortune 500s. 
 
 
 
 This talk will be a tour of various methods, best practices, and considerations used in the Airflow community when taking GenAI use cases to production. We’ll focus on 4 primary use cases; RAG, fine tuning, resource management, and batch inference and take a walk through patterns different members in the community have used to productionize this new, exciting technology.