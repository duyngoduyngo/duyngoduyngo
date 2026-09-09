<!--
  GitHub Profile README — duyngoduyngo
  Push to a repo named exactly: duyngoduyngo/duyngoduyngo (public)
  Only thing left to check: the dates in the Professional Journey table.
-->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:38bdf8,100:6366f1&height=180&section=header&text=Duy%20Ngo&fontSize=52&fontColor=f8fafc&fontAlignY=32&desc=Analytics%20Engineer%20in%20the%20making&descAlignY=54&descSize=18" width="100%" alt="Header" />
</div>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=800&lines=Data+Analyst+%E2%86%92+Analytics+Engineer;SQL+%7C+Python+%7C+dbt+%7C+Power+BI+%7C+Modern+Data+Stack;Banking+%26+Airline+Domain+%E2%80%A2+Finance+Background;Turning+Spreadsheet+Chaos+into+Modelled+Data"/>
</p>

<p align="center">
  <a href="mailto:duyngoduyngo@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/duyngoduyngo/"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>&nbsp;
  <a href="https://github.com/duyngoduyngo?tab=repositories"><img src="https://img.shields.io/badge/Projects-000000?style=for-the-badge&logo=github&logoColor=white"/></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=duyngoduyngo&style=for-the-badge&color=38BDF8" alt="views"/>
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

```mermaid
flowchart LR
    Source["📥 Source<br/><sub>SAP Fiori • Oracle • Excel • CSV</sub>"] --> Store["🛢️ Store<br/><sub>Snowflake • Databricks • MS Fabric • Postgres</sub>"]
    Store --> Transform["🔄 Transform<br/><sub>SQL • pandas • Power Query • dbt</sub>"]
    Transform --> Model["🧱 Model<br/><sub>Star schema • Staging → Marts</sub>"]
    Model --> BI["📊 BI &amp; Analytics<br/><sub>Power BI • Superset • Tableau • plotly</sub>"]

    Orchestrate["⚙️ Orchestrate<br/><sub>Airflow — learning</sub>"] -.-> Transform
    Quality["🛡️ Data Quality<br/><sub>dbt tests — learning</sub>"] -.-> Model
    CICD["🚀 Git &amp; CI/CD<br/><sub>Git • GitHub Actions — learning</sub>"] -.-> Transform

    style Source fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#f8fafc
    style Store fill:#0f172a,stroke:#c084fc,stroke-width:2px,color:#f8fafc
    style Transform fill:#0f172a,stroke:#fb7185,stroke-width:2px,color:#f8fafc
    style Model fill:#0f172a,stroke:#f59e0b,stroke-width:2px,color:#f8fafc
    style BI fill:#0f172a,stroke:#34d399,stroke-width:2px,color:#f8fafc
    style Orchestrate fill:#0f172a,stroke:#6366f1,stroke-width:2px,color:#94a3b8
    style Quality fill:#0f172a,stroke:#ec4899,stroke-width:2px,color:#94a3b8
    style CICD fill:#0f172a,stroke:#14b8a6,stroke-width:2px,color:#94a3b8
```

<sub>Solid boxes = used in real work. Dotted boxes = currently building fluency.</sub>

<br/>

<div align="center">
  <table width="100%">
    <tr>
      <td width="25%"><b>🔄 Transform &amp; Query</b></td>
      <td width="75%">
        <img src="https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
        <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
        <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R"/>
        <img src="https://img.shields.io/badge/Power_Query-217346?style=flat-square&logo=microsoft-excel&logoColor=white" alt="Power Query"/>
        <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt"/>
      </td>
    </tr>
    <tr>
      <td><b>🛢️ Store &amp; Platform</b></td>
      <td>
        <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" alt="Snowflake"/>
        <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks"/>
        <img src="https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Fabric"/>
        <img src="https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
        <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres"/>
      </td>
    </tr>
    <tr>
      <td><b>📊 BI &amp; Visualization</b></td>
      <td>
        <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI"/>
        <img src="https://img.shields.io/badge/Apache_Superset-0073B7?style=flat-square&logo=apache-superset&logoColor=white" alt="Superset"/>
        <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" alt="Tableau"/>
        <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" alt="Plotly"/>
        <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white" alt="Seaborn"/>
        <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white" alt="Excel"/>
      </td>
    </tr>
    <tr>
      <td><b>⚙️ Orchestrate &amp; Quality</b></td>
      <td>
        <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white" alt="Airflow"/>
        <img src="https://img.shields.io/badge/dbt_Tests-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt Tests"/>
        <img src="https://img.shields.io/badge/dbt_Docs-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt Docs"/>
      </td>
    </tr>
    <tr>
      <td><b>🚀 Git &amp; CI/CD</b></td>
      <td>
        <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
      </td>
    </tr>
    <tr>
      <td><b>🏢 Business Systems</b></td>
      <td>
        <img src="https://img.shields.io/badge/SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white" alt="SAP"/>
        <img src="https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white" alt="Power Apps"/>
        <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate"/>
      </td>
    </tr>
    <tr>
      <td><b>💻 IDE &amp; Tools</b></td>
      <td>
        <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" alt="VS Code"/>
        <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
        <img src="https://img.shields.io/badge/DBeaver-382923?style=flat-square&logo=dbeaver&logoColor=white" alt="DBeaver"/>
        <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Notion"/>
      </td>
    </tr>
  </table>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 📂 Featured Project

