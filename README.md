<div align="center">

# Aditya Pandita

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=800&lines=Cloud+%26+AI+Solutions+Architect;Serverless+SME+%7C+Data+%26+AI+%7C+Migration+%26+Modernization;Architecting+the+cloud+that+powers+nations" alt="Typing SVG" /></a>

### Cloud & AI Solutions Architect

**Serverless SME | Data & AI | Migration & Modernization | 5x AWS Certified**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adityapandita97)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityapandita97)
[![Portfolio](https://img.shields.io/badge/Portfolio-00e8c6?style=for-the-badge&logo=googlechrome&logoColor=black)](https://adityapandita.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adityapandita97@gmail.com)

---

*Architecting the cloud infrastructure that powers nations.*

</div>

## About

Cloud Solutions Architect with 7+ years building enterprise-grade cloud infrastructure for government and public sector organizations across India. I specialize in designing serverless architectures, AI/ML platforms, data analytics pipelines, and end-to-end cloud migration strategies — delivering $5M+ annual revenue impact across 10+ government ministries and PSUs.

**Education:** IIT Roorkee (Machine Learning) | IIM Kozhikode (MBA) | University of Western Australia | Murdoch University

---

## Technical Expertise

```mermaid
mindmap
  root((Cloud and AI<br/>Solutions Architect))
    Serverless
      AWS Lambda
      API Gateway
      Step Functions
      EventBridge
      SQS / SNS
      DynamoDB
    AI/ML and GenAI
      Amazon Bedrock
      SageMaker
      Rekognition
      Textract
      Comprehend
      Kendra
    Data and Analytics
      Redshift
      QuickSight
      Kinesis
      AWS Glue
      Athena
      OpenSearch
    Migration
      AWS MGN
      DMS
      Migration Hub
      SCT
    Cloud Infra and DR
      EC2
      ECS / EKS
      VPC
      Route 53
      Aurora
      Elastic DR
    Security
      IAM / KMS
      WAF / Shield
      GuardDuty
      Security Hub
      CloudTrail
```

**Multi-cloud & Tooling**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS%20CDK-232F3E?style=for-the-badge&logo=amazonaws&logoColor=F90)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

---

## Selected Projects

### 01 — National Smart Grid Infrastructure `Energy` `Enterprise`

Architected the cloud backbone for India's Advanced Metering Infrastructure (AMI) under PGCIL — enabling real-time monitoring, analytics, and management of **5M+ smart electricity meters** across the national grid.

```mermaid
flowchart LR
    M(["🔌 Smart Meters<br/>5M+ devices"]) ==>|telemetry| ING
    subgraph ING["🛡️ Ingest & Secure"]
        direction TB
        IOT["IoT Core"]
        AGW["API Gateway"]
        VPC["VPC + Security"]
    end
    ING ==>|stream| PROC
    subgraph PROC["⚙️ Process"]
        direction TB
        LAM["Lambda"]
        KIN["Kinesis"]
        SFN["Step Functions"]
    end
    PROC ==>|persist| STORE
    subgraph STORE["📊 Store & Visualize"]
        direction TB
        DDB["DynamoDB"]
        TS["Timestream"]
        QS["QuickSight"]
    end
    classDef meter fill:#1b7a3d,stroke:#fff,color:#fff,stroke-width:2px;
    classDef edge fill:#232F3E,stroke:#FF9900,color:#fff;
    classDef proc fill:#FF9900,stroke:#232F3E,color:#000;
    classDef data fill:#527FFF,stroke:#fff,color:#fff;
    class M meter;
    class IOT,AGW,VPC edge;
    class LAM,KIN,SFN proc;
    class DDB,TS,QS data;
```

| Metric | Value |
|--------|-------|
| Meters Managed | **5M+** |
| Cost Reduction | **42%** |
| Uptime SLA | **99.9%** |

---

### 02 — MNRE Solar Rooftop AI Analysis `AI/ML` `Government`

Built a multi-stage AI image validation pipeline for India's rooftop solar subsidy program. Images submitted for subsidy claims pass through three automated checks:

```mermaid
flowchart LR
    P(["🏛️ MNRE Portal"]) --> S3["📦 S3 Upload"]
    S3 --> CHK
    subgraph CHK["🔍 Automated Validation"]
        direction TB
        Q["✅ Quality<br/>Rekognition"]
        D["🔁 Duplicate<br/>Vector Search / RDS"]
        M["🧠 Custom ML<br/>Inclination · Morphing<br/>SageMaker + Bedrock"]
    end
    CHK --> R{"Decision"}
    R ==>|pass| A(["✔️ Accepted"])
    R ==>|fail| X(["✖️ Rejected"])
    classDef portal fill:#527FFF,stroke:#fff,color:#fff,stroke-width:2px;
    classDef svc fill:#232F3E,stroke:#FF9900,color:#fff;
    classDef dec fill:#FF9900,stroke:#232F3E,color:#000;
    classDef ok fill:#1b7a3d,stroke:#fff,color:#fff;
    classDef no fill:#c0392b,stroke:#fff,color:#fff;
    class P portal;
    class S3,Q,D,M svc;
    class R dec;
    class A ok;
    class X no;
```

> **Services:** Step Functions, Rekognition, SageMaker AI, Bedrock, RDS (pgvector), S3, Lambda

---

### 03 — Polaris — Energy Theft & Load Forecasting `AI/ML` `Energy`

ML use cases for power utilities — anomaly-based theft detection to identify tampered meters and unauthorized consumption, and demand forecasting for capacity planning across distribution networks.

| Use Case | Approach |
|----------|----------|
| Theft Detection | Anomaly models on meter reading patterns |
| Load Forecasting | Time-series prediction for grid demand |

---

### 04 — AI Insights — DISCOM Capacity Planning `GenAI` `Open Source`

End-to-end AI-powered capacity planning for power distribution companies analyzing four growth vectors across **411K+ records** and **11 cities**.

```mermaid
flowchart LR
    subgraph SRC["📊 Data — 411K+ records"]
        direction TB
        DT["DT Meters"]
        EV["EV Charging"]
        SO["Solar"]
        BE["BESS"]
    end
    SRC ==>|ingest| FN
    subgraph FN["⚙️ 5x Lambda Functions"]
        direction TB
        F1["DT Forecast"]
        F2["EV"]
        F3["Solar"]
        F4["Capacity"]
        F5["Chat Orchestrator"]
    end
    FN ==>|serve| UI
    subgraph UI["🖥️ Experience Layer"]
        direction TB
        R["React Dashboard<br/>Chart.js KPIs"]
        C["Multi-Agent AI Chat<br/>Bedrock Claude"]
    end
    classDef src fill:#527FFF,stroke:#fff,color:#fff;
    classDef fn fill:#FF9900,stroke:#232F3E,color:#000;
    classDef ui fill:#232F3E,stroke:#FF9900,color:#fff;
    class DT,EV,SO,BE src;
    class F1,F2,F3,F4,F5 fn;
    class R,C ui;
```

> **Stack:** Lambda, DynamoDB, Bedrock (Claude), API Gateway, React, Chart.js, CloudFormation

[![View on GitHub](https://img.shields.io/badge/View_Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/adityapandita97/AI-Insights-DISCOM)

---

### 05 — Power Utilities Visualization Pipeline `Data & Analytics` `Open Source`

Automated IaC solution — CloudFormation deploys an end-to-end ETL pipeline analyzing interval meter readings at 15-minute granularity.

```mermaid
flowchart LR
    A(["📄 CSV in S3"]) ==>|extract| B["⚙️ Lambda<br/>Python ETL"] ==>|load| C[("🗄️ Redshift")] ==>|visualize| D(["📊 QuickSight"])
    classDef n fill:#232F3E,stroke:#FF9900,color:#fff;
    classDef db fill:#527FFF,stroke:#fff,color:#fff;
    class A,B,D n;
    class C db;
```

> **Stack:** CloudFormation (24 resources), S3, Lambda, Redshift, QuickSight, VPC, IAM

[![View on GitHub](https://img.shields.io/badge/View_Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/adityapandita97/Power-Utilities-Visualization-Project)

---

### 06 — Serverless RAG — Chat with PDF `GenAI` `Serverless`

Fully serverless Retrieval Augmented Generation system — upload a PDF, ask questions in plain English, get answers grounded in the actual document with zero hallucinations.

```mermaid
flowchart LR
    PDF(["📄 PDF"]) -->|upload| S3["📦 S3"] -->|trigger| L["⚙️ Lambda<br/>chunk + embed"]
    L -->|index| OS[("🔎 OpenSearch<br/>vector store")]
    U(["💬 User Query"]) --> BR
    OS -->|retrieve| BR{{"🧠 Bedrock<br/>Titan + Claude"}}
    BR ==>|grounded| ANS(["✅ Answer"])
    classDef svc fill:#232F3E,stroke:#FF9900,color:#fff;
    classDef db fill:#527FFF,stroke:#fff,color:#fff;
    classDef ai fill:#8A2BE2,stroke:#fff,color:#fff;
    classDef out fill:#1b7a3d,stroke:#fff,color:#fff;
    class PDF,S3,L,U svc;
    class OS db;
    class BR ai;
    class ANS out;
```

> **Stack:** S3, Lambda, Bedrock (Titan + Claude 3 Haiku), OpenSearch Serverless, API Gateway, CDK

---

### 07 — IPv6 Smart Meter Migration `Networking` `Published`

Designed the IPv6 migration strategy for IoT-scale smart meter networks — solving address exhaustion for millions of connected devices. **Published on the AWS Industries Blog.**

---

### 08 — Enterprise Cloud Migration — NRL `Migration` `Enterprise`

End-to-end migration of Nurmaligarh Refinery's VMware infrastructure to AWS — modernizing legacy workloads using MGN and DMS, with DR strategies achieving lowest RPO/RTO targets.

---

### 09 — Serverless Computer Vision `Serverless` `Published`

End-to-end serverless image analysis using Lambda, Rekognition, and API Gateway. **Published on AWS Serverless Land.**

---

## Certifications

<div align="center">

![SA Pro](https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20Professional-232F3E?style=for-the-badge&logo=amazonaws&logoColor=F90)
![SA Associate](https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20Associate-232F3E?style=for-the-badge&logo=amazonaws&logoColor=F90)
![Developer Associate](https://img.shields.io/badge/AWS%20Certified-Developer%20Associate-232F3E?style=for-the-badge&logo=amazonaws&logoColor=F90)
![AI Practitioner](https://img.shields.io/badge/AWS%20Certified-AI%20Practitioner-232F3E?style=for-the-badge&logo=amazonaws&logoColor=F90)
![Cloud Practitioner](https://img.shields.io/badge/AWS%20Certified-Cloud%20Practitioner-232F3E?style=for-the-badge&logo=amazonaws&logoColor=F90)

![Lambda SME](https://img.shields.io/badge/SME-AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![API Gateway SME](https://img.shields.io/badge/SME-API%20Gateway-FF4F8B?style=for-the-badge&logo=amazonapigateway&logoColor=white)
![GenAI L200](https://img.shields.io/badge/AWS-GenAI%20Technical%20(L200)-8A2BE2?style=for-the-badge&logo=amazon&logoColor=white)
![Well-Architected](https://img.shields.io/badge/AWS-Well--Architected%20Proficient-232F3E?style=for-the-badge&logo=amazonaws&logoColor=F90)

*Plus AWS Support Engineering awards, Serverless Demonstrated, Digital Sovereignty (Technical), Migration Acceleration Authorized, and 25+ AWS technical & partner training badges.*

</div>

---

## Recognition

| Award | Details |
|-------|---------|
| "All Rounder" Award | 2 consecutive quarters |
| Rising Star Award | — |
| Bolster Award | — |
| Most Valuable Player (MVP) | 3x — AWS Support Engineering |
| AWS TFC Gold Member | Serverless & GenAI/ML Communities |

---

## Key Impact

<div align="center">

| $5M+ | 10+ | 5M+ | 42% |
|:---:|:---:|:---:|:---:|
| Annual Revenue | Govt Ministries & PSUs | Smart Meters Managed | Cost Reduction |

</div>

---

## GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=adityapandita97&show_icons=true&count_private=true&hide_border=true&theme=tokyonight" alt="stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityapandita97&layout=compact&hide_border=true&theme=tokyonight" alt="top langs" />

<img src="https://github-profile-trophy.vercel.app/?username=adityapandita97&theme=tokyonight&no-frame=true&column=7&margin-w=8" alt="trophies" />

</div>

---

## Notable Clients & Partners

PGCIL · MNRE · PMSG Portal · Bureau of Energy Efficiency · DGH · RECL · NBFC · Nurmaligarh Refinery · GRID India · Polaris-Intellismart · EPFO · GSTN · Accenture · Deloitte · PwC · CMS · CT · BCG

---

<div align="center">

**[adityapandita.com](https://adityapandita.com)**

*Built with HTML5, CSS3, and vanilla JavaScript. No frameworks, no dependencies.*

</div>
