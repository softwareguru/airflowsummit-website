---
title: "Seamless Migration: Leveraging Ruff for a Smooth Transition from Airflow 2 to Airflow 3"
slug: seamless-migration-leveraging-ruff-for-a-smooth-transition-from-airflow-2-to-airflow-3
speakers:
 - Wei Lee
topics:
 - Airflow 3
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

Migrating from Airflow 2 to the newly released Airflow 3 may seem intimidating due to numerous breaking changes and the introduction of new features. Although a backward compatibility layer has been implemented and most of the existing dags should work fine, some features—such as subdags and execution_date—have been removed based on community consensus.

To support this transition, we worked with Ruff to establish rules that automatically identify removed or deprecated features and even assist in fixing them. In this presentation, I will outline our current Ruff features, the migration rules from Airflow 2 to 3, and how this experience opens the door for us to promote best practices in Airflow through Ruff in the future.

After this session, Airflow users will understand how Ruff can facilitate a smooth transition to Airflow 3. As developers of Airflow, we will delve into the detail of how these migration rules were implemented and discuss how we can leverage this knowledge to introduce linting rules that encourage Airflow users to adopt best practices.