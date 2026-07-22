<h1 align="center">Hi, I'm Rishav Kumar 👋</h1>
<h3 align="center">Data Analyst · Power BI Developer · Builder of Power BI Automation Tools</h3>

<p align="center">
Microsoft-certified (PL-300) Data Analyst who turns raw, messy data into decisions —
<br/>and builds the tools that automate the manual grind behind Power BI.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rishav98kumar">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:kumar98rishav@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://dax-workbench.onrender.com/">
    <img src="https://img.shields.io/badge/Try-DAX%20Workbench-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="DAX Workbench"/>
  </a>
  <a href="https://dax-architect.onrender.com/">
    <img src="https://img.shields.io/badge/Try-DAX%20Architect-0078D4?style=for-the-badge&logo=powerbi&logoColor=white" alt="DAX Architect"/>
  </a>
</p>

---

### 🔗 Live Tools — Try Them Now (no install)

| Tool | What it does | Link |
|---|---|---|
| **⚡ DAX Architect** | Define a data model, describe a business question in plain English ("YoY growth %", "profit margin %", "running total"), and get structured, ready-to-paste DAX. 25+ patterns. Runs 100% in your browser — no Power BI, no internet needed. | **[dax-architect.onrender.com](https://dax-architect.onrender.com/)** |
| **🔧 DAX Workbench** | A Power BI External Tool that connects to your **live** open model, writes and *verifies* DAX on Microsoft's own engine, optimizes measures with before/after benchmarks, and deploys them back — deterministically. | **[dax-workbench.onrender.com](https://dax-workbench.onrender.com/)** |

---

### 🚀 About Me

- 📊 **Data Analyst / Power BI Developer** with 4+ years turning medical, legal, and insurance data into dashboards that drive decisions.
- 🧩 I own the full pipeline: **SQL → Power Query ETL → star-schema modeling → DAX → RLS → published Power BI Service.**
- 🛠️ **I build Power BI productivity tools** — shipped solo using AI-assisted development. My flagship, **DAX Workbench**, is a *deterministic* measure engine (no LLM in the DAX path) that writes, verifies, and optimizes DAX against your live model.
- 🏅 **Microsoft Certified: Power BI Data Analyst Associate (PL-300)** · Gold Medalist, M.Sc. Biomedical Science.
- 🌱 Currently deepening **Microsoft Fabric** and **Snowflake ELT**.

---

### 🛠️ Tech Stack

**BI & Analytics**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query%20(M)-F2C811?style=flat&logo=powerbi&logoColor=black)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=flat&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)

**Data & Databases**
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Tools & Automation**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%208-512BD4?style=flat&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

### 📌 Featured Projects

#### ⚡ [DAX Architect](https://dax-architect.onrender.com/) — *live, browser-only*
**From business question to structured DAX** — no Power BI or install required. Define your tables, columns, and relationships, describe what you want to calculate, and get clean, structured DAX for 25+ patterns (SUM, YoY/QoQ/MoM %, YTD/QTD/MTD, running total, rank, % of total, moving average, churn, retention, CLV, budget-vs-actual, and more). Everything runs locally in the browser — nothing is uploaded.

#### 🔧 [DAX Workbench](https://dax-workbench.onrender.com/) — *live*
A measure workbench that launches from **Power BI Desktop's own External Tools ribbon**. It reads the model you have open — real tables, real rows, real measures — writes the DAX, verifies it on Microsoft's own engine, optimizes it, and deploys it straight back.

- **Deterministic, not AI-guessed** — natural language is resolved against your live model; it *cannot* invent a column or a value. Every candidate is previewed and verified on the same Analysis Services engine your report runs on.
- **DAX Architect** — describe a measure in plain English, get ranked build plans (time intelligence, `SUMX`/`RELATED`, `VAR`/`RETURN`, `USERELATIONSHIP`).
- **Measure Factory** — one numeric field → a full analytical suite (YTD, prior year, YoY %, moving average, running total, rank) in a single pass.
- **Optimizer** — deterministic rewrites (`FILTER`→predicate, `COUNTROWS(FILTER())`→`CALCULATE`, bare `/`→`DIVIDE`), each proven by a cold-cache before/after benchmark on live data.
- **Model Doctor** — audits the live model for missing format strings, costly filters, and missing `DIVIDE()`, with one-click fixes written back to Desktop.
- **Architecture:** 17,000+ lines of strict TypeScript (Clean Architecture) + an 835-line C# / .NET 8 bridge (TOM/ADOMD) shipped as a single self-contained exe. Runs fully offline — your data never leaves the machine.

#### 🎨 [BI Visual Design](https://github.com/kumar98rishav-oss/bi-visual-design)
A **design studio for Power BI reports** that works directly on the `.pbip` files — mirrors every page and visual at its exact position, then restyles, recomposes, and lints.

- **Layout Lab** — drag/snap editing, alignment guides, z-order layers, 8 compose templates.
- **Style & Theme Lab** — one-click restyle of every visual via style packs + live theme editing.
- **Design Doctor** — linter for misalignments, off-palette colors, and inconsistent radii, with batch fixes.
- Reads field names, geometry, and formatting only — **zero data rows**. React 18 + TypeScript + Vite.

#### 📊 Power BI & Excel Analytics
- **[Hospital Business Intelligence Dashboard](https://github.com/kumar98rishav-oss/Hospital_Business_Intelligence_Dashboard_Power-BI)** — hospital operations, patient management, doctor performance, resource utilization.
- **[Power BI Retail Sales Analysis](https://github.com/kumar98rishav-oss/Power-BI-Retail-Sales-Analysis)** — multi-year retail trends, KPIs, markdowns, seasonality.
- **[UK Road Accident Analysis (Excel)](https://github.com/kumar98rishav-oss/Excel-UK-Road-Accident-Analysis-Dashboard)** — interactive Excel dashboard on UK accident trends & safety factors.

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kumar98rishav-oss&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kumar98rishav-oss&layout=compact&theme=default&hide_border=true" alt="Top Languages" height="165"/>
</p>

---

### 🏆 Certifications

- **Microsoft Certified: Power BI Data Analyst Associate (PL-300)** — Microsoft
- **SQL (Advanced)** — HackerRank

---

<p align="center"><i>📊 Turning raw data into decisions — and automating the boring parts.</i></p>
