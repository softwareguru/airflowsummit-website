---
title: "Hello Quality: Building CIs to run Providers Packages System Tests"
slug: hello-quality-building-cis-to-run-providers-packages-system-tests
speakers:
 - Freddy Demiane
 - Rahul Vats
 - Dennis Ferruzzi
time_start: 2024-09-12 15:10:00
time_end: 2024-09-12 16:10:00
room: California West
track: Community
day: 20243
timeslot: 104
gridarea: "13/3/15/4"
images: 
 - /images/sessions/2024/hello-quality.jpg
slides: 2024/95-hello-quality.pdf
video: 
---

Airflow operators are a core feature of Apache Airflow and it’s extremely important that we maintain high quality of operators, prevent regressions and on the other hand we help developers with automated tests results to double check if introduced changes don’t cause regressions or backward incompatible changes and we provide Airflow release managers with information whether a given version of a provider should be released or not yet.
 
Recently a new approach to assuring production quality was implemented for AWS, Google and Astronomer-provided operators - standalone Continuous Integration processes were configured for them and test results dashboards show the results of the last test runs. What has been working well for these operator providers might be a pattern to follow for others - during this presentation, AWS, Google and Astronomer engineers are going to share the information about the internals of Test Dashboards implemented for AWS, Google and Astronomer-provided operators. This approach might be a a ‘blueprint’ to follow for other providers.