---
title: "Open Source Healthcare Analytics: 20% ICU Transfer Reduction at Scale"
slug: open-source-healthcare-analytics
speakers:
 - Rakshit Khare
topics:
day: 20251
room: A
timeslot: 10
time_start: 2025-11-04T18:30:00.000Z
time_end: 2025-11-04T19:00:00.000Z
gridarea: 7/2/8/3

---

This presentation showcases an open source healthcare analytics platform that reduced ICU transfers by 20% through real-time patient risk prediction. Built entirely with open source technologies, the system demonstrates how healthcare organizations can leverage community-driven tools to achieve clinical impact without vendor lock-in.

The architecture combines Apache Kafka for real-time EMR streaming, Apache Spark for ML model training, and PostgreSQL with TimescaleDB for time-series clinical data. Docker containerization ensures reproducible deployments across environments, while Kubernetes orchestrates auto-scaling during patient admission surges. The ML pipeline uses scikit-learn and XGBoost models trained on anonymized historical cohorts, with MLflow tracking experiments and model versioning.

Key open source components include: Apache Airflow for workflow orchestration, Grafana for clinical dashboards, and Apache Superset for analytics visualization. The platform implements FHIR standards through HAPI FHIR server, ensuring interoperability with existing hospital systems.

Critical lessons learned include: designing privacy-preserving analytics with differential privacy libraries, implementing federated learning across hospital networks, and maintaining sub-second latency for critical alerts using Redis caching. The session covers practical deployment strategies, cost optimization techniques, and governance frameworks for open source healthcare analytics.

Attendees will learn to build production-ready healthcare analytics platforms using exclusively open source tools, complete with code examples, architecture patterns, and regulatory compliance strategies that deliver measurable patient outcomes.