---
title: "Stress-Free Airflow Development: From Dev to Prod at Stripe"
speakers:
 - Nick Bilozerov
track:
 - Use cases
images:
 - /images/sessions/2024/stripe.jpg 
time_start: 2024-09-10T16:00:00.000Z
time_end: 2024-09-10T16:45:00.000Z
draft: false
---

At Stripe, compliance with regulations is of utmost importance, and ensuring the integrity of production data is crucial. To address this challenge, Stripe developed a powerful system called User Scope Mode (USM), which allows users to safely and efficiently test new or existing Airflow pipelines without the risk of corrupting production data.

USM takes care of automatically overwriting the necessary configurations for Airflow pipelines, enabling users to test their production-ready pipelines locally with ease. This approach empowers Stripe's teams to iterate and refine their workflows without the burden of manual setup or the fear of disrupting live operations.

In this talk, we'll dive into the inner workings of USM and explore how it has transformed Stripe's development and testing processes. Discover how this system seamlessly integrates with Airflow, allowing users to validate their pipelines with confidence and agility, all while maintaining the highest standards of compliance and data integrity.


