---
title: "Scaling data pipelines @ Magenta Telekom"
slug: scaling-data-pipelines-magenta-telekom
speakers:
 - Georg Heiler
block: Orchestration & Platform Management
time_start: 2025-11-04T16:00:00.000Z
time_end: 2025-11-04T16:45:00.000Z
draft: false
---

Magenta Telekom ingests many terabytes of new data every day, and every downstream consumer wants it immediately. The real bottleneck turned out not to be hardware but humans wrestling with hidden, hard-wired dependencies in hundreds of heterogeneous pipelines and sometimes tool silos.
 
Our fix was to treat every data asset as a node in a data-dependency graph and every transformation as an edge. Ingestion, Transformation, AI and BI are all part of the same executable graph. By using suitable abstractions and dependency injection less technical people are empowered to contribute business logic which can be operationalized efficiently.
 
 This talk covers:
 - Unified asset graph – ingest → transforms → reports → ML all in one lineage-aware DAG.
 - Event-based pipelines: Events propagate state changes across the enterprise via the edges in the graph in near real-time 
 - Dependency-injection: By using the right abstractions we can empower more users along the data value chain to contribute. 
 
Operational challenges are handled by the abstractions and analysts only focus on the business logic.