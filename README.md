<img src="assets/banner.svg" alt="Manoj Kumar Chunduru, Epic Hospital Billing Analyst. Animated claim lifecycle where a denied claim is recovered through root cause analysis." width="100%"/>

I work the seam where clinical operations become revenue, and I build analytics that prove their own numbers: every metric on this page regenerates from a repo you can clone and run.

<p>
  <a href="mailto:hello.manojchunduru@gmail.com"><img src="https://img.shields.io/badge/Email-hello.manojchunduru%40gmail.com-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email"/></a>
  <!-- [VERIFY] replace YOUR-SLUG with the real LinkedIn slug before pushing -->
  <a href="http://www.linkedin.com/in/manoj-kumar-b4984762"><img src="https://img.shields.io/badge/LinkedIn-Manoj%20Kumar%20Chunduru-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Epic%20Analyst%20%7C%20RCM%20Analytics-0D1117?style=for-the-badge&logo=githubsponsors&logoColor=80ed99" alt="Open to roles"/>
</p>

## The numbers

<table>
  <tr>
    <td align="center">&#8987;<br/><b>3+ years</b><br/><sub>Epic HB / Resolute across<br/>large health systems</sub></td>
    <td align="center">&#129514;<br/><b>150+ scenarios</b><br/><sub>UAT executed for an<br/>Epic upgrade cycle</sub></td>
    <td align="center">&#128202;<br/><b>5K+ daily txns</b><br/><sub>supported, manual reporting<br/>effort cut 30%</sub></td>
    <td align="center">&#127942;<br/><b>4 certifications</b><br/><sub>Johns Hopkins &#215;2,<br/>MedCerts &#215;2</sub></td>
    <td align="center">&#128230;<br/><b>4 repos</b><br/><sub>every benchmark measured,<br/>95&#8211;96% test coverage</sub></td>
  </tr>
</table>

## Stack, by depth

<img src="assets/stack.svg" alt="Tech stack by experience level: Epic Resolute HB, SQL, Excel at expert; Python, DuckDB, Power BI at advanced; HL7, Tableau, SSRS at working level." width="100%"/>

## Featured work

Four repos, four different revenue cycle bottlenecks, four different mechanisms. Each includes a labeled synthetic data generator, so detection quality is a measurement against ground truth, not a claim.

| Repo | What it proves | Headline number |
|---|---|---|
| [**claims-denial-leakage-miner**](https://github.com/ManojKumarChunduru/claims-denial-leakage-miner) | Preventable denials can be classified to an actionable root cause even when remit codes lie | **99.5% precision, 100% recall, 99.1% cause accuracy**; $5.57M of $7.28M denied dollars traced to six preventable causes; 126K claims/s |
| [**rcm-upgrade-regression-sentinel**](https://github.com/ManojKumarChunduru/rcm-upgrade-regression-sentinel) | Upgrade UAT can be a declared contract with a measured catch rate, not an eyeball exercise | **100% catch rate over 1,299 planted regressions**, zero false alarms on a benign-only control; 1M rows in 67s; generates the Excel sign-off workbook |
| [**hl7-charge-capture-reconciler**](https://github.com/ManojKumarChunduru/hl7-charge-capture-reconciler) | Ordered care that never becomes a posted charge is findable and priceable from raw HL7v2 | **0.98 missing-charge recall** with honest false positive accounting; ~30K msg/s; $1.8M missing and $2.8M late charges priced |
| [**workqueue-flow-radar**](https://github.com/ManojKumarChunduru/workqueue-flow-radar) | Conflicting routing rules that ping-pong claims between queues can be caught and named from the event log alone | **1.0 precision and recall** on labeled victims; 1.1M events in 7s; renders the daily ops packet (Excel + PDF) |

Each repo carries architecture decision records, a documented war story with its fix commit, one feature deliberately out of scope with its trigger, and a README that says out loud when a perfect metric is a property of the synthetic world.

## Building blocks

<p>
  <img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=4cc9f0" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=4cc9f0" alt="SQL"/>
  <img src="https://img.shields.io/badge/DuckDB-0D1117?style=for-the-badge&logo=duckdb&logoColor=80ed99" alt="DuckDB"/>
  <img src="https://img.shields.io/badge/pandas-0D1117?style=for-the-badge&logo=pandas&logoColor=80ed99" alt="pandas"/>
  <img src="https://img.shields.io/badge/Power%20BI-0D1117?style=for-the-badge&logo=googleanalytics&logoColor=c77dff" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Tableau-0D1117?style=for-the-badge&logo=tableau&logoColor=c77dff" alt="Tableau"/>
  <img src="https://img.shields.io/badge/Excel-0D1117?style=for-the-badge&logo=googlesheets&logoColor=80ed99" alt="Excel"/>
  <img src="https://img.shields.io/badge/HL7%20%2F%20FHIR-0D1117?style=for-the-badge&logo=fastapi&logoColor=4cc9f0" alt="HL7 FHIR"/>
  <img src="https://img.shields.io/badge/pytest-0D1117?style=for-the-badge&logo=pytest&logoColor=4cc9f0" alt="pytest"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=80ed99" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/ServiceNow-0D1117?style=for-the-badge&logo=servicenow&logoColor=c77dff" alt="ServiceNow"/>
  <img src="https://img.shields.io/badge/Jira-0D1117?style=for-the-badge&logo=jira&logoColor=4cc9f0" alt="Jira"/>
</p>

## Current focus

- Turning denial reports into root-cause worklists a biller can act on without asking why a claim was flagged
- Automating UAT evidence for EHR upgrade cycles: the tolerance spec is the test plan, the workbook is the artifact
- Workqueue flow analytics: aging, first-pass yield, and the routing conflicts native queue views cannot see
- Porting the repos' plain-SQL models to MS SQL Server syntax, the warehouse most hospital reporting teams run

## Pivot point

I learned the revenue cycle from inside its workflows: UAT scripts, workqueues, and production support tickets at hospital scale. Then I went back to school for the data discipline (MS in Data Management &amp; Analytics, 2024) to measure what I had been supporting. The four repos above are that pivot made public: the same denials, charges, upgrades, and queues, now with labeled ground truth, benchmarks, and CI behind every claim.

<!-- Outside the code: add a short emoji hobby row here if Manoj wants one; nothing invented on his behalf -->

## Quick connect

<p>
  <a href="mailto:hello.manojchunduru@gmail.com"><img src="https://img.shields.io/badge/&#9993;&#65039;%20Email-0D1117?style=for-the-badge" alt="Email"/></a>
  <!-- [VERIFY] LinkedIn slug -->
  <a href="http://www.linkedin.com/in/manoj-kumar-b4984762"><img src="https://img.shields.io/badge/&#128188;%20LinkedIn-0D1117?style=for-the-badge" alt="LinkedIn"/></a>
  <a href="https://github.com/ManojKumarChunduru?tab=repositories"><img src="https://img.shields.io/badge/&#128230;%20All%20repos-0D1117?style=for-the-badge" alt="Repositories"/></a>
</p>

The fastest way to evaluate me: `git clone` any pinned repo and run the three-command quickstart.

<!-- profile views counter: low signal, some recruiters ignore it; delete this line to remove -->
<img src="https://komarev.com/ghpvc/?username=ManojKumarChunduru&style=flat-square&color=4cc9f0" alt="Profile views"/>
