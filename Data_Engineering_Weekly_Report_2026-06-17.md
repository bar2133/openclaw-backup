# Data Engineering — Weekly Report | June 15–17, 2026

**Sprint:** [June 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/June%202026) (Jun 1 – Jun 30) | 22 of 52 stories closed | 12 Features closed this sprint

---

## 1. [#268 Migrating to OR3](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) — ✅ On Track

- **Objective:** Migrate data infrastructure to the new OR3 Kratos data lake, validate gold table parity, and configure regional notifications.

- **Done this week:**
  - [#539 Migrate data to new kratos data lake - migration design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/539) — _Feature_
- **In progress:**
  - [#7427 Validate gold tables between new and old kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7427) — _Feature_
    - [#7126 [new Kratos] Validate gold tables between new and old kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7126) (SP:2) — _Uri_
  - [#7680 Create Slack channel for OR3 region notifications and configure Databricks jobs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7680) — _Feature_ **Unplanned**
    - [#7682 Create Slack channel for OR3 region notifications and configure Databricks jobs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7682) (SP:1) — _Daher_ **Unplanned**
- **Next week:**
  - [#4815 Migrate data to new kratos data lake](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4815) (SP:5) — _Daher_

> **Risk:** [#7126 [new Kratos] Validate gold tables between new and old kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7126) still Active — may carry over to July.

---

## 2. [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) — ✅ On Track

- **Objective:** Enhance the coverage system with regex filtering, admin panel, pass rate reporting, dashboards (cluster tag rollup, RC build trend), API auth, SDK, tag labels, and MCP backend support.

- **Done this week:**
  - [#590 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/590) — _Feature_
    - [#3943 support more then one regex in filters](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) — _Neta_
    - [#6003 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6003) (SP:2) — _Neta_
  - [#7237 Cluster Tag Coverage Rollup Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7237) — _Feature_
    - [#7238 Cluster Tag Coverage Rollup Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7238) (SP:5) — _Tomer_ (13 tasks completed: models, transform, service wiring, dashboard scaffold, KPIs, card components, minimap, focus window, edge states, tests, review)
    - [#7972 Filter coverage breakdown by tag selection](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7972) (SP:1) — _Tomer_ **Unplanned**
    - [#7973 Add free text search to coverage breakdown](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7973) (SP:1) — _Tomer_ **Unplanned**
  - [#7240 RC Build Coverage Trend Report Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7240) — _Feature_
    - [#7241 RC Build Coverage Trend Report](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7241) (SP:5) — _Tomer_
  - [#7463 Non-blocking unique_filters materialized-view refresh (fix /api/beta/filter/ DB stalls)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7463) — _Feature_
    - [#7464 Remove materialized-view refresh from the request path](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7464) (SP:2) — _Bar_
    - [#7468 Make the refresh non-blocking (CONCURRENTLY) and idempotent](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7468) (SP:2) — _Bar_
    - [#7472 Guarantee a single refresh runs at a time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7472) (SP:2) — _Bar_
    - [#7475 Schedule the refresh in the database via pg_cron](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7475) (SP:2) — _Bar_
    - [#7480 Roll out and verify across environments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7480) (SP:2) — _Bar_
  - [#7537 API authentication via Azure SSO middleware (Stage 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7537) — _Feature_ **Unplanned**
    - [#7538 Validate Azure AD access token in API auth middleware; keep 4 SDK open pairs working (Stage 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7538) (SP:2) — _Tomer_ **Unplanned** (5 tasks: AuthConfig settings, auth middleware, exclusion paths, k8s wiring, tests)
- **In progress:**
  - [#7500 Tag Labels Support SPCX](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7500) — _Feature_ **Unplanned**
    - [#7501 Tag Labels Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7501) (SP:4) — _Tomer_ **Unplanned**
- **Next week:**
  - [#2082 [coverage]attributes category splitting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2082) (SP:3) — _Neta_
  - [#6005 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6005) (SP:2) — _Neta_
  - [#7423 Now and Today Quick-Select Buttons](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7423) (SP:2) — _Neta_
  - [#4424 Tech debt](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4424) (SP:2) — _Neta_
  - [#5146 [Coverage Side]Expose the ability to report pass rate and details — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5146) (SP:1) — _Tomer_
  - [#6242 [Nlastic + Coverage]Expose the ability to report pass rate and details — Planning](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6242) (SP:2) — _Tomer_
  - [#7434 Create Web UI Adjustments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7434) (SP:3) — _Tomer_
  - [#7516 Tag-Driven Release Scope](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7516) (SP:3) — _Tomer_ **Unplanned**
  - [#7705 Move all FE logic to the BE to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7705) (SP:2) — _Tomer_ **Unplanned**
  - [#7708 Strict Pydantic model for system filters to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7708) (SP:2) — _Tomer_ **Unplanned**

> **Risk:** [#7501 Tag Labels Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7501) still Active — may carry over to July.

> **Risk:** [#661 Admin Panel](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/661) still Active with no stories started — may carry over to July.

---

## 3. [#1369 Solution FRs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1369) — ⚠️ At Risk

- **Objective:** Address customer feature requests including throughput reporting enhancements, resiliency test analysis, BER port display, syslog filtering, parallel group display fixes, and result analyzers.

- **In progress:**
  - [#7079 Table Not Displaying Results for Parallel Group Runs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7079) — _Feature_
    - [#7421 Table Not Displaying Results for Parallel Group](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7421) (SP:2) — _Uri_
- **Next week:**
  - [#7408 Distinguish between receiver and sender throughput](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7408) (SP:2) — _Gennady_
  - [#7411 RDMA BIDI Throughput Reporting: Sum Both Directions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7411) (SP:2) — _Gennady_
  - [#7413 Result Smart Analysis on Resiliency test results](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7413) (SP:2) — _Gennady_
  - [#7415 UFM - failed ports for effective BER](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7415) (SP:2) — _Gennady_
  - [#7419 Syslog event filter for Failure Mode](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7419) (SP:2) — _Uri_
  - [#7512 Implement analyzer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7512) — _Gennady_ (under [#6845 Resiliency test analyzer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6845))

> **Risk:** [#7079 Table Not Displaying Results for Parallel Group Runs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7079) still Active — may carry over to July.

> **Risk:** Majority of items still New with significant remaining work — 6 features not yet started.

---

## 4. [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) — ✅ On Track

- **Objective:** Build the NLastic storage and streaming service with OTLP collector routing, deployment, happy path implementation, dedup/retries, S3 target, and coverage SDK integration. Resolved critical data corruption bug this week.

- **Done this week:**
  - [#8702 Fix data corruption in Databricks caused by wrong scenario_uuid](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8702) — _Uri_ **Unplanned**
    - [#8707 Identify affected tables and time range of corrupted records](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8707) — _Uri_
    - [#8708 Build query to detect records with mismatched scenario_uuid](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8708) — _Uri_
    - [#8709 Remediate corrupted data (re-tag or backfill correct scenario_uuid)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8709) — _Uri_
    - [#8710 Validate data integrity post-fix](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8710) — _Uri_
  - [#8704 Fix NLastic streaming to capture scenario metadata at creation time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8704) — _Bar_ **Unplanned**
    - [#8711 Capture scenario metadata at record creation/enqueue time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8711) — _Bar_
    - [#8712 Add unit tests for scenario_uuid correctness under async serialization](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8712) — _Bar_
    - [#8713 Validate fix in staging environment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8713) — _Bar_
  - [#8703 Fix NLastic streaming to capture scenario metadata at creation time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8703) — _Bar_ **Unplanned**
- **In progress:**
  - [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) — _Feature_
    - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040)
      - [#6043 Monolith call sites: pass DUT collector coords into SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6043) — _Gennady_
      - [#6045 nlastic-data-streaming SDK: build envelope.targets from Consul-discovered (address, port)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6045) — _Gennady_
- **Next week:**
  - [#6032 [StorageService]W1 P1 — Deployment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6032) (SP:3) — _Gennady_
  - [#6243 [StorageService]W1 P1 — Happy Path Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6243) — _Gennady_
  - [#5779 [StorageService]W2 P1 - Bad Path — Dedup + Retries + DLQ + Deploy](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5779) (SP:3) — _Gennady_
  - [#5780 [StorageService]W3 P2 - S3 Target](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5780) (SP:4) — _Gennady_
  - [#5781 [StorageService]W4 P3 - Coverage SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5781) (SP:2) — _Gennady_

> **Risk:** [#6043 Monolith call sites: pass DUT collector coords into SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6043) and [#6045 nlastic-data-streaming SDK: build envelope.targets](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6045) still Active — may carry over to July.

---

## 5. [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) — ✅ On Track

- **Objective:** Ingest NCS telemetry data (NMXT, Cumulus, DTS, NVLink, MTBI, Incidents) into Databricks with data pipelines, silver-layer processing, and PHY/Tableau dashboards.

- **Done this week:**
  - [#6867 NMXT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6867) — _Feature_
    - [#7425 NMXT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7425) (SP:4) — _Roi_
      - [#7426 Implementation Silver L1](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7426) — _Roi_
  - [#6870 Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6870) — _Feature_
    - [#6871 [Data pipelines] Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6871) (SP:4) — _Roi_
    - [#8015 Cumulus counters silver L2](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8015) — _Roi_ **Unplanned**
      - [#8046 Pivot Table Assessment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8046) — _Roi_ **Unplanned**
  - [#6873 DTS data](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6873) — _Feature_
    - [#6874 [Data pipelines] DTS design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6874) (SP:2) — _Roi_
    - [#7343 [Data pipelines] DTS](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7343) (SP:3) — _Roi_
      - [#7344 Silver L1](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7344) — _Roi_
  - [#7055 MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7055) — _Feature_
    - [#7058 MTBI - Data  Review & Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7058) (SP:4) — _Uri_
    - [#7154 MTBI - Dashboard Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7154) (SP:2) — _Uri_
    - [#7341 [Data pipelines]  MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7341) (SP:5) — _Uri_
    - [#7342 MTBI - Data pipeline implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7342) (SP:3) — _Uri_
  - [#7348 NVlink metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7348) — _Feature_
    - [#7349 [Data pipelines] NVlink metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7349) (SP:4) — _Roi_
      - [#7350 Implemented Silver L1 for Cumulus](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7350) — _Roi_

- **In progress:**
  - [#6879 Incidents system - Pipelines and PHY/Tableau Dashboard (OR3)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6879) — _Feature_
    - [#6880 Incidents system - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6880) (SP:2) — _Roi_ ✅ Done
    - [#7150 Incidents system - PHY Dashboard Build](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7150) (SP:5) — _Roi_
      - [#7428 PHY Incidents — UFM core + Tableau dashboard (Phase 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7428) — _Roi_ (Active)
      - [#7429 PHY Incidents — Add UFM CPO source](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7429) — _Roi_ (New)
      - [#7430 PHY Incidents — Add NMX-T (NVLink) source](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7430) — _Roi_ (New)
      - [#7431 PHY Incidents — Blocked sources tracker](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7431) — _Roi_ (New)
      - [#7432 PHY Incidents — Production hardening](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7432) — _Roi_ (New)
    - [#7152 Incidents system - Good Morning Dashboard Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7152) (SP:3) — _Roi_

> **Risk:** [#7428 PHY Incidents — UFM core + Tableau dashboard (Phase 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7428) still Active — may carry over to July.

---

## Bugs — 0 High-Severity Open

- **Done this sprint:**
  - [#3943 support more then one regex in filters](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) — _Neta_
  - [#8702 Fix data corruption in Databricks caused by wrong scenario_uuid](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8702) — _Uri_ **Unplanned**
  - [#8703 Fix NLastic streaming to capture scenario metadata at creation time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8703) — _Bar_ **Unplanned**
  - [#8704 Fix NLastic streaming to capture scenario metadata at creation time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8704) — _Bar_ **Unplanned**
- **Open:**

| ID | Title | Sev | Assignee | Note |
| -- | ----- | --- | -------- | ---- |
| [#7380 Audit log: dispatcher.resolve_targets and OtlpPoolAdapter.deliver disagree on target_name — PENDING and OUTCOME rows cannot be correlated](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7380) | Audit log: dispatcher.resolve_targets and OtlpPoolAdapter.deliver disagree on ta | Low | _Gennady_ |  |
| [#7509 Custom dashboard filters with the same category + key overwrite previous values in URL](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7509) | Custom dashboard filters with the same category + key overwrite previous values  | Low | _Neta_ | **Unplanned** |

---

## Sprint Management

- **Generic Buffers:** Capacity buffers allocated per team member (Bug Buffer, individual buffers) under [#4773 Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773) — Active, tracking ongoing unplanned work absorption.


_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/June%202026)_
