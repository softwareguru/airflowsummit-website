---
id: z3
title: "Lessons Learned while Migrating Data Pipelines from Enterprise Schedulers to Airflow"
url: /sessions/2021/lessons-learned-while-migrating-data-pipelines
speakers:
 - Shivnath Babu
 - Hari Nair
time_start: 2021-07-09T17:00:00.000Z
time_end: 2021-07-09T17:25:00.000Z
block: Z
slot: 3
format: adoption
---

Digital transformation, application modernization, and data platform migration to the cloud are key initiatives in most enterprises today. These initiatives are stressing the scheduling and automation tools in these enterprises to the point that many users are looking for better solutions. A survey revealed that 88% of users believe that their business will benefit from an improved automation strategy across technology and business. Airflow has an excellent opportunity to capture mindshare and emerge as the leading solution here. At Unravel, we are seeing the trend where many of our enterprise customers are at various stages of migrating to Airflow from their enterprise schedulers or ETL/ELT orchestration tools like Autosys, Informatica, Oozie, Pentaho, and Tidal. 
 
 In this talk, we will share lessons learned and best practices found in the entire pipeline migration life-cycle which includes:
 
 (i) The evaluation process which led to picking Airflow, including certain aspects where Airflow can do better 
 
 (ii) The challenges in discovering and understanding all components and dependencies that need to be considered in the migration
 
 (iii) The challenges arising during the pipeline code and data migration, especially, in getting a single-pane-of-glass and apples-to-apples views to track the progress of the migration
 
 (iv) The challenges in ensuring that the pipelines that have been migrated to Airflow are able to perform and scale on par or better compared to what existed previously