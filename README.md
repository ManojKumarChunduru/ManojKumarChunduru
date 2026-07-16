<img src="assets/banner.svg" alt="Manoj Kumar Chunduru, Epic Hospital Billing Analyst. Animated claim lifecycle where a denied claim is recovered through root cause analysis." width="100%"/>

I work the seam where clinical operations become revenue, and I build analytics that prove their own numbers: every metric below regenerates from a repo you can clone and run.

<p>
  <a href="mailto:hello.manojchunduru@gmail.com"><img src="https://img.shields.io/badge/Email-hello.manojchunduru%40gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email"/></a>
  <!-- [VERIFY] replace with the real LinkedIn slug before pushing -->
  <a href="https://www.linkedin.com/in/YOUR-SLUG"><img src="https://img.shields.io/badge/LinkedIn-Manoj%20Kumar%20Chunduru-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Epic%20Analyst%20%7C%20RCM%20Analytics-0D1117?style=for-the-badge&logo=githubsponsors&logoColor=80ed99" alt="Open to roles"/>
</p>

## The numbers

<table>
  <tr>
    <td align="center"><b>3+</b><br/><sub>years on Epic HB /<br/>Resolute across large<br/>health systems</sub></td>
    <td align="center"><b>150+</b><br/><sub>UAT test scenarios<br/>executed for an Epic<br/>upgrade cycle</sub></td>
    <td align="center"><b>5K+</b><br/><sub>daily billing transactions<br/>supported, manual reporting<br/>effort cut 30%</sub></td>
    <td align="center"><b>4</b><br/><sub>public repos, every<br/>benchmark measured and<br/>reproducible from a clone</sub></td>
    <td align="center"><b>95&#8211;96%</b><br/><sub>measured test coverage<br/>across all four repos,<br/>enforced in CI</sub></td>
  </tr>
</table>

## Featured work

Four repos, four different revenue cycle bottlenecks, four different mechanisms. Each one includes a labeled synthetic data generator, so detection quality is a measurement against ground truth, not a claim.

| Repo | What it proves | Headline number |
|---|---|---|
| [**claims-denial-leakage-miner**](https://github.com/ManojKumarChunduru/claims-denial-leakage-miner) | Preventable denials can be classified to an actionable root cause even when remit codes lie | **99.5% precision, 100% recall, 99.1% cause accuracy**; $5.57M of $7.28M denied dollars traced to six preventable causes; 126K claims/s on 1 vCPU |
| [**rcm-upgrade-regression-sentinel**](https://github.com/ManojKumarChunduru/rcm-upgrade-regression-sentinel) | Upgrade UAT can be a declared contract with a measured catch rate, not an eyeball exercise | **100% catch rate over 1,299 planted regressions** across 7 classes, zero false alarms on a benign-only control; 1M rows in 67s; generates the Excel sign-off workbook |
| [**hl7-charge-capture-reconciler**](https://github.com/ManojKumarChunduru/hl7-charge-capture-reconciler) | Ordered care that never becomes a posted charge is findable and priceable from raw HL7v2 | **0.98 missing-charge recall** with honest false positive accounting; ~30K msg/s; $1.8M missing and $2.8M late charges priced |
| [**workqueue-flow-radar**](https://github.com/ManojKumarChunduru/workqueue-flow-radar) | Conflicting routing rules that ping-pong claims between queues can be caught and named from the event log alone | **1.0 precision and recall** on labeled victims; 1.1M events analyzed in 7s; renders the daily ops packet (Excel + PDF) |

Each repo carries architecture decision records, a documented war story with its fix commit, one feature deliberately left out of scope with the trigger for adding it, and a README that says out loud when a perfect metric is a property of the synthetic world.

## Tech stack by depth

| Tier | Stack | Where the depth comes from |
|---|---|---|
| **Expert** | Epic Resolute HB, RCM workflows, denial management (CARC/RARC), charge capture, workqueues, SQL, Excel | 3+ years of production support, Clarity and Reporting Workbench reporting, and upgrade UAT across large health systems |
| **Advanced** | Python, DuckDB, Power BI (star schemas, DAX), UAT and regression automation, pytest, GitHub Actions CI | Four public repos with 95&#8211;96% measured coverage, real benchmarks committed with machine context, Conventional Commit histories |
| **Working** | HL7v2 / FHIR, Tableau, SSRS, PostgreSQL, Oracle, ServiceNow, Jira | Interface validation experience plus the HL7 reconciler's purpose-built parser and Tableau spec |

## Current focus

- Turning denial reports into root-cause worklists that a biller can act on without asking why a claim was flagged
- Automating UAT evidence for EHR upgrade cycles: the tolerance spec is the test plan, the workbook is the artifact
- Workqueue flow analytics: aging, first-pass yield, and the routing conflicts native queue views cannot see
- Porting the repos' plain-SQL models to MS SQL Server syntax, the warehouse most hospital reporting teams actually run

## Quick connect

**hello.manojchunduru@gmail.com** &#183; open to Epic Analyst, Healthcare Data Analyst, and Revenue Cycle Analytics roles &#183; the fastest way to evaluate me is `git clone` any pinned repo and run the three-command quickstart
