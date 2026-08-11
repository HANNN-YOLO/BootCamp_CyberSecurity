# 🛡️ Cybersecurity BootCamp 2026

> **Portfolio repository for the Infotact Cybersecurity Technical Internship Program**

This repository documents my complete Cybersecurity BootCamp 2026 journey across **two engineering projects**:

1. 🔐 **Project 1 — Logistics & IoT Edge: Secure OTA Firmware Update & Code Signing Infrastructure**
2. 🏥 **Project 2 — HealthTech: Automated PHI/PII Redaction Pipeline for LLMs**

The repository combines both **team-based deliverables** and my **individual implementations**, including weekly learning activities, hands-on development, testing, security analysis, documentation, and final project outcomes.

The original internship specification defines three advanced cybersecurity project tracks and requires a transparent four-week GitHub development history for evaluation. This repository therefore keeps the learning process and implementation progress visible rather than presenting only the final result.

---

# 🎯 Repository Purpose

- 📚 Document the complete Cybersecurity BootCamp 2026 learning journey
- 👥 Preserve both team-project and individual-project contributions
- 🔐 Apply cybersecurity concepts through real engineering projects
- ⚙️ Practice cryptography, secure software development, automation, DevSecOps, NLP, privacy engineering, and security analysis
- 🧪 Document testing, validation, troubleshooting, and implementation progress
- 📝 Maintain a clear weekly development history through Git commits
- 🏆 Showcase the completed outcomes of Project 1 and Project 2

---

# 🗂️ Project Overview

| Project          | Domain               | Team Repository                   | Personal Repository   | Focus                                                                                                         |
| ---------------- | -------------------- | --------------------------------- | --------------------- | ------------------------------------------------------------------------------------------------------------- |
| 🔐 **Project 1** | Logistics & IoT Edge | `secure-ota-firmware-update`      | `secure-ota-firmware` | Secure OTA firmware distribution, signing, verification, versioning, and rollback protection                  |
| 🏥 **Project 2** | HealthTech           | `Health-Tech---Automated-PHI-PII` | `privacy-shield-llm`  | PHI/PII detection, pseudonymization, token mapping, Redis storage, restore, security analysis, and deployment |

---

# 📂 Project Repositories

## 🔐 Project 1 — Secure OTA Firmware

### 👥 Team Project

**Repository:**  
https://github.com/Gaurav167hue/secure-ota-firmware-update

**Project:**  
**Logistics & IoT Edge — Secure OTA Firmware Update & Code Signing Infrastructure**

**Team Scope**

The team repository contains the initial **Week 1 implementation**, covering:

- Public Key Infrastructure (PKI) setup
- Cryptographic hashing
- Firmware simulation
- Digital signing
- Signature verification
- Week 1 documentation

The project specification describes the objective as building a secure OTA framework in which firmware is digitally signed and an edge-device simulation verifies the firmware hash and signature before installation.

---

### 👨‍💻 Individual Project

**Repository:**  
https://github.com/HANNN-YOLO/secure-ota-firmware

My personal repository extends the team foundation into the complete four-week implementation:

- Week 1 — PKI & Cryptographic Foundations
- Week 2 — CI/CD Automated Code Signing
- Week 3 — OTA Client Development & Verification
- Week 4 — Secure OTA Hardening & Final Integration

---

# 🗺️ BootCamp Timeline

## 🚀 BootCamp Preparation

| Date          | Activity          |
| ------------- | ----------------- |
| June 06, 2026 | On Boarding       |
| June 07, 2026 | Division of Tasks |

---

## 📅 Week 1 — PKI Setup & Cryptographic Foundations

**June 08 – June 13, 2026**

| Date          | Day   | Activity                                      |
| ------------- | ----- | --------------------------------------------- |
| June 08, 2026 | Day 1 | Fundamental Cryptography                      |
| June 09, 2026 | Day 2 | SHA-256 Hashing                               |
| June 10, 2026 | Day 3 | Cryptography Library & ECDSA Key Generation   |
| June 11, 2026 | Day 4 | Firmware Simulation                           |
| June 12, 2026 | Day 5 | Digital Signature Generation                  |
| June 13, 2026 | Day 6 | Signature Verification & Week 1 Documentation |

### Week 1 Focus

- Understand cryptographic fundamentals
- Generate asymmetric keys
- Calculate SHA-256 firmware hashes
- Generate ECDSA signatures
- Verify firmware integrity and authenticity

---

## 📅 Week 2 — CI/CD Automated Code Signing

**June 14 – June 19, 2026**

