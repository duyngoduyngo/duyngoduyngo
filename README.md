<!--
  GitHub Profile README — duyngoduyngo
  Repo: duyngoduyngo/duyngoduyngo  (public, named exactly your username)

  This README is fully self-contained — no image files to commit.
  Safe to delete from the repo: assets/ (lineage.svg, pipeline.svg), lineage.html

  Still to check: the dates in the Professional Journey table.
-->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3f6212,30:84cc16,55:facc15,80:fde047,100:fef3c7&height=180&section=header&text=Duy%20Ngo&fontSize=52&fontColor=1a2e05&fontAlignY=32&desc=Analytics%20Engineer%20in%20the%20making&descAlignY=54&descSize=18" width="100%" alt="Header" />
</div>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&duration=3000&pause=1000&color=CA8A04&center=true&vCenter=true&width=800&lines=Data+Analyst+%E2%86%92+Analytics+Engineer;SQL+%7C+Python+%7C+dbt+%7C+Power+BI+%7C+Modern+Data+Stack;Banking+%26+Airline+Domain+%E2%80%A2+Finance+Background;Turning+Spreadsheet+Chaos+into+Modelled+Data"/>
</p>

<p align="center">
  <a href="mailto:duyngoduyngo@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/duyngoduyngo/"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>&nbsp;
  <a href="https://sites.google.com/view/duy-ngo-portfolio"><img src="https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=google&logoColor=white"/></a>&nbsp;
  <a href="https://github.com/duyngoduyngo?tab=repositories"><img src="https://img.shields.io/badge/Projects-000000?style=for-the-badge&logo=github&logoColor=white"/></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=duyngoduyngo&style=for-the-badge&color=CA8A04" alt="views"/>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 🧭 About Me

```yaml
analytics_engineer_in_transition:
  now: "Reporting & data analytics inside a bank's technology procurement team"
  next: "Analytics Engineering — owning the transformation layer, not just the dashboard"
  philosophy: "If only one person can rebuild the report, it isn't a data product yet."
  background:
    - "B.A. Finance & Banking — Academy of Finance"
    - "Airline distribution & planning (Sabre Vietnam)"
    - "Banking operations & technology procurement (VPBank, Agribank)"
  what_i_actually_do:
    reporting_automation:
      - "Extract from SAP Fiori, reshape in Power Query, publish in Power BI"
      - "Replaced manual monthly reporting cycles with refreshable models"
    analysis:
      - "Unit economics, cohort retention, conversion funnels, market basket"
      - "Vendor spend, procurement cycle time, budget variance"
    learning_in_public:
      - "Rebuilding my Power Query logic as version-controlled dbt models"
      - "Star-schema modelling, dbt tests, Git-based analytics workflow"
  why_analytics_engineering: >
    Most of my time was never spent analysing — it was spent transforming.
    That layer lived in my head and in ten thousand clicks. AE is the
    discipline that turns it into code someone else can read.
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 💼 Professional Journey

<div align="center">
  <table width="100%">
    <tr>
      <td align="center" valign="top" width="22%">
        <sub>Internship</sub><br /><br />
        <img src="https://www.google.com/s2/favicons?sz=32&domain=agribank.com.vn" width="24" height="24" /><br /><br />
        <a href="https://www.agribank.com.vn/"><b>Agribank</b></a><br />
        <sub>Banking Intern</sub>
      </td>
      <td align="center" valign="middle" width="2%">➔</td>
      <td align="center" valign="top" width="22%">
        <sub>2020 - 2025</sub><br /><br />
        <img src="https://www.google.com/s2/favicons?sz=32&domain=sabre.com" width="24" height="24" /><br /><br />
        <a href="https://www.sabre.com/"><b>Sabre Vietnam</b></a><br />
        <sub>Planning &amp; Data Analytics</sub>
      </td>
      <td align="center" valign="middle" width="2%">➔</td>
      <td align="center" valign="top" width="22%">
        <sub>2025 - </sub><img src="https://img.shields.io/badge/Present-2ea44f?style=flat-square" height="14" valign="middle" /><br /><br />
        <img src="https://www.google.com/s2/favicons?sz=32&domain=vpbank.com.vn" width="24" height="24" /><br /><br />
        <a href="https://www.vpbank.com.vn/"><b>VPBank</b></a><br />
        <sub>Technology Procurement &amp; Reporting</sub>
      </td>
      <td align="center" valign="middle" width="2%">➔</td>
      <td align="center" valign="top" width="22%">
        <sub>Target</sub><br /><br />
        <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" height="24" /><br /><br />
        <b>Analytics Engineer</b><br />
        <sub>Banking / FinTech</sub>
      </td>
    </tr>
  </table>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 🛠️ Tech Stack &amp; Ecosystem

The honest version of my stack is a migration in progress. The top lane is what ships at work today; the bottom lane is the same pattern built properly as code, in a repo you can clone and run.

```mermaid
flowchart LR
    subgraph now [" RUNS TODAY — clicks, not code "]
        direction LR
        A["sap_fiori<br/>SAP extract"] --> B["power_query<br/>reshape · clean"] --> C["power_bi<br/>leadership report"]
    end

    subgraph next [" BUILT AS CODE — smarttoys-analytics-pipeline "]
        direction LR
        D["dlt → DuckDB<br/>6 raw tables"] --> E["bronze_<br/>cast · clean<br/>6 views"] --> F["silver_<br/>business logic<br/>3 views"] --> G["gold_<br/>marts<br/>4 tables"] --> H["93 data tests<br/>on every build"]
    end

    C -.->|"same pattern"| E

    style A fill:#1f2416,stroke:#6b7d3a,stroke-width:1.5px,color:#e8e6d9
    style B fill:#1f2416,stroke:#6b7d3a,stroke-width:1.5px,color:#e8e6d9
    style C fill:#1f2416,stroke:#facc15,stroke-width:2.5px,color:#fef3c7
    style D fill:#1f2416,stroke:#84cc16,stroke-width:1.5px,color:#e8e6d9
    style E fill:#1f2416,stroke:#84cc16,stroke-width:1.5px,color:#e8e6d9
    style F fill:#1f2416,stroke:#84cc16,stroke-width:1.5px,color:#e8e6d9
    style G fill:#1f2416,stroke:#facc15,stroke-width:2.5px,color:#fef3c7
    style H fill:#1f2416,stroke:#3f6212,stroke-width:1.5px,color:#d9e5c4

    style now  fill:none,stroke:none,color:#8a8a8a
    style next fill:none,stroke:none,color:#8a8a8a

    linkStyle 0,1 stroke:#facc15,stroke-width:2px
    linkStyle 2,3,4,5 stroke:#84cc16,stroke-width:2px
    linkStyle 6 stroke:#a16207,stroke-width:1.5px
