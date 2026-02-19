<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a6bff,100:00d4ff&height=180&section=header&text=Mesaque%20Botelho%20Junior&fontSize=36&fontColor=ffffff&fontAlignY=35&desc=Data%20Engineer%20%7C%20Building%20Scalable%20Data%20Architectures&descSize=16&descAlignY=55&descColor=cccccc"/>



<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mesaquejunior)
[![Gmail](https://img.shields.io/badge/-Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mesaquejunior@gmail.com)
[![Snowflake Certified](https://img.shields.io/badge/-Snowflake%20Certified-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)](#-certifications)

</div>

---

## `> whoami`

```python
class DataEngineer:
    def __init__(self):
        self.name = "Mesaque Botelho Junior"
        self.role = "Data Engineer"
        self.location = "Brazil (Remote for US companies)"
        self.languages = ["Portuguese (Native)", "English (Advanced)"]
        self.experience = "8+ years in tech, 4+ years in data engineering"

    def current_focus(self):
        return [
            "Enterprise data architectures with Snowflake & AWS",
            "Event-driven pipelines at scale",
            "Real-time data ingestion & transformation",
        ]

me = DataEngineer()
```

---

## `> cat tech_stack.yaml`

<table>
<tr>
<td valign="top" width="33%">

### Data & Analytics
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Soda](https://img.shields.io/badge/Soda-5A2D82?style=flat-square&logoColor=white)

</td>
<td valign="top" width="33%">

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

</td>
<td valign="top" width="33%">

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

</td>
</tr>
</table>

<details>
<summary><b>Full AWS Toolkit</b></summary>
<br>

| Service | Use Case |
|---------|----------|
| **Lambda** | Serverless data processing & API handlers |
| **ECS** | Containerized pipeline workloads |
| **S3** | Data lake storage & staging |
| **RDS** | Managed PostgreSQL databases |
| **SQS/SNS** | Event-driven messaging |
| **EventBridge** | Pipeline orchestration triggers |
| **MSK** | Managed Kafka clusters |
| **Glue** | ETL catalog & crawlers |
| **DynamoDB** | Low-latency key-value storage |

</details>

<details>
<summary><b>Snowflake Deep Dive</b></summary>
<br>

```
 Snowflake Expertise
 ├── Dynamic Tables (100+ configured)
 ├── Snowpipe (automated ingestion)
 ├── External Stages (S3 integration)
 ├── Tasks & Streams (CDC pipelines)
 ├── Query Optimization
 │   ├── Clustering strategies
 │   ├── Warehouse cache
 │   ├── Query result cache
 │   └── Metadata cache
 └── File Formats & Integration
```

</details>

---

## `> ls projects/`

<div align="center">

```
 ╔═══════════════════════════════════════════════════════════════════════╗
 ║                      ARCHITECTURE PATTERNS                            ║
 ╠═══════════════════════════════════════════════════════════════════════╣
 ║                                                                       ║
 ║        [APIs]──►[Kafka]──►[S3]──►[Snowpipe]──►[Snowflake]             ║
 ║          │                                         │                  ║
 ║          ▼                                         ▼                  ║
 ║        [Lambda]                            [Dynamic Tables]           ║
 ║          │                                         │                  ║
 ║          ▼                                         ▼                  ║
 ║        [ECS]──►[Processing]──►[dbt]──►[ClickHouse/PostgreSQL]         ║
 ║                                              │                        ║
 ║                                              ▼                        ║
 ║                                         [Dashboards]                  ║
 ║                                                                       ║
 ╚═══════════════════════════════════════════════════════════════════════╝
```

</div>

### What I Build

| Domain | Stack | Description |
|--------|-------|-------------|
| **Data Pipelines** | Airflow + dbt + Snowflake | End-to-end ELT workflows with data quality checks via Soda |
| **Real-Time Ingestion** | Kafka + AWS Lambda + Snowpipe | Event-driven pipelines processing partner data (Kantar, Nielsen) |
| **API Data Acquisition** | Python + Lambda + ECS | Integrations with Facebook, YouTube, LinkedIn, Google Trends, Semrush |
| **Microservices** | Go + gRPC | High-performance backend services with OpenTelemetry observability |
| **Full-Stack Apps** | React + TypeScript | Internal tools and dashboards |
| **Infrastructure** | Terraform + Docker + K8s | Reproducible, scalable cloud environments on AWS |

---

## `> git log --oneline career.md`

```
 2023-present  Data Engineer @ Blueocean (USA)
               → Architected Snowflake-AWS integration, reducing data
                 availability from hours to minutes
               → Built 100+ Dynamic Tables for brand metrics calculations
               → Implemented event-driven pipelines with Lambda, ECS, S3

 2022-2023     Software Engineer @ GBT Embedded Solutions (Portugal)
               → Serverless applications on AWS (Python, TypeScript)
               → Data processing pipelines with AWS Glue & RDS

 2021-2022     Software Engineer @ Bee Engineering ICT (Portugal)
               → AWS serverless architectures
               → Aurora MySQL/PostgreSQL, Terraform IaC

 2017-2021     Software Developer @ Imagem (Brazil)
               → Geovisualization apps with thousands of daily users
               → React.js, Node.js, Python, ArcGIS Enterprise
```

---

## `> cat certifications.json`

```json
[
  { "name": "Snowflake Core (COF-C02)",     "issuer": "Snowflake",  "year": 2026, "icon": "❄️"  },
  { "name": "Azure Fundamentals (AZ-900)",  "issuer": "Microsoft",  "year": 2021, "icon": "☁️"  },
  { "name": "Enterprise Admin Professional", "issuer": "Esri",       "year": 2019, "icon": "🌍" },
  { "name": "MCSA: Windows Server 2016",    "issuer": "Microsoft",  "year": 2018, "icon": "🖥️"  }
]
```

---

## `> top -stats`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=mesaquejuniorbo&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=1a6bff&icon_color=00d4ff&text_color=c9d1d9&ring_color=1a6bff" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mesaquejuniorbo&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=1a6bff&text_color=c9d1d9" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=mesaquejuniorbo&theme=tokyonight&hide_border=true&background=0D1117&ring=1A6BFF&fire=00D4FF&currStreakLabel=00D4FF" />

</div>

---

## `> tail -f activity.log`

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mesaquejuniorbo&bg_color=0d1117&color=1a6bff&line=00d4ff&point=ffffff&area=true&area_color=1a6bff&hide_border=true" />

</div>

---

<div align="center">

```
              ╭──────────────────────────────────╮
              │   "Data is the new oil, but      │
              │    pipelines are the refinery." │
              ╰──────────────────────────────────╯
```

![Profile Views](https://komarev.com/ghpvc/?username=mesaquejuniorbo&color=1a6bff&style=for-the-badge&label=PROFILE+VIEWS)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a6bff,100:00d4ff&height=100&section=footer"/>
