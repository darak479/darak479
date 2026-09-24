<!-- ========================================================= -->
<!--  README for github.com/darak479  |  paste into darak479/darak479/README.md  -->
<!--  Lines marked "ADD METRIC" are optional slots for REAL numbers only.        -->
<!-- ========================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:7C3AED,100:06B6D4&height=230&section=header&text=Nihal%20Darak&fontSize=64&fontColor=ffffff&animation=twinkling&fontAlignY=36&desc=analytics%20engineer%20%E2%80%A2%20data%20whisperer%20%E2%80%A2%20pipeline%20person&descAlignY=58&descSize=18" width="100%"/>

<a href="https://www.linkedin.com/in/nihaldarak512/">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1100&color=A78BFA&center=true&vCenter=true&width=640&lines=I+ask+%22why%22+before+I+write+the+SQL;If+I+do+it+twice%2C+it+becomes+a+pipeline;dbt+%2B+Snowflake+%2B+Airflow+%3D+my+love+language;Turning+%22can+you+pull+this%3F%22+into+self-serve;Next+chapter+loading...+open+to+work" alt="typing intro"/>
</a>

<br/>

<img src="https://img.shields.io/badge/STATUS-open%20to%20work-22C55E?style=for-the-badge&logo=statuspage&logoColor=white"/>
<a href="https://www.linkedin.com/in/nihaldarak512/"><img src="https://img.shields.io/badge/LinkedIn-let's%20talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:nihal@myworkgmail.com"><img src="https://img.shields.io/badge/Email-say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Based%20in-Waukesha%2C%20WI-F59E0B?style=for-the-badge&logo=googlemaps&logoColor=white"/>

</div>

---

## `$ whoami`

```yaml
name:        Nihal Darak
role:        Analytics Engineer  # 5+ years
based_in:    Waukesha, Wisconsin 🧀
worked_at:   [JPMorgan Chase, Charles Schwab, S&P Global]
industries:  [financial services, market intelligence, telecommunications]
education:   M.S. Business Analytics @ UT Dallas
superpower:  turning "hey, can you pull this for me?" into a dashboard nobody has to ask for again
looking_for: Analytics Engineer / Data Engineer / BI Engineer roles at teams that move fast
off_duty:    [pickleball for hours, hunting down new cafes, chasing waterfalls]
```

---

## 📊 Impact Dashboard

<div align="center">

<img src="https://img.shields.io/badge/5%2B%20YEARS-in%20data-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/3%20COMPANIES-JPMC%20%E2%80%A2%20Schwab%20%E2%80%A2%20S%26P-06B6D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/3%20INDUSTRIES-finance%20%E2%80%A2%20market%20intel%20%E2%80%A2%20telecom-F472B6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/M.S.-Business%20Analytics-FACC15?style=for-the-badge"/>

</div>

