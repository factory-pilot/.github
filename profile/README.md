<p align="center">
  <a href="https://factory-pilot.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/factory-pilot/.github/main/profile/logo-dark.png">
      <img src="https://raw.githubusercontent.com/factory-pilot/.github/main/profile/logo.png" alt="Factory Pilot" width="520">
    </picture>
  </a>
</p>

<p align="center">
  <strong>AI-Driven Shopfloor Intelligence for Zero-Defect Manufacturing</strong>
</p>

<p align="center">
  <a href="https://factory-pilot.ai"><img src="https://img.shields.io/badge/WEBSITE-111827?style=for-the-badge" alt="Website"></a>
  <a href="https://factory-pilot.ai/en/book-demo"><img src="https://img.shields.io/badge/BOOK%20A%20DEMO-E8762D?style=for-the-badge" alt="Book a Demo"></a>
  <a href="https://www.linkedin.com/company/factory-pilot"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
</p>

---

Factory Pilot is a real-time monitoring and anomaly detection platform for manufacturing. It connects to existing machines and sensors on the shop floor, analyzes process data as it's produced, and surfaces deviations to the people who need to act on them. The goal is to catch problems like process drift, equipment degradation, and quality shifts early -- before they result in scrap, downtime, or missed shipments.

### How it works

The platform follows a connect-detect-act loop.

**Connect** -- Factory Pilot integrates with PLCs, CNCs, robots, and sensors through standard industrial protocols (OPC UA, MTConnect, MQTT, Modbus/TCP, REST). An edge gateway sits on-site, normalizes the signals, and streams them to the platform. CSV and REST endpoints cover legacy equipment.

**Detect** -- An anomaly detection engine runs threshold checks, drift and variance analysis, SPC rules, and machine learning models against incoming data. The ML layer uses self-supervised learning to establish what normal production looks like from unlabeled data, so it can flag deviations even when the failure mode hasn't been seen before. Baselines adapt automatically to shift changes, tool changes, and recipe switches.

**Act** -- When a deviation is detected, alerts route to the right person based on role, shift, and escalation rules. Notifications go out via Teams, Slack, email, SMS, or webhooks. The platform supports on-call rotations, SLA timers, stop-the-line workflows, and CAPA integration. Every alert, acknowledgment, and resolution is logged.

### What it covers

- **Real-time monitoring** -- live visibility into machine performance, cycle times, and production rates across equipment
- **Root-cause analysis** -- correlate signals, overlay batches and tools, trace events through the production line, and export evidence for 8D investigations
- **Predictive maintenance** -- ML-driven predictions flag equipment issues before unplanned downtime occurs
- **Dashboards and OEE** -- live cell/line views, golden-run overlays, OEE and FPY tracking, downtime categorization, and cost impact
- **Traceability** -- part-level genealogy linking process windows, tools, operators, and rework history

### Who uses it

Factory Pilot is designed for different roles across the plant. Operators receive real-time alerts with clear guidance. Engineers get diagnostic tools, anomaly analysis, and searchable evidence trails. Plant leadership gets OEE, quality metrics, and operational KPIs.

### Deployment

The platform runs on-prem, in the cloud, or hybrid. A small on-site gateway handles connectivity and edge processing. Deployment typically takes 30 days without disrupting existing operations. It scales across multiple facilities and supports Microsoft 365 SSO.

### Industries

Primary focus areas are automotive, aerospace and defense, and advanced manufacturing -- environments where tolerances are tight, traceability matters, and hidden process drift carries significant downstream risk.

---

### From this GitHub

Factory Pilot itself is not open source. Here we publish tools and utilities for the manufacturing data community.

<p>
  <a href="https://github.com/factory-pilot/test-historians"><img src="https://img.shields.io/badge/Repo-test--historians-111827?style=flat-square&logo=github&logoColor=white" alt="test-historians repository"></a>
  <a href="https://github.com/factory-pilot/test-historians"><img src="https://img.shields.io/badge/Docker-ready-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker ready"></a>
</p>

Spins up TimescaleDB, InfluxDB, and Grafana with 7 days of synthetic sensor data in a single command. Built for anyone developing against time-series databases.

---

<p align="center">
  <a href="https://factory-pilot.ai/en/book-demo"><img src="https://img.shields.io/badge/Book%20live%20demo-E8762D?style=for-the-badge&logo=calendly&logoColor=white" alt="Book a live demo"></a>
  <a href="https://factory-pilot.ai/en/contact"><img src="https://img.shields.io/badge/Contact%20us-111827?style=for-the-badge&logo=maildotru&logoColor=38BDF8" alt="Contact us"></a>
</p>
