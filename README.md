# 👋 Hi, I'm Dorian Salomon

### Applied AI / NLP / ML | Windows Endpoint Security | C/C++ Systems

**Member of Technical Staff, AI @ HigherYou · Co-Founder & Security Engineer @ Aydo**

I build production systems across **applied AI/NLP, backend and data engineering, reliability, and Windows endpoint security**.

- At **HigherYou**, I own applied AI systems end-to-end across data ingestion, information extraction, normalization, semantic/entity matching, ranking, validation, backend integration, evaluation, and production reliability.
- At **Aydo**, I co-build a Windows endpoint-protection platform spanning kernel/user-mode components, endpoint telemetry, static/dynamic analysis, C++ backend services, and isolated malware sandboxing.
- **B.Sc. Computer Science @ Bar-Ilan University · GPA 89 · Expected Sep 2027**

---

## 🚀 Featured Engineering Work

### 🛡️ [AYDO](https://github.com/NRG-Wardog/Aydo)

**Windows Endpoint Protection Platform — EPP / AV / EDR**

A Windows security platform spanning kernel/user-mode telemetry, endpoint services, static and dynamic detection, isolated malware analysis, backend infrastructure, and desktop management.

**Highlights:** Windows kernel driver + IOCTL · ETW/Sysmon telemetry · YARA/Sigma detection flows · VMware sandboxing · C++20/Drogon backend · PostgreSQL · installer/update/self-test infrastructure.

