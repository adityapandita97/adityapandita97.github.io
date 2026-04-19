<div align="center">

# Aditya Pandita

### Solutions Architect II — Amazon Web Services

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

```
┌─────────────────────────────────┐  ┌─────────────────────────────────┐  ┌─────────────────────────────────┐
│  ⚡ SERVERLESS & EVENT-DRIVEN   │  │  🧠 AI/ML & GENERATIVE AI       │  │  📊 DATA & ANALYTICS            │
│                                 │  │                                 │  │                                 │
│  AWS Lambda    API Gateway      │  │  Amazon Bedrock   SageMaker     │  │  Amazon Redshift  QuickSight    │
│  Step Functions EventBridge     │  │  Rekognition      Lex           │  │  Kinesis          AWS Glue      │
│  SQS  SNS  AppSync  DynamoDB   │  │  Comprehend       Textract      │  │  Athena           EMR           │
│  Fargate                        │  │  Kendra  Personalize  Forecast  │  │  Lake Formation   OpenSearch    │
└─────────────────────────────────┘  └─────────────────────────────────┘  └─────────────────────────────────┘
┌─────────────────────────────────┐  ┌─────────────────────────────────┐  ┌─────────────────────────────────┐
│  🔄 MIGRATION & MODERNIZATION  │  │  ☁️ CLOUD INFRA & DR             │  │  🛡️ SECURITY & COMPLIANCE       │
│                                 │  │                                 │  │                                 │
│  AWS MGN       DMS              │  │  EC2  ECS/EKS    VPC            │  │  IAM  KMS  WAF  Shield         │
│  Migration Hub SCT              │  │  Transit Gateway  Route 53      │  │  GuardDuty    Security Hub      │
│  Application Discovery          │  │  CloudFront  Direct Connect     │  │  Inspector    Macie             │
│  Transfer Family  CloudEndure   │  │  Elastic DR  Backup  Aurora     │  │  CloudTrail   Config            │
└─────────────────────────────────┘  └─────────────────────────────────┘  └─────────────────────────────────┘
```

---

## Selected Projects

### 01 — National Smart Grid Infrastructure `Energy` `Enterprise`

Architected the cloud backbone for India's Advanced Metering Infrastructure (AMI) under PGCIL — enabling real-time monitoring, analytics, and management of **5M+ smart electricity meters** across the national grid.

```
Smart Meters (5M+)
        │
        ▼
┌──────────────────────────┐
│  IoT Core  │  API GW     │
│  VPC       │  Security   │
└──────────┬───────────────┘
           ▼
┌──────────────────────────┐
│  Lambda    │  Kinesis     │
│  SQS       │  Step Fn     │
└──────────┬───────────────┘
           ▼
┌──────────────────────────┐
│  DynamoDB  │  Timestream  │
│  QuickSight Analytics    │
└──────────────────────────┘
```

| Metric | Value |
|--------|-------|
| Meters Managed | **5M+** |
| Cost Reduction | **42%** |
| Uptime SLA | **99.9%** |

---

### 02 — MNRE Solar Rooftop AI Analysis `AI/ML` `Government`

Built a multi-stage AI image validation pipeline for India's rooftop solar subsidy program. Images submitted for subsidy claims pass through three automated checks:

```
MNRE Portal → S3 Upload
                 │
    ┌────────────┼────────────┐
    ▼            ▼            ▼
┌────────┐ ┌──────────┐ ┌──────────────┐
│Quality │ │Duplicate │ │  Custom ML   │
│Check   │ │Check     │ │  Checks      │
│Rekog.  │ │Vector    │ │  Inclination │
│        │ │Search/RDS│ │  Morphing    │
└────┬───┘ └────┬─────┘ │  SageMaker   │
     │          │       │  Bedrock LLM │
     ▼          ▼       └──────┬───────┘
     └──────────┴──────────────┘
                 │
                 ▼
        Status: Accepted / Rejected
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

```
┌──────────────────────────────────────────┐
│           Data Sources (411K+ records)    │
│  DT Meters │ EV Charging │ Solar │ BESS  │
└──────────────────┬───────────────────────┘
                   ▼
┌──────────────────────────────────────────┐
│         5x Lambda Functions              │
│  DT Forecast │ EV │ Solar │ Capacity │   │
│              Chat Orchestrator           │
└──────────────────┬───────────────────────┘
                   ▼
┌──────────────────────────────────────────┐
│  React Dashboard  │  Multi-Agent AI Chat │
│  Chart.js KPIs    │  Bedrock Claude      │
└──────────────────────────────────────────┘
```

> **Stack:** Lambda, DynamoDB, Bedrock (Claude), API Gateway, React, Chart.js, CloudFormation

[![View on GitHub](https://img.shields.io/badge/View_Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/adityapandita97/AI-Insights-DISCOM)

---

### 05 — Power Utilities Visualization Pipeline `Data & Analytics` `Open Source`

Automated IaC solution — CloudFormation deploys an end-to-end ETL pipeline analyzing interval meter readings at 15-minute granularity.

```
CSV (S3) → Lambda (Python) → Redshift → QuickSight Dashboards
```

> **Stack:** CloudFormation (24 resources), S3, Lambda, Redshift, QuickSight, VPC, IAM

[![View on GitHub](https://img.shields.io/badge/View_Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/adityapandita97/Power-Utilities-Visualization-Project)

---

### 06 — Serverless RAG — Chat with PDF `GenAI` `Serverless`

Fully serverless Retrieval Augmented Generation system — upload a PDF, ask questions in plain English, get answers grounded in the actual document with zero hallucinations.

```
PDF → S3 → Lambda (chunking + embedding)
                    │
                    ▼
         OpenSearch Serverless
           (vector store)
                    │
      User Query →  ▼
         Bedrock (Titan Embeddings + Claude)
                    │
                    ▼
            Grounded Answer
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

| Certification | Domain |
|:---:|:---:|
| **AWS Solutions Architect Professional** | Cloud Architecture |
| **AWS Solutions Architect Associate** | Cloud Architecture |
| **AWS Developer Associate** | Development |
| **SME — Lambda & API Gateway** | Serverless |
| **AWS GenAI Certified** | Generative AI |
| **AWS Well-Architected** | Best Practices |

</div>

---

## Recognition

| Award | Details |
|-------|---------|
| "All Rounder" Award | 2 consecutive quarters |
| Rising Star Award | — |
| Bolster Award | — |
| AWS TFC Gold Member | Serverless & GenAI/ML Communities |

---

## Key Impact

<div align="center">

| $5M+ | 10+ | 5M+ | 42% |
|:---:|:---:|:---:|:---:|
| Annual Revenue | Govt Ministries & PSUs | Smart Meters Managed | Cost Reduction |

</div>

---

## Notable Clients & Partners

PGCIL · MNRE · PMSG Portal · Bureau of Energy Efficiency · DGH · RECL · NBFC · Nurmaligarh Refinery · GRID India · Polaris-Intellismart · EPFO · GSTN · Accenture · Deloitte · PwC · CMS · CT · BCG

---

<div align="center">

**[adityapandita.com](https://adityapandita.com)**

*Built with HTML5, CSS3, and vanilla JavaScript. No frameworks, no dependencies.*

</div>
