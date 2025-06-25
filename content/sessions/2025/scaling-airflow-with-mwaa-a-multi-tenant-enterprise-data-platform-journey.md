---
title: "Scaling Airflow with MWAA: A Multi-Tenant Enterprise Data Platform Journey"
slug: scaling-airflow-with-mwaa-a-multi-tenant-enterprise-data-platform-journey
speakers:
 - Srinivas Podila
 - Venkat Sadineni
topics:
 - Use cases
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

We use Amazon MWAA to orchestrate our enterprise data warehouse and MDM solutions. Our DAGs extract data from Salesforce, Oracle, Workday, and SFTP, transform it using Mulesoft, Informatica, and DBT, and load it into Salesforce Data Cloud and Snowflake. MWAA is configured as a multi-tenant platform, supporting more than 10 teams and managing thousands of DAGs per environment. Each team follows a full SDLC and has a dedicated Git repo integrated with Jenkins-based CI/CD pipelines for independent deployments.

To enhance security, we integrated CyberArk, assigning each team a SAFE and restricting access at the DAG level. We built custom Python frameworks for Salesforce, Snowflake, DBT Cloud, and Informatica, which not only trigger jobs in DBT Cloud and Informatica but also retrieve service account credentials from CyberArk at runtime. These frameworks bypass default Airflow plugins and eliminate the use of variables or hardcoded credentials, ensuring a secure and scalable approach to credential management.

We’ve enabled CloudWatch dashboards to monitor system health and resolve performance or DAG parsing issues, ensuring high availability and observability across environments.