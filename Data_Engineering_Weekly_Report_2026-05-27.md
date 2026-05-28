# Data Engineering — Weekly Report | May 25–31, 2026

**Sprint:** [May 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/May%202026) (May 1 – May 31) | 19 of 45 stories closed | 4 Features closed this week

---

## 1. [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) — Coverage & Expectations ⚠️ At Risk

- **Objective:** Expand the NSV coverage dashboard with regex filtering, admin panel improvements, Redmine writeback, and export capabilities for cluster-level coverage reports.

- **Done this week:**
  - [#2652 Write back to the Redmine](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2652) — _Feature_
    - [#6183 Extend RedmineService with write capabilities](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6183) — _Gennady_
    - [#6185 Build RedmineWritebackService orchestrator with feature flag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6185) — _Gennady_
    - [#6187 Wire Flow 1 into TagRouter (create + edit with FR diff)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6187) — _Gennady_
    - [#6189 Wire Flow 2 into QueriesRouter (tag-coverage dashboard)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6189) — _Gennady_
    - [#6191 Configuration + K8s rollout for new REDMINE_ env vars](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6191) — _Gennady_
    - [#6193 Tests for service, orchestrator, and routers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6193) — _Gennady_
    - [#6195 Operational readiness - structured logs and error monitoring](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6195) — _Gennady_
  - [#6197 Permutation sub-scenario auto-naming via permutation_name](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6197) — _Feature_
    - [#6198 Permutation sub-scenario auto-naming via permutation_name](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6198) — _Gennady_
  - [#602 ux enrichment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/602) (SP:2) — _Daher_
  - [#6240 Export Test Plan per Cluster from Dashboard (PDF/Image)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6240) (SP:5) — _Daher_
  - [#6241 Export Dashboard Coverage Status per Cluster (PDF/PPT)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6241) (SP:3) — _Daher_
  - [#6661 Report coverage support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6661) — _Daher_ **Unplanned**
  - [#5907 New or edited expectation saves hw/sw component keys in camelCase instead of snake_case](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5907) — _Gennady_
- **In progress:**
  - [#661 Admin Panel](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/661) — _Feature_ (blocked on attribute splitting)
  - [#601 UX Enrichments](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/601) — _Feature_ (remaining stories still New)
- **Next week:**
  - [#2082 Attributes category splitting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2082) (SP:3) — _Daher_
  - [#2083 Tool tip to total coverage gauge](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2083) — _Daher_
  - [#3132 Enrich UX in term of overview actions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3132) — _Daher_
  - [#590 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/590) — _Feature_
    - [#6003 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6003) (SP:2) — _Gennady_
  - [#664 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/664) — _Feature_
    - [#6005 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6005) (SP:2) — _Gennady_

> **Risk:** [#590 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/590) and [#664 Duplicate tag expectations](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/664) still New with full Features untouched — likely carry over to June.

> **Risk:** [#3943 Support more than one regex in filters](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) (Bug) still New — may carry over to June.

---

## 2. [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) — Streaming & Storage ✅ On Track

- **Objective:** Build a production-grade streaming service to push NLastic data directly to Kafka, replace the OTLP collector path, and implement the storage service routing layer.

- **Done this week:**
  - [#5874 Stream NLastic data directly to Kafka instead of OTLP collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5874) — _Feature_
    - [#6244 Stream NLastic data directly to Kafka — POC](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6244) (SP:5) — _Roi_
    - [#5992 Prod-grade implementation for Kafka streaming](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5992) (SP:2) — _Roi_
  - [#6261 nlastic-contracts: drop streaming/targets/+routing.py, add envelope.customer_id+target_override (v0.1.28)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6261) — _Roi_
  - [#6262 Streaming service: customer_id routing + flat dispatcher + YAML config + migration 0003](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6262) — _Roi_
  - [#6437 Streaming service: StreamingMessageHandler — Kafka consumer → dispatcher → audit writer (G-4)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6437) — _Roi_ **Unplanned**
  - [#6041 Migration 0002: drop target_override JSONB column from delivery_audit](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6041) — _Roi_
  - [#6042 Streaming service: smart router + lazy MultiLoggerPool + remove static OTLP + pool-size gauge](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6042) — _Roi_
  - [#6044 nlastic-contracts: TargetBase + OtlpTargetSpec + envelope.targets; drop target_override](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6044) — _Roi_
  - [#7171 Collected Samples streaming modifications](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7171) (SP:2) — _Roi_ **Unplanned**
- **Next week:**
  - [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) — _Feature_ (Active)
    - [#6243 W1 P1 — Happy Path Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6243) — _Roi_

---

## 3. [#2938 Knowledge Base Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2938) — Knowledge Base ⚠️ At Risk

- **Objective:** Build a unified Knowledge Base package with Milvus read/write paths, auth clients, MCP wrappers, and developer documentation for use across NLastic tools.

- **Done this week:**
  - [#7109 NVAuth JWT validation client (PyJWT + cached JWKS)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7109) — _Anan_ **Unplanned**
  - [#7110 FastAPI auth middleware (inject claims into request.state)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7110) — _Anan_ **Unplanned**
  - [#7111 Error mapping (401 / 502) into unified error envelope](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7111) — _Anan_ **Unplanned**
  - [#7112 LiteLLM-compatible embedding client (POST /v1/embeddings)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7112) — _Anan_ **Unplanned**
  - [#7113 API-key loader (env in dev, Vault in stg/prd) with masked logging](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7113) — _Anan_ **Unplanned**
  - [#7114 Timeout + retry policy with 502 mapping](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7114) — _Anan_ **Unplanned**
  - [#7115 pymilvus client pool + lifecycle hooks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7115) — _Anan_ **Unplanned**
  - [#7116 Readiness probe wiring to list_collections() (cached 2s)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7116) — _Anan_ **Unplanned**
  - [#7117 asyncpg / SQLAlchemy 2.0 async pool](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7117) — _Anan_ **Unplanned**
  - [#7118 Readiness probe wiring to SELECT 1 (cached 2s)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7118) — _Anan_ **Unplanned**
- **Next week:**
  - [#7245 Knowledge Base Package](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7245) — _Feature_ **Unplanned**
    - [#7246 Stable KBClient contract](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7246) — _Anan_
    - [#7250 Simple domain-scoped operations](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7250) — _Anan_
    - [#7251 Write path into Milvus](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7251) — _Anan_
    - [#7252 Retrieval path from Milvus](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7252) — _Anan_
    - [#7253 Milvus read/search backend](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7253) — _Anan_
    - [#7254 Thin command wrapper](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7254) (SP:1) — _Anan_
    - [#7255 Developer-ready package docs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7255) — _Anan_
    - [#7256 Cursor Skill guide](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7256) — _Anan_
    - [#7257 Read-only MCP wrappers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7257) — _Anan_

> **Risk:** [#7245 Knowledge Base Package](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7245) is a large Feature with 9 User Stories all still New — significant scope added mid-sprint, likely to carry over to June.

---

## 4. [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) — Telemetry Pipelines ✅ On Track **Unplanned**

- **Objective:** Design and implement data pipelines for NCS telemetry data (starting with UFM) in Databricks.

- **Done this week:**
  - [#6861 Design telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6861) — _Feature_ **Unplanned**
    - [#6862 Design telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6862) (SP:2) — _Neta_
- **In progress:**
  - [#6864 UFM telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6864) — _Feature_
    - [#6865 UFM telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6865) (SP:5) — _Neta_ (Active)

---

## 5. [#268 Migrating big-data to Kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) — Data Migration ✅ Done

- **Objective:** Complete migration of big-data workloads from legacy platform to Kratos, including graph data models and data reliability provisioning.

- **Done this week:**
  - [#4771 Handling Graph Data Model](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4771) — _Feature_
    - [#3584 f_nbu_nlastic_graph_data_model_bronze](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3584) — _Neta_
  - [#5670 Data Reliability - Data Provisioning in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5670) (SP:2) — _Neta_

---

## 6. [#269 Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/269) — Dashboard ✅ Done

- **Objective:** Add deep-dive navigation links to the Good Morning Dashboard for quick drill-down into detailed cluster data.

- **Done this week:**
  - [#6535 Deep-Dive Navigation Links](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6535) — _Feature_ **Unplanned**
    - [#6536 Deep-Dive Navigation Links - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6536) (SP:2) — _Sari_
    - [#6558 Deep-Dive Navigation Links - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6558) (SP:2) — _Sari_

---

## 7. [#4864 NYG - Nlastic Yaml Generator](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4864) — YAML Generator ⚠️ At Risk

- **Objective:** Enhance the NYG tool with support for nested YAMLs on the frontend, ongoing user support, usage analysis, and knowledge base updates.

- **In progress:**
  - [#6434 Support Nested YAMLs - Frontend](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6434) — _Michael_ (Active) **Unplanned**
- **Next week:**
  - [#5895 NYG Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5895) — _Feature_
    - [#6017 NYG Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6017) (SP:2) — _Michael_
  - [#6659 Analyse usage survey report](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6659) — _Michael_ **Unplanned**
  - [#5187 Update NYG Knowledge Base to April 2026 GA](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5187) (SP:1) — _Michael_
  - [#6007 Version specific knowledge base](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6007) (SP:2) — _Michael_
  - [#6013 NYG KB Migration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6013) (SP:2) — _Michael_

> **Risk:** [#6434 Support Nested YAMLs - Frontend](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6434) is the only Active item; multiple stories still New — NYG scope may carry over to June.

---

## 8. [#2497 Nlastic Reporting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2497) — Reporting Skills ⚠️ At Risk

- **Objective:** Build automated reporting skills (regression report and daily report) for Nlastic dashboards.

- **Next week:**
  - [#6063 Nlastic Reporting - Regression Report skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6063) — _Feature_ (Active)
    - [#6179 First Skills - Research, Planning and Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6179) (SP:2) — _Sari_
  - [#6420 Nlastic Reporting - Daily Report skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6420) — _Feature_ **Unplanned**
    - [#6477 Research the needed resources for the skill + implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6477) — _Sari_

> **Risk:** Both Features have all stories still New — may carry over to June.

---

## 9. [#4773 Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773) — Capacity Placeholders

- **Objective:** Capacity buffer for bug fixes, formal cycle testing, and buddy support across the team.

- [#5791 Bug Buffer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5791), [#5799 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5799), [#5810 Buddy Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5810) — capacity reservations, no specific deliverables.

---

## Bugs — 1 Open

- **Done this sprint:**
  - [#5045 OTLP: Large JSON payloads (pairs_table, workplan_graph) sent as single records can exceed 1MB limit](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5045) — _Daher_
  - [#5906 [E2E Coverage / Expectations] New or edited expectation saves hardware/software component keys in camelCase instead of snake_case](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5906) — _Neta_
  - [#5985 f_nbu_nlastic_running_table_bronze missing remote_nodes_uuid column](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5985) — _Uri_
  - [#6050 common-otlp-utils: GRPCOTLPLogger init crashes when OTLP_ENABLED=False and Consul discovery fails](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6050) — _Gennady_
  - [#6248 CoverageExpectationsManager.post missing settings=config in SDK calls](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6248) — _Bar_
  - [#7163 Bug: nlastic v1.22.0b98 Command Logs Not Fully Streaming to Datalake](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7163) — _Daher_ **Unplanned**
- **Open:**

| ID | Title | Sev | Assignee | Note |
| -- | ----- | --- | -------- | ---- |
| [#3943](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) | support more then one regex in filters | 3 - Low | _Neta_  |  |

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/May%202026)_
