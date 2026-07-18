# Estefano Senhor Ferreira

**Senior Software Engineer · Software Architect · AI Engineer**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21433809.svg)](https://zenodo.org/records/21433809)

---

## Professional Profile

Software engineer and architect with 11+ years of experience designing scalable, secure, and high-impact systems. I hold a postgraduate degree in Software Architecture & Solutions and an extension course in Data Science from ITA (Instituto Tecnológico de Aeronáutica). My work centers on leading complex migrations, implementing modern architectures, and applying agile and DevOps practices to deliver mission-critical quality.

Alongside my corporate track record, I pursue applied, reproducibility-first research. As the author of **CycloneNet** ([DOI: 10.5281/zenodo.21413397](https://doi.org/10.5281/zenodo.21433809)), I used **Python** to build an end-to-end machine-learning pipeline and to **train and evaluate deep-learning models (CNNs)** testing hypotheses about tropical-cyclone rapid intensification (RI). The models run on a **leakage-safe, two-basin dataset** I assembled from ERA5 reanalysis and IBTrACS — **16,780 events from 992 cyclones** (East Pacific + North Atlantic, 1980–2023) — with storm-level train/test splits that prevent leakage and a byte-reproducible provenance chain.

The validated contribution is the dataset and the auditable pipeline: the modeling claims from earlier versions were formally withdrawn and corrected in v3 — a self-correction I treat as part of doing the work properly.

---

## 🛠️ Tech Stack

**Backend & Core**

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Frontend**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Databases**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Observability & Automation**

![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=flat-square&logo=uipath&logoColor=white)

**AI / LLM Engineering** *(actively building — project in progress)*

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6E56CF?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-6E56CF?style=flat-square)
![LLM Guardrails](https://img.shields.io/badge/LLM%20Guardrails-6E56CF?style=flat-square)
![Context Engineering](https://img.shields.io/badge/Context%20Engineering-6E56CF?style=flat-square)
![Model-Oriented Architectures](https://img.shields.io/badge/Model--Oriented%20Architectures-6E56CF?style=flat-square)

**Also:** VB.NET · VB6 · VBA · ADVPL (Protheus/TOTVS) · Microservices & event-driven architecture

---

## 🔬 Applied Machine Learning & Open Science

**CycloneNet** — *A Reproducible Pipeline and Leakage-Safe Two-Basin Dataset for Tropical-Cyclone Rapid-Intensification Analysis*

- 📄 **Preprint & dataset:** [10.5281/zenodo.21413397](https://doi.org/10.5281/zenodo.21413397)
- 💻 **Code (MIT):** [github.com/estefano-ferreira/cyclone-net](https://github.com/estefano-ferreira/cyclone-net)
- 📊 **Dataset (CC BY 4.0):** 16,780 events · 992 cyclones · 1980–2023 · storm-level splits · byte-reproducible provenance

**Technical scope**

- **Deep learning** — designed, trained, and evaluated a CNN classifier for rapid-intensification detection over multi-channel spatio-temporal tensors (40×40 grid × 5 time levels × 14 channels) derived from ERA5 reanalysis and IBTrACS.
- **Data & feature engineering** — assembled 16,780 labeled events into `float32` cubes; normalization statistics fit on the training split only to avoid leakage; tri-state labeling with explicit UNDEFINED handling.
- **Leakage-safe evaluation** — storm-level (SID) train/validation/test splits via SHA-256 hash-determinism so no storm crosses splits; a preregistered metric and verdict branches fixed before results; ablation with bootstrap confidence intervals by storm cluster.
- **Reproducibility / MLOps** — per-window SHA-256 manifests, a byte-reproducible labeling chain from raw IBTrACS, and a replication-gate script; relative-path provenance across all writers.

The modeling claims from earlier versions were formally withdrawn in v3 — the validated contribution is the dataset and the auditable pipeline.

---

## 💼 Experience Highlights

- **Legacy Modernization** — led migrations from VB6/VB.NET to modern .NET, working across the full range from .NET Core 3.1 through the latest release, with Angular frontends — improving performance and reducing maintenance overhead.
- **Full-Stack Development** — built and maintained enterprise-grade applications with ASP.NET Core, Web API, SQL Server, and Angular.
- **Database Expertise** — designed schemas, optimized complex queries, and managed migrations across SQL Server, PostgreSQL, and Oracle.
- **Team Collaboration** — active in Agile/Scrum, conducted code reviews, and mentored junior developers.
- **Reproducibility & Rigor** — bring the same auditable, evidence-first standard from my research into production engineering.

---

## 📫 Contact

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/estefano-ferreira)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:estefano.senhor@gmail.com)
