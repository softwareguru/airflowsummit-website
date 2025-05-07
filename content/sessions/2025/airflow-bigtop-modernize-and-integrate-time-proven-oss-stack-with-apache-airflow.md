---
title: "Airflow & Bigtop: Modernize and integrate time-proven OSS stack with Apache Airflow"
slug: airflow-bigtop-modernize-and-integrate-time-proven-oss-stack-with-apache-airflow
speakers:
 - Kengo Seki
topics:
 - Airflow & ...
time_start: 2025-10-07 9:00:00
time_end: 2025-10-07 9:45:00
---

Apache Bigtop is a time-proven open-source software stack for building data platform, which has been built around the Hadoop and Spark ecosystem since 2011. Its software composition has been changed during such a long period, and recently job scheduler is removed mainly due to the inactivity of its development [1]. The speaker believes that Airflow perfectly fits into this gap and is proposing incorporating it in the Bigtop stack [2][3][4]. This presentation will introduce how easily users can build a data platform with Bigtop including Airflow, and how Airflow can integrate those software with its wide range of providers and enterprise-readiness such as the Kerberos support.

[1]: https://issues.apache.org/jira/browse/BIGTOP-4032
[2]: https://lists.apache.org/thread/9pv3jd769zh605os3gc7b82cqpod9lsw
[3]: https://github.com/apache/bigtop/pull/1328
[4]: https://issues.apache.org/jira/browse/BIGTOP-4370