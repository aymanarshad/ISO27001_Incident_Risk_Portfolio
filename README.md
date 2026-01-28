# 🛡️ ISO 27001 Incident → Risk Mapping
### *Phishing Incident Portfolio & GRC Workflow*

[![Compliance: ISO 27001](https://img.shields.io/badge/Compliance-ISO_27001-blue.svg)](https://www.iso.org/standard/27001)
[![Category: GRC](https://img.shields.io/badge/Category-GRC_Operations-green.svg)]()
[![Status: Audit_Ready](https://img.shields.io/badge/Status-Audit_Ready-orange.svg)]()

This repository demonstrates a **hands-on ISO 27001 GRC workflow**. It bridges the gap between technical SOC operations and risk management by tracking a phishing attack from initial detection through to a formal Statement of Applicability (SoA) update.

---

## 📋 Scenario: Phishing & Credential Compromise

| Attribute | Details |
| :--- | :--- |
| **Incident ID** | `IR-2024-001` |
| **Asset at Risk** | Corporate Email System (SaaS) |
| **Primary Threat** | Social Engineering / Phishing |
| **Compliance Goal** | Documented audit trail for ISO 27001 Clause 6.1 & 10.1 |

---

## 📂 Project Structure
*Based on the organized portfolio directory:*

```bash
/ISO27001_Incident_Risk_Portfolio
├── 📁 1.Read me             # Documentation & Project Overview
├── 📁 2.Incident_Reports    # Full SOC-style investigation (RCA, Timelines)
├── 📁 3.Risk_Register       # Assessment of Inherent vs. Residual Risk
├── 📁 4.AnnexA_Mapping      # Direct alignment with ISO 27001:2022 Controls
├── 📁 5.SoA_Update          # Formal Statement of Applicability adjustments
└── 📁 6.Lessons_Learned     # Clause 10 - Continual Improvement logs

graph LR
    A[1. Incident Investigation] --> B[2. Risk Assessment]
    B --> C[3. Control Mapping]
    C --> D[4. SoA Validation]
    D --> E[5. Continual Improvement]
    
    style A fill:#f96,stroke:#333
    style E fill:#9f9,stroke:#333

🔍 Module Breakdown
📂 2. Incident_Reports
Contains the forensic and administrative breakdown of IR-2024-001. Includes detection details via SIEM alerts, impact assessment, and containment actions taken.

📂 3. Risk_Register
Demonstrates the quantification of risk. Includes "Before" (Inherent) and "After" (Residual) risk scores, highlighting how specific mitigations lowered the likelihood of recurrence.

📂 4. AnnexA_Mapping
Maps the incident to specific Annex A controls, including:

A.5.17: Authentication Management (MFA)

A.6.3: Information Security Awareness & Training

A.8.23: Web Filtering & Email Security

📂 5. SoA_Update
A Statement of Applicability update that reflects why these controls are applicable, their current implementation status, and justification for the security posture.

📂 6. Lessons_Learned
The "Continual Improvement" phase (Clause 10). This captures the Root Cause Analysis (RCA) and documents what will be monitored to prevent future credential compromise.

🚀 Portfolio Summary
"I investigated a phishing incident, updated the ISO 27001 risk register using incident evidence, mapped Annex A controls, and updated the Statement of Applicability. This project demonstrates practical experience in maintaining audit traceability and an active Information Security Management System (ISMS)."