<div align="center">
  <a href="https://github.com/duyngoduyngo/smarttoys-ecommerce-analytics">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=duyngoduyngo&repo=smarttoys-ecommerce-analytics&theme=tokyonight&bg_color=0b0f19&title_color=06B6D4&text_color=e5e7eb&icon_color=8B5CF6&border_color=1f2937" alt="SmartToys E-commerce Analytics" />
  </a>
</div>

### 🧸 [SmartToys — Business Review &amp; Growth Strategy](https://github.com/duyngoduyngo/smarttoys-ecommerce-analytics)

A full business review of a 3-year e-commerce dataset: **472,871 sessions**, **32,313 orders**, 1.1M+ pageviews across 6 relational tables. The goal wasn't a dashboard — it was answering why gross revenue and actual profit had drifted apart.

**Three findings that changed the recommendations:**

- **The business has almost no customer lifecycle.** 98.14% of customers bought exactly once; revenue per customer ($61.16) is essentially the AOV. Every unit of growth had to be repurchased with new ad budget.
- **Mobile is the expensive leak.** 30.8% of traffic converting at 3.09% against desktop's 8.50% — and the gap holds across *all four* traffic sources, which points at the interface rather than traffic quality. Closing it is worth roughly **$473K**.
- **The most profitable product is buried.** Highest net margin (67.08%), lowest refund rate, best add-to-cart rate — but 62× fewer category-page clicks than the flagship. A merchandising problem, not a product problem.

Eight prioritised recommendations, each tied to a specific metric and an owning team. The README also documents where the analysis **can't** support a conclusion — RFM frequency capped at three values, market-basket lift below 1 across all pairs, no refund-reason field.

`Python` `pandas` `numpy` `plotly` `seaborn` · Unit economics · RFM · Cohort retention · Sankey · Funnel · Market Basket

<br/>

<div align="center">
  <table width="100%">
    <tr>
      <td width="50%" valign="top" align="center">
        <h4>🧱 dbt Analytics Project</h4>
        <sub><img src="https://img.shields.io/badge/In_Progress-f59e0b?style=flat-square"/></sub>
        <p>Rebuilding the SmartToys logic as layered dbt models — staging → intermediate → marts, with tests and docs.</p>
      </td>
      <td width="50%" valign="top" align="center">
        <h4>⚙️ Orchestrated Pipeline</h4>
        <sub><img src="https://img.shields.io/badge/Planned-64748b?style=flat-square"/></sub>
        <p>Scheduled ingestion + transformation with Airflow, versioned in Git with CI checks on every PR.</p>
      </td>
    </tr>
  </table>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 📈 Activity &amp; Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=duyngoduyngo&theme=tokyonight&show_icons=true&include_all_commits=true&count_private=true&bg_color=0b0f19&title_color=06B6D4&text_color=e5e7eb&icon_color=8B5CF6&border_color=1f2937" width="45%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=duyngoduyngo&layout=compact&theme=tokyonight&langs_count=8&bg_color=0b0f19&title_color=06B6D4&text_color=e5e7eb&border_color=1f2937" width="35%" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=duyngoduyngo&theme=tokyonight&hide_border=false&background=0b0f19&stroke=1f2937&ring=06B6D4&fire=8B5CF6&currStreakLabel=06B6D4" width="55%" alt="Streak" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

## 🎓 Certifications &amp; Training

```sql
SELECT credential, provider, status
FROM   my_learning
ORDER  BY relevance_to_analytics_engineering DESC;
```

| Credential | Provider | Status |
|---|---|---|
| Snowflake Bootcamp — modern data warehousing | Snowflake | ✅ Completed |
| Databricks Lakehouse Bootcamp | Databricks | ✅ Completed |
| Microsoft Fabric Bootcamp | Microsoft | ✅ Completed |
| Data Analyst in Python | DataCamp | 🔄 In progress |
| dbt Fundamentals | dbt Labs | 🔄 In progress |
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
  "unfair_advantage": "I sat in the meetings where the metric was defined",
  "always_include": "A section on what the data cannot tell you",
  "fun_fact": "Started in Finance, detoured through airline planning, landed in data"
}
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="8px" alt="Line Divider" />

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:38bdf8,100:0f172a&height=140&section=footer&text=Let's%20build%20something%20with%20data&fontSize=22&fontColor=f8fafc&fontAlignY=70" width="100%" alt="Footer" />
</div>
