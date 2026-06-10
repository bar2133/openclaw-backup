# Data Engineering — Weekly Report | Jun 1 – Jun 10, 2026

**Sprint:** [June 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/June%202026) (Jun 1 – Jun 30) | 9 of 54 stories closed | 4 Features closed this week

---

## 1. [#268 Migrating to OR3](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) — Migrating to OR3 ⚠️ At Risk

- **Objective:** Migrate data and infrastructure from CA1 to OR3 region, including data lake, dashboards, and monitoring.
- **Next week:**
  - [#4815 Migrate data to new kratos data lake](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4815) (SP:5) — _Daher_
  - [#7126 [new Kratos] Validate gold tables between new and old kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7126) (SP:2) — _Uri_
  - [#7682 Create Slack channel for OR3 region notifications and configure Databricks jobs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7682) (SP:1) — _Daher_ **Unplanned**
  - [#7702 Duplicate PHY dashboard from CA1 to OR3](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7702) (SP:2) — _Uri_ **Unplanned**

---

## 2. [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) — NSV Coverage System ✅ On Track

- **Objective:** Expand and harden the NSV Coverage platform — dashboards, SDK, API auth, filtering, and MCP support.
- **Done this week:**
  - [#7238 Cluster Tag Coverage Rollup Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7238) (SP:5) — _Tomer_
    - [#7239 Define ClusterTagRollupResponse / ClusterTagRollup / ClusterTagRollupTag models + TagSortMode](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7239) — _Tomer_
    - [#7447 Implement buildClusterTagRollup() transform (unique scenario UUIDs per cluster & tag) + pure helpers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7447) — _Tomer_
    - [#7448 Wire getClusterTagRollup into CoverageDashboardDataService (DashboardType.CLUSTER_TAG_ROLLUP + BehaviorSubject) + TagApiService.getTag enrichment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7448) — _Tomer_
    - [#7449 Scaffold ClusterTagRollupDashboardComponent (extends BaseDashboardComponent) + route + landing card + title constant](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7449) — _Tomer_
    - [#7450 Wire KPI HalfGauge + keep CoverageOvertimeChart + CoverageTable (coverageTableData grouped by cluster)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7450) — _Tomer_
    - [#7451 Build ClusterTagRollupCardComponent (legend, header, rows) + global sort sortTags (Gaps / Lowest %)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7451) — _Tomer_
    - [#7452 Add cluster-row tooltip + info icon (unique vs tag-membership calc note)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7452) — _Tomer_
    - [#7453 Build ClusterRollupRowComponent + local neutral minimap (moveToTag sliding lens)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7453) — _Tomer_
    - [#7454 Implement responsive focus window (ResizeObserver, focusSize, clamp focusIndex)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7454) — _Tomer_
    - [#7455 Build TagFocusCardComponent (uncovered-first strip, %, covered/total, gap)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7455) — _Tomer_
    - [#7457 Handle edge states (0 tags, total=0, long names, solution tag, null cluster)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7457) — _Tomer_
    - [#7458 Unit tests (transform, sort comparators, minimap math, tooltip gating)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7458) — _Tomer_
    - [#7459 Code review + fixes](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7459) — _Tomer_
  - [#7463 Non-blocking unique_filters materialized-view refresh (fix /api/beta/filter/ DB stalls)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7463) — _Feature_
    - [#7464 Remove materialized-view refresh from the request path](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7464) (SP:2) — _Bar_
      - [#7465 Remove _process_refresh_queue call from RationalFilterManager.reads()](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7465) — _Bar_
      - [#7466 Remove process_refresh_queue from manager and IFilterManager](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7466) — _Bar_
      - [#7467 Unit-test: read path issues only a SELECT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7467) — _Bar_
    - [#7468 Make the refresh non-blocking (CONCURRENTLY) and idempotent](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7468) (SP:2) — _Bar_
      - [#7469 Add ux_unique_filters UNIQUE index (item_category,item_name,item_value)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7469) — _Bar_
      - [#7470 refresh_unique_filters_materialized_view() uses CONCURRENTLY with plain fallback](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7470) — _Bar_
      - [#7471 Make auto_refresh_unique_filters_pure_sql.sql idempotent (drop new triggers before create)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7471) — _Bar_
    - [#7472 Guarantee a single refresh runs at a time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7472) (SP:2) — _Bar_
      - [#7473 Add pg_try_advisory_xact_lock guard in process_unique_filters_refresh_queue()](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7473) — _Bar_
      - [#7474 Verify contention: two sessions -> one refreshes, one no-ops](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7474) — _Bar_
    - [#7475 Schedule the refresh in the database via pg_cron](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7475) (SP:2) — _Bar_
      - [#7476 Build/push custom CNPG operand image (postgresql:17.5 + pg_cron)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7476) — _Bar_
      - [#7477 Configure CNPG: imageName, imagePullSecrets, shared_preload_libraries, cron settings](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7477) — _Bar_
      - [#7478 enable_pg_cron_unique_filters.sql (CREATE EXTENSION + cron.schedule)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7478) — _Bar_
      - [#7479 Remove obsolete postgresql-remove-shared-preload patch (prod)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7479) — _Bar_
    - [#7480 Roll out and verify across environments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7480) (SP:2) — _Bar_
      - [#7481 Apply + bootstrap + verify TESTING](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7481) — _Bar_
      - [#7482 Apply + bootstrap + verify STAGING](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7482) — _Bar_
      - [#7483 Apply + bootstrap + verify PRODUCTION (off-peak)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7483) — _Bar_
      - [#7484 Document manual DB bootstrap runbook](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7484) — _Bar_
  - [#7537 API authentication via Azure SSO middleware (Stage 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7537) — _Feature_
    - [#7538 Validate Azure AD access token in API auth middleware; keep 4 SDK open pairs working (Stage 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7538) (SP:2) — _Tomer_ **Unplanned**
      - [#7542 Wire API_AUTH_ENABLED + auth env vars into .env.example and k8s overlays (on deployed, off local/Cypress)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7542) — _Tomer_ **Unplanned**
      - [#7540 Implement auth middleware with fastapi-azure-auth (JWKS/issuer/audience/expiry/scope -> CORS-visible 401; claims on request.state)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7540) — _Tomer_ **Unplanned**
      - [#7539 Add AuthConfig pydantic-settings (tenant/audience/issuer/JWKS/scope + API_AUTH_ENABLED)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7539) — _Tomer_ **Unplanned**
      - [#7543 Tests: valid/invalid/expired/missing-scope token, CORS-visible 401, 4 SDK open pairs, exact health route, toggle off](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7543) — _Tomer_ **Unplanned**
      - [#7541 Build exclusion/open-paths list from GeneralConfig().version (4 SDK open pairs; exact health route; /mcp + infra open)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7541) — _Tomer_ **Unplanned**
- **Next week:**
  - [#6003 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6003) (SP:2) — _Neta_
  - [#2082 [coverage]attributes category splitting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2082) (SP:3) — _Neta_
  - [#6005 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6005) (SP:2) — _Neta_
  - [#7423 Now and Today Quick-Select Buttons](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7423) (SP:2) — _Neta_
  - [#4424 Tech debt](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4424) (SP:2) — _Neta_
  - [#5146 [Coverage Side]Expose the ability to report pass rate and details — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5146) (SP:1) — _Tomer_
  - [#6242 [Nlastic + Coverage]Expose the ability to report pass rate and details — Planning](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6242) (SP:2) — _Tomer_
  - [#7434 Create Web UI Adjustments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7434) (SP:3) — _Tomer_
  - [#7972 Filter coverage breakdown by tag selection](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7972) (SP:1) — _Tomer_ **Unplanned**
  - [#7973 Add free text search to coverage breakdown](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7973) (SP:1) — _Tomer_ **Unplanned**
  - [#7241 RC Build Coverage Trend Report](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7241) (SP:5) — _Tomer_
  - [#7501 Tag Labels Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7501) (SP:4) — _Tomer_ **Unplanned**
  - [#7516 Tag-Driven Release Scope](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7516) (SP:3) — _Tomer_ **Unplanned**
  - [#7705 Move all FE logic to the BE to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7705) (SP:2) — _Tomer_ **Unplanned**
  - [#7708 Strict Pydantic model for system filters to support the MCP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7708) (SP:2) — _Tomer_ **Unplanned**

> **Risk:** [#4870 expose the ability to report pass rate and details](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4870) still Active — may carry over to July.

> **Risk:** [#661 Admin Panel](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/661) still Active — may carry over to July.

> **Risk:** [#7237 Cluster Tag Coverage Rollup Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7237) still Active — may carry over to July.

> **Risk:** [#7240 RC Build Coverage Trend Report Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7240) still Active — may carry over to July.

---

## 3. [#1369 Solution FRs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1369) — Solution FRs ⚠️ At Risk

- **Objective:** Deliver customer-requested features for Nlastic solutions (resiliency, monitoring, throughput reporting).
- **Next week:**
  - [#7408 Distinguish between receiver and sender throughput](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7408) (SP:2) — _Gennady_
  - [#7417 Add cmdline to hover information](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7417) (SP:2) — _Uri_
  - [#7411 RDMA BIDI Throughput Reporting: Sum Both Directions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7411) (SP:2) — _Gennady_
  - [#7413 Result Smart Analysis on Resiliency test results](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7413) (SP:2) — _Gennady_
  - [#7415 UFM - failed ports for effective BER](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7415) (SP:2) — _Gennady_
  - [#7419 Syslog event filter for Failure Mode](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7419) (SP:2) — _Uri_
  - [#7512 Implement analyzer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7512) — _Gennady_ **Unplanned**
  - [#7421 Table Not Displaying Results for Parallel Group](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7421) (SP:2) — _Uri_

---

## 4. [#4773 Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773) — Generic Buffers ✅ On Track

- **Objective:** Team capacity buffer allocation for unplanned bug fixes and support work.
- **In progress:**
  - [#7354 June bug buffer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7354) (SP:14) — _Bar_
    - [#7359 Tomer Buffer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7359) — _Tomer_

---

## 5. [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) — Nlastic Storage & Streaming Service ✅ On Track

- **Objective:** Build a unified storage and streaming service for Nlastic data pipelines (OTLP, S3, DLQ, dedup).
- **Done this week:**
  - [#7367 TargetDispatcher: expose resolve_targets API for pre-dispatch PENDING audit writes](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7367) — _Gennady_
- **In progress:**
  - [#6243 [StorageService]W1 P1 — Happy Path Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6243) — _Gennady_
    - [#5750 E2E batch test with real OTLP collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5750) — _Gennady_
- **Next week:**
  - [#5779 [StorageService]W2 P1 - Bad Path — Dedup + Retries + DLQ + Deploy](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5779) (SP:3) — _Gennady_
  - [#5780 [StorageService]W3 P2 - S3 Target](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5780) (SP:4) — _Gennady_
  - [#5781 [StorageService]W4 P3 - Coverage SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5781) (SP:2) — _Gennady_
  - [#6032 [StorageService]W1 P1 — Deployment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6032) (SP:3) — _Gennady_
  - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040) (SP:1) — _Gennady_

> **Risk:** [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) still Active — may carry over to July.

---

## 6. [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) — NCS Telemetry Data in Databricks ✅ On Track

- **Objective:** Build data pipelines and dashboards for NCS telemetry (MTBI, DTS, Cumulus, NVLink, Incidents).
- **Done this week:**
  - [#6870 Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6870) — _Feature_
    - [#6871 [Data pipelines] Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6871) (SP:4) — _Roi_
  - [#6874 [Data pipelines] DTS design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6874) (SP:2) — _Roi_
- **Next week:**
  - [#7425 NMXT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7425) (SP:4) — _Roi_
  - [#8015 Cumulus counters silver L2](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8015) — _Roi_ **Unplanned**
  - [#7343 [Data pipelines] DTS](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7343) (SP:3) — _Roi_
  - [#6880 Incidents system - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6880) (SP:2) — _Anan_
  - [#7150 Incidents system - PHY Dashboard Build](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7150) (SP:6) — _Daher_
  - [#7152 Incidents system - Good Morning Dashboard Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7152) (SP:3) — _Uri_
  - [#7341 [Data pipelines]  MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7341) (SP:5) — _Uri_
  - [#7342 MTBI - Data pipeline implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7342) (SP:3) — _Uri_
  - [#7058 MTBI - Data  Review & Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7058) (SP:4) — _Uri_
  - [#7154 MTBI - Dashboard Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7154) (SP:2) — _Uri_
  - [#7349 [Data pipelines] NVlink metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7349) (SP:4) — _Roi_

> **Risk:** [#7055 MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7055) still Active — may carry over to July.

> **Risk:** [#6873 DTS data](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6873) still Active — may carry over to July.

> **Risk:** [#6879 Incidents system - Pipelines and Dashboards](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6879) still Active — may carry over to July.

---

## Bugs — 0 High-Severity Open

- **Open:**

| ID | Title | Sev | Assignee | Note |
| --- | --- | --- | --- | --- |
| [#7380](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7380) | Audit log: dispatcher.resolve_targets and OtlpPoolAdapter.deliver disagree on target_name — PENDING and OUTCOME rows cannot be correlated | 3 - Low | _Gennady_ |  |
| [#7509](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7509) | Custom dashboard filters with the same category + key overwrite previous values in URL | 3 - Low | _Neta_ | **Unplanned** |
| [#3943](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) | support more then one regex in filters | 3 - Low | _Neta_ |  |

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/June%202026)_