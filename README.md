# EU Cyber Shield 2026: Cyber Resilience Act (CRA) & NIS2 Self-Assessment Tool

[![EU 2026 Mandate](https://img.shields.io/badge/EU%20Mandate-2026%20Enforcement-blue.svg)](https://eroniichan.github.io/eu-cra-nis2-auditor/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20(Pure%20Vanilla)-success.svg)](https://eroniichan.github.io/eu-cra-nis2-auditor/)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-00F0FF.svg)](https://eroniichan.github.io/eu-cra-nis2-auditor/)

**EU Cyber Shield 2026** is a zero-dependency, single-file interactive compliance assessment application and SBOM policy generator tailored for European software vendors, SaaS founders, CTOs, and compliance officers navigating the **EU Cyber Resilience Act (CRA - Regulation (EU) 2024/2847)** and **NIS2 Directive (Directive (EU) 2022/2555)**.

---

## 🚀 Live Application
Access the tool directly in your browser:
**[https://eroniichan.github.io/eu-cra-nis2-auditor/](https://eroniichan.github.io/eu-cra-nis2-auditor/)**

*100% Client-side. No user data, architecture details, or vulnerability reports ever leave your browser.*

---

## ⚡ The 2026 European Regulatory Landscape

1. **Cyber Resilience Act (CRA - Reg. 2024/2847)**:
   - **September 2026 Milestone**: Mandatory **24-hour reporting** to ENISA and designated National CSIRTs of any actively exploited vulnerability or severe incident.
   - **December 2027 Milestone**: Full CE marking conformity, technical documentation file retention for 10 years, mandatory machine-readable SBOMs (CycloneDX / SPDX), and free 5-year security patch guarantees.
   - **Fines**: Up to **€15,000,000 or 2.5%** of global annual turnover.

2. **NIS2 Directive (Dir. 2022/2555)**:
   - Live national enforcement across all 27 EU member states (e.g. BSI in Germany, ANSSI in France, NCSC in Netherlands/Ireland).
   - **Article 20 (Board Liability)**: Personal liability and potential management suspensions for CEOs and board members failing to approve and oversee cybersecurity measures.
   - **Article 21**: 10 mandatory risk management pillars (supply chain audits, phishing-resistant MFA, immutable backups, encryption).
   - **Article 23 Incident Reporting SLAs**:
     * 24 Hours: CSIRT Early Warning.
     * 72 Hours: Intermediate Incident Notification with IoCs.
     * 1 Month: Comprehensive Final Report & Root Cause Analysis.
   - **Fines**: Up to **€10,000,000 or 2%** of global annual turnover for Essential Entities.

---

## 🛠️ Features

- **Statutory Scope & Fine Calculator**: Automatically detects whether your company is an **Essential Entity**, **Important Entity**, or under **Supply Chain Scrutiny**, calculating maximum statutory fine exposure based on headcount and annual revenue.
- **Interactive CRA Auditor**: 12 checkpoints across Security-by-Design, Vulnerability Management (24h CSIRT), SBOM Lifecycle, and CE Marking.
- **Interactive NIS2 Auditor**: 12 checkpoints across Article 20 Board Governance, Article 21 Technical Controls, and Article 23 Incident Reporting SLAs.
- **Real-Time Gap Analysis & Prioritized Roadmap**: Highlights critical red flags that trigger statutory sanctions and provides actionable remediation guidance.
- **Automated SBOM & Security.txt Generator**:
  - Generates machine-readable **CycloneDX 1.6** and **SPDX 2.3** JSON files.
  - Generates RFC 9116 compliant `/.well-known/security.txt` and `SECURITY.md`.
  - Generates corporate SBOM Management Policy documents ready for SOC 2 / ISO 27001 / NIS2 supplier audits.
- **Executive Audit Export**: One-click printable PDF view and formatted Markdown audit report download.
- **Local Persistence & JSON Import/Export**: State is automatically saved in `localStorage`; export/import audit progress at any time.

---

## 💼 €9 Pro NIS2 & CRA Incident Response Pack

When an incident occurs or auditors request documentation, legal consultation fees often exceed €1,500/hr. The **Pro Pack** provides instant, production-ready Markdown and document templates:

1. **NIS2 Article 23(4)(a)**: 24-Hour CSIRT Early Warning Incident Notification Form
2. **NIS2 Article 23(4)(b)**: 72-Hour Detailed Incident Notification Template (IoCs, MITRE ATT&CK)
3. **NIS2 Article 23(4)(e)**: 1-Month Final Incident Report & Root Cause Analysis Form
4. **CRA Article 11(1)**: Actively Exploited Vulnerability Notification to ENISA
5. **NIS2 Article 20**: Management Board Resolution on Cybersecurity Governance & Personal Liability Shield
6. **NIS2 Article 21(2)(d)**: 25-Point Supply Chain Vendor Cybersecurity Risk Assessment Questionnaire

### Instant Evaluation Code
In the web application modal, enter code:
`EUR-RESILIENCE-2026` to unlock all 6 templates immediately.

---

## 📂 Repository Structure

```text
├── index.html                   # Single-file zero-dependency web application
├── pro-templates/               # Complete source documents for the €9 Pro Pack
│   ├── NIS2-Article23-24h-Early-Warning-Template.md
│   ├── NIS2-Article23-72h-Incident-Notification-Template.md
│   ├── NIS2-Article23-Final-Report-1Month-Template.md
│   ├── CRA-Article11-Actively-Exploited-Vulnerability-CSIRT-Notification.md
│   ├── NIS2-Article20-Management-Board-Cybersecurity-Resolution.md
│   └── EU-SupplyChain-Vendor-Security-Questionnaire-25pt.md
├── build_saas.py                # Build script embedding templates into index.html
├── REPORT.md                    # Deployment and architecture report
└── README.md                    # Project documentation
```

---

## 📜 License
Licensed under the [MIT License](LICENSE).
