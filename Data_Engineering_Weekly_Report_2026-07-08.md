# Data Engineering — Weekly Report | July 1–8, 2026

**Sprint:** [July 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/July%202026) (Jul 1 – Jul 31) | 2 of 50 stories closed | 0 Features closed this week

---

## 1. [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) ⚠️ At Risk

- **Objective:** Onboard NCS telemetry data sources (UFM, SONiC, PHY incidents) into the Databricks lake, build incident pipelines and dashboards, and migrate notebook infrastructure.
- **Done this week:**
  - [#10315 Debug UFM via OTLP collector to find dups](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10315) — _Feature_
    - [#10532 Onboard Michael Goldfeld on UFM Telemetry Investigation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10532) — _Roi_ **Unplanned**
    - [#10550 Validate Anomalies with Matching Time Since Last Clear](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10550) — _Roi_ **Unplanned**
  - [#10784 [MTBI]: Switch level exposure table](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10784) — _Uri_ **Unplanned**
  - [#10067 Debug Grafana Data Anomaly with Ilya](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10067) — _Roi_ **Unplanned**
  - [#10579 Sync with Anna on OR3 Data Sources and Known Issues](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10579) — _Roi_ **Unplanned**
  - [#10592 Investigate Metadata Requirements with Daher](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10592) — _Roi_ **Unplanned**
  - [#10814 Map Additional Amber Concepts for PHY Incidents](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10814) — _Roi_ **Unplanned**
- **In progress:**
  - [#6879 Incidents system - Pipelines and PHY/Tableau Dashboard (OR3)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6879) — _Feature_
    - [#7150 Incidents system - PHY Dashboard Build](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7150) — _Daher_
    - [#7430 PHY Incidents — Add NMX-T (NVLink) source](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7430) — _Daher_
  - [#9751 Create Dedicated Table for PHY Incidents](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9751) — _Roi_
    - [#10068 Design PHY Incidents Table](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10068) — _Roi_ **Unplanned**
- **Next week:**
  - [#7431 PHY Incidents — Blocked sources tracker (Cumulus, DTS, SONiC)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7431) — _Daher_
  - [#6877 GNMI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6877) — _Roi_ (under [#6876 Sonic Counters gNMI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6876))
  - [#7120 Migrate all .ipynb notebooks to magic .py files for Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7120) — _Roi_
  - [#10313 Debug UFM via OTLP collector to find dups](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10313) — _Roi_ **Unplanned**

> **Risk:** [#9751 Create Dedicated Table for PHY Incidents](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9751) still Active — may carry over to August.

---

## 2. [#268 Migrating to OR3](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) ⚠️ At Risk

- **Objective:** Migrate data pipelines and storage to the OR3 Kratos data lake, including streaming large DOCA Perftest results and validating gold table parity.
- **Done this week:**
  - [#7126 [new Kratos] Validate gold tables between new and old kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7126) — _Uri_
- **In progress:**
  - [#9200 Stream large DOCA Perftest result JSONs to nlastic-db](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9200) — _Feature_
    - [#9201 Stream large DOCA Perftest result JSONs to nlastic-db](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9201) — _Daher_
- **Next week:**
  - [#6432 Migrate data to new kratos data lake - implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6432) — Unassigned

> **Risk:** [#9201 Stream large DOCA Perftest result JSONs to nlastic-db](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9201) still Active — may carry over to August.

---

## 3. [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) ⚠️ At Risk

- **Objective:** Build the Nlastic Storage Service with per-DUT OTLP routing, deduplication, retries, dead-letter queues, S3 target support, and Coverage SDK integration.
- **In progress:** None started yet
- **Next week:**
  - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040) — _Gennady_
  - [#5779 [StorageService]W2 P1 - Bad Path — Dedup + Retries + DLQ + Deploy](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5779) — _Gennady_
  - [#5780 [StorageService]W3 P2 - S3 Target](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5780) — _Gennady_
  - [#5781 [StorageService]W4 P3 - Coverage SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5781) — _Gennady_

> **Risk:** All User Stories still New — no progress yet in the sprint. May carry over to August.

---

## 4. [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) ⚠️ At Risk

- **Objective:** Build the NSV Coverage system including pass rate reporting, dashboard migration from frontend to API, Azure SSO authentication, test case ID integration, and MCP support via strict Pydantic models.
- **In progress:**
  - [#7532 Migrate dashboard aggregation logic from frontend to API](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7532) — _Feature (In Review)_
    - [#7536 Cluster-Tag Rollup + Status/Test-Plan report endpoints](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7536) — _Tomer_
    - [#7533 Tag Coverage: tag_coverage endpoint](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7533) — _Tomer_
    - [#7534 Component Coverage: component_coverage endpoint](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7534) — _Tomer_
    - [#7535 Release/Solution Coverage: solution_coverage endpoint](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7535) — _Tomer_
- **Next week:**
  - [#4870 Expose the ability to report pass rate and details](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4870) — _Feature_
    - [#5146 [Coverage Side] Expose the ability to report pass rate and details — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5146) — _Tomer_
    - [#6242 [Nlastic + Coverage] Expose the ability to report pass rate and details — Planning](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6242) — _Tomer_
    - [#7434 Create Web UI Adjustments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7434) — _Tomer_
  - [#9197 Test Case ID — Coverage Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9197) — _Feature_
    - [#9198 Test Case ID — Coverage Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9198) — _Tomer_
  - [#9132 API authentication via Azure SSO middleware (Stage 2 — enforce roles)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9132) — _Feature_
    - [#9133 API authentication via Azure SSO middleware (Stage 2 — enforce roles)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9133) — _Tomer_
  - [#7707 Strict Pydantic model for system filters to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7707) — _Feature_
    - [#7708 Strict Pydantic model for system filters to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7708) — _Tomer_

> **Risk:** [#7532 Migrate dashboard aggregation logic from frontend to API](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7532) — Feature in review but all child stories still New. Large backlog of Features planned; may need prioritization.

---

## 5. [#1369 Solution FRs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1369) ⚠️ At Risk

- **Objective:** Address customer feature requests including syslog event filters, bidirectional throughput reporting, resiliency test analysis, and parallel group result display.
- **In progress:** None started yet
- **Next week:**
  - [#3638 Add syslog event filter for Failure Mode in Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3638) — _Feature_
    - [#7419 Syslog event filter for Failure Mode](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7419) — _Uri_
  - [#7079 Table Not Displaying Results for Parallel Group Runs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7079) — _Feature_
    - [#7421 Table Not Displaying Results for Parallel Group](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7421) — _Uri_
  - [#1412 Distinguish between receiver and sender throughput bw in case of M2O](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1412) — _Feature_
    - [#7408 Distinguish between receiver and sender throughput](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7408) — _Gennady_
  - [#1423 RDMA BIDI Throughput Reporting: Sum Both Directions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1423) — _Feature_
    - [#7411 RDMA BIDI Throughput Reporting: Sum Both Directions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7411) — _Gennady_
  - [#1425 Result Smart Analysis on Resiliency test results](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1425) — _Feature_
    - [#7413 Result Smart Analysis on Resiliency test results](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7413) — _Gennady_

> **Risk:** All 5 Features and their User Stories still New — no progress yet. May carry over to August.

---

## 6. [#5837 Cluster Control Room System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5837) ⚠️ At Risk

- **Objective:** Build the Cluster Control Room V1 — requirements gathering, system design, environment bring-up across Testing/Staging/Production, and health monitoring modules (PHY, MTBI, Telemetry).
- **In progress:**
  - [#7069 Requirements Gathering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7069) — _Feature_
    - [#10292 Requirements Gathering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10292) — _Abed_ **Unplanned**
- **Next week:**
  - [#8558 System Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8558) — _Feature_
    - [#10294 System Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10294) — _Michael_ **Unplanned**
  - [#9572 V1 Env Bring-Up: Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9572) — _Feature_
    - [#9573 Infra - Namespace in OpenShift](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9573) — _Abed_
    - [#9575 Infra - TLS Certificate](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9575) — _Abed_
    - [#9577 Infra - Azure Application](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9577) — _Abed_
    - [#9579 Infra - RBAC over Azure](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9579) — _Abed_
    - [#9581 Infra - DNS Records](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9581) — _Abed_
    - [#9583 Infra - Web UI Skeleton](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9583) — _Abed_
  - [#9585 V1 Env Bring-Up: Staging](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9585) — _Feature_ (6 infra stories)
  - [#9598 V1 Env Bring-Up: Production](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9598) — _Feature_ (6 infra stories)
  - [#9611 V1: PHY Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9611) — _Feature_
    - [#9612 Cluster Control Room - V1: PHY Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9612) — _Abed_
  - [#9614 V1: MTBI Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9614) — _Feature_
    - [#9615 Cluster Control Room - V1: MTBI Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9615) — _Abed_
  - [#9617 V1: Telemetry Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9617) — _Feature_
    - [#9618 Cluster Control Room - V1: Telemetry Health](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9618) — _Abed_

> **Risk:** Large scope with 8 Features — majority still New. Only Requirements Gathering has started. May carry over to August.

---

## Bugs — 1 High-Severity Open

- **Done this sprint:**
  - [#2145 Abeline MRC O2O test results missing from Regression Analysis dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2145) (Medium) — _Roi_
  - [#8005 Missing Results for Scenario 280 from Last Night](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8005) (Low) — _Uri_
- **In review:**
  - [#9750 Dashboards hang on an infinite loading spinner when a coverage query fails](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9750) (Low) — _Tomer_
  - [#9774 Wrong Benchmark Name When Running 2 Jobs Simultaneously](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9774) (Low) — _Uri_
  - [#9849 Coverage Misreporting Due to Coarse Parameter-Based Matching](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9849) (Low) — _Tomer_
- **Open:**

| ID | Title | Sev | Assignee | Note |
| -- | ----- | --- | -------- | ---- |
| [#7961 Bug: Kafka and S3 saver fails in scale](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7961) | Kafka and S3 saver fails in scale | High | _Daher_ | **Critical** |
| [#7690 Bug: DOCA Perftest Raw Data File Split Mid-Row During Streaming](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7690) | DOCA Perftest Raw Data File Split Mid-Row During Streaming | Low | _Daher_ | Active |
| [#7380 Audit log: dispatcher.resolve_targets and OtlpPoolAdapter.deliver disagree on target_name — PENDING and OUTCOME rows cannot be correlated](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7380) | Audit log: dispatcher.resolve_targets disagree on target_name | Low | _Gennady_ | |
| [#8546 Bug: AnalysisReport Validation Failure Preventing S3 and Tableau Save](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8546) | AnalysisReport Validation Failure Preventing S3 and Tableau Save | Low | _Gennady_ | |
| [#9846 Bug: Benchmark Name Truncated in Tableau Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9846) | Benchmark Name Truncated in Tableau Dashboard | Low | _Uri_ | |
| [#10524 collected samples ETL stuck too long](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/10524) | collected samples ETL stuck too long | Low | _Daher_ | **Unplanned** |

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/July%202026)_