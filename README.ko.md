<div align="center">

# 강응찬 · Kane (Eungchan) Kang

**풀스택 & 데이터 플랫폼 엔지니어** · 서울

**DB 엔진 내부부터 대시보드까지** 확장 가능한 시스템을 만듭니다 —
아키텍처 설계 · 개발 · 배포 · 운영 최적화 전 주기.

[![Portfolio](https://img.shields.io/badge/Portfolio-yeschan119.com-00b4d8?style=flat-square&logo=googlechrome&logoColor=white)](https://www.yeschan119.com)
[![Resume](https://img.shields.io/badge/이력서-PDF-023e8a?style=flat-square&logo=readthedocs&logoColor=white)](https://yeschan119.com/docs/Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yeschan119-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yeschan119/)
[![Email](https://img.shields.io/badge/Email-yeschan119%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yeschan119@gmail.com)

[**English 🇺🇸**](README.md)

</div>

---

## 한눈에 보기

|  |  |
| :-- | :-- |
| **전문 영역** | 멀티테넌트 SaaS · 분산 클라우드 아키텍처(AWS / Azure) · RDBMS 내부 구조와 쿼리 최적화 |
| **다뤄본 규모** | **2,000개 이상 학교**를 대상으로 한 분석 플랫폼, 5년치 누적 데이터, 대시보드 평균 응답 **약 3초** |
| **깊이** | 상용 RDBMS 엔진(Tibero) **내부**에 옵티마이저·통계·SQL 튜닝 모듈을 직접 구현 (C/C++) |
| **현재** | 의류 유통 ERP를 단일 정본 시스템으로 구축 — **97개 테이블**, **야간 배치 16개**, AI 에이전트 운영 |
| **경력** | 5년+ · AI Vision → RDBMS 엔진 → SaaS 플랫폼 → 시스템 아키텍처 |

---

## 주요 프로젝트

| 프로젝트 | 성과 | 기술 |
| :-- | :-- | :-- |
| **[AWS BI Reporting System](https://github.com/yeschan119/aws-bi-reporting-system)**<br/>QuickSight 임베디드 분석 + 멀티테넌트 접근 제어 | BI 운영비 **약 90% 절감** · 대시보드 평균 **약 3초** · **2,000개+** 학교 | Angular · .NET · QuickSight · RDS · DynamoDB |
| **[Cloud Data Platform Migration](https://github.com/yeschan119/Cloud-Data-Platform-Migration)**<br/>Azure → AWS. 단순 이전이 아닌 전면 재설계 | 이벤트 기반 분산 스냅샷 엔진, 수평 확장 구조 확보 | Lambda · Step Functions · SQS · EC2 ASG · S3 · QuickSight |
| **[Incident Management Platform](https://github.com/yeschan119/incident-management-system)**<br/>멀티테넌트 실시간 리포팅, OLTP / 분석 워크로드 분리 | 대시보드 지연 **약 20% 감소** · 집계 성능 **약 30% 향상** | Angular · ASP.NET Core · MySQL · 파티셔닝 · DB View |
| **[SQL Tuning Advisor](https://github.com/yeschan119/SQL_Tuning_Advisor)**<br/>Oracle의 튜닝 어드바이저를 역설계해 상용 엔진 안에 재구현 | SQL Profile / 인덱스 / 통계 권고를 자동 생성 | C++ · PL/SQL · 옵티마이저 내부 |
| **[RDBMS Statistics & Optimizer](https://github.com/yeschan119/RDBMS-Stat-Optimizer-Engineering)**<br/>인덱스 전용 통계 수집 노드 개발, 클러스터링 팩터 부정확 문제 해결 | 통계 정확도 **90% 이상 개선** → 인덱스 스캔 플랜 안정화 | C · C++ · Tibero |
| **[APM Dashboard](https://github.com/yeschan119/APM-Dashboard)**<br/>Controller → API → SQL 분산 트레이싱 | 커스텀 OpenTelemetry Exporter, 트레이스 트리 완전 복원 | .NET · OpenTelemetry · DynamoDB · AWS |

<details>
<summary><b>그 외 프로젝트</b></summary>

<br/>

| 프로젝트 | 내용 | 기술 |
| :-- | :-- | :-- |
| **[Real-Time Messaging Service](https://github.com/yeschan119/real-time-messaging-service)** | 순서 보장 WebSocket 채팅 — SQS FIFO → Lambda → DynamoDB | .NET 8 · SignalR · SQS · Lambda |
| **[Insurance Claim Tracking](https://github.com/yeschan119/insurance-claim-tracking-system)** | Stedi EDI 플랫폼 기반 보험 청구 생애주기 추적 | Angular · .NET 8 · EventBridge · DynamoDB |
| **[Edge AI with YOLO](https://github.com/yeschan119/Edge-AI-with-YOLO)** | GPU 없는 엣지 디바이스용 객체 탐지 최적화 | Python · YOLO · OpenCV |
| **[SNU Data Voucher](https://github.com/yeschan119/SNU-data-voucher)** | 이미지 세그멘테이션 & 어노테이션 파이프라인 | Python · OpenCV |
| **[Database Build Project](https://github.com/yeschan119/Database_Build_Project)** | DB 엔진 인덱스 설계 — 탐색·범위탐색·삽입/수정/삭제·병렬 | C |
| **[Portfolio](https://github.com/yeschan119/portfolio)** | 포트폴리오 사이트 — 이중 언어, git 히스토리 학습 AI 챗 내장 | HTML · Tailwind · LLM |

</details>

> **아키텍처 상세**(다이어그램·설계 근거)는 포트폴리오에 있습니다:
> [BI Reporting](https://yeschan119.com/projects/aws-bi-reporting.html) ·
> [Cloud Migration](https://yeschan119.com/projects/cloud-data-platform-migration.html) ·
> [Incident Management](https://yeschan119.com/projects/incident-management-system.html) ·
> [SQL Tuning Advisor](https://yeschan119.com/projects/sql_tuning_advisor.html) ·
> [DB Administration](https://yeschan119.com/projects/database-administration.html) ·
> [ERP Database](https://yeschan119.com/projects/erp-database-design.html) ·
> [Agent-Native Platform](https://yeschan119.com/projects/agent-native-platform.html)

---

## 현재 진행 중

### 🏢 [Ko&Clo](https://github.com/ko-clo) — Senior Software Engineer 🔒 *비공개 조직*

판매·재고·주문·정산·매장운영을 아우르는 의류 유통 ERP.

**담당 트랙 2개**

| 트랙 | 내용 | 현재 상태 |
| :-- | :-- | :-- |
| **ERP 데이터베이스 & 배치 플랫폼** | 7년치 엑셀/CSV를 PostgreSQL 단일 정본으로 이관 | 5개 도메인 **97개 테이블** · **야간 배치 16개**(02:00–06:30) · 멱등 UPSERT 백필 · 매장별 리스트 파티셔닝 |
| **Agent-Native 개발 플랫폼** | Harness / Graph / Loop 엔지니어링으로 AI 에이전트가 안전하게 개발·운영 | **권한 규칙 46개** · **라이프사이클 훅 7개** · 서브탭과 1:1 대응하는 **에이전트 53개** · 3계층 메모리 |

**로드맵** *(실제 마일스톤 — 저장소는 비공개)*

| 마일스톤 | 진행률 | 범위 |
| :-- | :-- | :-- |
| 매장 운영 대시보드 | `9/12` ▓▓▓▓▓▓░░ 75% | 매장별 대시보드 기능 추가·수정 |
| 상품 카테고리 분류 | `8/9` ▓▓▓▓▓▓▓░ 89% | 카테고리 탭 활성화 |
| 도매 리오더 안정화 | `1/1` ▓▓▓▓▓▓▓▓ 100% | 도매리오더 기능 안정화 |
| 이미지 기반 품번 생성 | `예정` ░░░░░░░░ | 품번생성 프로젝트 |

**진행 중인 이슈** — 매장별 업무 진행 모니터링 AI Agent + MCP · 카테고리 분석 API ·
샘플반납 상세 플로우 · 도매리오더 기능 수정 · 리포트 탭 DB 전환

### 🎓 [Pennsylvania State University](https://github.com/psu-edu) — 소프트웨어 공학 석사

**소프트웨어 아키텍처** 분야 대학원 연구.

---

## 경력

| 기간 | 직무 | 소속 | 담당 |
| :-- | :-- | :-- | :-- |
| **2026.05 –** | Senior Software Engineer | **Ko&Clo** · 서울 | 의류 유통 통합 ERP · 계층형 아키텍처(도메인 / API / 데이터 / 배포) · AI 에이전트 운영 체계 |
| **2024.02 – 2026.04** | Full-Stack Software Engineer | **Kokomo Solutions** · 시카고 | 멀티테넌트 SaaS 아키텍처 · 분석 플랫폼 end-to-end · DB/백엔드 최적화로 전체 성능 **약 30% 향상** |
| **2022.01 – 2024.02** | Database Engineer *(RDBMS 엔진)* | **TmaxData** · 성남 | 옵티마이저·통계 모듈 · SQL Tuning Advisor · SPM · 금융권 SQL 튜닝 지원 · C → C++ 현대화 |
| **2021.09 – 2021.12** | AI Vision Engineer | **AIWORKX** · 서울 | GPU 없는 엣지 객체 탐지 · 세그멘테이션·어노테이션 제품화 |

**학력**

- **소프트웨어 공학 석사** — [Pennsylvania State University](https://github.com/psu-edu)
- **정보시스템학 학사** *(부전공: 컴퓨터공학)* — 한양대학교 · 학점 4.18 / 4.5

---

## 기술 스택

**언어**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL%20%7C%20PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)

**백엔드 & 프론트엔드**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**데이터**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MSSQL](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Tibero](https://img.shields.io/badge/Tibero-0066FF?style=flat-square)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**클라우드 & 운영**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

---

<div align="center">

**시니어 / 스태프 엔지니어 포지션에 열려 있습니다** — 플랫폼 · 데이터 · DB 중심 시스템.

[yeschan119.com](https://www.yeschan119.com) · [yeschan119@gmail.com](mailto:yeschan119@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yeschan119/)

</div>
