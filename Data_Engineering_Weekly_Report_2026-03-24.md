# Data Engineering — Weekly Report | Mar 18–24, 2026

**Sprint:** [March 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/March%202026) (Mar 1 – Mar 31) | 23 of 30 stories closed | 12 Features closed this sprint

---

## [Migrating Big-Data to Kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) ✅ On Track

**Objective:** Migrate Nlastic data tables and ETL pipelines from legacy big-data infrastructure to the new Kratos data lake, including silver/gold table transformations, dashboard connectivity, and repository migration.

**Done this week:**
- [#2753](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2753) Feature: Nlastic Data Tables — _Uri_, _Daher_
  - [#3585](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3585) Session Metadata Silver
  - [#3586](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3586) Scenario Metadata Silver
  - [#3587](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3587) Jobs Silver
  - [#3591](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3591) Run Failure Silver
  - [#3592](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3592) Job Readiness Silver
  - [#3593](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3593) Scenario Full Gold
  - [#3960](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3960) File Content Bronze
  - [#4046](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4046) Align ETLs to new logs table
  - [#4182](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4182) Stream missing data in nlastic logs table **Unplanned**
  - [#4281](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4281) Connect Unified dashboard in Tableau to new gold table **Unplanned**
  - [#4559](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4559) Add log time to command logs table **Unplanned**

**In progress:**
- [#557](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/557) Migrate data from old datalake to new datalake - initial design — _Daher_

**Next week:** [#4377](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4377) Move repo to NCS namespace — _Daher_ **Unplanned**

---

## [Nlastic Data Analysis - Real Time Analysis](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/271) ✅ On Track

**Objective:** Implement real-time accumulative/slices analysis with streaming chunk analysis, event management integration, and code review processes.

**Done this week:**
- [#543](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/543) Feature: Realtime data analysis - Accumulative/Slices analysis — _Gennady_
  - [#2369](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2369) Trigger chunk analysis - event management integration
  - [#3979](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3979) Code review: AnalysisQueue, trigger events, and AppParser refactor
  - [#3999](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3999) Integration testing: end-to-end chunk analysis pipeline validation
  - [#4000](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4000) Code review: streaming chunk analysis feature

---

## [NYG - Nlastic Yaml Generator](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/12) ⚠️ At Risk

**Objective:** Extend NYG capabilities with nested YAML support, adoption tracking/statistics, and file explorer functionality.

**Done this week:**
- [#2767](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2767) Feature: File Explorer — _Bar_
  - [#2774](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2774) File Explorer (SP:3)

**In progress:**
- [#4280](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4280) [NYG] Support Nested YAMLs — _Daher_ **Unplanned**
- [#2766](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2766) Feature: Adoption and adoption statistics — _Anan_

**Next week:** [#2771](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2771) [NYG] User engagement and support (SP:1) — _Anan_

> **Risk:** Feature [#2762](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2762) Support Nested YAMLs and Feature [#2766](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2766) Adoption still in progress with 1 week remaining. Nested YAML work was unplanned. May not fully close both by sprint end.

---

## [Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/269) ⚠️ At Risk

**Objective:** Realign and redesign Nlastic dashboards (Tableau/Grafana) with a requirements-first approach.

**In progress:**
- [#4196](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4196) [NlasticDashboards] Requirements Gathering & Design — _Uri_ **Unplanned**

> **Risk:** Feature [#3578](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3578) still in requirements phase (New state) with design work just started. Limited progress this sprint.

---

## [Nlastic Data Analysis - Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4444) ⚠️ At Risk

**Objective:** Design and architect the standalone Data Analysis service.

**Next week:** [#4195](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4195) Data Analysis Service - Design — _Gennady_ **Unplanned**

> **Risk:** Design work has not started yet (New state). Created mid-sprint — may slip to April.

---

## Completed Epics ✅

- [Coverage System - Overview](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4470): Visual improvements, expectation grouping, and pagination preferences — _Neta_, _Bar_
  - [#2920](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2920) Visual Distinction Between Expectations and Execution Tabs
  - [#2921](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2921) Group Expectations by Permutation Group
  - [#2922](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2922) Persist User's Items-Per-Page Preference
  - [#2256](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2256) Filter by NLastic scenario UUID
- [Coverage System - Dashboards](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4448): Paging in coverage widget and use case count per cluster — _Neta_
  - [#2502](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2502) Add Paging in Coverage widget
  - [#2907](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2907) Display Use Case Count Per Cluster
- [Coverage System - Nlastic Integration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4449): Direction and operation type support from Nlastic — _Bar_
  - [#3441](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3441) Support direction and operation type from NLASTIC
- [Coverage System - Tags](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4450): FR number filter and FR metadata in tags — _Bar_, _Neta_
  - [#2919](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2919) Filter Tags by FR Number in Search Bar
  - [#3643](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3643) Add metadata about FRs in FR tag
- [Data Analysis & Streaming Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/547): OTLP auto-detection — _Gennady_
  - [#4456](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4456) OTLP collector endpoint address auto detection
- [Solution FRs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1369): result_per_group flag for multi-rack testing — _Gennady_
  - [#1376](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1376) Add result_per_group flag for multi-rack testing
- [Data Engineering (NCS)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3089): Session classification tagging — _Roi_
  - [#4692](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4692) Session Classification Tagging

---

## Bugs ⚠️ 1 High-Severity Open (Resolved)

**Done this week:**
- [#4246](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4246) S3 Data Loss: \_\_dell\_\_ typo causing silent loss of POST_SCENARIO events (Sev 1 - High) — _Gennady_ **Unplanned**
- [#4204](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4204) Successful scenarios missing from DL running table (Sev 3 - Low) — _Gennady_ **Unplanned**
- [#596](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/596) [coverage] sharing links showing all tags under 1 filter (Sev 2 - Medium) — _Neta_

**In review:**
- [#4465](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4465) Streaming Nlastic logs to OTLP (Sev 2 - Medium) — _Anan_ **Unplanned**

**Open — next week:**
- [#5005](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5005) print_commands logs sent to OTLP redundantly via OTLPLogHandler (Sev 2 - Medium) — _Gennady_ **Unplanned**
- [#598](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/598) [coverage] add tooltip for trimmed values in drop-downs (Sev 2 - Medium) — _Neta_
- [#2905](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2905) Limited Traffic Pattern Options in Expectations (Sev 3 - Low) — _Anan_

> **Risk:** [#5005](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5005) redundant OTLP logging is new (created today) — needs triage. [#2905](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2905) has been active since prior sprints.

---

## Sprint Management & Standalone Items

- [#4142](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4142) US: Productize NLA agent — Active — _Anan_ **Unplanned**
  - [#4143](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4143) handle file size — New
  - [#4169](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4169) support vector db service instead of in memory — New
  - [#4170](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4170) utilize postgres db for metadata/persistent cache — New
  - [#4179](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4179) split workflow config — New
  - [#4219](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4219) Review and fix cursor code review comments — New
  - [#4220](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4220) add TTL for in memory cache and vector stores — New
  - [#4378](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4378) Integrate with new kratos — New
- [#4194](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4194) US: [DataEngineering] Nightly Regression Identification (SP:2) — Closed — _Bar_ **Unplanned**
- [#3446](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3446) Task: Map Mongo dashboard users — New — _Uri_

> **Risk:** [#4142](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4142) Productize NLA agent has 7 child tasks all in New state — significant scope added mid-sprint with no tasks started yet.

---

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/March%202026)_
