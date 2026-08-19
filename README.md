# 👋 Hi, I'm Dorian Salomon

### Windows Endpoint Security | C/C++ Systems | Applied AI/ML

**C · C++ · Python · Windows Internals · Endpoint Security · Machine Learning · NLP**

I build systems at the intersection of **endpoint security, systems programming, and applied AI/ML**.

My main technical focus is Windows endpoint security — working with **kernel/user-mode components, endpoint telemetry, detection pipelines, malware analysis, backend infrastructure, and defensive engineering**.

Alongside security research and development, I work on production AI systems at **HigherYou**, turning large amounts of real-world and unstructured information into structured data, matching signals, automation, and actionable decisions.

---

## 🚀 Featured Projects

### 🛡️ [AYDO](https://github.com/NRG-Wardog/Aydo)

**Windows Endpoint Protection Platform — EPP / AV / EDR**

AYDO is my primary security engineering project: a Windows endpoint protection platform built to explore and implement the architecture behind modern endpoint-security products.

The system spans the endpoint, detection layer, backend infrastructure, sandbox environment, and management tooling.

**Key areas:**

* Windows kernel driver development
* Kernel ↔ user-mode communication via IOCTL
* Windows services
* Endpoint telemetry with ETW / Sysmon
* Static file analysis
* Dynamic malware analysis
* Hash and signature-based detection
* YARA scanning
* Sigma-based detection logic
* Real-time protection
* Self-protection mechanisms
* VMware-based isolated sandboxing
* C++ backend services
* Authentication and server APIs
* Malware intelligence / rule update pipelines
* Desktop management application
* Testing, diagnostics, and CI/CD

**Stack**

`C++` · `Windows` · `Kernel Development` · `ETW` · `Sysmon` · `YARA` · `Sigma` · `Drogon` · `PostgreSQL` · `VMware`

> **Status:** Active development

---

### 🧠 [SpamGuard](https://github.com/NRG-Wardog/SpamGuard)

**Transformer-Based Email Spam Detection**

An end-to-end NLP project for classifying real email messages as spam or legitimate mail.

The project covers significantly more than model training — it includes data ingestion, preprocessing, evaluation, `.eml` parsing, Gmail integration, and usable inference.

**Highlights:**

* Fine-tuning **XLM-RoBERTa**
* Multiple public email datasets
* Data ingestion and normalization
* Content deduplication
* Tokenization and preprocessing
* Precision / Recall / F1 evaluation
* ROC-AUC analysis
* Confusion matrices
* Raw `.eml` parsing
* Batch inference
* Gmail OAuth integration
* Streamlit demo application
* Classical ML baseline for comparison

**Stack**

`Python` · `PyTorch` · `Transformers` · `Hugging Face` · `scikit-learn` · `Pandas` · `Streamlit`

---

### 🍔 [AdvancedWolt](https://github.com/AdvancedWolt/wolt)

**Full-Stack Multi-Client Platform & C++ Recommendation System — Team Project**

A multi-stage food-delivery platform built as a collaborative software-engineering project. The system combines a **C++ TCP recommendation service**, a **Node.js / Express REST API**, **React** web client, **React Native / Expo** mobile client, **MongoDB**, JWT authentication, and Docker-based deployment.

My work is represented directly in the repository's merged pull-request history, including contributions across the recommendation/data layer, backend architecture, search, restaurant and menu management, mobile authentication, ordering, and system integration.

**Selected contributions:**

* C++ recommendation and persistence architecture
* Recommendation ranking and user-product interaction logic
* Database abstraction, CRUD flows, rollback-safe persistence, and command/response architecture
* Backend MVC architecture and REST workflows
* Search functionality
* Restaurant and menu management with owner-based authorization
* Mobile authentication and protected flows
* Cart, ordering, order history, and cancellation flows
* Docker-based multi-service integration
* Automated and integration testing
* GitHub pull-request workflow and collaborative code review

**Stack**

`C++` · `Node.js` · `Express` · `MongoDB` · `React` · `React Native` · `Docker` · `REST` · `TCP` · `JWT`

> **Contribution note:** This is a collaborative repository under the **AdvancedWolt** organization. My contributions are visible in the merged PR history under `NRG-Wardog`.

---

### ♟️ [Chess Project](https://github.com/NRG-Wardog/Chess)

**C++ Chess Engine & Windows IPC Project**

A collaborative C++ chess project implementing game logic through an object-oriented architecture and communicating with a graphical frontend using **Windows named pipes**.

**Engineering concepts:**

* Object-oriented C++ design
* Inheritance and polymorphism
* Deterministic board-state management
* Piece-specific movement logic
* Legal-move validation
* Check, checkmate, and stalemate detection
* Self-check prevention and transactional rollback
* Windows named-pipe IPC
* Multi-component application architecture
* Deterministic automated tests
* Linux GCC and Windows MSVC CI

**Stack**

`C++` · `OOP` · `Windows` · `Named Pipes` · `IPC` · `CMake` · `CI`