| ⚡ Impact area | 🛠️ What that looks like in practice | 📌 Receipt |
| :-- | :-- | :-- |
| **Legacy → cloud** | Moving on-prem databases into Snowflake, BigQuery and S3, with modeled and tested layers on top instead of a lift-and-shift mess | Snowflake · BigQuery · S3 <!-- ADD METRIC: e.g. tables migrated, runtime before vs after --> |
| **Manual → automated** | Replacing hand-run scripts and spreadsheet refreshes with orchestrated, CI-tested pipelines | Airflow · GitHub Actions <!-- ADD METRIC: e.g. hours/week saved --> |
| **Data you can trust** | Severity-graded dbt tests that warn early and block loudly before bad data ever reaches a dashboard | [analytics-quality-pipeline](https://github.com/darak479/analytics-quality-pipeline) |
| **Governed self-serve BI** | Semantic models in Power BI and Tableau so analysts answer their own questions instead of waiting in a ticket queue | Power BI (DAX) · Tableau <!-- ADD METRIC: e.g. # of users or reports --> |
| **Finance-grade reconciliation** | SCD2 history, incremental facts, and auto-flagged breaks when numbers don't match the custodian | [portfolio-reconciliation-engine](https://github.com/darak479/portfolio-reconciliation-engine) |

<details>
<summary><b>🍕 where my week actually goes (vibes-based, not audited)</b></summary>
<br/>

```mermaid
%%{init: {'theme':'base','themeVariables':{'pie1':'#7C3AED','pie2':'#06B6D4','pie3':'#F472B6','pie4':'#FACC15','pie5':'#34D399','pieStrokeColor':'#0F172A','pieOuterStrokeColor':'#0F172A'}}}%%
pie
    title a normal week
    "Modeling + testing in dbt" : 35
    "Pipelines + orchestration" : 25
    "Talking to the business first" : 20
    "Shipping BI people actually open" : 15
    "Asking why two dashboards disagree" : 5
```

</details>

---

## 💼 How I Work (my operating system)

> **"The best dashboard is the one nobody has to ask me to update."**

<table>
<tr>
<td width="33%" valign="top">

### 🎯 Label the pain first
Before I pick a tool, I find out what's actually broken for the business and who is feeling it. The tech choice comes second.

</td>
<td width="33%" valign="top">

### 🔁 Twice = pipeline
If I do something by hand twice, it becomes a scheduled, tested job. Humans are for judgment, not for re-running scripts.

</td>
<td width="33%" valign="top">

### 🧪 Trust is a feature
A pipeline without tests is a rumor. Every model ships with tests and docs, so people can rely on the number, not just see it.

</td>
</tr>
</table>

---

## 🏗️ The Platform I Build

```mermaid
flowchart LR
    subgraph SRC["🗄️ Sources"]
        A1[Legacy on-prem DBs]
        A2[SaaS apps + APIs]
        A3[Files + market feeds]
    end
    subgraph ING["📥 Ingest"]
        B1[Fivetran]
        B2[Python · AWS Glue]
        B3[Spark · EMR]
    end
    subgraph WH["❄️ Store"]
        C1[(Snowflake)]
        C2[(BigQuery)]
        C3[(S3 lake)]
    end
    subgraph TR["🧱 Transform with dbt"]
        D1[staging] --> D2[intermediate] --> D3[marts]
    end
    subgraph SRV["📊 Serve"]
        E1[Power BI semantic model]
        E2[Tableau]
    end
    F([🧑‍💼 Business teams<br/>answering their own questions])

    SRC --> ING --> WH --> TR --> SRV --> F
    G{{⏱️ Airflow}} -. orchestrates .-> ING
    G -. orchestrates .-> TR
    H{{✅ tests + CI/CD}} -. guards .-> TR

    classDef purple fill:#7C3AED,stroke:#A78BFA,color:#fff
    classDef cyan fill:#0E7490,stroke:#06B6D4,color:#fff
    classDef pink fill:#BE185D,stroke:#F472B6,color:#fff
    classDef green fill:#047857,stroke:#34D399,color:#fff
    class D1,D2,D3 purple
    class C1,C2,C3 cyan
    class G,H pink
    class F green
```

---

## 📈 The Plot So Far

```mermaid
timeline
    title career speedrun
    2019 : Data Analyst Intern at S&P Global
    2020 : Data / Analytics Engineer at S&P Global
    2021 : B.Tech in Electronics + Communication Engineering
    2022 : Started M.S. Business Analytics at UT Dallas
    2024 : Graduated UT Dallas
         : Associate Analytics Engineer at Charles Schwab
    2025 : Analytics Engineer at JPMorgan Chase
    2026 : Next chapter loading 👀
         : Open to AE / DE / BI roles
```

---

## 🎖️ Receipts (things I built, not just claimed)

<table>
<tr>
<td width="50%" valign="top">

### 🧪 [Automated Data Quality Pipeline](https://github.com/darak479/analytics-quality-pipeline)

**The pain:** data quality checks that only happen when someone remembers to run them.

**The build:** dbt + DuckDB + GitHub Actions. Every push rebuilds the warehouse, runs the full test suite, and posts a readable report. Staging issues **warn**, mart issues **block**, and the mart layer actually dedupes instead of just flagging.

**The twist:** an optional AI-written summary that falls back to a deterministic report, because a pipeline should never break when an LLM call does.

`dbt` `DuckDB` `GitHub Actions` `Python` `Claude API`

</td>
<td width="50%" valign="top">

### 💰 [Portfolio Reconciliation Engine](https://github.com/darak479/portfolio-reconciliation-engine)

**The pain:** month-end close depends on someone catching when internal portfolio values drift from what the custodian reports.

**The build:** holdings rebuilt from trade logs with window functions, priced against a daily market feed in an incremental fact table, then compared to custodian statements. Anything off by more than 2% gets flagged.

**The twist:** a real SCD Type 2 snapshot of client allocations, proven end to end with a simulated rebalance, feeding a governed Power BI model with DAX measures.

`dbt` `BigQuery` `Fivetran` `Power BI` `SCD2`

</td>
</tr>
</table>

---

## 🛠️ My Stack, Arranged Like a Pipeline

<div align="center">
<img src="https://skillicons.dev/icons?i=python,aws,gcp,git,github,githubactions,vscode&theme=dark" />
</div>
<br/>

| 📥 Ingest | ❄️ Store | 🧱 Transform | ⏱️ Orchestrate | 📊 Serve |
| :-: | :-: | :-: | :-: | :-: |
| ![](https://img.shields.io/badge/Fivetran-0073FF?style=flat-square&logo=fivetran&logoColor=white) | ![](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) | ![](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat-square&logo=dbt&logoColor=white) | ![](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) | ![](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) |
| ![](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) | ![](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white) | ![](https://img.shields.io/badge/Advanced%20SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) | ![](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) | ![](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) |
| ![](https://img.shields.io/badge/AWS%20Glue-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) | ![](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white) | ![](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) | ![](https://img.shields.io/badge/CI%2FCD-6D28D9?style=flat-square&logo=git&logoColor=white) | ![](https://img.shields.io/badge/DAX%20%2B%20Power%20Query-F2C811?style=flat-square&logoColor=black) |
| ![](https://img.shields.io/badge/AWS%20EMR-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) | ![](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) | ![](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | ![](https://img.shields.io/badge/AWS%20Serverless-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white) | ![](https://img.shields.io/badge/Data%20Governance-34D399?style=flat-square&logoColor=white) |

---

## 🔭 Right Now

- 🔨 **Building** public dbt projects that mirror real production patterns (see receipts above)
- 📚 **Studying for** the Claude Certified Architect (Foundations) exam
- 🤖 **Using AI** to speed up docs, tests and code review, not to replace engineering judgment
- 💬 **Ask me about** SCD2 snapshots, incremental models, or why your two dashboards show different revenue
- 🏓 **Hot take:** pickleball is the only cardio I will voluntarily do for three hours

> 🤝 **Hiring?** If your team is growing fast and your data still lives in spreadsheets and Slack threads, I'd love to talk. [LinkedIn](https://www.linkedin.com/in/nihaldarak512/) is the fastest way to reach me.

---

## 🐍 Automation in Action

This snake is a scheduled GitHub Action that regenerates itself every day. Same instinct as my day job: if it can run on a schedule, it shouldn't need a human.

<div align="center">

<img alt="contribution snake" src="https://raw.githubusercontent.com/darak479/darak479/output/github-contribution-grid-snake.svg" />

</div>

<details>
<summary><b>📊 GitHub stats</b></summary>
<br/>
<div align="center">
<img height="165" src="https://github-stats-extended.vercel.app/api?username=darak479&show_icons=true&theme=tokyonight&hide_border=true&title_color=A78BFA&icon_color=06B6D4" />
<img height="165" src="https://streak-stats.demolab.com/?user=darak479&theme=tokyonight&hide_border=true&ring=7C3AED&fire=F472B6&currStreakLabel=A78BFA" />
</div>
</details>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=darak479&color=7C3AED&style=for-the-badge&label=PROFILE+VIEWS" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:7C3AED,100:0F172A&height=120&section=footer" width="100%"/>

</div>