**Evidence:** [Architecture](https://github.com/NRG-Wardog/Aydo/blob/production/docs/ARCHITECTURE.md) · [Security policy](https://github.com/NRG-Wardog/Aydo/blob/production/SECURITY.md)

---

### 🧠 [SpamGuard](https://github.com/NRG-Wardog/SpamGuard)

[![SpamGuard CI](https://github.com/NRG-Wardog/SpamGuard/actions/workflows/ci.yml/badge.svg)](https://github.com/NRG-Wardog/SpamGuard/actions/workflows/ci.yml)

**NLP Email Classification + Governed ML Data Pipeline**

End-to-end NLP/ML engineering around reproducible and auditable data preparation, evaluation, and inference.

**Highlights:** source provenance and allowed-use metadata · data-quality reporting · exact/conflicting-label deduplication · template clustering · deterministic train/validation/test splits · explicit leakage checks · transformer training/inference · `.eml` and read-only Gmail workflows · CI-tested pipeline invariants.

**Recorded experiment:** final test **F1 99.24%**, **ROC AUC 99.97%** in the committed notebook run; documented with explicit provenance and generalization caveats.

**Evidence:** [Results](https://github.com/NRG-Wardog/SpamGuard/blob/main/docs/RESULTS.md) · [ML engineering invariants](https://github.com/NRG-Wardog/SpamGuard/blob/main/docs/ML_ENGINEERING.md) · [CI](https://github.com/NRG-Wardog/SpamGuard/actions/workflows/ci.yml)

---

### 🍔 [AdvancedWolt](https://github.com/AdvancedWolt/wolt)

**Full-Stack Multi-Client Platform + C++ Recommendation System — Team Project**

Collaborative food-delivery platform combining a **C++ TCP recommendation service**, **Node.js / Express API**, **React**, **React Native / Expo**, **MongoDB**, JWT, and Docker.

My contribution is visible in **12 merged PRs**, including recommendation/persistence architecture, ranking logic, backend MVC/REST workflows, search, restaurant/menu management, mobile authentication, orders, and Docker integration.

**Representative PRs:** [#12 — C++ recommendation/data architecture + 46 tests](https://github.com/AdvancedWolt/wolt/pull/12) · [#29 — restaurant/menu management](https://github.com/AdvancedWolt/wolt/pull/29) · [#42 — mobile auth](https://github.com/AdvancedWolt/wolt/pull/42) · [#43 — cart/orders/history](https://github.com/AdvancedWolt/wolt/pull/43) · [#44 — management + Docker](https://github.com/AdvancedWolt/wolt/pull/44)

---

### ♟️ [Chess](https://github.com/ysilberg/Chess)

[![Chess CI](https://github.com/ysilberg/Chess/actions/workflows/ci.yml/badge.svg)](https://github.com/ysilberg/Chess/actions/workflows/ci.yml)

**C++ Chess Engine + Windows IPC — Collaborative Project**

Deterministic chess-engine logic with legal-move validation, check/checkmate/stalemate detection, transactional rollback for self-check prevention, board serialization, Windows named-pipe IPC, automated tests, CMake, and Linux/Windows CI.

**Evidence:** [Modernization PR #1](https://github.com/ysilberg/Chess/pull/1) · [CI](https://github.com/ysilberg/Chess/actions/workflows/ci.yml)

---

### 🔔 [whenTheAnswer](https://github.com/NRG-Wardog/whenTheAnswer)

[![whenTheAnswer CI](https://github.com/NRG-Wardog/whenTheAnswer/actions/workflows/ci.yml/badge.svg)](https://github.com/NRG-Wardog/whenTheAnswer/actions/workflows/ci.yml)

**Reliability-Focused Cross-Platform Monitoring**

Playwright-based monitoring with a modular Python package separating browser integration, snapshot persistence, runtime orchestration, and reliability controls; built around persistent sessions, a persistent `CLOSED / OPEN / HALF_OPEN` circuit breaker, request/rate budgets, retry/backoff, `Retry-After` handling, challenge detection, failure-safe recovery, deterministic tests, and CI.

**Evidence:** [Modular package](https://github.com/NRG-Wardog/whenTheAnswer/tree/main/watcher) · [Reliability invariants](https://github.com/NRG-Wardog/whenTheAnswer/blob/main/docs/RELIABILITY.md) · [CI](https://github.com/NRG-Wardog/whenTheAnswer/actions/workflows/ci.yml)

---

## 🏢 Production & Private Engineering Scope

Production engineering at **HigherYou since 2023**; **Member of Technical Staff, AI since Dec 2025**.

Work includes:

- NLP/ML extraction, classification, semantic/entity matching, ranking, validation, and decision pipelines
- large-scale/unstructured data ingestion and data-quality controls
- asynchronous backend services, APIs, WebSockets, PostgreSQL/SQLAlchemy, and external integrations
- ML evaluation: calibration, shadow/replay evaluation, statistical evidence gates, experiment tracking, and leakage controls
- multilingual speech/NLP pipelines including ASR, diarization, embeddings, and translation
- production reliability: observability, retries, health checks, diagnostics, retention, and failure recovery
- secure integrations with OAuth 2.0 / PKCE, JWT, encrypted secret storage, and audit logging

Product names, customer data, internal datasets, and private business logic are intentionally excluded.

---

## 🧪 Additional Public Work

- **[AntiVirus](https://github.com/NRG-Wardog/Antivirus)** — hardened C signature scanner with recursive traversal, bounded binary matching, normal/quick modes, deterministic MSVC smoke tests, and CI; historical progression toward AYDO.
- **[TheLost](https://github.com/NRG-Wardog/TheLost)** — BLE proximity prototype using Android/Java, Python/Bleak, RSSI estimation, Firebase, tests, and CI.
- **[GifMaker](https://github.com/NRG-Wardog/GifMaker)** — C frame-sequence editor using linked structures, persistence, and OpenCV.
- **[Shoot-It](https://github.com/EladCohen08/Shoot-It)** — contributed Windows implementation/fixes to a cross-platform screenshot automation utility.

---

## 🧰 Core Stack

**Languages**  
`C` · `C++` · `Python` · `Java` · `JavaScript` · `SQL` · `x86 Assembly`

**AI / ML / NLP**  
`PyTorch` · `Transformers` · `NLP` · `Information Extraction` · `Semantic Matching` · `Ranking` · `NER` · `Embeddings` · `ASR` · `Speaker Diarization` · `Model Evaluation` · `Calibration` · `Dataset Governance` · `Leakage Prevention`

**Systems & Security**  
`Windows Internals` · `Kernel/User-Mode` · `EPP/EDR` · `ETW` · `IOCTL` · `Win32 API` · `Windows Services` · `Sysmon` · `YARA` · `Sigma` · `IPC` · `Reverse Engineering` · `Static/Dynamic Analysis` · `Malware Sandboxing`

**Backend & Data**  
`FastAPI` · `Node.js` · `Express` · `PostgreSQL` · `MongoDB` · `SQLite` · `SQLAlchemy` · `Pydantic` · `REST` · `WebSockets` · `OAuth 2.0 / PKCE` · `JWT`

**Engineering**  
`Docker` · `Nginx` · `CMake` · `GitHub Actions` · `Linux` · `PowerShell` · `Git` · `Testing` · `CI/CD` · `Observability` · `Structured Logging` · `Reliability Engineering`

---

## ⚙️ Engineering Approach

**Problem → Architecture → Implementation → Testing → Evaluation → Deployment → Observability**

I optimize for **correctness, reliability, security, maintainability, data quality, measurable evaluation, and explicit failure behavior**.

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dorian%20Salomon-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dorian-salomon/)
[![Email](https://img.shields.io/badge/Email-dorian123456785%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dorian123456785@gmail.com)
