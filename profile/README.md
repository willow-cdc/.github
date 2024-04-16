# Overview

Willow is an open-source, self-hosted framework for building log-based change data capture pipelines that update caches in near real-time based on changes in a database.

Willow abstracts away the complexity of setting up and configuring open source tools like Debezium and Apache Kafka. Utilizing log-based change data capture, Willow non-invasively monitors changes in a user's PostgreSQL database and reflects those row-level changes in a user's Redis cache. Without requiring in-depth technical knowledge and expertise, data pipelines can be created or deleted using Willow's web user interface, simplifying setup and teardown.
