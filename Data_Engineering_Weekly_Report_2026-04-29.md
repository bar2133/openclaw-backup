# Data Engineering — Weekly Report | April 23–29, 2026

**Sprint:** [April 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/April%202026) (Apr 1 – Apr 30) — **Final week** | 22 of 28 stories closed | 12 of 17 Features closed
**⏭️ May 2026 sprint starts next week**

---

## [NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) ⚠️ At Risk

**Objective:** Enhance coverage dashboard with scenario grouping, export capabilities, tag auto-population, and pass-rate reporting.

**Done this sprint:**

- [#4615](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4615) Permutation Scenarios Grouping in Dashboard Coverage View — *Bar*
  - [#4806](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4806) Permutation Scenarios Grouping in Dashboard Coverage View (SP:3) — *Bar*
- [#2917](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2917) Auto-Populate Tag Name from RedMine FR Number — *Bar*
  - [#4828](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4828) Auto-Populate Tag Name from RedMine FR Number (SP:2) — *Bar*
- [#4696](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4696) Support adding Scenario Names to Executions in Nlastic — *Bar*
  - [#4814](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4814) Support adding Scenario Names to Executions in Nlastic — *Bar*
- [#5521](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5521) Auto-propagate scenario name from scenario tag config when creating coverage (SP:2) — *Bar* **Unplanned**

**In progress:**

- [#4808](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4808) Export Test Plan per Cluster from Dashboard (PDF/Image) (SP:5) — *Neta*

**Carries over to May:**

- [#4560](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4560) Export Test Plan per Cluster from Dashboard (PDF/Image) — *Neta*
  - [#4808](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4808) Export Test Plan per Cluster from Dashboard (PDF/Image) (SP:5) — *Neta*
- [#4561](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4561) Export Dashboard Coverage Status per Cluster (PDF/PPT) — *Neta*
  - [#4810](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4810) Export Dashboard Coverage Status per Cluster (PDF/PPT) (SP:3) — *Neta*
- [#5144](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5144) Expose the ability to report pass rate and details — Planning (SP:1) — *Bar*

> **Risk:** 3 Features (8 SP) not started — will carry over to May 2026. Neta's export features need prioritization in May planning.

---

## [Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) 🔥 High Activity

**Objective:** Design and implement the Nlastic Storage Service for data persistence and streaming.

**Done this week:**

- [#4882](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4882) Nlastic Storage Service — Design — *Gennady*
  - [#4884](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4884) Nlastic Storage Service — Planning (SP:5) — *Gennady*
  - [#5778](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5778) Roadmap — *Gennady* **Unplanned**
- [#5740](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5740) Nlastic Contracts Validation — *Gennady* **Unplanned**
- [#5742](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5742) common-otlp-utils multi-instance Container support — *Gennady* **Unplanned**
- Happy Path tasks completed: template cleanup, StructType enum, DeliveryStatus models, domain protocols, S3/OTLP adapters, Alembic migration, AppConfig additions — *Gennady*

**In progress:**

- [#5721](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5721) Happy Path Implementation — *Gennady* **Unplanned**
  - [#5726](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5726) TargetRegistry: struct_type routing + target_override — *Gennady*
  - [#5727](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5727) TargetDispatcher: parallel delivery — *Gennady*
  - [#5728](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5728) MessageHandler: backup → dispatch → audit — *Gennady*
  - [#5732](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5732) BackupRepository: implements BackupStore — *Gennady*
  - [#5733](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5733) Streaming Prometheus metrics — *Gennady*
  - [#5734](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5734) StreamingMessageHandler: Kafka ↔ domain adapter — *Gennady*
  - [#5736](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5736) DI container wiring + main.py registration — *Gennady*
  - [#5737](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5737) Integration test: Kafka → backup → mock OTLP — *Gennady*
  - [#5738](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5738) Smoke test: full service consume + persist — *Gennady*
  - [#5744](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5744) Docker Compose stack — build + validate E2E — *Gennady*
  - [#5750](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5750) E2E batch test with real OTLP collector — *Gennady*
- [#5875](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5875) Stream NLastic data directly to Kafka instead of OTLP collector (SP:2) — *Daher* **Unplanned**

**Carries over to May:** Implementation feature ([#4883](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883)) with ~12 active tasks + Kafka streaming feature ([#5874](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5874))

> **Risk:** Massive scope expansion via unplanned items — started from 15 SP planned, now 30+ tasks. Good velocity from Gennady but significant carryover into May. Needs sprint planning attention.

---

## [NYG - Nlastic Yaml Generator](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4864) ⚠️ At Risk

**Objective:** Add nested YAML support, editor mode UX, and workspace management to NYG.

**Done this sprint:**

- [#2762](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2762) Support Nested YAMLs — *Daher* (Feature Active, tasks closed)
  - [#5531](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5531) Feature recipe and KB ingestion — *Daher* **Unplanned**
  - [#5532](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5532) Nested yaml validation MCP modifications — *Daher* **Unplanned**
  - [#5545](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5545) Detail prompt modification — *Daher* **Unplanned**
  - [#5592](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5592) Generation — *Daher* **Unplanned**

**Carries over to May:**

- [#530](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/530) UX - Editor mode — *Daher* (New)
- [#4863](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4863) Workspaces — *Daher* (New)

> **Risk:** 2 Features (Editor mode, Workspaces) not started — carrying over. Nested YAMLs feature still marked Active despite all tasks closed (needs state update).

---

## Completed Epics ✅

- [Migrating big-data to Kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268): Data lake migration, cluster sampling, and OTLP integration all closed
  - [#4790](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4790) Cluster sampling from NLastic to DL — *Uri*, *Daher*
  - [#5084](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5084) OTLP integration gaps — *Bar*
  - [#539](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/539) Migrate data to new kratos data lake — *Daher*
- [Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/269): Phase 1 complete
  - [#4794](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4794) Good Morning Dashboard - Phase 1 (SP:5) — *Uri*
- [CI/CD Infra](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/275): Mandatory documentation stage in CI/CD delivered
  - [#2447](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2447) Mandatory documentation stage in CI/CD (SP:6) — *Tomer*
- [Knowledge base service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2938): Vector DB benchmarks (Milvus vs. Qdrant) complete, architecture decision made, Phase 2 backlog created
  - [#4621](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4621) Vector DB Service - Research & Selection — *Sari*, *Tomer*
- [Tableau and Data Lake Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/270): RDMA issue resolved — [#3980](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3980)
- [Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773): Bug buffer and formal cycle testing all closed
  - [#5011](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5011) Formal Cycle Testing (SP:6) — *Bar*, *Daher*, *Uri*, *Roi*, *Gennady*, *Neta*, *Michael*
  - [#4774](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4774) Bug Buffer — whole team

---

## Bugs

**Done this sprint:** [#4440](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4440) Nlastic 1.17.0rc1 Log Scanners Returning Error Code -9 (Sev 1) — *Uri* | [#5005](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5005) print_commands logs sent to OTLP redundantly (Sev 2) — *Bar* | [#598](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/598) Coverage tooltip for trimmed values (Sev 2) — *Neta* | [#5043](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5043) OTLP log queue not flushed before shutdown (Sev 3) — *Bar* | [#4028](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4028) No bandwidth result from nccl_bw (Sev 3) — *Gennady* | [#3133](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3133) NCCL Status Mismatch in Dashboard (Sev 3) — *Uri* | [#5370](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5370) Analysis ignore_analysis_failure flag not working (Sev 3) — *Tzvi* **Unplanned** | [#5618](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5618) CommandOrientedAnalyzer crashes on array-like values (Sev 3) — *Gennady* **Unplanned**

**Open — carries over to May:**

| ID | Title | Sev | Assignee | Note |
| --- | --- | --- | --- | --- |
| [#5906](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5906) | [E2E Coverage / Expectations] New or edited expectation save | 3 - Low | *Neta* | **Unplanned** |
| [#6050](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6050) | common-otlp-utils: GRPCOTLPLogger init crashes when OTLP_ENABLED off | 3 - Low | *Gennady* | **Unplanned** |

---

## Sprint Management

| ID | Title | State |
| --- | --- | --- |
| [#4133](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4133) | Add a link to the performance dashboards in Unified dashboard | Closed |
| [#5182](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5182) | Buddy support - April 2026 | Closed |
| [#5587](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5587) | Debug and resolve issue | Closed **Unplanned** |
| [#5716](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5716) | [KBs] Design | New — carries over |
| [#4824](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4824) | [GM-Dashboard] Tableau Dashboard | Closed |

---

## 📊 Sprint Summary — April 2026

| Metric | Value |
| --- | --- |
| Stories closed | 22 / 28 (79%) |
| Features closed | 12 / 17 (71%) |
| Bugs closed | 8 / 10 |
| Unplanned items | 30+ items added mid-sprint |
| Key carryover | NSV exports (Neta), Storage Service impl (Gennady), NYG features (Daher), Kafka streaming (Daher) |

**Sprint highlights:**
- 🏆 Kratos migration epic fully closed — data lake, sampling, and OTLP gaps done
- 🏆 GM Dashboard Phase 1 shipped
- 🏆 KB service research complete — architecture decision made, Phase 2 planned
- 🏆 All high/medium severity bugs resolved
- 📈 Storage Service went from 0 to ~50% implementation in one sprint
- ⚠️ NSV export features untouched — need May prioritization

**May sprint planning notes:**
- Storage Service implementation is the largest carryover — scope and break down remaining work
- NSV export features (8 SP) need commitment from Neta
- NYG Editor mode and Workspaces features need planning
- 2 low-severity bugs carry over
- [KBs] Design item needs review — is it still relevant?

---

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/April%202026)_
