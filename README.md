# 🛡️ ISO 27001 Incident → Risk Mapping
### *Phishing Incident Portfolio & GRC Workflow*

[![Compliance: ISO 27001](https://img.shields.io/badge/Compliance-ISO_27001-blue.svg)](https://www.iso.org/standard/27001)
[![Category: GRC](https://img.shields.io/badge/Category-GRC_Operations-green.svg)]()
[![Status: Audit_Ready](https://img.shields.io/badge/Status-Audit_Ready-orange.svg)]()

This folder demonstrates a **hands-on ISO 27001 GRC workflow**. It documents the lifecycle of a phishing attack from initial detection through risk assessment and control implementation, culminating in a formal Statement of Applicability (SoA) update.

---

## 📋 Scenario Overview

| Attribute | Details |
| :--- | :--- |
| **Incident ID** | `IR-2024-001` |
| **Incident Type** | Phishing → Credential Compromise |
| **Primary Asset** | Corporate Email System (SaaS) |
| **Objective** | Bridge the gap between SOC operations and GRC documentation. |

---

## 📂 Folder Structure

```bash
/incident-to-risk-mapping
├── 📄 incident-report.md       # Full SOC investigation & RCA
├── 📊 risk-register-before.xlsx # Pre-incident risk posture
├── 📊 risk-register-after.xlsx  # Post-mitigation residual risk
├── 🔗 annex-a-mapping.md        # Alignment with ISO 27001 Annex A
├── 📑 soa-update.xlsx           # Statement of Applicability update
└── 💡 lessons-learned.md        # Clause 10 - Continual Improvement

---

graph LR
    A[Incident Logged] --> B[Impact Assessment]
    B --> C[Risk Treatment]
    C --> D[Annex A Alignment]
    D --> E[SoA Update]
    E --> F[Clause 10 Improvement]
    style A fill:#f96,stroke:#333,stroke-width:2px
    style F fill:#9f9,stroke:#333,stroke-width:2px



🔍 File Descriptions

1️⃣ incident-report.md
A detailed SOC-style report capturing the "Who, What, and How."

Key Sections: Detection timeline, impact assessment, containment/recovery, and Root Cause Analysis (RCA).

2️⃣ risk-register-before.xlsx / after.xlsx
Demonstrates the quantification of risk using Likelihood (L) x Impact (I) scoring.

Before: High inherent risk due to "Human Element" vulnerabilities.

After: Reduced Residual Risk following the implementation of MFA and automated mail filtering.

3️⃣ annex-a-mapping.md
Direct mapping of the incident to specific ISO 27001:2022 Controls:

A.5.17: Authentication Management (MFA enforcement)

A.6.3: Info. Sec. Awareness & Training

A.8.23: Web Filtering & Email Security

4️⃣ soa-update.xlsx
The definitive document for auditors. Shows how this specific incident justified the continued applicability of controls and documented their current implementation status.

5️⃣ lessons-learned.md
Addresses ISO 27001 Clause 10. This captures what failed in the control environment and how the ISMS (Information Security Management System) was adjusted to prevent recurrence.

🚀 Professional Summary
"I bridge the gap between technical incidents and organizational risk. By investigating this phishing breach, I didn't just 'fix' the email; I updated the ISO 27001 Risk Register, mapped Annex A controls, and ensured the Statement of Applicability reflected our new security posture. This ensures audit traceability and continuous improvement."
