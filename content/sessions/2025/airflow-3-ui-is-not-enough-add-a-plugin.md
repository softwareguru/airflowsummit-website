---
title: "Airflow 3 UI is not enough? Add a Plugin!"
slug: airflow-3-ui-is-not-enough-add-a-plugin
speakers:
 - Jens Scheffler
 - Brent Bovenzi
 - Pierre Jeambrun
topics:
 - Airflow 3
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

In Airflow 2 there was a plugin mechanism to extend the UI for new functions as well as be able to add hooks and other features.

As Airflow 3 rewrote the UI old Plugins were not working for all cases anymore. Airflow 3.1 now provides a re-vamped option to extend the UI with a new plugin schema in native React components and embedded iframes following AIP-68 definitions.

In this session we will provide an overview about capabilities and give some intro how you can roll-your-own.