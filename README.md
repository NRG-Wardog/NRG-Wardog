# 👋 Hi, I'm Dorian Salomon

### Applied AI / NLP / ML | Windows Endpoint Security | C/C++ Systems

**Member of Technical Staff, AI @ HigherYou · Co-Founder & Security Engineer @ Aydo**

I build production systems across **applied AI/NLP, backend and data engineering, reliability, and Windows endpoint security**.

At **HigherYou**, I own applied AI systems end-to-end: data ingestion, information extraction, normalization, semantic/entity matching, ranking, validation, decision pipelines, backend integration, observability, and operational reliability.

At **Aydo**, I co-build a Windows endpoint-protection platform spanning kernel/user-mode components, endpoint telemetry, static and dynamic analysis, C++ backend services, and isolated malware sandboxing.

**B.Sc. Computer Science @ Bar-Ilan University · GPA 89 · Expected Sep 2027**

---

## 🏢 Production AI Engineering — HigherYou

Production engineering at HigherYou since **2023**; **Member of Technical Staff, AI** since **December 2025**.

My current scope includes:

- End-to-end ownership of production AI/NLP systems
- Large-scale and unstructured data ingestion
- Information extraction and structured normalization
- Semantic / entity matching and ranking
- Classification, validation, and decision pipelines
- Backend services and external integrations
- Data-quality controls and evaluation workflows
- Reliability, observability, retries, structured logging, and failure handling
- Operational automation connected to real business workflows

A large part of this work is private, so product names, customer data, internal datasets, and business logic are intentionally kept out of the public profile.

### Private engineering scope

Across non-public systems, I have also worked on engineering problems including:

- **Multilingual speech + NLP pipelines**: ASR, speaker diarization, embeddings, translation, evidence-grounded outputs
- **Real-time ML/backend systems**: asynchronous Python services, WebSockets, PostgreSQL/SQLAlchemy, model orchestration, analytics
- **ML evaluation systems**: calibration, shadow/replay evaluation, statistical evidence gates, experiment tracking, leakage controls
- **Secure integrations**: OAuth 2.0 / PKCE, JWT, encrypted secret storage, audit logging, provider integrations
- **Production tooling**: retention-aware artifacts, health checks, operator controls, deterministic tests, CI, diagnostics, and recovery workflows

---

## 🚀 Featured Engineering Work

### 🛡️ [AYDO](https://github.com/NRG-Wardog/Aydo)

**Windows Endpoint Protection Platform — EPP / AV / EDR**

AYDO is my primary security and systems-engineering project. It spans endpoint software, kernel components, detection, backend infrastructure, sandboxing, and desktop management.

**Engineering areas:**

- Windows kernel driver development and kernel ↔ user-mode communication via IOCTL
- Windows endpoint service, static scanning, real-time monitoring, and scan orchestration
- Endpoint telemetry with ETW / Sysmon
- YARA and Sigma-oriented detection flows
- Static and dynamic malware analysis
- VMware-based isolated sandboxing with reusable warm-VM lifecycle management
- C++ backend services with Drogon and PostgreSQL
- Electron / React desktop management application
- Self-tests, diagnostics, installer and update pipelines

**Stack:** `C++20` · `Windows` · `Kernel Development` · `ETW` · `Sysmon` · `YARA` · `Sigma` · `Drogon` · `PostgreSQL` · `VMware`

