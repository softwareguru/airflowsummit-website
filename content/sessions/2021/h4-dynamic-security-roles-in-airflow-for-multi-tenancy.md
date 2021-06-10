---
id: h4
title: "Dynamic Security Roles in Airflow for Multi-Tenancy"
url: /sessions/2021/dynamic-security-roles-in-airflow-for-multi-tenancy
speakers:
 - Mark Merling
 - Sean Lewis
time_start: 2021-07-16T17:30:00.000Z
time_end: 2021-07-16T17:55:00.000Z
block: h
slot: 4
format: presentation

aliases:
 - /sessions/Dynamic-Security-Roles-in-Airflow-for-Multi-Tenancy
---

Multi-tenant Airflow instances can help save costs for an organization. This talk will walk through how we dynamically assigned roles to users based on groups in Active Directory so that teams would have access to DAGs they created in the UI on our multi-tenant Airflow instance. We created our own custom AirflowSecurityManager class in order to achieve this that ultimately ties LDAP and RBAC together.