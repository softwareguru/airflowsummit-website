---
id: c1t
title: "SciDAP: Airflow and CWL-powered bioinformatics platform"
url: /sessions/2021/scidap
speakers:
 - Nick Luckey
 - Michael Kotliar
time_start: 2021-07-13T16:10:00.000Z
time_end: 2021-07-13T16:20:00.000Z
block: c
slot: 1t
---

Reproducibility is the fundamental principle of a scientific research. This also applies to the computational workflows that are used to process research data. Common Workflow Language (CWL) is a highly formalized way to describe pipelines that was developed to achieve reproducibility and portability of computational analysis. However, there were only few workflow execution platforms that could run CWL pipelines. Here, we present CWL-Airflow – an extension for Airflow to execute CWL pipelines. CWL-Airflow serves as a processing engine for Scientific Data Analysis Platform (SciDAP) – a data analysis platform that makes complex computational workflows both user-friendly and reproducible. In our presentation we are going to explain why we see Airflow as the perfect backend for running scientific workflows, what problems we encountered in extending Airflow to run CWL pipelines and how we solved them. We will also discuss what are the pros and cons of limiting our platform to CWL pipelines and potential applications of CWL-Airflow outside the realm of biology.