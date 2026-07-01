# Data Engineering — Weekly Report | June 29 – July 5, 2026

**Sprint:** [July 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/July%202026) (Jul 1 – Jul 31) | 0 of 37 stories closed | 0 Features closed this week

> 📋 Sprint just kicked off — all items are in **New** state. This report captures the planned scope and initial assignments.

---

## 1. [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) — Storage & Streaming ⚠️ At Risk

- **Objective:** Build and deploy the Nlastic Storage Service with deduplication, retry/DLQ handling, S3 target support, and a Coverage SDK — plus per-DUT OTLP collector routing.

- **Planned this sprint:**
  - [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) — _Feature_ (Active)
    - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040) (SP:1) — _Gennady_
    - [#5779 [StorageService]W2 P1 - Bad Path — Dedup + Retries + DLQ + Deploy](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5779) (SP:3) — _Gennady_
    - [#5780 [StorageService]W3 P2 - S3 Target](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5780) (SP:4) — _Gennady_
    - [#5781 [StorageService]W4 P3 - Coverage SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5781) (SP:2) — _Gennady_

> **Risk:** All items are New at sprint start. Four User Stories (10 SP total) scoped to a single developer (_Gennady_) — heavy load may cause carry-over to August.

---

## 2. [#268 Migrating to OR3](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) — OR3 Migration ✅ On Track

- **Objective:** Enable streaming of large DOCA Perftest result JSONs into nlastic-db, splitting them into reassemblable units for OR3 compatibility.

- **Planned this sprint:**
  - [#9200 Stream large DOCA Perftest result JSONs to nlastic-db (split into reassemblable units)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9200) — _Feature_
    - [#9201 Stream large DOCA Perftest result JSONs to nlastic-db (split into reassemblable units)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9201) (SP:2) — _Daher_

---

## 3. [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) — Coverage System ✅ On Track

- **Objective:** Enhance the NSV Coverage platform with pass-rate reporting, server-side dashboard aggregation, Test Case ID integration, Azure SSO auth enforcement, and MCP-compatible Pydantic filters.

- **Planned this sprint:**
  - [#4870 expose the ability to report pass rate and details](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4870) — _Feature_ (Active)
    - [#6242 [Nlastic + Coverage]Expose the ability to report pass rate and details — Planning](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6242) (SP:2) — _Tomer_
    - [#5146 [Coverage Side]Expose the ability to report pass rate and details — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5146) (SP:1) — _Tomer_
    - [#7434 Create Web UI Adjustments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7434) (SP:3) — _Tomer_
  - [#7532 Migrate dashboard aggregation logic from frontend to API](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7532) — _Feature_
    - [#7533 Tag Coverage: tag_coverage endpoint returns fully-aggregated dashboard structure](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7533) (SP:3) — _Tomer_
    - [#7534 Component Coverage: component_coverage endpoint returns fully-aggregated dashboard structure](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7534) (SP:2) — _Tomer_
    - [#7535 Release/Solution Coverage: solution_coverage endpoint returns fully-aggregated dashboard structure](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7535) (SP:2) — _Tomer_
    - [#7536 Cluster-Tag Rollup + Status/Test-Plan report endpoints (server-side aggregation)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7536) (SP:5) — _Tomer_
  - [#9197 Test Case ID — Coverage Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9197) — _Feature_
    - [#9198 Test Case ID — Coverage Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9198) (SP:2) — _Tomer_
  - [#9132 API authentication via Azure SSO middleware (Stage 2 — enforce roles)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9132) — _Feature_
    - [#9133 API authentication via Azure SSO middleware (Stage 2 — enforce roles)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9133) (SP:2) — _Tomer_
  - [#7707 Strict Pydantic model for system filters to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7707) — _Feature_
    - [#7708 Strict Pydantic model for system filters to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7708) (SP:2) — _Tomer_

> **Risk:** 5 Features with 24 SP all assigned to _Tomer_ — prioritization will be key to avoid carry-over.

---

## 4. [#5837 Cluster Control Room System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5837) — Cluster Control Room ✅ On Track

- **Objective:** Stand up the Cluster Control Room V1 across three environments (Testing, Staging, Production) with infrastructure provisioning, health dashboards (PHY, MTBI, Telemetry), and system design.

- **Planned this sprint:**
  - [#9572 Cluster Control Room - V1 Env Bring-Up: Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9572) — _Feature_
    - [#9573 Infra - Namespace in OpenShift](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9573) (SP:2) — _Abed_
    - [#9575 Infra - TLS Certificate](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9575) (SP:2) — _Abed_
    - [#9577 Infra - Azure Application](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9577) (SP:2) — _Abed_
    - [#9579 Infra - RBAC over Azure](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9579) (SP:2) — _Abed_
    - [#9581 Infra - DNS Records](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9581) (SP:2) — _Abed_
    - [#9583 Infra - Web UI Skeleton](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9583) (SP:2) — _Abed_
  - [#9585 Cluster Control Room - V1 Env Bring-Up: Staging](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9585) — _Feature_
    - [#9586 Infra - Namespace in OpenShift](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9586) (SP:2) — _Abed_
    - [#9588 Infra - TLS Certificate](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9588) (SP:2) — _Abed_
    - [#9590 Infra - Azure Application](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9590) (SP:2) — _Abed_
    - [#9592 Infra - RBAC over Azure](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9592) (SP:2) — _Abed_
    - [#9594 Infra - DNS Records](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9594) (SP:2) — _Abed_
    - [#9596 Infra - Web UI Skeleton](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9596) (SP:2) — _Abed_
  - [#9598 Cluster Control Room - V1 Env Bring-Up: Production](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9598) — _Feature_
    - [#9599 Infra - Namespace in OpenShift](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9599) (SP:2) — _Abed_
    - [#9601 Infra - TLS Certificate](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9601) (SP:2) — _Abed_
    - [#9603 Infra - Azure Application](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9603) (SP:2) — _Abed_
    - [#9605 Infra - RBAC over Azure](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9605) (SP:2) — _Abed_
    - [#9607 Infra - DNS Records](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9607) (SP:2) — _Abed_
    - [#9609 Infra - Web UI Skeleton](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9609) (SP:2) — _Abed_
  - [#9611 Cluster Control Room - V1: PHY Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9611) — _Feature_
    - [#9612 Cluster Control Room - V1: PHY Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9612) (SP:2) — _Abed_
  - [#9614 Cluster Control Room - V1: MTBI Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9614) — _Feature_
    - [#9615 Cluster Control Room - V1: MTBI Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9615) (SP:2) — _Abed_
  - [#9617 Cluster Control Room - V1: Telemetry Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9617) — _Feature_
    - [#9618 Cluster Control Room - V1: Telemetry Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9618) (SP:2) — _Abed_
  - [#7069 Requirements Gathering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7069) — _Feature_ (Active) — _Abed_
  - [#8558 System Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8558) — _Feature_ — _Michael_

> **Risk:** Largest Epic in the sprint — 8 Features, 21 User Stories (42 SP), all assigned to _Abed_. Env bring-up across 3 environments has repetitive infra work that should parallelize well, but volume is high.

---

## 5. [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) — Telemetry in Databricks ✅ On Track

- **Objective:** Ingest Sonic Counters via gNMI into Databricks for NCS telemetry data analysis.

- **Planned this sprint:**
  - [#6876 Sonic Counters gNMI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6876) — _Feature_
    - [#6877 GNMI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6877) (SP:5) — _Roi_

---

## Bugs — 0 High-Severity Open

- **Open:**

| ID | Title | Sev | Assignee | Note |
| -- | ----- | --- | -------- | ---- |
| [#7380 Audit log: dispatcher.resolve_targets and OtlpPoolAdapter.deliver disagree on target_name — PENDING and OUTCOME rows cannot be correlated](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7380) | Audit log: dispatcher.resolve_targets and OtlpPoolAdapter.deliver disagree on ta | Low | _Gennady_ | |

---

## Sprint Management Summary

| Metric | Value |
| ------ | ----- |
| Total User Stories | 37 |
| Total Story Points | 83 |
| Stories Closed | 0 |
| Features in Sprint | 15 |
| Features Closed | 0 |
| Bugs Open | 1 (Low) |
| Sprint Progress | Day 1 of 31 |

**Load by Assignee:**

| Assignee | Stories | SP |
| -------- | ------- | -- |
| _Abed_ | 21 | 42 |
| _Tomer_ | 10 | 24 |
| _Gennady_ | 4 | 10 |
| _Roi_ | 1 | 5 |
| _Daher_ | 1 | 2 |

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/July%202026)_
