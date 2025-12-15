---
layout: archive
title: "Projects"
permalink: /projects/
---

### CodeCollab: Collaborative Code Execution Platform
[GitHub](https://github.com/jayanthanala/codecollab)

A real-time collaborative code editor supporting multiple programming languages with live synchronization.

**Tech Stack**: Next.js, TypeScript, Python, CRDTs (Y.js), AWS (ECS, Fargate, Lambda, S3), API Gateway, DynamoDB

**Highlights**:
- Built real-time collaborative editor with Next.js (TypeScript), Python, and CRDTs (Y.js), supporting 50 concurrent users per session with synchronization latency <100ms
- Architected a cloud-native solution using AWS ECS, Fargate, Lambda, S3, API Gateway, and DynamoDB to handle 1,000+ concurrent code executions per second, prioritizing availability and ensuring secure isolation
- Implemented CI/CD pipelines with GitHub Actions, CodeBuild, and CodePipeline, along with background jobs for session cleanup and resource optimization, enabling zero-downtime deployments and reducing cloud costs

---

### LeetStory: AI-Powered Interview Prep Tool
[GitHub](https://github.com/jayanthanala/leetstory)

A Chrome extension that uses generative AI to contextualize LeetCode problems into real-world interview scenarios.

**Tech Stack**: JavaScript, Node.js, Chrome Extension APIs, Small Language Model (SLM), AI/ML

**Highlights**:
- Developed a Chrome extension with JavaScript and Node.js that uses a small language model (SLM) API to rephrase LeetCode problems into interview scenarios
- Serves 1K+ users, helping them understand problems in practical, real-world contexts
- Integrates seamlessly with the LeetCode interface for a smooth user experience

---

### sMart: Supermarket Management System

A full-stack application for managing supermarket operations with real-time features.

**Tech Stack**: Django, React, PostgreSQL, WebSockets, Redis

**Highlights**:
- Developed a comprehensive supermarket management system with inventory tracking, POS, and supplier management
- Implemented real-time tendering system via WebSockets for live auction-style procurement
- Reduced manual inventory tasks by 45% through automation and smart alerts
- Built responsive React frontend with real-time updates and analytics dashboard

---

### Understanding Wildlife Trafficking
[GitHub](https://github.com/jayanthanala/Understanding-wildlife-trafficking)

Big data analysis platform for tracking and analyzing wildlife trafficking patterns.

**Tech Stack**: Python, Flask, GraphQL, PostgreSQL, Kafka, Spark, AWS (Lambda, EC2), Grafana, Prometheus

**Highlights**:
- Developed RESTful and GraphQL APIs with Flask and Python for real-time wildlife trafficking analysis, supporting queries on 300K+ records with sub-200ms response times
- Optimized AWS infrastructure by offloading batch jobs to Lambda, leveraging EC2 auto-scaling groups, and integrating S3 lifecycle policies, reducing system downtime by 20% and lowering operational costs
- Designed a Kafka-based ingestion workflow that processes continuously scraped marketplace data and feeds cleaned records into downstream APIs and ETL jobs, improving data freshness by 40%
- Deployed observability stack with Prometheus and Grafana, automating metrics and alerts and reducing incident response time by 20%

---

### COVID-19 Stats Dashboard
[GitHub](https://github.com/jayanthanala/COVID-19-Stats)

A frontend application for visualizing COVID-19 statistics and trends.

**Tech Stack**: EJS, JavaScript, Node.js, REST APIs, Chart.js

**Highlights**:
- Built an interactive dashboard displaying real-time COVID-19 statistics
- Integrated multiple public health APIs for comprehensive data coverage
- Implemented data visualization with charts and geographic maps

---

### Social Network Analysis using Twitter
[GitHub](https://github.com/jayanthanala/SNA-usingTwitter)

Analyzing social network patterns and influence using Twitter data.

**Tech Stack**: R, Network Analysis Libraries, Data Visualization

**Highlights**:
- Performed social network analysis on Twitter data to identify influence patterns
- Visualized network graphs and community structures
- Applied statistical methods to understand information propagation