```

### Where each tool actually comes from

| Layer | Tools | Where I've used them |
|---|---|---|
| **Transform &amp; query** | <img src="https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white"/> <img src="https://img.shields.io/badge/Power_Query-217346?style=flat-square&logo=microsoft-excel&logoColor=white"/> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/dlt-2C3E50?style=flat-square&logoColor=white"/> <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black"/> | SQL and Power Query daily at VPBank; dbt Core 1.12 + dlt + DuckDB on the SmartToys pipeline; pandas across the analysis repo |
| **Modelling** | `medallion` `bronze → silver → gold` `dbt tests` `dbt docs` | 13 models and 93 automated tests shipped in the SmartToys pipeline; every mart cross-checked against an independent pandas run |
| **Warehouse &amp; platform** | <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white"/> <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white"/> <img src="https://img.shields.io/badge/Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white"/> <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white"/> | Bootcamps on all three; evaluated them as platforms while doing tech procurement in a bank |
| **BI &amp; visualization** | <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/> <img src="https://img.shields.io/badge/Superset-0073B7?style=flat-square&logo=apache-superset&logoColor=white"/> <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/> <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white"/> | Power BI in production for leadership reporting; plotly throughout SmartToys |
| **Orchestration** | <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white"/> | Learning. No production DAG yet — and on the SmartToys pipeline I argued against adding one, since a static export gives it nothing to solve |
| **Version control** | <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/> | Every project repo here; CI on the dbt rebuild |
| **Business systems** | <img src="https://img.shields.io/badge/SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white"/> <img src="https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white"/> | SAP Fiori extracts (QT0304) and Power Apps at VPBank |

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 📂 Featured Projects

Two repos, one dataset, deliberately built in that order: analyse it first, then make the analysis reproducible.

### 🏗️ [SmartToys Analytics Pipeline](https://github.com/duyngoduyngo/smarttoys-analytics-pipeline) — dlt · DuckDB · dbt

<p>
  <img src="https://img.shields.io/badge/13-dbt_models-FF694B?style=flat-square"/>
  <img src="https://img.shields.io/badge/93-data_tests-3FB950?style=flat-square"/>
  <img src="https://img.shields.io/badge/11/11-metrics_matched-CA8A04?style=flat-square"/>
  <img src="https://img.shields.io/badge/dlt-2C3E50?style=flat-square"/>
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black"/>
  <img src="https://img.shields.io/badge/dbt_Core_1.12-FF694B?style=flat-square&logo=dbt&logoColor=white"/>
</p>

Turns the exploratory notebook below into a warehouse anyone can clone and rebuild. Six CSVs land in DuckDB through a dlt pipeline, then move through a medallion stack — 6 bronze views, 3 silver views, 4 gold marts — with tests running in dependency order so a failure stops bad data before it reaches a mart.

**What I'd point an interviewer at:**

- **Cross-validation.** Eleven metrics computed twice on fully independent paths — once in pandas, once in SQL — agree exactly, down to `$1,938,509.75` gross revenue and a 0.84% month-1 retention mean. That's the evidence the models are right, not just green.
- **Tests that replaced hand-checks.** Three problems handled manually in the notebook (session fan-out, multiple refunds per line item, unverified foreign keys) became `unique`, `relationships` and singular tests. In a notebook, forgetting a check produces no signal at all.
- **A documented failure.** One build reported `PASS=54` and looked healthy while 16 tests silently never ran — a truncated `schema.yml` meant dbt couldn't bind them, and it warned instead of erroring. The README explains the blind spot and the habit adopted afterwards: verify the `Found X data tests` count moves after every schema change.
- **A layer deliberately left out.** No orchestrator, because the source is a static export. Two gold models also read straight from bronze, skipping silver, since a silver model used in exactly one place earns nothing.

### 🧸 [SmartToys E-commerce Analytics](https://github.com/duyngoduyngo/smarttoys-ecommerce-analytics) — the analysis it came from

<p>
  <img src="https://img.shields.io/badge/472,871-sessions-38BDF8?style=flat-square"/>
  <img src="https://img.shields.io/badge/32,313-orders-A78BFA?style=flat-square"/>
  <img src="https://img.shields.io/badge/1.1M+-pageviews-34D399?style=flat-square"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/>
</p>

A three-year business review across six relational tables. The question was never "what does the dashboard say" — it was why gross revenue and actual profit had drifted apart.

| Finding | Evidence | So what |
|---|---|---|
| **No customer lifecycle** | 98.14% bought exactly once; revenue per customer $61.16 ≈ AOV | Every unit of growth had to be repurchased with new ad budget |
| **Mobile is the expensive leak** | 30.8% of traffic at 3.09% CR vs desktop 8.50% — gap holds across *all four* sources, so it's the interface, not traffic quality | Closing it is worth roughly **$473K** |
| **Best product is buried** | Highest net margin (67.08%), lowest refunds, best add-to-cart — but 62× fewer category clicks than the flagship | Merchandising problem, not a product problem |

Eight prioritised recommendations, each tied to a metric and an owning team — plus a section on where the analysis **can't** support a conclusion: RFM frequency capped at three values, market-basket lift below 1 across every pair, no refund-reason field in the source.

`Unit economics` · `RFM` · `Cohort retention` · `Sankey` · `Conversion funnel` · `Market basket`

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 📈 Activity &amp; Stats

<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=duyngoduyngo&theme=tokyonight&show_icons=true&bg_color=0b0f19&title_color=CA8A04&text_color=e5e7eb&icon_color=84CC16&border_color=1f2937" width="45%" alt="GitHub Stats" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=duyngoduyngo&layout=compact&theme=tokyonight&langs_count=8&bg_color=0b0f19&title_color=CA8A04&text_color=e5e7eb&border_color=1f2937" width="35%" alt="Top Languages" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 🎓 Certifications &amp; Training

| Credential | Provider | Status |
|---|---|---|
| dbt Fundamentals | dbt Labs | ✅ Completed |
| Data Analyst in Python | DataCamp | ✅ Completed |
| Associate Data Analyst in SQL | DataCamp | ✅ Completed |
| Snowflake Bootcamp — modern data warehousing | Snowflake | ✅ Completed |
| Databricks Lakehouse Bootcamp | Databricks | ✅ Completed |
| Microsoft Fabric Bootcamp | Microsoft | ✅ Completed |
| B.A. Finance &amp; Banking | Academy of Finance | 🎓 Graduated |
| TOEIC 840 | ETS | ✅ Certified |

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 🧩 GET /api/v1/fun-facts

```json
{
  "status": "Open to Analytics Engineer / Senior Data Analyst roles",
  "location": "Hanoi, Vietnam — remote friendly",
  "languages": ["Vietnamese (native)", "English (TOEIC 840)"],
  "domains": ["Banking", "Airline distribution", "Procurement", "E-commerce"],
  "favorite_stack": ["SQL", "dbt", "Power BI"],
  "always_include": "A section on what the data cannot tell you",
  "fun_fact": "Started in Finance, detoured through airline planning, landed in data"
}
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:fef3c7,25:fde047,50:facc15,75:84cc16,100:3f6212&height=140&section=footer&text=Let's%20build%20something%20with%20data&fontSize=22&fontColor=1a2e05&fontAlignY=70" width="100%" alt="Footer" />
</div>
