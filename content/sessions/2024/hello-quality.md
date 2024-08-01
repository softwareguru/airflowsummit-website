---
title: "Hello Quality: Building CIs to run Providers Packages System Tests"
speakers:
 - Freddy Demiane
 - Rahul Vats
 - Dennis Ferruzzi
track:
 - Community
images:
 - /images/sessions/2024/hello-quality.jpg 
room: 
time_start: 2024-09-10 9:00:00
time_end: 2024-09-10 9:25:00
---

Airflow operators are a core feature of Apache Airflow and it’s extremely important that we maintain high quality of operators, prevent regressions and on the other hand we help developers with automated tests results to double check if introduced changes don’t cause regressions or backward incompatible changes and we provide Airflow release managers with information whether a given version of a provider should be released or not yet.

Recently a new approach to assuring production quality was implemented for AWS, Google and Astronomer-provided operators - standalone Continuous Integration processes were configured for them and test results dashboards show the results of the last test runs. What has been working well for these operator providers might be a pattern to follow for others - during this presentation, AWS, Google and Astronomer engineers are going to share the information about the internals of Test Dashboards implemented for AWS, Google and Astronomer-provided operators. This approach might be a a ‘blueprint’ to follow for other providers.
