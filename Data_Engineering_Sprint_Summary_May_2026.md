# Data Engineering — Sprint Summary | May 2026

**Sprint:** [May 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/May%202026) (May 1 – May 31) | 21 of 42 stories closed | 34.5 of 60 SP completed | 7 Features closed this sprint

---

## 1. [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) ✅ On Track

- **Objective:** Enhance the NSV Coverage Dashboard with UX improvements, Redmine write-back integration, export capabilities, and permutation naming — extending the platform's usability and automation.

- **Done this sprint:**
  - [#601 UX ENRICHMENTS](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/601) — _Feature_
    - [#2083 tool tip to total coverage gauge](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2083) — _Neta_
    - [#3132 enrich UX in term of overview actions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3132) — _Neta_
    - [#602 ux enrichment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/602) (SP:2) — _Neta_
      - [#603 color palette](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/603), [#604 dashboard bars alignment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/604), [#605 overview tables adjustable full width](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/605), [#606 components minimum width](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/606), [#607 nvidia fonts](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/607), [#608 navbar design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/608), [#609 sidebar design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/609)
  - [#2652 Write back to the Redmine](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2652) — _Feature_
    - [#6183 Extend RedmineService with write capabilities](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6183) (SP:1) — _Bar_
    - [#6185 Build RedmineWritebackService orchestrator with feature flag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6185) (SP:1) — _Bar_
    - [#6187 Wire Flow 1 into TagRouter (create + edit with FR diff)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6187) (SP:0.5) — _Bar_
    - [#6189 Wire Flow 2 into QueriesRouter (tag-coverage dashboard)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6189) (SP:0.5) — _Bar_
    - [#6191 Configuration + K8s rollout for new REDMINE_ env vars](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6191) (SP:0.5) — _Bar_
    - [#6193 Tests for service, orchestrator, and routers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6193) (SP:1.5) — _Bar_
    - [#6195 Operational readiness - structured logs and error monitoring](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6195) (SP:0.5) — _Bar_
  - [#6197 Permutation sub-scenario auto-naming via permutation_name](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6197) — _Feature_
    - [#6198 Permutation sub-scenario auto-naming via permutation_name](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6198) (SP:2) — _Bar_
  - [#4561 Export Dashboard Coverage Status per Cluster (PDF/PPT)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4561) — _Feature_
    - [#6241 Export Dashboard Coverage Status per Cluster (PDF/PPT)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6241) (SP:3) — _Neta_
  - [#4560 Export Test Plan per Cluster from Dashboard (PDF/Image)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4560) — _Feature_
    - [#6240 Export Test Plan per Cluster from Dashboard (PDF/Image)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6240) (SP:5) — _Neta_
  - [#6248 CoverageExpectationsManager.post missing settings=config in SDK calls](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6248) — _Bar_ (Bug fix)
  - [#5906 New or edited expectation saves hardware/software component keys in camelCase instead of snake_case](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5906) — _Neta_ (Bug fix)

- **Not started:**
  - [#590 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/590) — _Feature_
    - [#6003 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6003) (SP:2) — _Neta_
  - [#3943 support more than one regex in filters](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) — _Neta_ (Bug)

> **Risk:** [#590 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/590) and [#3943 support more than one regex in filters](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) still New — will carry over to June.

---

## 2. [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) ⚠️ At Risk

- **Objective:** Build the core Storage Service for NLastic data, implement Kafka-based streaming to replace OTLP collectors, and resolve data pipeline reliability issues.

- **Done this sprint:**
  - [#5874 Stream NLastic data directly to Kafka instead of OTLP collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5874) — _Feature_
    - [#6244 Stream NLastic data directly to Kafka instead of OTLP collector - POC](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6244) (SP:5) — _Daher_
    - [#5992 Prod-grade implementation for Kafka streaming](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5992) (SP:2) — _Daher_
  - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040) — all 6 tasks closed — _Gennady_
    - [#6261 nlastic-contracts: drop streaming/targets/+routing.py, add envelope.customer_id+target_override](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6261)
    - [#6262 Streaming service: customer_id routing + flat dispatcher + YAML config + migration 0003](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6262)
    - [#6437 Streaming service: StreamingMessageHandler — Kafka consumer → dispatcher → audit writer](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6437)
    - [#6041 Migration 0002: drop target_override JSONB column from delivery_audit](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6041)
    - [#6042 Streaming service: smart router + lazy MultiLoggerPool + remove static OTLP + pool-size gauge](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6042)
    - [#6044 nlastic-contracts: TargetBase + OtlpTargetSpec + envelope.targets; drop target_override](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6044)
  - [#6050 common-otlp-utils: GRPCOTLPLogger init crashes when OTLP_ENABLED=False and Consul discovery fails](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6050) — _Gennady_ (Bug fix)
  - [#5045 OTLP: Large JSON payloads (pairs_table, workplan_graph) sent as single records can exceed 1MB limit](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5045) — _Daher_ (Bug fix)

- **In progress:**
  - [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) — _Feature_
    - [#6243 [StorageService] W1 P1 — Happy Path Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6243) — _Gennady_ (10 of 14 tasks closed, 4 Active)
      - Active: [#5736 DI container wiring + main.py registration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5736), [#5737 Integration test: Kafka → backup → mock OTLP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5737), [#5738 Smoke test: full service consume + persist](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5738), [#5750 E2E batch test with real OTLP collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5750)

> **Risk:** [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) has 4 Active integration/E2E test tasks — likely carry-over to June.

---

## 3. [#2938 Knowledge Base Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2938) ✅ On Track

- **Objective:** Build the Knowledge Base Python package with Milvus backend, CLI tooling, MCP wrappers, and developer docs — enabling domain-scoped ingestion, retrieval, and search for NLastic's AI-powered workflows.

- **Done this sprint:**
  - [#7245 Knowledge Base Package](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7245) — _Feature_ **Unplanned**
    - [#7246 Stable KBClient contract](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7246) (SP:0.83) — _Tomer_ — all 3 tasks closed
    - [#7250 Simple domain-scoped operations](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7250) (SP:0.83) — _Tomer_ — all 3 tasks closed
    - [#7251 Write path into Milvus](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7251) (SP:0.83) — _Tomer_ — all 3 tasks closed
    - [#7252 Retrieval path from Milvus](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7252) (SP:0.83) — _Tomer_ — all 3 tasks closed
    - [#7253 Milvus read/search backend](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7253) (SP:0.67) — _Tomer_ — all 2 tasks closed
    - [#7254 Thin command wrapper](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7254) (SP:1) — _Tomer_ — all 3 tasks closed
    - [#7255 Developer-ready package docs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7255) (SP:0.83) — _Tomer_ — all 3 tasks closed
    - [#7256 Cursor Skill guide](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7256) (SP:0.5) — _Tomer_ — closed
    - [#7257 Read-only MCP wrappers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7257) (SP:0.83) — _Tomer_ — closed
  - Infrastructure tasks (no parent, KB-related) — _Tomer_ — all closed:
    - [#7109 NVAuth JWT validation client (PyJWT + cached JWKS)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7109)
    - [#7110 FastAPI auth middleware (inject claims into request.state)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7110)
    - [#7111 Error mapping (401 / 502) into unified error envelope](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7111)
    - [#7112 LiteLLM-compatible embedding client (POST /v1/embeddings)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7112)
    - [#7113 API-key loader (env in dev, Vault in stg/prd) with masked logging](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7113)
    - [#7114 Timeout + retry policy with 502 mapping](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7114)
    - [#7115 pymilvus client pool + lifecycle hooks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7115)
    - [#7116 Readiness probe wiring to list_collections() (cached 2s)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7116)
    - [#7117 asyncpg / SQLAlchemy 2.0 async pool](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7117)
    - [#7118 Readiness probe wiring to SELECT 1 (cached 2s)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7118)

- **In progress:**
  - [#7384 QA + Review](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7384) — _Tomer_ **Unplanned** (QA task still New)

- **Not started:**
  - [#5187 Update NYG Knowledge Base to April 2026 GA](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5187) — _Tomer_

> **Risk:** [#7384 QA + Review](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7384) and [#5187 Update NYG Knowledge Base to April 2026 GA](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5187) still New — may carry over to June.

---

## 4. [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) ⚠️ At Risk

- **Objective:** Design and implement telemetry data pipelines to bring NCS device telemetry (starting with UFM) into Databricks for analysis. **Unplanned** — entire Epic added during the sprint.

- **Done this sprint:**
  - [#6861 Design telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6861) — _Feature_
    - [#6862 Design telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6862) (SP:2) — _Bar_ **Unplanned**

- **In progress:**
  - [#6864 UFM telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6864) — _Feature_
    - [#6865 UFM telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6865) (SP:5) — _Roi_ **Unplanned** (Active)

> **Risk:** [#6865 UFM telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6865) (SP:5) still Active — will carry over to June.

---

## 5. [#4864 NYG - Nlastic Yaml Generator](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4864) ⚠️ At Risk

- **Objective:** Continue NYG development with nested YAML support, ongoing support tasks, and usage analysis.

- **In progress:**
  - [#2762 [NYG] Support Nested YAMLs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2762) — _Feature_
    - [#6434 [NYG] Support Nested YAMLs - Frontend](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6434) — _Daher_ **Unplanned** (Active)
      - [#5547 Multi-File Generation (state, representation, output)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5547) — Closed
      - [#5550 FE output modifications](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5550) — Closed

- **Not started:**
  - [#5895 [NYG] Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5895) — _Feature_
    - [#6017 [NYG] Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6017) (SP:2) — _Daher_
  - [#6658 [NYG] General tasks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6658) — _Feature_
    - [#6659 [NYG] Analyse usage survey report](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6659) — _Tzvi_ **Unplanned**

> **Risk:** [#6434 Nested YAMLs Frontend](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6434) still Active, [#6017 NYG Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6017) and [#6659 Analyse usage survey report](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6659) still New — carry over to June.

---

## 6. [#2497 NSV Reporting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2497) ⚠️ At Risk

- **Objective:** Build NLastic reporting skills — automated regression and daily report generation for NSV clusters.

- **In progress:**
  - [#6063 Nlastic Reporting - Regression Report skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6063) — _Feature_
    - [#6179 First Skills - Research, Planning and Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6179) (SP:2) — _Sari_ (New)

- **Not started:**
  - [#6420 Nlastic Reporting - Daily Report skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6420) — _Feature_
    - [#6477 research the needed resources for the skill + implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6477) — _Sari_ **Unplanned**
      - [#6478 get all the needed resources from the appropriate people](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6478) — Closed
      - [#6481 adaptable skill per cluster](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6481) — New
      - [#6482 get the constraint of the skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6482) — New
      - [#6483 implement the skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6483) — New

> **Risk:** [#6179 Research, Planning and Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6179) still New, and [#6420 Daily Report skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6420) largely unstarted — both carry over to June.

---

## 7. [#268 Migrating to OR3](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) ✅ Done

- **Objective:** Complete data migration work for OR3, including graph data model handling and Databricks data reliability.

- **Done this sprint:**
  - [#4771 Handling Graph Data Model](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4771) — _Feature_
    - [#3584 [New Kratos] f_nbu_nlastic_graph_data_model_bronze](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3584) — _Uri_
  - [#5669 Data Reliability - Data Provisioning in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5669) — _Feature_
    - [#5670 Data Reliability - Data Provisioning in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5670) (SP:2) — _Uri_

---

## 8. [#269 Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/269) ✅ Done

- **Objective:** Add deep-dive navigation links to the Good Morning Dashboard for faster drill-down into cluster data.

- **Done this sprint:**
  - [#6535 Deep-Dive Navigation Links](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6535) — _Feature_ **Unplanned**
    - [#6536 Deep-Dive Navigation Links - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6536) (SP:2) — _Uri_
    - [#6558 Deep-Dive Navigation Links - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6558) (SP:2) — _Uri_

---

## 9. Miscellaneous — Orphan Items

- **Done this sprint:**
  - [#7171 Collected Samples streaming modifications](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7171) — _Daher_

---

## 10. [#4773 Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773) ✅ Done

- **Bug buffer:** All team members' bug buffer tasks closed
- **Formal Cycle Testing:** All formal cycle testing tasks closed (_Daher_, _Anan_, _Uri_, _Gennady_, _Neta_)

---

## Bugs — 0 High-Severity Open

- **Done this sprint:**
  - [#6248 CoverageExpectationsManager.post missing settings=config in SDK calls](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6248) — _Bar_
  - [#5906 New or edited expectation saves hardware/software keys in camelCase instead of snake_case](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5906) — _Neta_
  - [#5985 f_nbu_nlastic_running_table_bronze missing remote_nodes_uuid column](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5985) — _Uri_
  - [#6050 common-otlp-utils: GRPCOTLPLogger init crashes when OTLP_ENABLED=False and Consul discovery fails](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6050) — _Gennady_
  - [#5045 OTLP: Large JSON payloads can exceed 1MB limit](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5045) — _Daher_
  - [#7163 nlastic v1.22.0b98 Command Logs Not Fully Streaming to Datalake](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7163) — _Daher_ **Unplanned**

- **Open:**

| ID | Title | Sev | Assignee | Note |
|----|-------|-----|----------|------|
| [#3943](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) | support more than one regex in filters | Low | _Neta_ | Carry-over |
| [#7399](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7399) | Fix: Login icon shows "?" instead of user email | Low | _Neta_ | **Unplanned** |
| [#7401](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7401) | hardware software display name | Low | _Neta_ | **Unplanned** |

---

## Sprint Summary

| Metric | Value |
|--------|-------|
| Stories | 21 / 42 closed (50%) |
| Story Points | 34.5 / 60 SP completed (57%) |
| Features | 7 closed, 3 resolved/active, 7 remaining |
| Bugs | 6 closed, 3 open (all Low severity) |
| Unplanned items | ~15 items added during sprint |

*Key accomplishments:*
- *NSV Coverage:* Full Redmine write-back pipeline delivered (Bar), dashboard export PDF/PPT completed (Neta), UX overhaul shipped, permutation naming done
- *Storage & Streaming:* Kafka streaming to production (Daher), OTLP collector routing fully implemented (Gennady), Storage Service happy path 70% complete
- *Knowledge Base:* Entire KB package built from scratch — client, Milvus backend, CLI, MCP wrappers, docs (Tomer) — massive unplanned delivery
- *Telemetry:* New Databricks telemetry initiative launched — design complete (Bar), UFM pipeline in progress (Roi)
- *Good Morning Dashboard:* Deep-dive navigation shipped (Uri)
- *OR3 Migration:* Graph data model and data reliability work completed (Uri)

*Carry-over to June:*
- Storage Service E2E testing (4 tasks — Gennady)
- UFM telemetry data pipelines (Roi)
- NYG nested YAMLs frontend, support, and usage survey
- NSV Reporting skills (Sari)
- Regex filtering (Neta)
- KB QA + Knowledge Base update

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/May%202026)_
