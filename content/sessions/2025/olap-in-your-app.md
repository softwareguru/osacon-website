---
title: "OLAP in your App: Integrating realtime & agentic analytics into your app"
slug: olap-in-your-app
speakers:
 - Chris Crane
block: 
time_start: 2025-11-04T16:00:00.000Z
time_end: 2025-11-04T16:45:00.000Z
draft: false
---

Modern analytics experiences demand “conversation-fast” backends—systems that serve the requests of an agent or LLM in real time at the speed of a natural conversation. In this talk, we’ll get deep into an open-source reference architecture for powering conversational AI and real-time analytics in user-facing applications. We’ll get hands-on in the code, and explore practical patterns for integrating streaming and analytical infrastructure into your web application, including AI chat systems—where the right real-time architecture can make AI conversations feel natural.

We’ll focus on a reference architecture that integrates transactional (Postgres) and analytical engines (ClickHouse), along with RedPanda for streaming, a React web app frontend, and MCP interfaces for enabling LLM chat within the app. The whole analytics stack is defined in code using the MooseStack open source framework. This architecture ensures the low-latency responsiveness users expect with analytics visualizations and conversational AI, and a modern, local-first developer experience that integrates naturally into your stack.