# adityapandita.com

Personal portfolio website for **Aditya Pandita** — Solutions Architect II at Amazon Web Services.

## Live

[adityapandita.com](https://adityapandita.com)

## About

Cloud Solutions Architect with 7+ years building enterprise-grade cloud infrastructure for government and public sector organizations. Serverless SME, 5x AWS Certified, with deep expertise in Data & AI, Migration & Modernization, and Security.

**Education:** IIT Roorkee (Machine Learning) | IIM Kozhikode (MBA) | University of Western Australia | Murdoch University

## Tech Stack

| Layer | Technology |
|---|---|
| **Markup** | HTML5, Semantic Elements |
| **Styling** | CSS3 (Custom Properties, Grid, Flexbox, Animations) |
| **Scripting** | Vanilla JavaScript (Canvas API, Intersection Observer, requestAnimationFrame) |
| **Fonts** | Inter (body), JetBrains Mono (code/labels) — Google Fonts |
| **Icons** | Font Awesome 6.4 |
| **Hosting** | GitHub Pages |
| **Domain** | Custom domain via CNAME |

## Features

- **Interactive Neural Network** — Canvas-based particle system in the hero section with mouse-reactive connections
- **Animated AI Chip SVG** — Floating chip illustration with pulsing circuit traces and traveling data dots
- **Circuit Board Dividers** — Animated SVG circuit traces with glowing junction nodes between sections
- **Floating Background Icons** — Subtle drifting tech icons (microchip, brain, cloud, server) across the page
- **Word-by-Word Reveal** — Scroll-triggered intro text animation with keyword highlighting
- **Stats Counter** — Animated number counting on scroll into view
- **Scroll Reveal** — Intersection Observer-based fade-in-up animations for all sections
- **Glass Morphism Nav** — Sticky navigation with backdrop blur on scroll
- **Responsive Design** — Fully responsive across desktop, tablet, and mobile breakpoints
- **Service Tags** — AWS service pills on each expertise card

## Sections

### Hero
Solutions Architect II title, animated tagline, CTA buttons, neural particle canvas, and floating AI chip.

### About
Word-by-word animated intro paragraph highlighting key terms (cloud, infrastructure, serverless, AI/ML, etc.).

### Stats
Key metrics — $5M+ revenue, 10+ government ministries, 5M+ smart meters, 42% cost reduction.

### Technical Expertise

Six domains, each with AWS service tags:

1. **Serverless & Event-Driven** — Lambda, API Gateway, Step Functions, EventBridge, SQS, SNS, AppSync, DynamoDB, Fargate
2. **AI/ML & Generative AI** — Bedrock, SageMaker, Rekognition, Lex, Comprehend, Textract, Kendra, Personalize, Forecast
3. **Data & Analytics** — Redshift, QuickSight, Kinesis, Glue, Athena, EMR, Lake Formation, OpenSearch, MSK
4. **Migration & Modernization** — MGN, DMS, Migration Hub, SCT, Application Discovery, Transfer Family, CloudEndure
5. **Cloud Infra & Disaster Recovery** — EC2, ECS/EKS, VPC, Transit Gateway, Route 53, CloudFront, Direct Connect, Elastic DR, Backup, Aurora Global
6. **Security & Compliance** — IAM, KMS, WAF, Shield, GuardDuty, Security Hub, Inspector, Macie, CloudTrail, Config

### Industry Projects

| # | Project | Domain | Highlights |
|---|---|---|---|
| 01 | **National Smart Grid Infrastructure** | Energy / Enterprise | 5M+ meters, 42% cost reduction, 99.9% uptime — with animated architecture diagram |
| 02 | **MNRE Solar Rooftop AI Analysis** | AI/ML / Government | 3-stage image validation (Rekognition + vector search + SageMaker/Bedrock) for fraud prevention |
| 03 | **Polaris — Energy Theft & Load Forecasting** | AI/ML / Energy | ML-based theft detection and demand forecasting for power utilities |
| 04 | **AI Insights — DISCOM Capacity Planning** | GenAI / Open Source | Multi-agent Bedrock platform analyzing 411K+ records across 11 cities ([GitHub](https://github.com/adityapandita97/AI-Insights-DISCOM)) |
| 05 | **Power Utilities Visualization Pipeline** | Data & Analytics | S3 → Lambda → Redshift → QuickSight ETL pipeline via CloudFormation ([GitHub](https://github.com/adityapandita97/Power-Utilities-Visualization-Project)) |
| 06 | **Serverless RAG — Chat with PDF** | GenAI / Serverless | Bedrock (Titan + Claude) + OpenSearch Serverless vector store, deployed via CDK |
| 07 | **IPv6 Smart Meter Migration** | Networking | Published on AWS Industries Blog — IoT-scale address migration |
| 08 | **Enterprise Cloud Migration — NRL** | Migration / Enterprise | VMware to AWS via MGN/DMS, DR with lowest RPO/RTO |
| 09 | **Serverless Computer Vision** | Serverless | Lambda + Rekognition + API Gateway — published on AWS Serverless Land |

### Certifications

- AWS Solutions Architect Professional
- AWS Solutions Architect Associate
- AWS Developer Associate
- SME — Lambda & API Gateway
- AWS GenAI Certified
- AWS Well-Architected

### Awards

- "All Rounder" Award (2 consecutive quarters)
- Rising Star Award
- Bolster Award
- AWS TFC Gold Member — Serverless & GenAI Communities

### Notable Clients & Partners

PGCIL, MNRE, PMSG Portal, Bureau of Energy Efficiency, DGH, RECL, NBFC, Nurmaligarh Refinery Ltd, GRID India, Polaris-Intellismart, EPFO, GSTN, Accenture, Deloitte, PwC, CMS, CT, BCG, and Fortune 500 enterprises.

## Project Structure

```
adityapandita97.github.io/
├── CNAME              # Custom domain configuration
├── README.md          # This file
├── index.html         # Portfolio (AWS-branded light theme)
├── index1.html        # Portfolio (Netflix dark theme v1)
├── index2.html        # Portfolio (Netflix dark theme v2)
└── index3.html        # Portfolio (Terminal Industries-inspired dark theme) ← current
```

## Local Development

No build tools required — open `index3.html` directly in a browser:

```bash
open index3.html
```

Or use a local server:

```bash
python3 -m http.server 8000
# → http://localhost:8000/index3.html
```

## Deployment

Hosted on GitHub Pages. Push to `main` to deploy:

```bash
git add .
git commit -m "update portfolio"
git push origin main
```

## Contact

- **Email:** adityapandita97@gmail.com
- **LinkedIn:** [linkedin.com/in/adityapandita97](https://linkedin.com/in/adityapandita97)
- **GitHub:** [github.com/adityapandita97](https://github.com/adityapandita97)

## License

All rights reserved. This is a personal portfolio — not intended for redistribution.
