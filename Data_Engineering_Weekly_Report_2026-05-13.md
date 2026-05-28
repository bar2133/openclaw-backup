# Data Engineering — Weekly Report | May 1–31, 2026

**Sprint:** [May 2026](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/May%202026) (May 1 – May 31, 2026) | 9 of 70 stories closed | 4 Features closed this sprint

---

## [#4881 Nlastic Storage & Streaming Service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4881) ✅ On Track

**Objective:** Implement the NLastic Storage & Streaming Service — building the full Happy Path pipeline (Kafka ingestion, OTLP routing, persistence) and establishing direct Kafka streaming from NLastic agents.

**In progress:**

- [#4883 Nlastic Storage Service — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4883) — _Gennady_
  - [#5727 Task 6 — TargetDispatcher: parallel delivery](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5727) — _Gennady_
  - [#5728 Task 7 — MessageHandler: backup → dispatch → audit (happy path)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5728) — _Gennady_
  - [#5732 Task 11 — BackupRepository: implements BackupStore](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5732) — _Gennady_
  - [#5733 Task 12 — Streaming Prometheus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5733) — _Gennady_
  - [#5734 Task 13 — StreamingMessageHandler: Kafka ↔ domain adapter](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5734) — _Gennady_
  - [#5736 Task 15 — DI container wiring + main.py registration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5736) — _Gennady_
  - [#5737 Task 16 — Integration test: Kafka → backup → mock OTLP](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5737) — _Gennady_
  - [#5738 Task 17 — Smoke test: full service consume + persist](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5738) — _Gennady_
  - [#5744 Docker Compose stack — build + validate end-to-end](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5744) — _Gennady_
  - [#5750 E2E batch test with real OTLP collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5750) — _Gennady_
  - [#6262 Streaming service: customer_id routing + flat dispatcher + YAML config + migration 0003](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6262) — _Gennady_
  - [#5726 Task 5 — TargetRegistry: struct_type routing + target_override](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5726) — _Gennady_
  - [#6261 nlastic-contracts: drop streaming/targets/+routing.py, add envelope.customer_id+target_override (v0.1.28)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6261) — _Gennady_
  - [#6041 Migration 0002: drop target_override JSONB column from delivery_audit](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6041) — _Gennady_
  - [#6042 Streaming service: smart router + lazy MultiLoggerPool + remove static OTLP + pool-size gauge](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6042) — _Gennady_
  - [#6044 nlastic-contracts: TargetBase + OtlpTargetSpec + envelope.targets; drop target_override](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6044) — _Gennady_
  - [#5779 [StorageService]W2 P1 - Bad Path — Dedup + Retries + DLQ + Deploy](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5779) (SP:5) — _Gennady_
  - [#5780 [StorageService]W3 P2 - S3 Target](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5780) (SP:4) — _Gennady_
  - [#5781 [StorageService]W4 P3 - Coverage SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5781) (SP:2) — _Gennady_
  - [#6243 [StorageService]W1 P1 — Happy Path Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6243) — _Gennady_
  - [#6032 [StorageService]W1 P1 — Deployment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6032) (SP:3) — _Gennady_
  - [#6040 W1: Per-DUT OTLP collector routing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040) — _Gennady_
  - [#5739 Task 18 — Final verification: lint, boot checks, full suite](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5739) — _Gennady_
  - [#5880 Refactor RoutingConfig to two-tier](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5880) — _Gennady_
  - [#6437 Streaming service: StreamingMessageHandler — Kafka consumer → dispatcher → audit writer (G-4)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6437) — _Gennady_ **[Unplanned]**
  - [#6043 Monolith call sites: pass DUT collector coords into SDK](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6043) — _Gennady_
  - [#6045 nlastic-data-streaming SDK: build envelope.targets from Consul-discovered (address, port)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6045) — _Gennady_
- [#5874 Stream NLastic data directly to Kafka instead of OTLP collector](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5874) — _Daher_
  - [#5992 Prod-grade implementation for Kafka streaming](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5992) (SP:2) — _Daher_
  - [#6244 Stream NLastic data directly to Kafka instead of OTLP collector - POC](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6244) (SP:2) — _Daher_

> **Risk:** Storage Service W1 Happy Path ([#6243](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6243), [#6032](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6032)) and per-DUT routing ([#6040](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6040)) still New with 10+ active tasks in parallel — delivery pressure. **Mitigation:** Gennady and Daher are co-owning; daily sync recommended.

---

## [#277 NSV Coverage System](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/277) ✅ On Track

**Objective:** Advance the NSV Coverage System: complete write-back to Redmine, ship permutation auto-naming, and progress UX enrichments, admin panel, and regex filtering for the coverage dashboard.

**Done this sprint:**

- [#4560 Export Test Plan per Cluster from Dashboard (PDF/Image)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4560) — _Neta_
  - [#6240 Export Test Plan per Cluster from Dashboard (PDF/Image)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6240) (SP:5) — _Neta_
- [#4561 Export Dashboard Coverage Status per Cluster (PDF/PPT)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4561) — _Neta_
  - [#6241 Export Dashboard Coverage Status per Cluster (PDF/PPT)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6241) (SP:3) — _Neta_
- [#6197 Permutation sub-scenario auto-naming via permutation_name](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6197) — _Bar_
  - [#6198 Permutation sub-scenario auto-naming via permutation_name](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6198) (SP:2) — _Bar_

**Next / Planned:**

- [#590 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/590) — _Neta_
  - [#5907 [E2E Coverage / Expectations] New or edited expectation saves hardware/software component keys in camelCase instead of snake_case](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5907) — _Neta_
  - [#6003 Regex filtering](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6003) (SP:2) — _Neta_
- [#601 UX ENRICHMENTS](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/601) — _Neta_
  - [#2083 tool tip to total coverage gauge](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2083) — _Neta_
  - [#3132 enrich UX in term of overview actions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3132) — _Neta_
  - [#602 ux enrichment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/602) (SP:2) — _Neta_
  - [#603 color palette](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/603) — _Neta_
  - [#604 dashboard bars aligment](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/604) — _Neta_
  - [#605 overview tables adjustable full width](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/605) — _Neta_
  - [#606 components minimum width](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/606) — _Neta_
  - [#608 navbar design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/608) — _Neta_
  - [#609 sidebar design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/609) — _Neta_
  - [#607 nvidia fonts](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/607) — _Neta_
- [#661 Admin Panel](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/661) — _Neta_
  - [#2082 [coverage]attributes category splitting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2082) (SP:3) — _Neta_
  - [#2085 code review](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2085) — _Neta_
  - [#2086 implemnt](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2086) — _Neta_
- [#664 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/664) — _Neta_
  - [#6005 Duplicate tag expectations and permutations to another tag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6005) (SP:2) — _Neta_
- [#2652 Write back to the Redmine](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2652) — _Bar_
  - [#6183 Extend RedmineService with write capabilities](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6183) (SP:1) — _Bar_
  - [#6185 Build RedmineWritebackService orchestrator with feature flag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6185) (SP:1) — _Bar_
  - [#6187 Wire Flow 1 into TagRouter (create + edit with FR diff)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6187) (SP:0) — _Bar_
  - [#6189 Wire Flow 2 into QueriesRouter (tag-coverage dashboard)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6189) (SP:0) — _Bar_
  - [#6191 Configuration + K8s rollout for new REDMINE_ env vars](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6191) (SP:0) — _Bar_
  - [#6193 Tests for service, orchestrator, and routers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6193) (SP:1) — _Bar_
  - [#6195 Operational readiness - structured logs and error monitoring](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6195) (SP:0) — _Bar_
  - [#6184 Implement: Extend RedmineService with write capabilities](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6184) — _Bar_
  - [#6186 Implement: Build RedmineWritebackService orchestrator with feature flag](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6186) — _Bar_
  - [#6188 Implement: Wire Flow 1 into TagRouter (create + edit with FR diff)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6188) — _Bar_
  - [#6190 Implement: Wire Flow 2 into QueriesRouter (tag-coverage dashboard)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6190) — _Bar_
  - [#6192 Implement: Configuration + K8s rollout for new REDMINE_ env vars](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6192) — _Bar_
  - [#6194 Implement: Tests for service, orchestrator, and routers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6194) — _Bar_
  - [#6196 Implement: Operational readiness - structured logs and error monitoring](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6196) — _Bar_
- [#4870 expose the ability to report pass rate and details](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4870) — _Bar_
  - [#5146 Expose the ability to report pass rate and details — Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5146) (SP:1) — _Bar_
  - [#6242 Expose the ability to report pass rate and details — Planning](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6242) (SP:1) — _Bar_

> **Risk:** Write-back to Redmine feature ([#2652](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2652)) has 7 open User Stories all still New — late start risk. **Mitigation:** Bar to confirm implementation start date.

---

## [#6859 NCS Telemetry Data in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6859) ✅ On Track

**Objective:** Build NCS telemetry data pipelines in Databricks — designing and implementing UFM, NMXT, Cumulus metrics, DTS, GNMI, and Phy Data ingestion flows.

**Done this sprint:**

- [#6861 Design telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6861) — _Bar_ **[Unplanned]**
  - [#6862 Design telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6862) (SP:2) — _Bar_ **[Unplanned]**

**Next / Planned:**

- [#6864 UFM telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6864) — _Roi_ **[Unplanned]**
  - [#6865 UFM telemetry data pipelines](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6865) (SP:2) — _Roi_ **[Unplanned]**
- [#6867 NMXT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6867) — _Bar_ **[Unplanned]**
  - [#6868 NMXT](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6868) (SP:2) — _Bar_ **[Unplanned]**
- [#6870 Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6870) — _Roi_ **[Unplanned]**
  - [#6871 Cumulus metrics](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6871) (SP:2) — _Roi_ **[Unplanned]**
- [#6873 Host side DTS](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6873) — _Bar_ **[Unplanned]**
  - [#6874 Host side DTS](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6874) (SP:2) — _Bar_ **[Unplanned]**
- [#6876 GNMI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6876) — _Bar_ **[Unplanned]**
  - [#6877 GNMI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6877) (SP:2) — _Bar_ **[Unplanned]**
- [#6879 Phy Data - Pipelines and Dashboards](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6879) — _Bar_ **[Unplanned]**
  - [#6880 Phy Data - Pipelines and Dashboards](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6880) (SP:2) — _Bar_ **[Unplanned]**
- [#6882 Data Provisioning - Incidents system](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6882) — _Bar_ **[Unplanned]**
  - [#6883 Data Provisioning - Incidents system](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6883) (SP:2) — _Bar_ **[Unplanned]**
- [#7055 MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7055) — _Uri_ **[Unplanned]**
  - [#7058 MTBI](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7058) (SP:2) — _Uri_ **[Unplanned]**
- [#7056 MTBF](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7056) — _Uri_ **[Unplanned]**
  - [#7057 MTBF](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/7057) (SP:2) — _Uri_ **[Unplanned]**

> **Risk:** Most telemetry pipeline items ([#6864](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6864), [#6867](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6867), [#6870](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6870), [#6879](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6879)) are still New; sprint is half over. **Mitigation:** Confirm owners are actively engaged with Roi and Bar.

---

## [#4864 NYG - Nlastic Yaml Generator](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4864) ✅ On Track

**Objective:** Develop the NLastic YAML Generator (NYG) — supporting nested YAMLs, multi-file generation, and ongoing user support tasks.

**In progress:**

- [#2762 [NYG] Support Nested YAMLs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2762) — _Daher_
  - [#6434 [NYG] Support Nested YAMLs - Frontend](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6434) — _Daher_ **[Unplanned]**
  - [#5547 Multi-File Generation (state, representation, output)](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5547) — _Daher_
  - [#5550 FE output modifications](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5550) — _Daher_

**Next / Planned:**

- [#5895 [NYG] Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5895) — _Daher_
  - [#6017 [NYG] Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6017) (SP:2) — _Daher_
- [#6658 [NYG] General tasks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6658) — _Tzvi_ **[Unplanned]**
  - [#6659 [NYG] Analyse usage survey report](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6659) — _Tzvi_ **[Unplanned]**

> **Risk:** NYG nested YAML and multi-file generation tasks ([#5547](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5547), [#5550](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5550)) are Active but no closure yet; support items accumulating. **Mitigation:** Daher to provide daily update.

---

## [#268 Migrating big-data to Kratos](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/268) ✅ On Track

**Objective:** Complete Kratos migration by implementing NLastic actions handling and wrapping up Data Reliability / Data Provisioning work in Databricks.

**Done this sprint:**

- [#4771 Handling Graph Data Model](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4771) — _Uri_
  - [#3584 [New Kratos] f_nbu_nlastic_graph_data_model_bronze](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3584) — _Uri_
- [#5669 Data Reliability - Data Provisioning in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5669) — _Uri_
  - [#5670 Data Reliability - Data Provisioning in Databricks](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5670) (SP:2) — _Uri_

**Next / Planned:**

- [#4793 NLastic actions handling](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4793) — _Uri_
  - [#4665 [NewKratos] Actions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4665) — _Uri_
  - [#4853 NLastic actions handling - nlastic side](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4853) — _Uri_

> **Risk:** NLastic Actions handling ([#4793](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4793)) has 3 open items still New. **Mitigation:** Uri to confirm timeline alignment with Kratos team.

---

## [#269 Good Morning Dashboard](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/269) ✅ On Track

**Objective:** Deliver Good Morning Dashboard improvements: ship Deep-Dive Navigation Links, advance Status Classification Refinement, and design the next wave of features.

**Done this sprint:**

- [#6535 Deep-Dive Navigation Links](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6535) — _Uri_ **[Unplanned]**
  - [#6536 Deep-Dive Navigation Links - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6536) (SP:2) — _Uri_ **[Unplanned]**
  - [#6558 Deep-Dive Navigation Links - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6558) (SP:2) — _Uri_ **[Unplanned]**

**Next / Planned:**

- [#6532 Infrastructure & Data Architecture Overhaul](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6532) — _Uri_ **[Unplanned]**
  - [#6533 Infrastructure & Data Architecture Overhaul - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6533) (SP:2) — _Uri_ **[Unplanned]**
  - [#6556 Infrastructure & Data Architecture Overhaul - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6556) (SP:2) — _Uri_ **[Unplanned]**
- [#6538 Cluster Health Tab](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6538) — _Uri_ **[Unplanned]**
  - [#6539 Cluster Health Tab - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6539) (SP:2) — _Uri_ **[Unplanned]**
  - [#6560 Cluster Health Tab - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6560) (SP:2) — _Uri_ **[Unplanned]**
- [#6541 Status Classification Refinement](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6541) — _Uri_ **[Unplanned]**
  - [#6542 Status Classification Refinement - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6542) (SP:2) — _Uri_ **[Unplanned]**
  - [#6562 Status Classification Refinement - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6562) (SP:2) — _Uri_ **[Unplanned]**
- [#6544 Automated Potential Degradation Detection](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6544) — _Uri_ **[Unplanned]**
  - [#6545 Automated Potential Degradation Detection - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6545) (SP:2) — _Uri_ **[Unplanned]**
  - [#6564 Automated Potential Degradation Detection - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6564) (SP:2) — _Uri_ **[Unplanned]**
- [#6547 Node Allocation Transparency](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6547) — _Uri_ **[Unplanned]**
  - [#6548 Node Allocation Transparency - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6548) (SP:2) — _Uri_ **[Unplanned]**
  - [#6566 Node Allocation Transparency - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6566) (SP:2) — _Uri_ **[Unplanned]**
- [#6550 Post-Execution Run Tagging & Saved Tests](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6550) — _Uri_ **[Unplanned]**
  - [#6551 Post-Execution Run Tagging & Saved Tests - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6551) (SP:2) — _Uri_ **[Unplanned]**
  - [#6568 Post-Execution Run Tagging & Saved Tests - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6568) (SP:2) — _Uri_ **[Unplanned]**
- [#6553 Identifier-Based Run Comparison](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6553) — _Uri_ **[Unplanned]**
  - [#6554 Identifier-Based Run Comparison - Design](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6554) (SP:2) — _Uri_ **[Unplanned]**
  - [#6570 Identifier-Based Run Comparison - Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6570) (SP:2) — _Uri_ **[Unplanned]**

> **Risk:** 7 of 8 features in Good Morning Dashboard are still fully New with designs pending — no implementation started. **Mitigation:** Uri to front-load design reviews this week.

---

## [#2497 Nlastic Reporting](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2497) ✅ On Track

**Objective:** Build NLastic Reporting skills — implement the Regression Report skill and begin work on the Daily Report skill.

**Next / Planned:**

- [#6063 Nlastic Reporting - Regression Report skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6063) — _Sari_
  - [#6179 First Skills - Research, Planning and Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6179) (SP:2) — _Sari_
- [#6420 Nlastic Reporting - Daily Report skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6420) — _Sari_ **[Unplanned]**
  - [#6477 research the needed resources for the skill + implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6477) — _Sari_ **[Unplanned]**
  - [#6478 get all the needed resources form the appropriate people](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6478) — _Sari_ **[Unplanned]**
  - [#6481 adaptable skill per cluster](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6481) — _Sari_ **[Unplanned]**
  - [#6482 get the constraint of the skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6482) — _Sari_ **[Unplanned]**
  - [#6483 implement the skill](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6483) — _Sari_ **[Unplanned]**

> **Risk:** Regression Report skill ([#6063](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6063)) is Active but Daily Report ([#6420](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6420)) items are all New. **Mitigation:** Sari to align scope with stakeholders.

---

## [#2938 Knowledge base service](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2938) ✅ On Track

**Objective:** Advance the Knowledge Base Service — update the NYG Knowledge Base to April 2026 GA and start V1 implementation.

**Next / Planned:**

- [#2299 [NYG] Automated Knowledge Base Pipeline](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2299) — _Tomer_
  - [#5189 QA and test the new Knowledge Base](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5189) — _Tomer_
  - [#5187 Update NYG Knowledge Base to April 2026 GA](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5187) (SP:1) — _Tomer_
  - [#5188 Build updated Knowledge Base instance](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5188) — _Tomer_
  - [#5190 Publish and deploy the Knowledge Base](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5190) — _Tomer_
  - [#5879 create a PPT for knowledge base usage in recipes.](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5879) — _Tomer_
- [#2335 [NYG] Version specific knowledge base](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2335) — _Tomer_
  - [#6007 [NYG] Version specific knowledge base](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6007) (SP:2) — _Tomer_
- [#5088 VectorDB Platform Build-out](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5088) — _Tomer_
  - [#6011 VectorDB Platform Build-out](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6011) (SP:2) — _Tomer_
- [#5530 NYG KB Migration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5530) — _Tomer_
  - [#6013 NYG KB Migration](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6013) (SP:2) — _Tomer_
- [#6000 Knowledge Base Service - V1 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6000) — _Tomer_
  - [#6001 Knowledge Base Service - V1 Implementation](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6001) (SP:7) — _Tomer_

> **Risk:** Knowledge Base Service V1 ([#6000](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6000)) and NYG KB update ([#2299](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/2299)) both sit in New state. **Mitigation:** Tomer to confirm implementation kickoff.

---

## [#1369 Solution FRs](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/1369) ⚠️ At Risk

**Objective:** Implement Solution Feature Requests — add socket_group_id support in doca-perftests.

**Next / Planned:**

- [#5986 Feature Request: Add socket_group_id Support in doca-perftest Executions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5986) — _Uri_
  - [#6019 Feature Request: Add socket_group_id Support in doca-perftest Executions](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6019) (SP:2) — _Uri_

> **Risk:** socket_group_id feature request ([#5986](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5986)) items all New — not yet started. **Mitigation:** Confirm priority with Uri.

---

## [#4773 Generic Buffers](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/4773) ⚠️ At Risk

**Objective:** Manage sprint capacity buffers, formal cycle testing, and buddy support activities.

**Next / Planned:**

- [#5799 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5799) — _Bar_
  - [#5800 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5800) (SP:6) — _Bar_
  - [#5801 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5801) — _Daher_
  - [#5802 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5802) — _Anan_
  - [#5803 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5803) — _Uri_
  - [#5805 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5805) — _Gennady_
  - [#5806 Formal Cycle Testing](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5806) — _Neta_
- [#5810 Buddy Support](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5810) — _Bar_

> **Risk:** Formal Cycle Testing tasks ([#5799](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5799)) are spread across multiple team members; coordination needed to avoid last-minute crunch. **Mitigation:** Bar to set cycle start date.

---

## Bugs ⚠️

**Closed this sprint:** [#6248 CoverageExpectationsManager.post missing settings=](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6248) — _Bar_ | [#5906 [E2E Coverage / Expectations] New or edited expect](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5906) — _Neta_ | [#5985 f_nbu_nlastic_running_table_bronze missing remote_](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5985) — _Uri_ | [#6050 common-otlp-utils: GRPCOTLPLogger init crashes whe](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/6050) — _Gennady_ | [#5045 OTLP: Large JSON payloads (pairs_table, workplan_g](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5045) — _Daher_

**Open — planned next:**

| ID | Title | Sev | Assignee | Note |
| --- | --- | --- | --- | --- |
| [#5897](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5897) | "Ask Mode" should state al capabilities of NYG when ask | Low | _Daher_ |  |
| [#5899](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5899) | Pairing allocation docs and recipe issue | Low | _Daher_ |  |
| [#5902](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/5902) | NYG generated invalid yamls | Low | _Daher_ |  |
| [#3943](https://dev.azure.com/NCS-RnD/NLASTIC/_workitems/edit/3943) | support more then one regex in filters | Low | _Neta_ |  |

> **Risk:** 4 open Low-severity bugs across NYG and Coverage — no high/critical items currently. Monitor for escalation.

---

## Sprint Management & Capacity

| ID | Title | State | Assignee |
| --- | --- | --- | --- |

_[View sprint board](https://dev.azure.com/NCS-RnD/NLASTIC/_sprints/taskboard/Data%20Engineering/NLASTIC/May%202026)_
