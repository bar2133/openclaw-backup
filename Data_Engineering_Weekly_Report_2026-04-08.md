# Data Engineering — Weekly Report | Apr 1–8, 2026

**Sprint:** [April 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/April%202026) (Apr 1 – Apr 30) | 4 of 24 stories closed | 3 Features closed this week

---

## [E2E Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) — Coverage Dashboard & Automation ✅ On Track

**Objective:** Enhance the E2E coverage dashboard with better grouping, export capabilities, scenario name support, and automated tag population from RedMine.

**Done this week:**

- [#4615](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4615) Feature: Permutation Scenarios Grouping in Dashboard Coverage View — _Bar_
  - [#4806](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4806) Permutation Scenarios Grouping in Dashboard Coverage View (SP:3) — _Bar_
- [#2917](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2917) Feature: Auto-Populate Tag Name from RedMine FR Number — _Bar_
  - [#4828](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4828) Auto-Populate Tag Name from RedMine FR Number (SP:2) — _Bar_
- [#598](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/598) Bug: [coverage] add tooltip for trimmed values in drop-downs (SP:1) — _Neta_

**In progress:**

- [#4560](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4560) Feature: Export Test Plan per Cluster from Dashboard (PDF/Image) — _Neta_
  - [#4808](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4808) Export Test Plan per Cluster from Dashboard (PDF/Image) (SP:5) — _Neta_

**Next week:** [#4561](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4561) Export Dashboard Coverage Status per Cluster (PDF/PPT) — _Neta_ | [#4696](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4696) Support adding Scenario Names to Executions — _Bar_ | [#4870](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4870) Expose the ability to report pass rate and details — _Bar_ | [#5144](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5144) Pass rate & details — Planning (SP:1) — _Bar_

---

## [Migrating big-data to Kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) — Data Lake Migration & OTLP ⚠️ At Risk

**Objective:** Migrate data from the old data lake to the new Kratos platform, integrate OTLP telemetry, handle cluster sampling, and implement NLastic actions handling.

**Done this week:**

- [#557](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/557) Migrate data from old datalake to new datalake - initial design — _Daher_ (under [#539](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/539) Migrate data to new kratos data lake)

**In progress:**

- [#539](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/539) Feature: Migrate data to new kratos data lake — _Daher_
  - [#4815](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4815) Migrate data to new kratos data lake (SP:5) — _Daher_ — New

**Next week:** [#4790](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4790) Cluster sampling from NLastic to DL — _Uri_ | [#4793](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4793) NLastic actions handling — _Uri_ | [#5084](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5084) OTLP integration gaps — _Bar_

> **Risk:** Large scope — 4 Features still in New state with multiple child stories unstarted. [#4664](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4664) Stream Sampling data, [#4665](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4665) Actions, [#4791](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4791) Sampling Data Handling, [#4853](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4853) Actions nlastic-side, [#5085](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5085) OTLP integration gaps all New. Need prioritization to avoid carryover.

---

## [Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/269) — Dashboard Migration & Rebuild ⚠️ At Risk

**Objective:** Rebuild the Good Morning Dashboard on the new Kratos platform — Phase 1 implementation, Tableau migration, failure categorization, and health events.

**In progress:**

- [#4794](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4794) Feature: Good Morning Dashboard - Phase 1 — _Uri_
  - [#4796](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4796) [NewKratos] Phase 1 implement — _Uri_ — Active
  - [#5285](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5285) [CA1] Phase 1 implement — _Uri_ — New **Unplanned**
  - [#4795](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4795) Good morning dashboard - stage 1 (SP:5) — _Uri_ — New

**Next week:** [#538](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/538) Migrate good morning dashboard features to new kratos — _Daher_ | [#3446](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3446) Map Mongo dashboard users — _Uri_ | [#4824](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4824) [GM-Dashboard] Tableau Dashboard (SP:2) — _Anan_

> **Risk:** Multiple Features still New with no child items started. Unplanned task [#5285](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5285) added mid-sprint may indicate scope change.

---

## [NYG - Nlastic Yaml Generator](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4864) — YAML Generator Enhancements ✅ On Track

**Objective:** Add nested YAML support, workspace management, and UX editor improvements to the Nlastic YAML Generator tool.

**In progress:**

- [#2762](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2762) Feature: [NYG] Support Nested YAMLs — _Daher_
  - [#4280](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4280) [NYG] Support Nested YAMLs — _Daher_ — Active

**Next week:** [#4863](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4863) [NYG] Workspaces — _Daher_ | [#530](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/530) [NYG] UX - Editor mode — _Daher_

---

## [Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) — Storage Service Design & Build ✅ On Track

**Objective:** Plan and implement a new Nlastic Storage & Streaming Service for centralized data management.

**In progress:**

- [#4882](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4882) Feature: Nlastic Storage Service — Planning — _Gennady_
  - [#4884](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4884) Nlastic Storage Service — Planning (SP:5) — _Gennady_ — New

**Next week:** [#4883](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) Nlastic Storage Service — Implementation — _Gennady_ | [#4885](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4885) Nlastic Storage Service — Implementation (SP:10) — _Gennady_

---

## Completed Epics ✅

- [Tableau and Data Lake Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/270): RDMA issue support — [#3980](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3980) Support RDMA issue closed, [#4830](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4830) Support RDMA issue (SP:2) — _Bar_
- [Nlastic Data Analysis and Data Streaming - Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/547): Streaming to Observability — [#5288](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5288) closed (under [#3130](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3130) Streaming to Observability)

---

## [Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773) — Testing & Bug Buffer ✅ On Track

**Objective:** Manage formal cycle testing capacity and maintain bug buffer allocation across the team.

**Done this week:**

- [#5015](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5015) Formal Cycle Testing — _Anan_ (under [#5011](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5011) Formal Cycle Testing)

**Next week:** [#5012](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5012) Formal Cycle Testing (SP:6) — _Bar_ | [#5014](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5014) Formal Cycle Testing — _Daher_ | [#5016](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5016) Formal Cycle Testing — _Uri_ | [#5017](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5017) Formal Cycle Testing — _Roi_ | [#5018](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5018) Formal Cycle Testing — _Gennady_

---

## Bugs ⚠️ 1 High-Severity Open

**Done this week:** [#598](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/598) [coverage] add tooltip for trimmed values in drop-downs — _Neta_

**In progress:** [#5045](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5045) OTLP: Large JSON payloads can exceed 1MB limit (Low) — _Daher_

**Open — next week:**

| ID | Title | Sev | Assignee | Note |
| -- | ----- | --- | -------- | ---- |
| [#4440](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4440) | Nlastic 1.17.0rc1 Log Scanners Returning Error Code -9 | High | _Uri_ | |
| [#5005](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5005) | print_commands logs sent to OTLP redundantly via OTLPLogHandler | Medium | _Bar_ | |
| [#5043](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5043) | OTLP log queue not flushed before scenario shutdown | Low | _Gennady_ | |
| [#4028](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4028) | No bandwidth result from nccl_bw after execution | Low | _Gennady_ | |
| [#3133](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3133) | NCCL Status Mismatch in Dashboard | Low | _Uri_ | |

> **Risk:** [#4440](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4440) is High severity and still New — needs attention from _Uri_ this sprint.

---

## Sprint Management & Misc

| ID | Title | State |
| -- | ----- | ----- |
| [#4133](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4133) | Add a link to the performance dashboards in Unified dashboard (SP:0.5) | New — _Uri_ |

---

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/April%202026)_
