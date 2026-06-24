# Data Engineering — Weekly Report | June 22–28, 2026

**Sprint:** [June 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/June%202026) (Jun 1 – Jun 30) | 23 of 56 stories closed | 3 Features closed this week

---

## 1. [#268 Migrating to OR3](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) — ✅ On Track

- **Objective:** Migrate data pipelines and infrastructure to the OR3 region, including Kratos data lake migration and Slack monitoring channel setup.

- **Done this week:**
  - [#7680 Create Slack channel for OR3 region notifications and configure Databricks jobs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7680) — _Feature_
    - [#7682 Create Slack channel for OR3 region notifications and configure Databricks jobs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7682) (SP:1) — _Daher_ **Unplanned**
  - [#539 Migrate data to new kratos data lake - migration design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/539) — _Feature_

- **In progress:**
  - [#7126 [new Kratos] Validate gold tables between new and old kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7126) (SP:2) — _Uri_

- **Next week:**
  - [#4815 Migrate data to new kratos data lake](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4815) (SP:5) — _Daher_

> **Risk:** [#6432 Migrate data to new kratos data lake - implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6432) has 1 items still New — may carry over to July.

---

## 2. [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) — ✅ On Track

- **Objective:** Expand the NSV Coverage platform with new dashboards (Cluster Tag Rollup, RC Build Trend), API authentication, regex filtering, tag management, and UI improvements.

- **Done this week:**
  - [#7237 Cluster Tag Coverage Rollup Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7237) — _Feature_
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
    - [#7972 Filter coverage breakdown by tag selection](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7972) (SP:1) — _Tomer_ **Unplanned**
    - [#7973 Add free text search to coverage breakdown](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7973) (SP:1) — _Tomer_ **Unplanned**
  - [#7240 RC Build Coverage Trend Report Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7240) — _Feature_
    - [#7241 RC Build Coverage Trend Report](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7241) (SP:5) — _Tomer_
  - [#7537 API authentication via Azure SSO middleware (Stage 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7537) — _Feature_
    - [#7538 Validate Azure AD access token in API auth middleware; keep 4 SDK open pairs working (Stage 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7538) (SP:2) — _Tomer_ **Unplanned**
      - [#7539 Add AuthConfig pydantic-settings (tenant/audience/issuer/JWKS/scope + API_AUTH_ENABLED)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7539) — _Tomer_
      - [#7540 Implement auth middleware with fastapi-azure-auth (JWKS/issuer/audience/expiry/scope -> CORS-visible 401; claims on request.state)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7540) — _Tomer_
      - [#7541 Build exclusion/open-paths list from GeneralConfig().version (4 SDK open pairs; exact health route; /mcp + infra open)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7541) — _Tomer_
      - [#7542 Wire API_AUTH_ENABLED + auth env vars into .env.example and k8s overlays (on deployed, off local/Cypress)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7542) — _Tomer_
      - [#7543 Tests: valid/invalid/expired/missing-scope token, CORS-visible 401, 4 SDK open pairs, exact health route, toggle off](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7543) — _Tomer_
  - [#590 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/590) — _Feature_
    - [#6003 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6003) (SP:2) — _Neta_
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

- **In progress:**
  - [#7501 Tag Labels Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7501) (SP:4) — _Tomer_ **Unplanned**

- **Next week:**
  - [#5146 [Coverage Side]Expose the ability to report pass rate and details — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5146) (SP:1) — _Tomer_
  - [#6242 [Nlastic + Coverage]Expose the ability to report pass rate and details — Planning](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6242) (SP:2) — _Tomer_
  - [#7434 Create Web UI Adjustments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7434) (SP:3) — _Tomer_
  - [#2082 [coverage]attributes category splitting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2082) (SP:3) — _Neta_
  - [#2085 code review](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2085) — _Neta_
  - [#2086 implemnt](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2086) — _Neta_
  - [#8776 Fix token expiry handling — detect expired token and redirect to login](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8776) — _Tomer_ **Unplanned**
  - [#6005 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6005) (SP:2) — _Neta_
  - [#7423 Now and Today Quick-Select Buttons](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7423) (SP:2) — _Neta_
  - [#7424 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7424) — _Neta_
  - [#4424 Tech debt](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4424) (SP:2) — _Neta_
  - [#4425 combine retries mechanism from all call](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4425) — _Neta_

> **Risk:** [#4870 expose the ability to report pass rate and details](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4870) has 3 items still New — may carry over to July.

> **Risk:** [#661 Admin Panel](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/661) has 3 items still New — may carry over to July.

> **Risk:** [#664 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/664) has 1 items still New — may carry over to July.

> **Risk:** [#3444 Add "Now" and "Today" Quick-Select Buttons to Coverage Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3444) has 2 items still New — may carry over to July.

> **Risk:** [#4422 SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4422) has 2 items still New — may carry over to July.

---

## 3. [#1369 Solution FRs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1369) — ⚠️ At Risk

- **Objective:** Deliver customer-requested solution features: syslog failure mode filtering, throughput direction distinction, RDMA BIDI reporting, resiliency smart analysis, UFM BER ports, and parallel group display fixes.

- **Next week:**
  - [#7419 Syslog event filter for Failure Mode](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7419) (SP:2) — _Uri_
  - [#7420 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7420) — _Uri_
  - [#7408 Distinguish between receiver and sender throughput](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7408) (SP:2) — _Gennady_
  - [#7409 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7409) — _Gennady_
  - [#7411 RDMA BIDI Throughput Reporting: Sum Both Directions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7411) (SP:2) — _Gennady_
  - [#7412 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7412) — _Gennady_
  - [#7413 Result Smart Analysis on Resiliency test results](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7413) (SP:2) — _Gennady_
  - [#7414 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7414) — _Gennady_
  - [#7415 UFM - failed ports for effective BER](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7415) (SP:2) — _Gennady_
  - [#7416 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7416) — _Gennady_
  - [#7421 Table Not Displaying Results for Parallel Group](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7421) (SP:2) — _Uri_
  - [#7422 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7422) — _Uri_
  - [#7512 Implement analyzer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7512) — _Gennady_ **Unplanned**
  - [#7513 Research analyzer req](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7513) — _Gennady_ **Unplanned**
  - [#7514 Analyzer implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7514) — _Gennady_ **Unplanned**

> **Risk:** [#3638 Feature Request: Add syslog event filter for Failure Mode in Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3638) has 2 items still New — may carry over to July.

> **Risk:** [#1412 [Nlastic][monitor]Distinguish between receiver and sender throughput bw in case of M2O](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1412) has 2 items still New — may carry over to July.

> **Risk:** [#1423 Request to support RDMA BIDI Throughput Reporting: Sum Both Directions for Client-Server Pairs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1423) has 2 items still New — may carry over to July.

> **Risk:** [#1425 Result Smart Analysis on Resiliency test results](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1425) has 2 items still New — may carry over to July.

> **Risk:** [#1438 Add support in UFM to show failed ports for effective BER](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1438) has 2 items still New — may carry over to July.

> **Risk:** [#7079 Feature Request: Table Not Displaying Results for Parallel Group Runs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7079) has 2 items still New — may carry over to July.

> **Risk:** [#6845 Feature Request: In resiliency test,  a typical case is calculate traffic  convergence time from ](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6845) has 3 items still New — may carry over to July.

---

## 4. [#2497 NSV Reporting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2497) — ✅ On Track

- **Objective:** Build a Cluster Control Room POC for NSV reporting, with telemetry drill-downs, data source integrations, and monitoring KPIs.

- **Done this week:**
  - [#8956 Cluster Control Room _ POC](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8956) — _Feature_
    - [#8946 Telemetry tab – per-cluster drill-down enhancements (mock)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8946) — _Roi_ **Unplanned**
      - [#8960 Reporting stability: fixed 7-day window, Hosts/Devices/Ports order, selectable granularity](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8960) — _Roi_
      - [#8947 Freshness color-coding](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8947) — _Roi_
      - [#8948 Row drill-down charts (rows / DLQ)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8948) — _Roi_
      - [#8949 Granularity selector - rows/DLQ charts](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8949) — _Roi_
      - [#8950 Granularity selector - stability charts](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8950) — _Roi_
      - [#8951 Backend telemetry payload (mock-only)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8951) — _Roi_
    - [#8966 Data Sources](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8966) — _Sari_ **Unplanned**
      - [#8972 connect to databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8972) — _Sari_
      - [#8973 connect to to clusters via SSH for FW versions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8973) — _Sari_

- **In progress:**
  - [#8967 implement frontend based on the mock by abed+ keep updated](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8967) — _Sari_ (10.0h remaining) **Unplanned**
  - [#8969 frontend based on the mock+  continues changes](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8969) — _Sari_ (10.0h remaining) **Unplanned**
  - [#8970 connect to databricks and look at the correct metrics if using telmetry otherwiese using the incednts gold table](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8970) — _Sari_ (15.0h remaining) **Unplanned**
  - [#8946 Telemetry tab – per-cluster drill-down enhancements (mock)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8946) — _Roi_ **Unplanned**

- **Next week:**
  - [#8963 Dashboard Hub](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8963) — _Sari_ **Unplanned**
  - [#8964 MTBI KPI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8964) — _Sari_ **Unplanned**
  - [#8965 PHY KPI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8965) — _Sari_ **Unplanned**
  - [#8966 Data Sources](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8966) — _Sari_ **Unplanned**

---

## 5. [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) — ✅ On Track

- **Objective:** Build and deploy the Nlastic Storage & Streaming Service — per-DUT OTLP routing, dedup/retry pipelines, S3 targets, and coverage SDK integration.

- **Done this week:**
  - [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) — _Feature_
    - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040) (SP:1) — _Gennady_
      - [#7367 TargetDispatcher: expose resolve_targets API for pre-dispatch PENDING audit writes](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7367) — _Gennady_
      - [#6043 Monolith call sites: pass DUT collector coords into SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6043) — _Gennady_
      - [#6045 nlastic-data-streaming SDK: build envelope.targets from Consul-discovered (address, port)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6045) — _Gennady_
  - [#8707 Identify affected tables and time range of corrupted records](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8707) — _Uri_ **Unplanned**
  - [#8708 Build query to detect records with mismatched scenario_uuid](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8708) — _Uri_ **Unplanned**
  - [#8709 Remediate corrupted data (re-tag or backfill correct scenario_uuid)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8709) — _Uri_ **Unplanned**
  - [#8710 Validate data integrity post-fix](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8710) — _Uri_ **Unplanned**
  - [#8711 Capture scenario metadata at record creation/enqueue time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8711) — _Bar_ **Unplanned**
  - [#8712 Add unit tests for scenario_uuid correctness under async serialization](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8712) — _Bar_ **Unplanned**
  - [#8713 Validate fix in staging environment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8713) — _Bar_ **Unplanned**

- **In progress:**
  - [#5750 E2E batch test with real OTLP collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5750) — _Gennady_ (3.0h remaining)

- **Next week:**
  - [#6243 [StorageService]W1 P1 — Happy Path Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6243) — _Gennady_
  - [#5779 [StorageService]W2 P1 - Bad Path — Dedup + Retries + DLQ + Deploy](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5779) (SP:3) — _Gennady_
  - [#5780 [StorageService]W3 P2 - S3 Target](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5780) (SP:4) — _Gennady_
  - [#5781 [StorageService]W4 P3 - Coverage SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5781) (SP:2) — _Gennady_
  - [#7369 Retire pre-alpha migration squash; reinstate forward-only migration chain before first prod deploy](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7369) — _Gennady_
  - [#6032 [StorageService]W1 P1 — Deployment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6032) (SP:3) — _Gennady_
  - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040) (SP:1) — _Gennady_

> **Risk:** [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) has 7 items still New — may carry over to July.

---

## 6. [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) — ✅ On Track

- **Objective:** Ingest and process NCS telemetry data in Databricks — MTBI, DTS, NVLink, NMX-T, Cumulus metrics pipelines, and the PHY Incidents dashboard.

- **Done this week:**
  - [#7055 MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7055) — _Feature_
    - [#7341 [Data pipelines]  MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7341) (SP:5) — _Uri_
    - [#7342 MTBI - Data pipeline implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7342) (SP:3) — _Uri_
    - [#7058 MTBI - Data  Review & Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7058) (SP:4) — _Uri_
    - [#7154 MTBI - Dashboard Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7154) (SP:2) — _Uri_
  - [#6873 DTS data](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6873) — _Feature_
    - [#7343 [Data pipelines] DTS](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7343) (SP:3) — _Roi_
      - [#7344 Silver L1](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7344) — _Roi_
    - [#6874 [Data pipelines] DTS design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6874) (SP:2) — _Roi_
  - [#7348 NVlink metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7348) — _Feature_
    - [#7349 [Data pipelines] NVlink metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7349) (SP:4) — _Roi_
      - [#7350 Implemented Silver L1 for Cumulus](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7350) — _Roi_
  - [#6867 NMXT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6867) — _Feature_
    - [#7425 NMXT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7425) (SP:4) — _Roi_
      - [#7426 Implementation Silver L1](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7426) — _Roi_
  - [#6870 Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6870) — _Feature_
    - [#8015 Cumulus counters silver L2](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8015) — _Roi_ **Unplanned**
      - [#8046 Pivot Table Assessment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8046) — _Roi_
    - [#6871 [Data pipelines] Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6871) (SP:4) — _Roi_
  - [#6879 Incidents system - Pipelines and PHY/Tableau Dashboard (OR3)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6879) — _Feature_
    - [#7150 Incidents system - PHY Dashboard Build](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7150) (SP:6) — _Daher_
      - [#7428 PHY Incidents — UFM core + Tableau dashboard (Phase 1)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7428) — _Daher_
      - [#7151 buffer + exploration (learning)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7151) — _Daher_
    - [#6880 Incidents system - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6880) (SP:2) — _Anan_

- **In progress:**
  - [#7430 PHY Incidents — Add NMX-T (NVLink) source](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7430) — _Daher_

- **Next week:**
  - [#7429 PHY Incidents — Add UFM CPO source](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7429) — _Daher_
  - [#7431 PHY Incidents — Blocked sources tracker (Cumulus, DTS, SONiC)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7431) — _Daher_
  - [#7432 PHY Incidents — Production hardening (ops dashboard, email migration, runbooks, maintenance)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7432) — _Daher_
  - [#7150 Incidents system - PHY Dashboard Build](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7150) (SP:6) — _Daher_
  - [#7152 Incidents system - Good Morning Dashboard Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7152) (SP:3) — _Uri_

> **Risk:** [#6879 Incidents system - Pipelines and PHY/Tableau Dashboard (OR3)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6879) has 5 items still New — may carry over to July.

---

## Bugs — 0 High-Severity Open

- **Done this sprint:**
  - [#8704 Fix NLastic streaming to capture scenario metadata at creation time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8704) — _Bar_
  - [#3943 support more then one regex in filters](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) — _Neta_
  - [#8702 Fix data corruption in Databricks caused by wrong scenario_uuid](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8702) — _Uri_
  - [#8703 Fix NLastic streaming to capture scenario metadata at creation time instead of serialization time](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8703) — _Bar_

- **Open:**

| ID | Title | Sev | Assignee | Note |
| --- | --- | --- | --- | --- |
| [#8775](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8775) | Azure app token expires after 24h — UI stuck without redirect to login | 3 - Low | _Tomer_ | **Unplanned** |
| [#7380](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7380) | Audit log: dispatcher.resolve_targets and OtlpPoolAdapter.deliver disagree on target_name | 3 - Low | _Gennady_ |  |
| [#7509](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7509) | Custom dashboard filters with same category + key overwrite previous values in URL | 3 - Low | _Neta_ | **Unplanned** |

## 7. Unlinked Items

- [#9074 Add ncs-ai-skills repo to NVCARPS registry](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/9074) — _Daher_ (New) **Unplanned**
- [#8942 Deep Dive into UFM Data](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8942) — _Roi_ (Closed) **Unplanned**
- [#8945 UFM - data anomaly](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/8945) — _Roi_ (New) **Unplanned**


_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/June%202026)_
