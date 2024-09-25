---
title: "Stress-Free Airflow development: From Dev to Prod at Stripe"
slug: stress-free-airflow-development-from-dev-to-prod-at-stripe
speakers:
 - Nick Bilozerov
 - Thomas Tauber-Marshall

time_start: 2024-09-11 12:30:00
time_end: 2024-09-11 13:15:00
room: California East
track: Use cases
day: 20242
timeslot: 54
gridarea: "8/2/10/3"

images: 
 - /images/sessions/2024/stripe.jpg
slides: 2024/39-Stress-Free-Airflow-development.pdf
video: 
---

At Stripe, compliance with regulations is of utmost importance, and ensuring the integrity of production data is crucial. To address this challenge, Stripe developed a powerful system called User Scope Mode (USM), which allows users to safely and efficiently test new or existing Airflow pipelines without the risk of corrupting production data.
 
USM takes care of automatically overwriting the necessary configurations for Airflow pipelines, enabling users to test their production-ready pipelines locally with ease. This approach empowers Stripe's teams to iterate and refine their workflows without the burden of manual setup or the fear of disrupting live operations.
 
In this talk, we'll dive into the inner workings of USM and explore how it has transformed Stripe's development and testing processes. Discover how this system seamlessly integrates with Airflow, allowing users to validate their pipelines with confidence and agility, all while maintaining the highest standards of compliance and data integrity.