| Date          | Day    | Activity                                       |
| ------------- | ------ | ---------------------------------------------- |
| June 14, 2026 | Day 8  | Git Workflow Fundamentals                      |
| June 15, 2026 | Day 9  | GitHub Actions Fundamentals                    |
| June 16, 2026 | Day 10 | Build GitHub Actions Workflow                  |
| June 17, 2026 | Day 11 | GitHub Secrets Management                      |
| June 18, 2026 | Day 12 | Python Workflow Integration                    |
| June 19, 2026 | Day 13 | Docker-based OTA Server & Week 2 Documentation |

### Week 2 Focus

- Automate firmware signing
- Integrate signing into GitHub Actions
- Protect private keys using GitHub Secrets
- Integrate Python scripts into the workflow
- Prepare a Docker-based OTA distribution environment

---

## 📅 Week 3 — OTA Client Development & Verification

**June 21 – June 26, 2026**

| Date          | Day    | Activity                                 |
| ------------- | ------ | ---------------------------------------- |
| June 21, 2026 | Day 15 | OTA Server Fundamentals                  |
| June 22, 2026 | Day 16 | Create OTA Request Client                |
| June 23, 2026 | Day 17 | Build Verification Logging               |
| June 24, 2026 | Day 18 | Firmware Hash Verification               |
| June 25, 2026 | Day 19 | Firmware Signature Verification          |
| June 26, 2026 | Day 20 | Testing Scenarios & Week 3 Documentation |

### Week 3 Focus

- Build the simulated OTA client
- Download firmware payloads
- Verify SHA-256 integrity
- Verify digital signatures
- Log verification results
- Reject invalid firmware

---

## 📅 Week 4 — Secure OTA Hardening & Final Integration

**June 28 – July 04, 2026**

| Date          | Day    | Activity                                  |
| ------------- | ------ | ----------------------------------------- |
| June 28, 2026 | Day 22 | Semantic Versioning                       |
| June 29, 2026 | Day 23 | Firmware Versioning                       |
| June 30, 2026 | Day 24 | Anti-Rollback Research                    |
| July 01, 2026 | Day 25 | Rollback Protection                       |
| July 02, 2026 | Day 26 | Threat Modeling                           |
| July 03, 2026 | Day 27 | Security Architecture Diagram             |
| July 04, 2026 | Day 28 | Final Documentation & Project Integration |

### Week 4 Focus

- Introduce firmware version control
- Research anti-rollback mechanisms
- Implement rollback protection
- Perform threat modeling
- Document the security architecture
- Integrate the complete OTA workflow

---

## 🏆 Project 1 — Final Outcome

The completed personal implementation covers:

- ✅ Public Key Infrastructure (PKI)
- ✅ SHA-256 Firmware Integrity Verification
- ✅ ECDSA Digital Signatures
- ✅ Automated Code Signing
- ✅ GitHub Actions CI/CD
- ✅ GitHub Secrets for Key Protection
- ✅ Docker-based OTA Server
- ✅ OTA Client Verification
- ✅ Firmware Versioning
- ✅ Anti-Rollback / Rollback Protection
- ✅ Threat Modeling
- ✅ Security Architecture
- ✅ End-to-End Secure OTA Workflow
- ✅ Technical Documentation

---

## 📊 Progress Tracking

| Phase                                                | Status       |
| ---------------------------------------------------- | ------------ |
| 🚀 BootCamp Preparation                              | ✅ Completed |
| 🔐 Week 1 — PKI & Cryptographic Foundations          | ✅ Completed |
| ⚙️ Week 2 — CI/CD Automated Code Signing             | ✅ Completed |
| 🌐 Week 3 — OTA Client Development & Verification    | ✅ Completed |
| 🛡️ Week 4 — Secure OTA Hardening & Final Integration | ✅ Completed |
| 🏆 Final Secure OTA Firmware Project                 | ✅ Completed |

---

## 🏥 Project 2 — HealthTech

### 👥 Team Project

**Repository:**  
https://github.com/Gaurav167hue/Health-Tech---Automated-PHI-PII

**Project:**  
**HealthTech — Automated PHI/PII Redaction Pipeline for LLMs**

**Team Scope**

The team repository focuses on the **Week 3 Mapping Engine deliverables**, including:

- Sensitive-data replacement
- Token mapping
- Redis-based mapping storage
- Mapping retrieval
- Restore of original sensitive values after the LLM response
- End-to-end pseudonymization flow validation
- Week 3 documentation

The project specification defines the core goal as protecting healthcare data before it reaches an external LLM while preserving enough context for the model to remain useful.

---

### 👨‍💻 Individual Project

**Repository:**  
https://github.com/HANNN-YOLO/privacy-shield-llm

My personal repository expands the HealthTech project into the complete four-week implementation:

