<!-- Header -->
<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║    ██╗  ██╗███████╗████████╗ █████╗ ██╗                     ║
║    ██║  ██║██╔════╝╚══██╔══╝██╔══██╗██║                     ║
║    ███████║█████╗     ██║   ███████║██║                     ║
║    ██╔══██║██╔══╝     ██║   ██╔══██║██║                     ║
║    ██║  ██║███████╗   ██║   ██║  ██║███████╗                ║
║    ╚═╝  ╚═╝╚══════╝   ╚═╝   ╚═╝  ╚═╝╚══════╝                ║
║                                                              ║
║         Data Engineer · Boston, MA                          ║
║         Building pipelines that power decisions at scale    ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=1D9E75&center=true&vCenter=true&multiline=true&width=600&height=80&lines=500K%2B+Events%2FSec+Streamed+via+Apache+Kafka;%244.2M+Fraud+Prevented+Annually+via+ML;9%2C000%2B+Store+Locations+Connected+in+Real-Time)

</div>

---

## `$ whoami`

```python
hetal = {
    "role"       : "Data Engineer",
    "company"    : "CVS Health",
    "location"   : "Boston, MA",
    "experience" : "4+ years",
    "domains"    : ["Healthcare", "Financial Services", "E-Commerce"],
    "focus"      : ["Real-Time Streaming", "Cloud Migration",
                    "Lakehouse Architecture", "ML Platforms"],
    "open_to"    : "New Opportunities in Data & ML Engineering"
}
```

---

## `$ cat pipeline.txt`

```
┌─────────────┐    ┌──────────────────┐    ┌──────────┐
│ POS Systems │───▶│  Apache Kafka    │───▶│  Bronze  │
│ EHR / FHIR  │    │  Auto Loader     │    │  Delta   │
│ Oracle OLTP │    │  GoldenGate CDC  │    │  Layer   │
└─────────────┘    └──────────────────┘    └────┬─────┘
                                                │
                   ┌──────────────────┐    ┌────▼─────┐
                   │   dbt / Gold     │◀───│  Silver  │
                   │   MetricFlow     │    │  DLT     │
                   │   120+ Models    │    │  Layer   │
                   └────────┬─────────┘    └──────────┘
                            │
              ┌─────────────┼──────────────┐
              ▼             ▼              ▼
        ┌──────────┐  ┌──────────┐  ┌──────────┐
        │QuickSight│  │ Tableau  │  │  ML API  │
        │ Power BI │  │ Snowflake│  │  FastAPI │
        └──────────┘  └──────────┘  └──────────┘
```

---

## `$ ls -la tech-stack/`

### ⚡ Streaming & Processing
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=Apache+Airflow&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logo=databricks&logoColor=white)

### ☁️ Cloud Platforms
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

### ❄️ Data Warehousing
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)

### 🤖 Machine Learning
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

### ⚙️ Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---

## `$ cat impact.log`

| Metric | Result |
|--------|--------|
| 🚀 Kafka Streaming Latency | **6 hours → < 60 seconds** |
| 🏪 Store Locations Connected | **9,000+ CVS stores** |
| 💸 Fraud Prevented Annually | **$4.2M via ML pipeline** |
| 🎯 Fraud Detection Recall | **93% (XGBoost + Isolation Forest)** |
| 📉 Infrastructure Cost Saved | **35% via SSIS → AWS Glue migration** |
| 🧪 dbt Schema Tests | **680+ tests, 200+ models** |
| 🏥 HIPAA Compliance Findings | **Zero — automated with KMS + Macie** |
| ⚡ ML Inference Latency | **140ms p99 on GKE** |
| 📊 Analysts Served | **300+ on Snowflake Gold layer** |
| 🔬 ML Model AUC Improvement | **0.71 → 0.88 (TF Wide & Deep)** |

---

## `$ ls projects/`

```
📁 cvs-health/
   ├── 01_kafka-pharmacy-streaming     # 500K events/sec · Delta Lake · QuickSight
   ├── 02_ssis-to-aws-glue-migration   # 47 packages · HIPAA · Blue-Green CI/CD
   ├── 05_databricks-snowflake-lakehouse # FHIR R4 · Unity Catalog · DLT · MPI
   └── 06_dbt-healthcare-metrics       # 200+ models · MetricFlow · Semantic Layer

📁 magna-infotech/
   ├── 03_snowflake-financial-dw       # IFRS 9 · Basel III · GoldenGate CDC
   └── 04_ml-fraud-detection           # XGBoost · SHAP · GKE · Vertex AI

📁 personal/
   ├── aws-data-pipeline               # S3 · Lambda · Glue · Athena · Step Functions
   ├── airflow-orchestration           # DAG design · workflow automation
   ├── airbnb-dbt-snowflake            # End-to-end ELT pipeline
   ├── databricks-spark-pipelines      # Medallion architecture
   ├── kafka-stock-market-streaming    # Real-time market data analysis
   ├── sql-data-warehouse              # Dimensional modeling from scratch
   ├── pan-card-validation             # Python + SQL data quality
   ├── crime-analysis-tableau          # Data visualization · UMass Boston
   ├── cassandra-nosql                 # Distributed systems · UMass Boston
   └── python-web-scraping             # Data extraction · UMass Boston
```

---

## `$ cat education.txt`

```
┌─────────────────────────────────────────────────────┐
│  🎓 M.S. Information Technology                     │
│     University of Massachusetts Boston              │
│     GPA: 3.78 · Aug 2022 – May 2024                 │
│     Half Tuition Waiver · Graduate Assistantship    │
├─────────────────────────────────────────────────────┤
│  🎓 B.E. Information Technology                     │
│     Gujarat Technological University                │
│     CGPA: 8.04 · Jul 2014 – May 2018               │
└─────────────────────────────────────────────────────┘
```

---

## `$ cat contact.txt`

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-0a0f0d?style=for-the-badge&logo=googlechrome&logoColor=1D9E75)](https://hetal4246.github.io/Portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hetal42)
[![Email](https://img.shields.io/badge/Email-1D9E75?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hetalvaghela1010@gmail.com)

</div>

---

## `$ git log --stats`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hetal4246&show_icons=true&theme=dark&bg_color=0a0f0d&title_color=1D9E75&icon_color=5DCAA5&text_color=8aad9e&border_color=1D9E75&hide_border=false&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hetal4246&layout=compact&theme=dark&bg_color=0a0f0d&title_color=1D9E75&text_color=8aad9e&border_color=1D9E75&hide_border=false)

![GitHub Streak](https://streak-stats.demolab.com?user=hetal4246&theme=dark&background=0a0f0d&border=1D9E75&ring=1D9E75&fire=5DCAA5&currStreakLabel=5DCAA5&sideLabels=8aad9e&dates=4a6b5c)

</div>

---

<div align="center">

```
// always building · always shipping · always learning
```

![Visitor Count](https://komarev.com/ghpvc/?username=hetal4246&color=1D9E75&style=flat-square&label=Profile+Views)

</div>
