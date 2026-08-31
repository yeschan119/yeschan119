<div align="center">

# Kane (Eungchan) Kang · 강응찬

**Full-Stack & Data Platform Engineer** · Seoul, Korea

Building scalable systems from **database internals** to **dashboards** —
architecture, delivery, and production optimization across the full lifecycle.

[![Portfolio](https://img.shields.io/badge/Portfolio-yeschan119.com-00b4d8?style=flat-square&logo=googlechrome&logoColor=white)](https://www.yeschan119.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-023e8a?style=flat-square&logo=readthedocs&logoColor=white)](https://yeschan119.com/docs/Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yeschan119-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yeschan119/)
[![Email](https://img.shields.io/badge/Email-yeschan119%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yeschan119@gmail.com)

[**한국어 🇰🇷**](README.ko.md)

</div>

---

## At a glance

|  |  |
| :-- | :-- |
| **Focus** | Multi-tenant SaaS · Distributed cloud architecture (AWS / Azure) · RDBMS internals & query optimization |
| **Scale shipped** | Analytics platform for **2,000+ schools**, 5 years of historical data, **~3s** average dashboard response |
| **Depth** | Built optimizer, statistics, and SQL-tuning modules **inside a commercial RDBMS engine** (Tibero, C/C++) |
| **Now building** | An apparel ERP as a single system of record — **97 tables**, **16 nightly batches**, operated by AI agents |
| **Experience** | 5+ years · AI Vision → RDBMS Engine → SaaS Platform → System Architecture |

---

## Selected work

| Project | Impact | Stack |
| :-- | :-- | :-- |
| **[AWS BI Reporting System](https://github.com/yeschan119/aws-bi-reporting-system)**<br/>Embedded QuickSight analytics with multi-tenant access control | **↓ ~90%** BI operating cost · **~3s** avg dashboard · **2,000+** schools | Angular · .NET · QuickSight · RDS · DynamoDB |
| **[Cloud Data Platform Migration](https://github.com/yeschan119/Cloud-Data-Platform-Migration)**<br/>Azure → AWS. A full redesign, not a lift-and-shift | Event-driven distributed snapshot engine with horizontal scaling | Lambda · Step Functions · SQS · EC2 ASG · S3 · QuickSight |
| **[Incident Management Platform](https://github.com/yeschan119/incident-management-system)**<br/>Multi-tenant real-time reporting, OLTP / analytics separated | **↓ ~20%** dashboard latency · **↑ ~30%** aggregation performance | Angular · ASP.NET Core · MySQL · partitioning · DB views |
| **[SQL Tuning Advisor](https://github.com/yeschan119/SQL_Tuning_Advisor)**<br/>Oracle's advisor reverse-engineered and rebuilt inside a commercial engine | Automated SQL Profile / index / statistics recommendations | C++ · PL/SQL · optimizer internals |
| **[RDBMS Statistics & Optimizer](https://github.com/yeschan119/RDBMS-Stat-Optimizer-Engineering)**<br/>Dedicated index-statistics node; fixed clustering-factor inaccuracy | **↑ 90%+** statistics accuracy → stable index scan plans | C · C++ · Tibero |
| **[APM Dashboard](https://github.com/yeschan119/APM-Dashboard)**<br/>Distributed tracing, Controller → API → SQL | Custom OpenTelemetry exporter, full trace-tree reconstruction | .NET · OpenTelemetry · DynamoDB · AWS |

<details>
<summary><b>More projects</b></summary>

<br/>

| Project | What it is | Stack |
| :-- | :-- | :-- |
| **[Real-Time Messaging Service](https://github.com/yeschan119/real-time-messaging-service)** | WebSocket chat with strict ordering — SQS FIFO → Lambda → DynamoDB | .NET 8 · SignalR · SQS · Lambda |
| **[Insurance Claim Tracking](https://github.com/yeschan119/insurance-claim-tracking-system)** | Claim lifecycle tracking on the Stedi EDI platform | Angular · .NET 8 · EventBridge · DynamoDB |
| **[Edge AI with YOLO](https://github.com/yeschan119/Edge-AI-with-YOLO)** | Object detection tuned for edge devices without GPUs | Python · YOLO · OpenCV |
| **[SNU Data Voucher](https://github.com/yeschan119/SNU-data-voucher)** | Image segmentation & annotation pipeline | Python · OpenCV |
| **[Database Build Project](https://github.com/yeschan119/Database_Build_Project)** | DB engine index design — search, range, insert/update/delete, parallel | C |
| **[Portfolio](https://github.com/yeschan119/portfolio)** | This site — bilingual, AI chat trained on my git history | HTML · Tailwind · LLM |

</details>

> **Architecture deep dives** with diagrams and design rationale live on the portfolio:
> [BI Reporting](https://yeschan119.com/projects/aws-bi-reporting.html) ·
> [Cloud Migration](https://yeschan119.com/projects/cloud-data-platform-migration.html) ·
> [Incident Management](https://yeschan119.com/projects/incident-management-system.html) ·
> [SQL Tuning Advisor](https://yeschan119.com/projects/sql_tuning_advisor.html) ·
> [DB Administration](https://yeschan119.com/projects/database-administration.html) ·
> [ERP Database](https://yeschan119.com/projects/erp-database-design.html) ·
> [Agent-Native Platform](https://yeschan119.com/projects/agent-native-platform.html)

---

## Currently building

### 🏢 [Ko&Clo](https://github.com/ko-clo) — Senior Software Engineer 🔒 *private org*

An apparel distribution ERP covering sales, inventory, ordering, settlement, and store operations.

**Two tracks I own**

| Track | What it is | Where it stands |
| :-- | :-- | :-- |
| **ERP Database & Batch Platform** | Seven years of Excel/CSV moved into one PostgreSQL system of record | **97 tables** across 5 domains · **16 nightly batches** (02:00–06:30) · idempotent UPSERT backfill · per-store list partitioning |
| **Agent-Native Development Platform** | Harness / Graph / Loop engineering so AI agents can build and operate the system safely | **46 permission rules** · **7 lifecycle hooks** · **53 agents** mapped 1:1 onto subtabs · 3-layer memory |

**Roadmap** *(live milestones — repos are private)*

| Milestone | Progress | Scope |
| :-- | :-- | :-- |
| Store operations dashboard | `9/12` ▓▓▓▓▓▓░░ 75% | 매장별 대시보드 기능 추가·수정 |
| Product category classification | `8/9` ▓▓▓▓▓▓▓░ 89% | 카테고리 탭 활성화 |
| Wholesale reorder stabilization | `1/1` ▓▓▓▓▓▓▓▓ 100% | 도매리오더 안정화 |
| Product-code generation from images | `planned` ░░░░░░░░ | 품번생성 프로젝트 |

**Open threads** — AI Agent + MCP for per-store task monitoring · category analysis API ·
sample-return detail flow · wholesale reorder revisions · report tab migrated onto the DB

### 🎓 [Pennsylvania State University](https://github.com/psu-edu) — M.S. Software Engineering

Graduate research in **software architecture**.

---

## Experience

| Period | Role | Where | What I owned |
| :-- | :-- | :-- | :-- |
| **2026.05 –** | Senior Software Engineer | **Ko&Clo** · Seoul | Unified apparel distribution ERP · layered architecture (domain / API / data / deploy) · AI-agent operations framework |
| **2024.02 – 2026.04** | Full-Stack Software Engineer | **Kokomo Solutions** · Chicago | Multi-tenant SaaS architecture · end-to-end analytics platform · **~30%** overall performance gain via DB/backend optimization |
| **2022.01 – 2024.02** | Database Engineer *(RDBMS Engine)* | **TmaxData** · Seongnam | Optimizer & statistics modules · SQL Tuning Advisor · SPM · enterprise/bank SQL tuning support · C → C++ modernization |
| **2021.09 – 2021.12** | AI Vision Engineer | **AIWORKX** · Seoul | Edge object detection without GPUs · segmentation & annotation productization |

**Education**

- **M.S. Software Engineering** — [Pennsylvania State University](https://github.com/psu-edu)
- **B.S. Information Systems** *(minor: Computer Science)* — Hanyang University · GPA 4.18 / 4.5

---

## Tech

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%7C%20PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MSSQL](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Tibero](https://img.shields.io/badge/Tibero-0066FF?style=flat-square)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Cloud & Ops**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

---

<div align="center">

**Open to senior / staff engineering roles** — platform, data, and database-heavy systems.

[yeschan119.com](https://www.yeschan119.com) · [yeschan119@gmail.com](mailto:yeschan119@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yeschan119/)

</div>
