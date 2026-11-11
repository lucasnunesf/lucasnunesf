### Hi, I'm Lucas

**Data Engineer | Data & BI Analyst** · SQL · Python · Power BI · Azure · Microsoft Fabric · dbt

I work where operations meet data: ERP systems, legacy databases and spreadsheets that nobody wants to reconcile by hand.
I turn that into automated pipelines and dashboards people actually use. 3+ years at **Toyota**, **Bosch** and **AC Metais**, working daily in English with teams in Japan, Thailand and the United States.

📍 EU citizen (no visa required), **based in Lisbon from February 2027** · [Download CV (PDF)](https://github.com/lucasnunesf/CV/blob/main/Lucas_Fernandes_Nunes_CV.pdf)

---

### 🛠️ Stack

![Python](https://img.shields.io/badge/Python%20%2F%20PySpark-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI%20%2B%20DAX-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-117865?style=flat)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![SAP](https://img.shields.io/badge/SAP%20ERP-0FAAFF?style=flat&logo=sap&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-867DB1?style=flat)

---

### 📈 Impact so far

- **5 h 10 min → 8 min 38 s per order (up to 97% faster)**: automated PR/PO creation in SAP ERP with Python + VBA at **Toyota do Brasil**, selected as a **top 3 Toyota Business Practices project**
- **163 supplier files → 1 dashboard**: cost reduction tracking that replaced days of monthly manual work with one refresh
- **30 spreadsheets → 1 Power BI view**: replaced a 30-spreadsheet reporting routine with a single report
- **Weekly executive dashboards** for Engineering Change (ECI) tracking, fed by Python + SQL extractions from the legacy SIQ system
- **ERP migration (TOIOS → SAP)**: standardized databases and data workflows across the TLAC region (Brazil and Argentina)
- **Azure data platform at AC Metais**: delivered the Power BI reporting layer on top of the gold models and supported ingestion into ADLS Gen2 and transformations with PySpark (Microsoft Fabric) and dbt
- **−60% sheet metal lookup time, −15% scrap**: Power BI dashboards integrated with the Kiron ERP at **AC Metais**
- **≈60% fewer inventory losses and rework** at **Bosch**: contributed to a QR-code based prototype inventory solution, plus Python scripts parsing emails into Power BI for real-time stock visibility

### 🚀 Projects

Every project runs on synthetic data and has automated tests. All of them except industrial-data-platform also run those tests in CI on every commit.

**Data engineering**

| Project | What it does | Tech stack |
|---|---|---|
| [industrial-data-platform](https://github.com/lucasnunesf/industrial-data-platform) ✅ MVP | End-to-end rebuild of the Azure + Microsoft Fabric data platform I worked on at AC Metais: plant simulator and PostgreSQL ERP → incremental ingestion to ADLS Gen2 (bronze) → PySpark in Fabric (silver) → dbt star schema with tests (gold) → Power BI on bottlenecks, lead time and on-time delivery. Infrastructure in Terraform. Next: streaming, Airflow and CI/CD | PostgreSQL · Python · Docker · ADLS Gen2 · Microsoft Fabric · PySpark · Delta Lake · dbt · Terraform · Power BI |
| [pipeline-cost-reduction-powerbi](https://github.com/lucasnunesf/pipeline-cost-reduction-powerbi) | 150 supplier Excel files into one star model in about 3 s: 25+ kinds of defects cleaned, every fix logged, forecast vs fiscal year target. 48 tests | Python · SQL (CTEs, window functions) · SQLite · pytest · Power BI |
| [pipeline-eng-change-powerbi](https://github.com/lucasnunesf/pipeline-eng-change-powerbi) | Replaces ~20 min of weekly spreadsheet work with one command: business rules in SQL views and a weekly snapshot fact table that keeps history. 27 tests | Python · pandas · SQL · SQLite · pytest · Power BI |

**BI & Analytics dashboards**

| Project | What it shows | Tech stack |
|---|---|---|
| [production-planning-dashboard](https://github.com/lucasnunesf/production-planning-dashboard) | Capacity vs load by work center: the shop runs at 76%, but welding is the bottleneck, over 100% in 7 weeks and up to 138% | Power BI · DAX · Power Query · TMDL/PBIR · Python · pytest |
| [sheet-metal-intake-dashboard](https://github.com/lucasnunesf/sheet-metal-intake-dashboard) | Supplier scorecard for sheet metal receiving: the cheapest mill is 10–12% cheaper but on time only 64% of the time, vs 95% for the best service center | Power BI · DAX · Power Query · TMDL/PBIR · Python · pytest |
| [laser-remnant-inventory](https://github.com/lucasnunesf/laser-remnant-inventory) | Laser cutting offcuts: stock, aging and reuse vs scrap. With a control process, reuse goes from 20.5% to 74.1% | Power BI · DAX · Power Query · TMDL/PBIR · Python · pytest |

**Databases & process automation**

| Project | What it does | Tech stack |
|---|---|---|
| [prototype-inventory-sql](https://github.com/lucasnunesf/prototype-inventory-sql) | QR code part tracking with the business rules inside PostgreSQL: triggers, procedures for count closing, a reporting mart for Power BI, roles and row-level security, 12 analysis queries. 31 SQL checks + 47 tests | PostgreSQL · PL/pgSQL · SQL · Python · pytest · GitHub Actions |
| [sap-automation](https://github.com/lucasnunesf/sap-automation) | Creates requisitions and POs in SAP from 5 supplier formats: up to 97% faster, 5 h 10 min → 8 min 38 s per order (Toyota top 3 project). Parser, business rule and end-to-end tests | Python · VBA · SAP GUI · Excel · pytest |

**Embedded**

| Project | What it does | Tech stack |
|---|---|---|
| [robot-sumo-competition](https://github.com/lucasnunesf/robot-sumo-competition) | Sumo robot firmware with a state machine and a match simulator that found a rule losing wins: 97% of simulated matches won instead of 72% (simulator results, not a real competition) | C++17 · Arduino · ESP32 · GitHub Actions |

### 📊 Case studies

Full write-ups on Notion (problem, approach and results; all data anonymized or synthetic):

- [**Industrial Data Platform**](https://lucasnunesf.notion.site/Industrial-Data-Platform-415917c89c1781d5803ff41dbe762350): the end-to-end Azure + Microsoft Fabric lakehouse, from the ERP to the Power BI dashboard
- [**Automating the purchasing cycle in SAP**](https://lucasnunesf.notion.site/Automating-the-purchasing-cycle-in-SAP-a73917c89c1783d49fb301b2a65ab928): requisitions and purchase orders created automatically, cutting time per order by up to 97%
- [**Automotive Cost Reduction Tracking**](https://lucasnunesf.notion.site/Automotive-Cost-Reduction-Tracking-3de917c89c1780c38feccacc9238ab6e): 163 supplier files brought into one Power BI dashboard, showing the gap to the fiscal year target mid-year
- [**Power BI – Engineering Change Tracking**](https://lucasnunesf.notion.site/Power-BI-Engineering-Change-Tracking-3e5917c89c1780978911c01acd0b21b3): two dashboards for change requests, with field parameters switching six approval stages on one page
- [**Production planning: capacity vs load**](https://lucasnunesf.notion.site/Production-planning-capacity-vs-load-415917c89c17811d9e26f20595fd2a08): load vs capacity by work center and week, with the welding bottleneck the shop total hides
- [**Sheet metal intake: supplier performance**](https://lucasnunesf.notion.site/Sheet-metal-intake-supplier-performance-415917c89c1781e5a657d396b4fd7caf): price next to on-time, fill rate and quality for each sheet metal supplier
- [**Laser remnant inventory**](https://lucasnunesf.notion.site/Laser-remnant-inventory-415917c89c17816ea8def6a95caba375): laser offcuts from cut to reuse or scrap, before and after a control process
- [**Tracking prototype parts with QR codes**](https://lucasnunesf.notion.site/Tracking-prototype-parts-with-QR-codes-81a917c89c17830b82b38101d66af8e3): the QR code → form → spreadsheet process introduced at Bosch, which cut inventory losses and rework by about 60%

→ [Full portfolio](https://lucasnunesf.notion.site/Lucas-Nunes-Data-BI-Analyst-3de917c89c178092885cf639b619767b)

### 🎓 Education & training

- **Bachelor's Degree in Engineering**, FACENS (2022–2026) · **Technical Degree in Business Intelligence and Administration**, ETEC (2020–2022)
- **Microsoft Power BI Data Analyst** – Professional Certificate course completed, Microsoft via Coursera (2026): Power Query ETL, star schema modeling and DAX
- **IBM Data Engineering** – Professional Certificate course, IBM via Coursera (2026)
- **Microsoft Fabric Analytics Engineer (DP-600)**: exam scheduled for December 21, 2026
- 🇧🇷 Portuguese (native) · 🇬🇧 English (professional working proficiency, CEFR B2)

### 🤖 Beyond data

Led the design and assembly of combat robots at **Omegabotz (FACENS)**, programming microcontroller and motor control logic in C++ and analyzing real-time telemetry data. **2nd place at an international championship in Greece.** Also built data acquisition routines for the **SAE Formula/Baja** team and coordinate the automation and electrical sub-teams at **Falcons Aerodesign**. Competing taught me the same thing the factory did: a system is only as good as the data you can read from it while it runs.

### 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasfernandesnunes)
[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?style=flat&logo=notion&logoColor=white)](https://lucasnunesf.notion.site/Lucas-Nunes-Data-BI-Analyst-3de917c89c178092885cf639b619767b)
[![Email](https://img.shields.io/badge/lucasnunes100f@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:lucasnunes100f@gmail.com)
[![CV](https://img.shields.io/badge/Download%20CV-PDF-1F3864?style=flat&logo=readdotcv&logoColor=white)](https://github.com/lucasnunesf/CV/blob/main/Lucas_Fernandes_Nunes_CV.pdf)
