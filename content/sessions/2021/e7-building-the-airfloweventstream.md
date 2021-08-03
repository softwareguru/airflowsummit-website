---
id: e7
title: "Building the AirflowEventStream"
url: /sessions/2021/building-the-airfloweventstream
speakers:
 - Jelle Munk
time_start: 2021-07-15T07:00:00.000Z
time_end: 2021-07-15T07:25:00.000Z
block: e
slot: 7
format: adoption
crowdcast_id: 37
video: https://youtu.be/qFNzL957VO0
slides: 2021/e7-AirflowEventStream.pdf
---

Or how to keep our traditional java application up-to-date on everything big data.

 At Adyen we process tens of millions of transactions a day, a number that rises every day.
 This means that generating reports, training machine learning models or any other operation that requires a bird’s eye view on weeks or months of data requires the use of Big Data technologies.

 We recently migrated to Airflow for scheduling all batch operations on our on-premise Big Data cluster. Some of these operations require input from our merchants or our support team. Merchants can for instance subscribe to reports, choose their preferred time zone, and even specify which columns they want included. After generating the reports, these reports then need to become available in our customer portal.

 So how do we keep track in our Customer Area which reports have been generated in Airflow?
 How do we launch ad-hoc backfills when one of our merchants subscribes to a new report?
 How do we integrate all of this into our existing monitoring pipeline?

 This talk will focus on how we have successfully integrated our big data platform with our existing Java web applications and how Airflow (with some simple add-ons) played a crucial role in achieving this.
