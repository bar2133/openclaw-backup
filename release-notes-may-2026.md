# Data Engineering — May 2026 Release Notes

**Sprint:** May 2026  
**Team:** Data Engineering (NLASTIC)  
**Period:** May 1 – May 31, 2026

---

## Summary

13 features completed across 8 epics, covering Kafka streaming, Redmine integration, UX improvements, telemetry pipelines, a new Knowledge Base package, and more.

---

## NSV Coverage System

### [#601 — UX Enrichments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/601)
**Owner:** Neta Ronen

Polished the Coverage System UI with enriched overview actions, added tooltips to the total coverage gauge, and improved overall usability.

- Enriched the overview actions UX
- Added tooltip to the total coverage gauge
- General UX polish and enrichments

### [#2652 — Write Back to the Redmine](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2652)
**Owner:** Bar Nachlieli

Closed the feedback loop between the Coverage System and Redmine — R&D engineers and program managers now see coverage activity automatically on their Redmine feature tickets instead of having to check the Coverage UI manually.

Scope included:
- Extended RedmineService with write capabilities
- Built RedmineWritebackService orchestrator with feature flag support
- Wired Flow 1 into TagRouter (create + edit with FR diff)
- Wired Flow 2 into QueriesRouter (tag-coverage dashboard)
- Configuration & K8s rollout for new `REDMINE_` env vars
- Full test coverage for service, orchestrator, and routers
- Operational readiness — structured logs and error monitoring

### [#6197 — Permutation Sub-Scenario Auto-Naming via `permutation_name`](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6197)
**Owner:** Bar Nachlieli

Permutation sub-scenarios now carry a distinct, human-readable name derived from the `permutation_name` field, so they can be told apart in the Coverage system without drilling into arguments.

---

## NLastic Storage & Streaming Service

### [#5874 — Stream NLastic Data Directly to Kafka Instead of OTLP Collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5874)
**Owner:** Daher Daher (SW)

Removed the OTLP collector from the NLastic data path and replaced it with direct publishing to a dedicated Kafka topic, simplifying the pipeline and improving throughput.

- POC to validate direct-to-Kafka data flow
- Production-grade Kafka streaming implementation
- End-to-end validation of the new pipeline

---

## Good Morning Dashboard

### [#6535 — Deep-Dive Navigation Links](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6535)
**Owner:** Uri Menkes

Added contextual deep-dive links from the entry tab to domain-specific dashboards (RDMA, NCCL, AI, Logs, etc.) that carry the user's current filters, turning the entry tab into a one-click routing layer.

- Design phase
- Full implementation

---

## Migrating to OR3

### [#4771 — Handling Graph Data Model](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4771)
**Owner:** Uri Menkes

Moved from passthrough streaming of the Graph Data Model to full unpacking and processing inside the new Kratos pipeline, enabling proper GDM handling downstream.

---

## NCS Telemetry Data in Databricks

### [#6861 — Design Telemetry Data Pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6861)
**Owner:** Bar Nachlieli

Completed the end-to-end architectural design for ingesting NCS telemetry data into Databricks, defining schemas, pipeline stages, and partitioning strategy.

### [#6864 — UFM Telemetry Data Pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6864)
**Owner:** Roi Zilberzwaig

Implemented the UFM telemetry data pipelines that stream fabric-manager health and performance data into Databricks for analysis.

---

## NSV Reporting

### [#6063 — NLastic Reporting — Regression Report Skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6063)
**Owner:** Sari Ayik

Built a Claude/Cursor AI skill that auto-generates regression reports following the SP-X guidelines, so the execution team can quickly produce and share results with performance peers.

---

## Knowledge Base Service

### [#7245 — Knowledge Base Package](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7245)
**Owner:** Tomer Arbiv

Shipped the Knowledge Base v0.1 as a self-contained Python package with a single `KBClient` entry point, Milvus-backed vector storage, domain-scoped ingestion/retrieval, a CLI, and read-only MCP wrappers for AI-tool integration.

- Stable `KBClient` contract and public API
- Domain-scoped ingestion and retrieval operations
- Milvus as the default vector backend (write + read/search paths)
- Thin CLI command wrapper
- Read-only MCP wrappers
- Cursor Skill guide for developer integration
- Developer-ready package documentation
- QA & review

---

## Generic Buffers

### [#5791 — Bug Buffer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5791)
**Owner:** Bar Nachlieli

Reserved capacity for triaging and fixing unplanned bugs that surfaced during the sprint.

### [#5799 — Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5799)
**Owner:** Bar Nachlieli

Dedicated effort for running the formal test cycle and verifying deliverables before sprint close.

### [#5810 — Buddy Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5810)
**Owner:** Bar Nachlieli

Cross-team support capacity for ad-hoc requests and knowledge-sharing with partner teams.

---

## Contributors

| Name | Features |
|---|---|
| Bar Nachlieli | Write Back to Redmine, Permutation Auto-Naming, Telemetry Design, Bug Buffer, Formal Cycle Testing, Buddy Support |
| Neta Ronen | UX Enrichments |
| Uri Menkes | Graph Data Model, Deep-Dive Navigation Links |
| Daher Daher (SW) | Kafka Streaming |
| Roi Zilberzwaig | UFM Telemetry Pipelines |
| Sari Ayik | Regression Report Skill |
| Tomer Arbiv | Knowledge Base Package |
