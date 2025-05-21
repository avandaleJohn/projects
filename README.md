# SQL Server EventStream & Rethinking Restrictions

A pair of architecture-led projects that reimagine how enterprise systems track, stream, and apply data rules in SQL Server environments. Together, they demonstrate how to modernize legacy compliance systems using native capabilities, clear design thinking, and robust integration patterns.

---

## 🔗 Live Project Pages

- [📄 EventStream — Centralized Change Events in SQL Server](https://avandalejohn.github.io/event-stream/)
- [📄 Rethinking Restrictions — A New Model for Rule Application](https://avandalejohn.github.io/rethinking-restrictions/)

---

## 📌 Project 1: SQL Server EventStream

**EventStream** turns SQL Server into the authoritative source of truth for row-level change events. It replaces traditional audit tables with a scalable, event-driven design using:

- **Triggers + Service Broker** to emit immutable events
- **Automatic code generation** that adapts to schema changes
- **Structured event delivery** to downstream consumers via queues

### Key Features

- Durable, tamper-evident auditability
- Loose coupling between core database and external systems
- Infrastructure-light implementation using native SQL Server features

📖 Full walkthrough: [Visit the EventStream page](https://avandalejohn.github.io/event-stream/)

---

## 📌 Project 2: Rethinking Restrictions

**Rethinking Restrictions** is a conceptual and practical rework of how complex business rules ("restrictions") are modeled and enforced. Inspired by real-world challenges in regulatory compliance, the project proposes:

- A **normalized data model** separating rules from data
- An architecture that supports **composability and reuse**
- A Google Maps–style metaphor to distinguish between **rules** and **paths**

### Why It Matters

- Traditional relational approaches struggle with layered, overlapping, or temporal rule enforcement
- This model allows for both **traceable evaluation** and **future-proof extension**
- Pairs naturally with event streaming for real-time validation

📖 Explore the concept: [Visit the Rethinking Restrictions page](https://avandalejohn.github.io/rethinking-restrictions/)

---

## 🚀 Why These Projects?

These are not academic experiments — they emerged from the need to modernize brittle, high-risk systems in regulated financial environments. Together, they offer a pattern language for transforming legacy SQL Server environments into:

- Stream-driven, loosely coupled ecosystems
- Rule-governed platforms that scale with business complexity
- Architecturally consistent foundations for compliance and audit

---

If you're a systems architect, data engineer, or technical leader wrestling with auditability, integration, or compliance logic at scale — these projects aim to give you blueprints that are practical, testable, and extensible.
---

If you're evaluating event streaming within a SQL Server environment—whether for compliance, analytics, or microservices integration—this project is a compelling reference implementation.



