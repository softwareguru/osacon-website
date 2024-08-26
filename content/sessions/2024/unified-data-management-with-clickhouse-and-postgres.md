---
title: "Unified Data Management with ClickHouse and Postgres"
slug: unified-data-management-with-clickhouse-and-postgres
speakers:
 - Shivji Kumar Jha
 - Tarun Annapareddy
topics:
 - Databases
room: 
time_start: 2024-11-19T09:00:00-04:00
time_end: 2024-11-19T09:25:00-04:00
---

Given the AI hype, organisations want to capture every data point which very quickly results into capturing extensive data from analytics, user interactions, transactions, metrics, logs, and time series. Given different shapes, volumes, scale, consistency and availability requirements, this evolves to many data stores to explore, manage and nurture. However, relying on multiple specialized databases increases operational costs, makes developers loaded with cognitive overload, necessitates various dashboards, and eventually demands significant expertise spread across teams.
 
 This talk proposes a unified data platform using just two databases: ClickHouse and Postgres. Postgres protocol is evolving quickly to all kinds of distributed data. But the ecosystem outside OLTP is not mature yet. With Clickhouse and Postgres both allowing to query foreign data, we'll demonstrate how ClickHouse can efficiently handle OLAP, metrics, logs and transactional workloads. By consolidating these diverse workloads, organisations can achieve substantial cost savings, streamline resource utilisation, and simplify data management.
 
 We will delve into strategies for integrating these functionalities, ensuring data isolation and smooth operations across teams. Real-world examples will highlight the effectiveness of ClickHouse and Postgres, showcasing how this unified approach enhances efficiency and reduces complexity.