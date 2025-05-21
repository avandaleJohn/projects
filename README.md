# projects
This is a site to expand a bit more on some of the interesting projects I've worked on over the years.


# SQL Server EventStream

A centralized, event-driven architecture for capturing and streaming row-level changes in SQL Server—built to replace a legacy history-tracking database with a robust, scalable solution that integrates seamlessly with downstream systems.

👉 **Live Project Page:** [EventStream Documentation & Demo](https://avandalejohn.github.io/event-stream/)

## Overview

This project presents a novel architectural pattern that turns Microsoft SQL Server into the authoritative event source for an enterprise platform. By leveraging native features such as triggers, stored procedures, and Service Broker, it delivers:

- **Immutable event capture** for every insert, update, and delete
- **Schema evolution support** through automatic code generation
- **Loose coupling** between systems via queues and event consumers
- **End-to-end traceability** of data changes across the estate

The solution addresses the challenges of auditing, replication, and integration by transforming operational database changes into structured events—offering a practical alternative to both Change Data Capture (CDC) and third-party pipelines.

## What's Inside

The GitHub Pages site linked above includes:

- A full walkthrough of the architectural design
- Diagrams illustrating event propagation and message flow
- Code samples demonstrating how events are captured and consumed
- A discussion of trade-offs and lessons learned

## Use Cases

- Replacing legacy audit or history tables
- Building an event backbone without introducing Kafka or Debezium
- Creating extensible integration patterns for financial systems

---

If you're evaluating event streaming within a SQL Server environment—whether for compliance, analytics, or microservices integration—this project is a compelling reference implementation.



