<div align="center">

# Anthony Apollis

**Senior Data Engineer · Analytics Specialist · ML Practitioner**

*12+ years turning raw, messy data into trusted, decision-ready platforms*

[![Portfolio](https://img.shields.io/badge/Portfolio-anthonyapollis.github.io-3B82F6?style=for-the-badge&logo=github&logoColor=white)](https://anthonyapollis.github.io)
[![Email](https://img.shields.io/badge/Email-anthony.apollis%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anthony.apollis@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anthonyapollis)

*Cape Town, South Africa · Open to local & remote/international roles*

</div>

---

## What I Deliver

> **End-to-end data platforms** — raw ingestion → clean pipelines → dimensional models → ML → dashboards.
> Every project below is production-grade in scope, built from scratch, and documented to handover standard.

| What I bring | Proof |
|---|---|
| Cloud data engineering (GCP, Snowflake) | GCP Marketing Analytics Platform — Bronze/Silver/Gold medallion on BigQuery |
| Pipeline orchestration & automation | Apache Airflow DAG · BQ Data Transfer Service · Cloud Dataflow (Apache Beam) |
| Data modelling & transformation | dbt incremental models · Star schema · SCD Type 2 · 30M+ records |
| Machine learning end-to-end | 15 models trained · 0.81 ROC-AUC · R10.1M projected saving |
| BI & stakeholder-ready reporting | Interactive HTML dashboards · Power BI · Tableau · Excel advanced |
| Web analytics implementation | GA4 · GTM datalayer · BigQuery export · Consent Mode |

---

## Tech Stack

**Cloud & Data Platforms**

![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Pipelines & Orchestration**

![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Cloud Dataflow](https://img.shields.io/badge/Cloud_Dataflow-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Apache Beam](https://img.shields.io/badge/Apache_Beam-00A86B?style=flat-square&logo=apache&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache NiFi](https://img.shields.io/badge/Apache_NiFi-728E9B?style=flat-square&logo=apache&logoColor=white)
![SSIS](https://img.shields.io/badge/SSIS-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

**Transformation & Modelling**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Machine Learning**

![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**BI & Visualisation**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![Excel](https://img.shields.io/badge/Excel_(Advanced)-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**Web Analytics**

![GA4](https://img.shields.io/badge/Google_Analytics_4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![GTM](https://img.shields.io/badge/Google_Tag_Manager-246FDB?style=flat-square&logo=googletagmanager&logoColor=white)
![BigQuery Export](https://img.shields.io/badge/BQ_Data_Transfer-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)

---

## Featured Projects

### ☁️ [GCP Marketing Analytics Platform](https://github.com/anthonyapollis/GCP-Marketing-Analytics-Platform)

> Medallion pipeline (Bronze → Silver → Gold) on Google Cloud for 5 advertising sources.

| Layer | Technology | What happens |
|-------|-----------|-------------|
| Ingestion | BigQuery Data Transfer Service | GA4 · Google Ads · CM360 · DV360 · YouTube — managed connectors |
| Bronze | BigQuery (permissive STRING schema) | Raw data landed as-is, partitioned by `_pipeline_date` |
| Validation | Cloud Dataflow / Apache Beam | Row-level quality tagging, quarantine routing, Cloud Monitoring metrics |
| Silver | dbt incremental models | Dedupe · date-parse · type-cast · clamp negatives · normalise strings |
| Gold | dbt mart models | `fct_cross_channel_performance` · `rpt_channel_attribution` |
| Orchestration | Apache Airflow 2.x | TaskGroups · daily schedule · Slack alerting |

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/anthonyapollis/GCP-Marketing-Analytics-Platform)

---

### 🏆 [Pargo Parcels — ML & Data Warehouse Platform](https://github.com/anthonyapollis/PargoParcels-Portfolio)

> End-to-end analytics for South Africa's leading parcel pickup network — 30M parcels, 15 ML models.

| Metric | Value |
|--------|-------|
| Dataset scale | **30.2M parcels · 152.8M tracking events** |
| ML models trained | **15** (classification, regression, clustering, forecasting, CLV) |
| Best ROC-AUC | **0.81** (Stacking Ensemble) |
| Projected business impact | **R10.1M** RTS cost saving |
| Stack | Snowflake · dbt · XGBoost · LightGBM · Python · Chart.js |

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/anthonyapollis/PargoParcels-Portfolio)
[![Live Dashboard](https://img.shields.io/badge/Live_Dashboard-3B82F6?style=flat-square&logo=googlechrome&logoColor=white)](https://anthonyapollis.github.io)

---

### 🧠 [Lyra Wellbeing Analytics — Data Warehouse](https://github.com/anthonyapollis/Lyra-Analytics-Project)

> Star-schema dimensional model with SCD Type 2 employee history tracking.

| Metric | Value |
|--------|-------|
| Total rows | **1.4M+** across 16 tables |
| Fact tables | Sessions · Medication sales · Patient experience |
| History tracking | **SCD Type 2** on Employee & Consent dimensions |
| Stack | Snowflake · SQL Server · Python |

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/anthonyapollis/Lyra-Analytics-Project)

---

### 📊 [PenBev — BI Dashboard Suite](https://github.com/anthonyapollis/PenBev-Analytics)

> 4 self-contained HTML dashboards: revenue, trade spend ROI, product health, and SKU master.

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/anthonyapollis/PenBev-Analytics)

---

### 📈 [GA4 Analytics Portfolio](https://github.com/anthonyapollis/GA4-Analytics-Showcase)

> Full GA4 implementation: BigQuery exports, GTM datalayer, ecommerce funnel SQL, consent mode audit.

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/anthonyapollis/GA4-Analytics-Showcase)

---

## GitHub Stats

<div align="center">

![Anthony's GitHub stats](https://github-readme-stats.vercel.app/api?username=anthonyapollis&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=anthonyapollis&layout=compact&theme=tokyonight&hide_border=true&langs_count=6)

</div>

---

<div align="center">

**Seeking Data Engineering · Analytics Engineering · Senior BI roles**

12+ years of experience · Cape Town, South Africa · Open to remote

[![Full Portfolio](https://img.shields.io/badge/See_Full_Portfolio-anthonyapollis.github.io-3B82F6?style=for-the-badge)](https://anthonyapollis.github.io)

</div>
