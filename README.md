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

### ♟️ [Chess Project](https://github.com/NRG-Wardog/Chess-Project-Magshimim)

**C++ Chess Engine & Windows IPC Project**

A collaborative C++ chess project implementing game logic through an object-oriented architecture.

The project models pieces through dedicated classes, handles legal-move validation and game state, and communicates with a graphical frontend using **Windows named pipes**.

**Engineering concepts:**

* Object-oriented C++ design
* Inheritance and polymorphism
* Board-state management
* Piece-specific movement logic
* Move validation
* Check detection
* Exception-based error handling
* Windows named-pipe IPC
* Multi-component application architecture

**Stack**

`C++` · `OOP` · `Windows` · `Named Pipes` · `IPC`

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

### Languages

![C](https://img.shields.io/badge/C-00599C?style=flat\&logo=c\&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat\&logo=cplusplus\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat\&logo=python\&logoColor=white)

### Systems & Security

![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat\&logo=windows11\&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat\&logo=powershell\&logoColor=white)

`Windows Internals` · `Kernel Development` · `ETW` · `Services` · `IPC`

### AI / ML

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat\&logo=pytorch\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat\&logo=scikitlearn\&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat\&logo=pandas\&logoColor=white)

### Backend & Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat\&logo=fastapi\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat\&logo=docker\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat\&logo=nginx\&logoColor=white)

`REST APIs` · `Authentication` · `PostgreSQL / SQLite` · `Automation` · `Background Services`

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

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dorian%20Salomon-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/dorian-salomon/)

[![Discord](https://img.shields.io/badge/Discord-dori__so-5865F2?style=for-the-badge\&logo=discord\&logoColor=white)](https://discord.gg/dori_so)

[![Instagram](https://img.shields.io/badge/Instagram-dori__sal12-E4405F?style=for-the-badge\&logo=instagram\&logoColor=white)](https://www.instagram.com/dori_sal12/)

---

![](https://showme-levis.vercel.app/api/visitors?username=NRG-Wardog)
