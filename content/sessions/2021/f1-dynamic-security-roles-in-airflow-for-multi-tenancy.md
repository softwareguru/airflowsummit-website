---
id: f1
title: "Dynamic Security Roles in Airflow for Multi-Tenancy"
url: /sessions/2021/dynamic-security-roles-in-airflow-for-multi-tenancy
speakers:
 - Mark Merling
 - Sean Lewis
time_start: 2021-07-15T16:00:00.000Z
time_end: 2021-07-15T16:25:00.000Z
block: f
slot: 1
format: presentation

aliases:
 - /sessions/Dynamic-Security-Roles-in-Airflow-for-Multi-Tenancy
crowdcast_id: 38
---

Multi-tenant Airflow instances can help save costs for an organization. This talk will walk through how we dynamically assigned roles to users based on groups in Active Directory so that teams would have access to DAGs they created in the UI on our multi-tenant Airflow instance. We created our own custom AirflowSecurityManager class in order to achieve this that ultimately ties LDAP and RBAC together.
