---
title: "Dynamic Security Roles in Airflow for Multi-Tenancy"
url: /sessions/Dynamic-Security-Roles-in-Airflow-for-Multi-Tenancy
speakers:
 - Sean Lewis
 - Mark Merling
block: 
time_start: 2021-07-18T16:00:00.000Z
time_end: 2021-07-18T16:45:00.000Z
draft: false
---

Multi-tenant Airflow instances can help save costs for an organization. This talk will walk through how we dynamically assigned roles to users based on groups in Active Directory so that teams would have access to DAGs they created in the UI on our multi-tenant Airflow instance. We created our own custom AirflowSecurityManager class in order to achieve this that ultimately ties LDAP and RBAC together.