**Engineering evidence:** [Architecture](https://github.com/NRG-Wardog/Aydo/blob/production/docs/ARCHITECTURE.md) · [Security policy](https://github.com/NRG-Wardog/Aydo/blob/production/SECURITY.md)

---

### 🧠 [SpamGuard](https://github.com/NRG-Wardog/SpamGuard)

[![SpamGuard CI](https://github.com/NRG-Wardog/SpamGuard/actions/workflows/ci.yml/badge.svg)](https://github.com/NRG-Wardog/SpamGuard/actions/workflows/ci.yml)

**NLP Email Classification + Governed ML Data Pipeline**

SpamGuard is an end-to-end NLP/ML engineering project built around reproducible data preparation and usable inference, not just model training.

**Engineering highlights:**

- Multi-source ingestion with provenance and allowed-use metadata
- Data-quality reporting across source, label, language, length, links, and duplicates
- Exact-text deduplication and conflicting-label exclusion
- Template-aware clustering before splitting
- Deterministic train / validation / test generation
- Explicit verification that exact text and template clusters do not leak across splits
- Transformer-based training, evaluation, and inference
- Raw `.eml` parsing, batch inference, read-only Gmail integration, and Streamlit review tooling
- Deterministic CI tests around policy, reproducibility, deduplication, conflicts, and leakage

**Stack:** `Python` · `PyTorch` · `Transformers` · `NLP` · `Data / ML Engineering` · `Gmail API`

**Engineering evidence:** [ML engineering invariants](https://github.com/NRG-Wardog/SpamGuard/blob/main/docs/ML_ENGINEERING.md) · [CI](https://github.com/NRG-Wardog/SpamGuard/actions/workflows/ci.yml)

---

### 🍔 [AdvancedWolt](https://github.com/AdvancedWolt/wolt)

**Full-Stack Multi-Client Platform + C++ Recommendation System — Team Project**

A collaborative food-delivery platform combining a **C++ TCP recommendation service**, **Node.js / Express REST API**, **React** web client, **React Native / Expo** mobile client, **MongoDB**, JWT authentication, and Docker.

My work is directly visible in **12 merged pull requests** under `NRG-Wardog`.

**Selected contributions:**

- C++ recommendation and persistence architecture
- Similarity-weighted recommendation ranking and user-product interaction logic
- Database abstraction with rollback-safe persistence
- Command / response architecture and integration-level test coverage
- Backend MVC and REST workflows
- Search, restaurant/menu CRUD, and owner-based authorization
- Mobile authentication and protected routes
- Cart, ordering, history, and cancellation flows
- Docker-based multi-service integration

**Stack:** `C++` · `Node.js` · `Express` · `MongoDB` · `React` · `React Native` · `Docker` · `REST` · `TCP` · `JWT`

**Representative merged PRs:** [#12 — C++ data/recommendation architecture + 46 tests](https://github.com/AdvancedWolt/wolt/pull/12) · [#29 — restaurant/menu management](https://github.com/AdvancedWolt/wolt/pull/29) · [#42 — mobile auth](https://github.com/AdvancedWolt/wolt/pull/42) · [#43 — cart/orders/history](https://github.com/AdvancedWolt/wolt/pull/43) · [#44 — management + Docker integration](https://github.com/AdvancedWolt/wolt/pull/44)

> Collaborative repository under the **AdvancedWolt** organization. Contribution history is preserved in the merged PRs.

---

### ♟️ [Chess](https://github.com/NRG-Wardog/Chess)

[![Chess CI](https://github.com/NRG-Wardog/Chess/actions/workflows/ci.yml/badge.svg)](https://github.com/NRG-Wardog/Chess/actions/workflows/ci.yml)

**C++ Chess Engine + Windows IPC**

A collaborative C++ engine focused on deterministic game-state logic and multi-component communication.

**Engineering highlights:**

- Object-oriented C++ design and polymorphic piece model
- Legal-move validation and piece-specific rules
- Check, checkmate, and stalemate detection
- Self-check prevention and transactional board-state rollback
- Deterministic board parsing and serialization
- Windows named-pipe IPC with a graphical frontend
- Deterministic automated tests
- Linux GCC and Windows MSVC CI

**Stack:** `C++` · `OOP` · `Windows` · `Named Pipes` · `IPC` · `CMake` · `CI`

> Collaborative project developed by **Dorian Salomon and Yan Silberg**. The original repository was hosted under my teammate's account; this fork preserves the shared development history.

---

### 🔔 [whenTheAnswer](https://github.com/NRG-Wardog/whenTheAnswer)

[![whenTheAnswer CI](https://github.com/NRG-Wardog/whenTheAnswer/actions/workflows/ci.yml/badge.svg)](https://github.com/NRG-Wardog/whenTheAnswer/actions/workflows/ci.yml)

**Reliability-Focused Cross-Platform Monitoring**

A Windows/Linux monitoring system built around conservative automation, persistent protection state, and explicit failure behavior.

**Engineering highlights:**

- Persistent authenticated browser sessions
- Persistent `CLOSED / OPEN / HALF_OPEN` circuit breaker
- Exponential backoff and controlled recovery workflows
- Request spacing, hourly rate budgets, and jitter
- `Retry-After` and block/challenge detection
- Authentication-attempt limits and failure-safe recovery
- Persistent state across process restarts
- Deterministic tests for parsing, circuit transitions, persistence, and recovery
- Cross-platform notifications

**Stack:** `Python` · `Playwright` · `Windows` · `Linux` · `Reliability Engineering`

**Engineering evidence:** [Reliability invariants](https://github.com/NRG-Wardog/whenTheAnswer/blob/main/docs/RELIABILITY.md) · [CI](https://github.com/NRG-Wardog/whenTheAnswer/actions/workflows/ci.yml)

---

## 🧪 Additional Public Work

- **[TheLost](https://github.com/NRG-Wardog/TheLost)** — BLE proximity safety prototype using Android/Java, Python/Bleak, RSSI distance estimation, Firebase, isolated proximity logic, tests, and CI.
- **[AntiVirus](https://github.com/NRG-Wardog/Antivirus)** — early C signature scanner with recursive directory scanning, quick/full scan modes, logging, and a documented progression into AYDO.
- **[Shoot-It](https://github.com/EladCohen08/Shoot-It)** — contributed the Windows implementation/fixes to a cross-platform screenshot automation utility.
- **[GifMaker](https://github.com/NRG-Wardog/GifMaker)** — early C project using linked structures, persistence, and OpenCV to build/edit/play frame sequences.

---

## 🧰 Core Stack

### 💻 Languages

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/x86%20Assembly-24292F?style=flat-square" alt="x86 Assembly" />
</p>

### 🛡️ Systems & Security

<p>
  <img src="https://img.shields.io/badge/Windows%20Internals-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Windows Internals" />
  <img src="https://img.shields.io/badge/Kernel%20%2F%20User--Mode-24292F?style=flat-square" alt="Kernel / User-Mode" />
  <img src="https://img.shields.io/badge/Endpoint%20Security-B31B1B?style=flat-square" alt="Endpoint Security" />
  <img src="https://img.shields.io/badge/EPP%20%2F%20EDR-8B0000?style=flat-square" alt="EPP / EDR" />
  <img src="https://img.shields.io/badge/ETW-0078D4?style=flat-square" alt="ETW" />
  <img src="https://img.shields.io/badge/IOCTL-4B5563?style=flat-square" alt="IOCTL" />
  <img src="https://img.shields.io/badge/YARA-5A1A1A?style=flat-square" alt="YARA" />
  <img src="https://img.shields.io/badge/Sigma-6B7280?style=flat-square" alt="Sigma" />
</p>

`Win32 API` · `Windows Services` · `Sysmon` · `IPC` · `Endpoint Telemetry` · `Detection Engineering` · `Static & Dynamic Analysis` · `Reverse Engineering` · `Malware Sandboxing`

### 🧠 AI / ML / NLP

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square" alt="Transformers" />
  <img src="https://img.shields.io/badge/NLP-6F42C1?style=flat-square" alt="NLP" />
  <img src="https://img.shields.io/badge/Information%20Extraction-7C3AED?style=flat-square" alt="Information Extraction" />
  <img src="https://img.shields.io/badge/Semantic%20Matching-4F46E5?style=flat-square" alt="Semantic Matching" />
  <img src="https://img.shields.io/badge/Ranking-4338CA?style=flat-square" alt="Ranking" />
  <img src="https://img.shields.io/badge/Embeddings-5B21B6?style=flat-square" alt="Embeddings" />
  <img src="https://img.shields.io/badge/ASR-0F766E?style=flat-square" alt="ASR" />
  <img src="https://img.shields.io/badge/Speaker%20Diarization-115E59?style=flat-square" alt="Speaker Diarization" />
</p>

`NER` · `Text Classification` · `Training / Evaluation / Inference` · `Model Calibration` · `Data / ML Pipelines` · `Dataset Governance` · `Leakage Prevention` · `Shadow / Replay Evaluation` · `Statistical Evaluation`

### ⚙️ Backend & Data

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square" alt="WebSockets" />
</p>

`SQLAlchemy` · `Pydantic` · `OAuth 2.0 / PKCE` · `JWT` · `Async Workflows` · `Service Integrations` · `Data Processing`

### 🚀 Infrastructure & Engineering

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

`Testing` · `CI/CD` · `Observability` · `Structured Logging` · `Health Checks` · `Failure Recovery` · `Reliability Engineering`

### 📱 Frontend / Mobile

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
</p>

---

## ⚙️ Engineering Approach

I treat serious projects like products:

**Problem → Architecture → Implementation → Testing → Evaluation → Deployment → Observability**

I optimize for:

**correctness · reliability · performance · security · maintainability · data quality · measurable evaluation · explicit failure behavior**

I prefer **evidence over demos**: deterministic tests, reproducible data preparation, CI, metrics, failure handling, documented limitations, and clear operational behavior.

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dorian%20Salomon-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dorian-salomon/)
[![Email](https://img.shields.io/badge/Email-dorian123456785%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dorian123456785@gmail.com)
