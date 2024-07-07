---
title: "Airflow at UniCredit – why we implemented our overnight EOD in a single DAG"
slug: airflow-at-unicredit-why-we-implemented-our-overnight-eod-in-a-single-dag
speakers:
 - Jędrzej Matuszak
 - Marcin Mankiewicz
 - Piotr Slivchuk
track:
 - Use cases
images:
 - /images/sessions/2024/unicredit.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
draft: true
---

Overnight EOD reporting in a multi-entity banking environment is by definition a highly complex pipeline, with multiple external dependencies and strict SLAs. In our session we will discuss how we scheduled our overnight Murex processing in Airflow, and why we are treating it as an end-to-end process with 8000 tasks managed by a single DAG. We will also explore our Airflow plugins and external tools, which we designed to manage the complexity of the overall process, including SLA monitoring, a Murex task wrapper and a file distribution platform.