---
title: "Airflow 3 UI is not enough? Add a Plugin!"
slug: airflow-3-ui-is-not-enough-add-a-plugin
speakers:
 - Jens Scheffler
 - Brent Bovenzi
 - Pierre Jeambrun
topics:
 - Airflow 3
time_start: 2025-10-08 12:30:00
time_end: 2025-10-08 12:55:00
room: Columbia A
track: Airflow 3
day: 20252
timeslot: 61
gridarea: 7/2/8/3
slides: 2025/airflow-3-ui-is-not-enough-add-a-plugin.pdf
video: https://youtu.be/qVG5ioC7Qbk
images:
 - /images/sessions/2025/airflow-3-ui-is-not-enough-add-a-plugin.png
---

In Airflow 2 there was a plugin mechanism to extend the UI for new functions as well as be able to add hooks and other features.

As Airflow 3 rewrote the UI old Plugins were not working for all cases anymore. Airflow 3.1 now provides a re-vamped option to extend the UI with a new plugin schema in native React components and embedded iframes following AIP-68 definitions.

In this session we will provide an overview about capabilities and give some intro how you can roll-your-own.