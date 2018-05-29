camunda 7.9.0 and apache camel
==============================

This project is there to test if apache camel and camunda 7.9.0 go together.

Tl;dr
-----

It seems that Apache Camel is [not yet Spring Boot 2 compatible](https://issues.apache.org/jira/browse/CAMEL-12423) , but
they're getting there.

Camunda 7.9.0 and spring boot appear to require Spring Boot 2.

There's an issue open in the [camunda camel extension](https://github.com/camunda/camunda-bpm-camel/issues/43) where I try to track progress.