- Week 1 — FastAPI Server
- Week 2 — Regex Detection
- Week 3 — NLP Detection & Mapping Engine
- Week 4 — Integration, Performance, Security & Documentation

---

# 🗺️ BootCamp Timeline

## 🚀 BootCamp Preparation

| Date          | Activity          |
| ------------- | ----------------- |
| June 06, 2026 | On Boarding       |
| July 13, 2026 | Division of Tasks |

## 📅 Week 1 — FastAPI Server

**July 13 – July 19, 2026**

| Date          | Day   | Activity                                                       |
| ------------- | ----- | -------------------------------------------------------------- |
| July 13, 2026 | Day 1 | API Architecture Research & REST API Fundamentals              |
| July 14, 2026 | Day 2 | FastAPI Project Initialization                                 |
| July 15, 2026 | Day 3 | API Endpoint Development                                       |
| July 16, 2026 | Day 4 | Request & Response Processing                                  |
| July 17, 2026 | Day 5 | API Validation & Error Handling                                |
| July 18, 2026 | Day 6 | Front-End Development, Back-End Refactoring & CORS Integration |
| July 19, 2026 | Day 7 | API Testing & Week 1 Documentation                             |

### Week 1 Focus

- Understand REST API architecture
- Initialize the FastAPI application
- Build API endpoints
- Process JSON requests and responses
- Validate incoming data
- Handle API errors
- Connect front-end and back-end using CORS
- Test and document the API

---

## 📅 Week 2 — Regex Detection

**July 20 – July 26, 2026**

| Date          | Day    | Activity                             |
| ------------- | ------ | ------------------------------------ |
| July 20, 2026 | Day 8  | Fundamental Regex Pattern Research   |
| July 21, 2026 | Day 9  | Email Detection Module               |
| July 22, 2026 | Day 10 | Phone Detection Module               |
| July 23, 2026 | Day 11 | Date Detection Module                |
| July 24, 2026 | Day 12 | Identity Detection Module            |
| July 25, 2026 | Day 13 | Regex Detection Pipeline             |
| July 26, 2026 | Day 14 | Regex Testing & Week 2 Documentation |

### Week 2 Focus

- Build structured PII detection rules
- Detect email addresses
- Detect phone numbers
- Detect dates
- Detect patient IDs and SSNs
- Combine detectors into a pipeline
- Validate detection against sample clinical notes

---

## 📅 Week 3 — NLP Detection & Mapping Engine

**July 27 – August 02, 2026**

| Date           | Day    | Activity                                        |
| -------------- | ------ | ----------------------------------------------- |
| July 27, 2026  | Day 15 | NLP & NER Research                              |
| July 28, 2026  | Day 16 | spaCy Integration                               |
| July 29, 2026  | Day 17 | Microsoft Presidio Integration                  |
| July 30, 2026  | Day 18 | Person Entity Detection                         |
| July 31, 2026  | Day 19 | Address Entity Detection                        |
| August 01,2026 | Day 20 | Context-Aware Detection                         |
| August 02,2026 | Day 21 | NLP Pipeline Integration & Week 3 Documentation |

### Mapping Engine Scope

The team project specifically emphasizes the Mapping Engine:

- Sensitive data replacement
- Token generation
- Token mapping
- Redis-based mapping storage
- Mapping retrieval
- Restore of original values after the LLM response
- End-to-end pseudonymization flow

### Week 3 Focus

- Move beyond basic Regex detection
- Integrate NLP and Named Entity Recognition
- Detect people, doctors, addresses, and locations
- Improve context-aware entity detection
- Preserve the relationship between original values and generated tokens
- Store mappings in Redis
- Prepare the data flow for restore after the LLM response

---

## 📅 Week 4 — Integration, Performance, Security & Deployment

**August 03 – August 09, 2026**

| Date            | Day    | Activity                                                           |
| --------------- | ------ | ------------------------------------------------------------------ |
| August 03, 2026 | Day 22 | Pseudonymization Engine                                            |
| August 04, 2026 | Day 23 | Redis Token Mapping Service                                        |
| August 05, 2026 | Day 24 | Restore Mapping Integration                                        |
| August 06, 2026 | Day 25 | System Validation & Performance Testing                            |
| August 07, 2026 | Day 26 | Threat Modeling & Security Analysis for PHI/PII Redaction Pipeline |
| August 08, 2026 | Day 27 | Project Documentation, Architecture & Security Report              |
| August 09, 2026 | Day 28 | Week 4 Documentation                                               |

### Week 4 Focus

- Build the pseudonymization engine
- Implement Redis token mapping
- Integrate mapping retrieval into the restore flow
- Validate the complete pipeline
- Measure processing and restore performance
- Perform PHI/PII threat modeling
- Document architecture and security considerations
- Finalize project documentation

