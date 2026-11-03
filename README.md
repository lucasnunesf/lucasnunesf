### Hi, I'm Lucas

**Data Analyst | BI Analyst** · Mechanical Engineer · building toward **Analytics & Data Engineering**

I work where operations meet data: ERP systems, legacy databases and spreadsheets that nobody wants to reconcile by hand.
I turn that into automated pipelines and dashboards people actually use. 3+ years at **Toyota**, **Bosch** and **AC Metais**, working daily in English with teams in Japan, Thailand and the United States.

📍 EU citizen (no visa required), **based in Lisbon from February 2027** · [Download CV (PDF)](https://github.com/lucasnunesf/lucasnunesf/blob/main/Lucas_Fernandes_Nunes_CV.pdf)

---

### 🧰 Tools at a glance

| Area | Tools | Where to see it |
|---|---|---|
| **BI & analytics** | Power BI · DAX · Power Query · star schema · Excel | [Power BI case studies](https://lucasnunesf.notion.site/Lucas-Nunes-Data-BI-Analyst-3de917c89c178092885cf639b619767b) |
| **SQL** | PostgreSQL · SQLite · SQL Server · window functions, CTEs, views, triggers | [prototype-inventory-sql](https://github.com/lucasnunesf/prototype-inventory-sql) · [pipeline-cost-reduction-powerbi](https://github.com/lucasnunesf/pipeline-cost-reduction-powerbi) |
| **Python** | Python · PySpark · openpyxl · psycopg | [sap-automation](https://github.com/lucasnunesf/sap-automation) · [pipeline-eng-change-powerbi](https://github.com/lucasnunesf/pipeline-eng-change-powerbi) · [industrial-data-platform](https://github.com/lucasnunesf/industrial-data-platform) |
| **Cloud & lakehouse** | Azure (Data Lake Storage Gen2) · Azure Databricks · Delta Lake · medallion architecture | [industrial-data-platform](https://github.com/lucasnunesf/industrial-data-platform) |
| **Transformation & orchestration** | dbt (models + tests) · Apache Airflow · incremental ingestion | [industrial-data-platform](https://github.com/lucasnunesf/industrial-data-platform) |
| **DevOps** | Git (feature branches + pull requests) · Docker / Docker Compose · GitHub Actions (CI) | [industrial-data-platform](https://github.com/lucasnunesf/industrial-data-platform) · [prototype-inventory-sql](https://github.com/lucasnunesf/prototype-inventory-sql) |
| **Business systems & automation** | SAP ERP (SAP GUI scripting) · VBA · Salesforce · OutSystems | [sap-automation](https://github.com/lucasnunesf/sap-automation) |
| **Embedded** | C++ (ESP32) | [robot-sumo-competition](https://github.com/lucasnunesf/robot-sumo-competition) |

![Python](https://img.shields.io/badge/Python%20%2F%20PySpark-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI%20%2B%20DAX-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![SAP](https://img.shields.io/badge/SAP%20ERP-0FAAFF?style=flat&logo=sap&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-867DB1?style=flat)

---

### 📈 Impact so far

- **3–6 hours → under 5 minutes**: automated PR/PO creation in SAP ERP with Python + VBA at **Toyota do Brasil** (over 95% faster), selected as a **top 3 Toyota Business Practices project**
- **163 supplier files → 1 dashboard**: cost reduction tracking that replaced days of monthly manual work with one refresh
- **30 spreadsheets → 1 Power BI view**: replaced a 30-spreadsheet reporting routine with a single report
- **Weekly executive dashboards** for Engineering Change (ECI) tracking, fed by Python + SQL extractions from the legacy SIQ system
- **ERP migration (TOIOS → SAP)**: standardized databases and data workflows across the TLAC region (Brazil and Argentina)
- **−60% sheet metal lookup time, −15% scrap**: Power BI dashboards integrated with the Kiron ERP at **AC Metais**
- **≈60% fewer inventory losses and rework** at **Bosch**: contributed to a QR-code based prototype inventory solution, plus Python scripts parsing emails into Power BI for real-time stock visibility

### 🚀 Featured projects

| Project | What it shows |
|---|---|
| [**industrial-data-platform**](https://github.com/lucasnunesf/industrial-data-platform) *(in progress, MVP December 2026)* | End-to-end lakehouse on Azure for a metal fabrication plant, based on the real operation of AC Metais. **Built:** a PostgreSQL ERP (14 tables: orders, routings, production stage events, quality, shipping) running in Docker, fed by a deterministic Python plant simulator that adds history incrementally like a live ERP. **Next:** incremental load to Azure Data Lake Storage → Databricks bronze/silver (PySpark, Delta Lake) → dbt gold star schema with tests → Airflow → Power BI for lead time and bottlenecks. |
| [**sap-automation**](https://github.com/lucasnunesf/sap-automation) | **Payments Postponed**, a Toyota Business Practices project (top 3 of the 2026 internship programme), rebuilt on synthetic data: standardizes the payment flow for tooling, services and investments with a five-stage Python + VBA pipeline that normalizes five supplier formats, validates every line and creates requisitions and purchase orders in SAP GUI (3–6 hours → under 5 minutes). |
| [**pipeline-eng-change-powerbi**](https://github.com/lucasnunesf/pipeline-eng-change-powerbi) | Python + SQL pipeline replacing a manual weekly spreadsheet: staging, cleaning, business rules in SQL views, and a weekly snapshot that gives the Power BI report the history its source system never kept. |
| [**pipeline-cost-reduction-powerbi**](https://github.com/lucasnunesf/pipeline-cost-reduction-powerbi) | A redesign of how supplier Excel files could feed one cost reduction report, run on 150 synthetic files: all cleaning done in SQL, a data quality log recording every fix, a star model with a fiscal calendar, and a test that checks the result against the original data. |
| [**prototype-inventory-sql**](https://github.com/lucasnunesf/prototype-inventory-sql) | The QR-code tracking process for prototype parts at Bosch, rebuilt in PostgreSQL on synthetic data: business rules enforced by triggers, an append-only movement history, physical count reconciliation and nine analysis queries, all tested on every push with GitHub Actions. |

### 📊 Case studies

Full write-ups on Notion (problem, approach and results; all data anonymized or synthetic):

- [**Automating the purchasing cycle in SAP**](https://lucasnunesf.notion.site/Automating-the-purchasing-cycle-in-SAP-a73917c89c1783d49fb301b2a65ab928): requisitions and purchase orders created automatically, cutting document creation time by over 95%
- [**Automotive Cost Reduction Tracking**](https://lucasnunesf.notion.site/Automotive-Cost-Reduction-Tracking-3de917c89c1780c38feccacc9238ab6e): 163 supplier files brought into one Power BI dashboard, showing the gap to the fiscal year target mid-year
- [**Power BI – Engineering Change Tracking**](https://lucasnunesf.notion.site/Power-BI-Engineering-Change-Tracking-3e5917c89c1780978911c01acd0b21b3): two dashboards for change requests, with field parameters switching six approval stages on one page
- [**Tracking prototype parts with QR codes**](https://lucasnunesf.notion.site/Tracking-prototype-parts-with-QR-codes-81a917c89c17830b82b38101d66af8e3): the QR code → form → spreadsheet process introduced at Bosch, which cut inventory losses and rework by about 60%

→ [Full portfolio](https://lucasnunesf.notion.site/Lucas-Nunes-Data-BI-Analyst-3de917c89c178092885cf639b619767b)

### 🎓 Education & training

- **Bachelor's Degree in Mechanical Engineering**, FACENS (2022–2026) · **Technical Degree in Business Intelligence and Administration**, ETEC (2020–2022)
- **Microsoft Power BI Data Analyst** – Professional Certificate course, Microsoft via Coursera (2026): Power Query ETL, star schema modeling and DAX, as preparation for the PL-300 exam
- **IBM Data Engineering** – Professional Certificate course, IBM via Coursera (2026)
- **Microsoft Azure Data Fundamentals (DP-900)**: exam prep completed, exam scheduled for December 2026
- 🇧🇷 Portuguese (native) · 🇬🇧 English (professional working proficiency, CEFR B2)

### 🤖 Beyond data

Led the design and assembly of combat robots at **Omegabotz (FACENS)**, programming microcontroller and motor control logic in C++ and analyzing real-time telemetry data. **2nd place at an international championship in Greece.** Also built data acquisition routines for the **SAE Formula/Baja** team and coordinate the automation and electrical sub-teams at **Falcons Aerodesign**. Competing taught me the same thing the factory did: a system is only as good as the data you can read from it while it runs.

→ [robot-sumo-competition](https://github.com/lucasnunesf/robot-sumo-competition): ESP32 firmware in C++ with state machines, sensor logic separated from strategy, and unit tests that run on a PC.

### 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasfernandesnunes)
[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?style=flat&logo=notion&logoColor=white)](https://lucasnunesf.notion.site/Lucas-Nunes-Data-BI-Analyst-3de917c89c178092885cf639b619767b)
[![Email](https://img.shields.io/badge/lucasnunes100f@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:lucasnunes100f@gmail.com)
[![CV](https://img.shields.io/badge/Download%20CV-PDF-1F3864?style=flat&logo=readdotcv&logoColor=white)](https://github.com/lucasnunesf/lucasnunesf/blob/main/Lucas_Fernandes_Nunes_CV.pdf)
