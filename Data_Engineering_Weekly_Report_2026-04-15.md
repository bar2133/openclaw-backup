# Data Engineering — Weekly Report | Apr 13–15, 2026

**Sprint:** [April 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/April%202026) (Apr 1 – Apr 30) | 4 of 24 stories closed | 3 Features closed this sprint

---

## [Migrating big-data to Kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) — Big-data Migration ⚠️ At Risk

**Objective:** Migrate data infrastructure from legacy datalake to Kratos/Databricks, including cluster sampling, OTLP integration, actions handling, and data reliability.

**Done this week:**

- [#557](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/557) US: Migrate data from old datalake to new datalake - initial design — _Daher_

**In progress:**

- [#4664](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4664) US: Stream Sampling data - NLastic side (SP:1) — _Daher_
- [#4665](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4665) US: [NewKratos] Actions — _Uri_

**Next week:**

- [#5669](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5669) Feature: Data Reliability - Data Provisioning in Databricks (SP:2) — _Uri_ **Unplanned**
  - [#5670](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5670) US: Data Reliability - Data Provisioning in Databricks (SP:2) — _Uri_
- [#4790](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4790) Feature: Cluster sampling from NLastic to DL — _Uri_
  - [#4791](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4791) US: Sampler Data - Handle in DB — _Uri_
- [#4793](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4793) Feature: NLastic actions handling — _Uri_
  - [#4853](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4853) US: NLastic actions handling - nlastic side — _Uri_
- [#5084](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5084) Feature: OTLP integration gaps (SP:2) — _Bar_
  - [#5085](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5085) US: OTLP integration gaps (SP:2) — _Bar_

> **Risk:** Heavy backlog — 5 Features still New with 0 progress. Multiple Uri-owned items competing for bandwidth.

---

## [Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/269) — Dashboard Migration ⚠️ At Risk

**Objective:** Migrate Good Morning Dashboard features to new Kratos platform (Phase 1), including failure categorization, health events, and Tableau dashboards.

**Done this week:**

- [#4794](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4794) Feature: Good Morning Dashboard - Phase 1 (SP:5) — _Uri_ (Active)
  - [#5285](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5285) Task: [CA1] Phase 1 implement — _Uri_ ✅ **Unplanned**
  - [#4796](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4796) Task: [NewKratos] Phase 1 implement — _Uri_ ✅

**In progress:**

- [#4794](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4794) Feature: Good Morning Dashboard - Phase 1 (SP:5) — _Uri_ — feedback fixes pending
  - [#5672](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5672) Task: Feedback fix buffer — _Uri_ (New) **Unplanned**

**Next week:**

- [#538](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/538) Feature: Migrate good morning dashboard features to new kratos — _Daher_
  - [#555](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/555) US: [GM-dashboard] Migrate failure categorization — _Daher_
  - [#556](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/556) US: [GM-Dashboard] health events — _Daher_
- [#4824](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4824) US: [GM-Dashboard] Tableau Dashboard (SP:2) — _Anan_
- [#3446](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3446) Task: Map Mongo dashboard users — _Uri_

> **Risk:** Phase 1 implementation done but feedback fixes still open. Legacy migration (failure categorization, health events) hasn't started — _Daher_ split across multiple Epics.

---

## [Tableau and Data Lake Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/270) — RDMA Support ✅ Done

**Objective:** Provide Tableau and Data Lake support, including RDMA issue resolution.

**Done this sprint:**

- [#3980](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3980) Feature: Support RDMA issue — _Bar_
  - [#4830](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4830) US: Support RDMA issue (SP:2) — _Bar_

---

## [NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) — Coverage Dashboard ⚠️ At Risk

**Objective:** Enhance the NSV coverage dashboard with permutation grouping, auto-populate tag names, scenario name support, and export capabilities.

**Done this sprint:**

- [#4615](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4615) Feature: Permutation Scenarios Grouping in Dashboard Coverage View — _Bar_
  - [#4806](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4806) US: Permutation Scenarios Grouping in Dashboard Coverage View (SP:3) — _Bar_
- [#2917](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2917) Feature: Auto-Populate Tag Name from RedMine FR Number — _Bar_
  - [#4828](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4828) US: Auto-Populate Tag Name from RedMine FR Number (SP:2) — _Bar_

**In progress:**

- [#4808](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4808) US: Export Test Plan per Cluster from Dashboard (PDF/Image) (SP:5) — _Neta_

**Next week:**

- [#4560](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4560) Feature: Export Test Plan per Cluster from Dashboard (PDF/Image) — _Neta_
- [#4561](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4561) Feature: Export Dashboard Coverage Status per Cluster (PDF/PPT) — _Neta_
  - [#4810](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4810) US: Export Dashboard Coverage Status per Cluster (PDF/PPT) (SP:3) — _Neta_
- [#4696](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4696) Feature: support adding Scenario Names to Executions in Nlastic — _Bar_
  - [#4814](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4814) US: support adding Scenario Names to Executions in Nlastic — _Bar_
- [#5144](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5144) US: Expose the ability to report pass rate and details — Planning (SP:1) — _Bar_

> **Risk:** 4 Features still New. Export features (PDF/PPT) are large (SP:8 combined) and all assigned to _Neta_ — capacity concern.

---

## [Nlastic Data Analysis and Data Streaming - Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/547) — Data Analysis Support ✅ On Track

**Objective:** Ongoing support for data analysis and streaming infrastructure.

No active stories this sprint — buffer work only.

---

## [NYG - Nlastic Yaml Generator](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4864) — YAML Generator ✅ On Track

**Objective:** Enhance NYG with nested YAML support, workspaces, multi-file generation, and UX editor mode.

**Done this week:**

- [#2762](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2762) Feature: [NYG] Support Nested YAMLs — _Daher_ (Active — tasks completed)
  - [#5531](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5531) Task: Feature recipe and KB ingestion — _Daher_ ✅ **Unplanned**
  - [#5532](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5532) Task: nested yaml validation MCP modifications — _Daher_ ✅ **Unplanned**
  - [#5545](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5545) Task: detail prompt modification — _Daher_ ✅ **Unplanned**
  - [#5592](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5592) Task: generation — _Daher_ ✅ **Unplanned**

**In progress:**

- [#4280](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4280) US: [NYG] Support Nested YAMLs — _Daher_
  - [#5547](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5547) Task: Multi-File Generation (state, representation, output) — _Daher_ **Unplanned**
  - [#5550](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5550) Task: FE output modifications — _Daher_ **Unplanned**

**Next week:** [#530](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/530) Feature: [NYG] UX - Editor mode — _Daher_ | [#4863](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4863) Feature: [NYG] Workspaces — _Daher_

> **Risk:** All NYG work on _Daher_ alone — single point of failure. Multiple unplanned tasks added mid-sprint.

---

## [Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) — Storage Service ⚠️ At Risk

**Objective:** Design and implement the Nlastic Storage & Streaming Service for data persistence and streaming.

**In progress:**

- [#4884](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4884) US: Nlastic Storage Service — Planning (SP:5) — _Gennady_

**Next week:**

- [#4882](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4882) Feature: Nlastic Storage Service — Design (SP:5) — _Gennady_
- [#4883](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) Feature: Nlastic Storage Service — Implementation (SP:10) — _Gennady_
  - [#4885](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4885) US: Nlastic Storage Service — Implementation (SP:10) — _Gennady_

> **Risk:** Large scope (SP:15 combined) entirely on _Gennady_. Design phase hasn't completed — implementation unlikely to start this sprint.

---

## [Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773) — Capacity & Testing ✅ On Track

**Objective:** Sprint capacity buffers and formal cycle testing across the team.

**Done this sprint:**

- [#5015](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5015) Task: Formal Cycle Testing — _Anan_

**Next week:**

- [#5011](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5011) Feature: Formal Cycle Testing (SP:6) — _Bar_
  - [#5012](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5012) US: Formal Cycle Testing (SP:6) — _Bar_

---

## Bugs ⚠️ 1 High-Severity Open

**Done this sprint:**

- [#598](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/598) [coverage] add tooltip for trimmed values in drop-downs — _Neta_
- [#5370](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5370) Bug: Analysis ignore_analysis_failure flag not working — _Tzvi_ **Unplanned**
- [#5043](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5043) OTLP log queue is not flushed before scenario shutdown — _Bar_
- [#4028](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4028) Bug: No bandwidth result from nccl_bw after execution — _Gennady_

**In review:**

- [#5618](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5618) CommandOrientedAnalyzer._get_lit_columns crashes on array-like values with ambiguous truth value (Low) — _Gennady_ **Unplanned**

**In progress:**

- [#5045](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5045) OTLP: Large JSON payloads exceed 1MB limit (Low) — _Daher_

**Open — next week:**

| ID | Title | Sev | Assignee | Note |
| -- | ----- | --- | -------- | ---- |
| [#4440](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4440) | Nlastic 1.17.0rc1 Log Scanners Returning Error Code -9 | High | _Uri_ | |
| [#3133](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3133) | NCCL Status Mismatch in Dashboard | Low | _Uri_ | |
| [#5005](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5005) | print_commands logs sent to OTLP redundantly | Medium | _Bar_ | |

> **Risk:** [#4440](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4440) High-severity bug still open and unaddressed — _Uri_ stretched across many items.

---

## Sprint Management & Orphans

| ID | Title | State |
| -- | ----- | ----- |
| [#4133](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4133) | Add a link to the performance dashboards in Unified dashboard | New |
| [#5587](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5587) | Debug and resolve issue — _Tzvi_ | Closed **Unplanned** |

---

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/April%202026)_