---

# 🏆 Project 2 — Final Project Outcome

Based on the completed four-week implementation, the HealthTech project delivers:

- ✅ FastAPI-based privacy proxy foundation
- ✅ REST API request/response processing
- ✅ Request validation and error handling
- ✅ CORS-based front-end/back-end integration
- ✅ Regex-based structured PII detection
- ✅ Email detection
- ✅ Phone number detection
- ✅ Date detection
- ✅ Patient ID / SSN detection
- ✅ NLP and Named Entity Recognition
- ✅ spaCy integration
- ✅ Microsoft Presidio integration
- ✅ Person and healthcare-related entity detection
- ✅ Address and location detection
- ✅ Context-aware sensitive-entity detection
- ✅ Pseudonymization engine
- ✅ Token generation and mapping
- ✅ Redis-based mapping storage
- ✅ Restore pipeline
- ✅ End-to-end pseudonymization and restore validation
- ✅ Performance testing
- ✅ PHI/PII threat modeling
- ✅ Security architecture and project documentation

## 📊 Progress Tracking

| Phase                                           | Status       |
| ----------------------------------------------- | ------------ |
| 🚀 BootCamp Preparation                         | ✅ Completed |
| ⚡ Week 1 — FastAPI Server                      | ✅ Completed |
| 🔎 Week 2 — Regex Detection                     | ✅ Completed |
| 🧠 Week 3 — NLP Detection & Mapping Engine      | ✅ Completed |
| 🛡️ Week 4 — Integration, Performance & Security | ✅ Completed |
| 🏆 Final HealthTech Privacy Pipeline            | ✅ Completed |

---

# 🏅 BootCamp Completion Summary

| Project                        | Team Contribution | Individual Contribution | Final Status |
| ------------------------------ | ----------------- | ----------------------- | ------------ |
| 🔐 Secure OTA Firmware         | Week 1            | Weeks 1–4               | ✅ Completed |
| 🏥 HealthTech Privacy Pipeline | Week 3            | Weeks 1–4               | ✅ Completed |

# 🧩 Technical Skills Demonstrated

### 🔐 Security & Cryptography

- Public Key Infrastructure
- SHA-256
- ECDSA
- Digital signatures
- Firmware integrity verification
- Rollback protection
- Threat modeling
- Security architecture

### ⚙️ Backend & Automation

- Python
- FastAPI
- REST API
- JSON
- CORS
- GitHub Actions
- Docker
- Git & GitHub

### 🏥 Privacy Engineering & AI Security

- PHI/PII detection
- Regex-based detection
- NLP / NER
- spaCy
- Microsoft Presidio
- Pseudonymization
- Token mapping
- Redis
- Restore processing
- Privacy-preserving LLM integration

### 🧪 Engineering Practices

- Incremental development
- Automated workflows
- Testing and validation
- Performance testing
- Technical documentation
- Security analysis
- Structured Git history

---

# 🔒 Security & Development Principles

The internship specification emphasizes continuous and auditable development. The repository therefore follows these principles:

- 🔹 Keep development history visible through granular commits
- 🔹 Use descriptive semantic commit messages
- 🔹 Separate logical changes into appropriate commits
- 🔹 Track work through GitHub Issues / Projects where applicable
- 🔹 Use feature branches and Pull Requests
- 🔹 Never hardcode private keys, API keys, or credentials
- 🔹 Use environment variables and GitHub Secrets for sensitive configuration
- 🔹 Never expose real PHI, PII, enterprise logs, or credentials in documentation
- 🔹 Treat security as a continuous engineering process

---

# 📚 Project Specification Reference

The project requirements are based on the **Infotact Technical Internship Program — Advanced Cybersecurity Project Specifications and Evaluation Criteria**.

The specification covers:

- Project 1 — Logistics & IoT Edge / Secure OTA Firmware
- Project 2 — HealthTech / Automated PHI/PII Redaction Pipeline for LLMs
- Project 3 — Enterprise Cloud / SOAR Incident Containment Engine
- Four-week engineering roadmaps
- GitHub contribution and version-control requirements
- Security and credential-management requirements

---

# 👨‍💻 Author

**HANNN-YOLO**

Cybersecurity BootCamp 2026

**Projects**

- 🔐 Secure OTA Firmware Update & Code Signing Infrastructure
- 🏥 HealthTech Automated PHI/PII Redaction Pipeline for LLMs

---

> 🛡️ **Learn → Build → Test → Secure → Document**
>
> This repository represents the complete progression from cybersecurity fundamentals to practical security engineering and privacy-focused application development.
