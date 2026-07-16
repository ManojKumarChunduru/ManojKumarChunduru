<img src="assets/banner.svg" alt="Manoj Kumar Chunduru, Epic Hospital Billing Analyst, Revenue Cycle Analytics" width="100%"/>

Epic Hospital Billing analyst working the seam where clinical operations become revenue: denials, charge capture, workqueues, and the reporting that keeps all three honest. I build analytics the way UAT taught me to: every claim gets a measured number behind it, and every number regenerates from code you can clone and run.

## What I build

| Project | The problem it attacks | Measured result |
|---|---|---|
| [claims-denial-leakage-miner](https://github.com/ManojKumarChunduru/claims-denial-leakage-miner) | Preventable denials hide inside denial reports; remit codes lie | 99.5% precision, 100% recall, 99.1% root-cause accuracy against labeled ground truth; $5.57M of $7.28M denied dollars traced to six preventable causes; 126K claims/s on 1 vCPU |
| [hl7-charge-capture-reconciler](https://github.com/ManojKumarChunduru/hl7-charge-capture-reconciler) | Ordered care that never becomes a posted charge is silent revenue loss | 31K HL7v2 messages parsed and reconciled at ~30K msg/s; 0.98 missing-charge recall with honest false-positive accounting; $1.8M missing and $2.8M late charges priced |
| [rcm-upgrade-regression-sentinel](https://github.com/ManojKumarChunduru/rcm-upgrade-regression-sentinel) | EHR upgrades ship silent report regressions; exact-match diffing drowns UAT in noise | 100% catch rate over 1,299 planted regressions across 7 classes, zero false alarms on a benign-only control; 1M rows validated in 67s; generates the Excel sign-off evidence workbook |
| [workqueue-flow-radar](https://github.com/ManojKumarChunduru/workqueue-flow-radar) | Conflicting routing rules ping-pong claims between queues, invisibly | 1.0 precision and recall on labeled victims; conflicting rule pairs named from the event log alone; 1.1M events analyzed in 7s; renders the daily ops packet (Excel + PDF) |

Four repos, four different bottlenecks (revenue integrity, charge capture, change-management safety, ops throughput), four different mechanisms (rule classification, event-stream reconciliation, tolerance-aware diffing, cycle detection over event logs).

## How I work

- **Numbers over adjectives.** Each repo includes a labeled synthetic data generator, so precision, recall, and catch rates are measurements, not aspirations. When a metric is flattered by the synthetic world (a 100% recall usually is), the README says so and explains why.
- **Decisions written down.** Every repo carries architecture decision records arguing the trade-off, including the boring choices, plus one feature deliberately left out of scope with the trigger condition for adding it.
- **War stories, not demos.** Each build's hardest real bug is documented with its fix commit: a ground-truth generator describing its own claims wrongly, two dead code paths cancelling each other under pandas 3, a findings dataset silently truncated by its own rendering cap, a planted rule conflict shadowed into dormancy by precedence.
- **The artifact ops actually uses.** Power BI semantic models, Tableau specs, and generated Excel evidence workbooks and ops packets, because sign-off meetings consume files, not dashboards.

## Toolbox

**Domain:** Epic Resolute Hospital Billing, revenue cycle management, denial management (CARC/RARC), charge capture, workqueues, HL7v2, ICD-10 / CPT / HCPCS, UAT and upgrade validation
**Data:** SQL (window functions, layered models), Python, DuckDB, pandas, parquet
**Reporting:** Power BI (star schemas, DAX), Tableau, Excel automation (openpyxl), SSRS concepts, reportlab
**Engineering:** pytest (95-96% measured coverage across repos), ruff, GitHub Actions CI, Conventional Commits, ADRs

## Contact

- Email: hello.manojchunduru@gmail.com
- Open to Epic Analyst, Healthcare Data Analyst, and Revenue Cycle Analytics roles