> This was a **collaborative project developed by Dorian Salomon and Yan Silberg**.
> The original repository was hosted under my teammate's GitHub account; this fork preserves our shared project and development history.

---

### 🔔 [whenTheAnswer](https://github.com/NRG-Wardog/whenTheAnswer)

**Reliable Cross-Platform Monitoring & Automation**

A Windows/Linux monitoring system designed around reliability and defensive failure handling rather than aggressive retry behavior.

**Engineering features:**

* Persistent authenticated browser sessions
* Circuit breaker architecture
* `CLOSED / OPEN / HALF_OPEN` states
* Exponential backoff
* Request rate budgets
* Request throttling
* Persistent recovery state
* Controlled recovery probes
* Authentication-attempt limits
* Cross-platform notifications
* Failure-safe recovery

**Stack**

`Python` · `Playwright` · `Windows` · `Linux`

---

### 🛡️ [AntiVirus](https://github.com/NRG-Wardog/Antivirus)

**Early C Antivirus Scanner**

An earlier security project implementing recursive signature-based malware scanning.

**Features:**

* Signature-based detection
* Recursive directory scanning
* Full and quick scan modes
* Scan logging and reporting

This project represents an earlier stage of my security-development work and eventually evolved into the broader endpoint-security architecture explored in **AYDO**.

**Stack**

`C` · `Windows` · `Systems Programming`

---

## 🏢 Production Engineering — HigherYou

At **HigherYou**, I work on production systems involving AI, data processing, automation, and information understanding.

My work includes:

* NLP pipelines
* AI-powered information extraction
* Structured extraction from unstructured data
* Data normalization and validation
* Semantic and entity matching
* Candidate / job information processing
* Matching and ranking signals
* Automated decision pipelines
* Backend services
* Large-scale data ingestion
* Operational automation
* AI-assisted workflows

A large part of this production work is private, so my public repositories focus on engineering concepts and systems that can be demonstrated openly.

---

## 🔐 Security & Systems Focus

I'm particularly interested in:

`Windows Internals`
`Endpoint Security`
`EDR / EPP Architecture`
`Detection Engineering`
`Kernel Development`
`Endpoint Telemetry`
`ETW / Sysmon`
`PE Analysis`
`Static & Dynamic Analysis`
`Malware Sandboxing`
`YARA / Sigma`
`False-Positive Reduction`
`Secure Software Design`
`Reliability Engineering`

---

## 🤖 Applied AI / ML

My AI work is focused on turning models into usable systems rather than keeping them as isolated experiments.

**Typical pipeline:**

`Data → Processing → Model → Decision Logic → API → Workflow → Monitoring`

Areas of interest include:

`NLP` · `Transformers` · `Classification` · `Information Extraction` · `Semantic Matching` · `Model Evaluation` · `Data Quality`

---

## 🧰 Core Stack

### 💻 Languages

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
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

`Win32 API` · `Windows Services` · `Sysmon` · `IPC` · `Detection Engineering` · `Static & Dynamic Analysis` · `Reverse Engineering`

### 🧠 AI / ML / NLP

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square" alt="Transformers" />
  <img src="https://img.shields.io/badge/NLP-6F42C1?style=flat-square" alt="NLP" />
  <img src="https://img.shields.io/badge/Information%20Extraction-7C3AED?style=flat-square" alt="Information Extraction" />
  <img src="https://img.shields.io/badge/Semantic%20Matching-4F46E5?style=flat-square" alt="Semantic Matching" />
  <img src="https://img.shields.io/badge/Ranking-4338CA?style=flat-square" alt="Ranking" />
  <img src="https://img.shields.io/badge/NER-5B21B6?style=flat-square" alt="NER" />
  <img src="https://img.shields.io/badge/Model%20Evaluation-6366F1?style=flat-square" alt="Model Evaluation" />
</p>

`Text Classification` · `Data / ML Pipelines` · `Data Quality` · `Training / Evaluation / Inference`

### ⚙️ Backend & Data

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
</p>

`Async Workflows` · `Authentication` · `Service Integrations` · `Data Processing`

### 🚀 Infrastructure & Engineering

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

`Testing` · `CI/CD` · `Observability` · `Structured Logging` · `Reliability Engineering`

### 📱 Frontend / Mobile

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
</p>

---

## ⚙️ Engineering Approach

I prefer building systems end-to-end:

**Problem → Architecture → Implementation → Testing → Evaluation → Deployment → Monitoring**

I care about:

**correctness · reliability · performance · security · observability · maintainability · detection quality · false-positive control**

Every serious project should have:

**docs · tests · benchmarks · architecture · roadmap**

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dorian%20Salomon-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dorian-salomon/)

[![Discord](https://img.shields.io/badge/Discord-dori__so-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/dori_so)

[![Instagram](https://img.shields.io/badge/Instagram-dori__sal12-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/dori_sal12/)

---

![](https://showme-levis.vercel.app/api/visitors?username=NRG-Wardog)
