# Micro-SaaS #3: EU Cyber Resilience Act (CRA) & NIS2 Readiness Auditor + SBOM Generator

**Deployment & Project Report — Agent #16**  
**Date**: October 29, 2026  
**Status**: Successfully Deployed to Production  

---

## 🌐 Live Deployments & URLs

- **Live Web Application (GitHub Pages)**:  
  👉 **[https://eroniichan.github.io/eu-cra-nis2-auditor/](https://eroniichan.github.io/eu-cra-nis2-auditor/)**
- **Public GitHub Repository**:  
  👉 **[https://github.com/EroNiiChan/eu-cra-nis2-auditor](https://github.com/EroNiiChan/eu-cra-nis2-auditor)**

---

## 🎯 Target Audience & 2026 Market Problem

The European cybersecurity regulatory landscape underwent a monumental shift in 2024-2026:
1. **NIS2 Directive (Directive (EU) 2022/2555)** enforcement is active across all 27 EU Member States. Essential and Important Entities face statutory fines up to **€10M or 2% of worldwide turnover**, with Article 20 introducing personal liability and potential managerial bans for CEOs and Board Members.
2. **Cyber Resilience Act (Regulation (EU) 2024/2847 - CRA)** establishes product cybersecurity requirements for all software and connected products sold in the EU. In **September 2026**, mandatory **24-hour reporting** of actively exploited vulnerabilities to ENISA and CSIRTs becomes legally binding, leading up to full CE Marking and SBOM obligations by late 2027 with fines up to **€15M or 2.5% of turnover**.
3. **The Micro-SaaS Opportunity**: Software vendors, SaaS startups, and IT suppliers struggle to know their legal status, lack machine-readable SBOM generators, and dread the prospect of drafting statutory incident notifications from scratch under a ticking 24-hour clock.

---

## 🏗️ Technical Architecture & Zero-Dependency Guarantee

- **Single-File Architecture (`index.html`)**: The entire frontend, interactive assessment engines, visual SVG gauges, SBOM generator, template viewer, and export tools are packaged into a single, self-contained `index.html` (125 KB).
- **Zero External Dependencies**: No third-party CDN scripts, no external analytics, no web fonts requiring external network access. Operates with 100% offline reliability.
- **Client-Side Privacy**: Compliance answers, employee counts, revenue figures, and vulnerability disclosures remain strictly within the user's browser `localStorage`.
- **Responsive Cybersecurity UI**: Custom dark/light mode cybersecurity dashboard featuring deep midnight tones (`#090D16`), electric cyan (`#00F0FF`), EU blue (`#003399`), and gold accents (`#F59E0B`).
- **Executive PDF & Print Engine**: Bespoke `@media print` CSS cleanly strips navigation and interactive controls, generating an audit-ready executive dossier for leadership and external certifiers.

---

## 📋 Core Capabilities Delivered

### 1. Statutory Scope & Fine Risk Engine
- Automated evaluation based on EU Headcount (<50, 50-249, 250+ FTE), Annual Turnover (<€10M, €10M-€50M, >€50M), and Sector classification.
- Automatically calculates NIS2 status (**Essential Entity**, **Important Entity**, or **Supply Chain Scrutiny**) and CRA track (**Module A Self-Assessment**, **Class I**, **Class II**, or **Critical**).
- Computes real-time maximum statutory fine liability (up to €15M+).

### 2. Interactive CRA Readiness Checklist (Annex I & Articles 10, 11, 13)
- 12 comprehensive checkpoints covering Attack Surface Minimization, Modern Cryptography, Exploit Mitigation, 24h CSIRT Active Exploit Pipeline, Coordinated Vulnerability Disclosure (`security.txt`), CI/CD Security Scanning, SBOM Tracking, Upstream Patch SLA (48-72h), 5-Year Free Security Update Guarantee, Signed OTA Updates, 10-Year Technical Documentation Archive, and CE Conformity.

### 3. Interactive NIS2 Readiness Checklist (Articles 20, 21, 23)
- 12 comprehensive checkpoints covering Board Cybersecurity Oversight & Approval (Art. 20(1)), Board Training & Liability Shield (Art. 20(2)), ISMS & Risk Analysis (Art. 21(2)(a)), Mandatory Phishing-Resistant MFA (Art. 21(2)(j)), Cryptography & KMS (Art. 21(2)(h)), Immutable Air-Gapped Backups (Art. 21(2)(c)), Supply Chain 25-Point Vendor Due Diligence (Art. 21(2)(d)), Continuous Vulnerability Management (Art. 21(2)(e)), Cyber Hygiene Training (Art. 21(2)(g)), Independent Effectiveness Audits (Art. 21(2)(f)), 24-Hour CSIRT Early Warning (Art. 23(4)(a)), and 72-Hour / 1-Month Incident Forensics Pipeline (Art. 23(4)(b),(e)).

### 4. SBOM & Coordinated Disclosure Suite
- Machine-readable **CycloneDX 1.6 (JSON)** and **SPDX 2.3 (JSON)** generator with components, package URLs (purls), SHA-256 hashes, and SPDX license identifiers.
- RFC 9116 compliant `/.well-known/security.txt` and `SECURITY.md` generator.
- Corporate SBOM & Vulnerability Disclosure Policy Markdown document generator.

### 5. Gap Analysis & Remediation Engine
- Animated circular SVG gauges for Overall Compliance Index, CRA score, and NIS2 score.
- Dynamic gap prioritization highlighting critical compliance red flags with concrete remediation instructions.
- Full JSON state export & import to save and resume audits.
- One-click Executive Audit Report download in GitHub Flavored Markdown.

---

## 💰 Monetization Architecture (€9 Upsell)

### The Problem it Solves
When a cybersecurity breach or actively exploited zero-day occurs, organizations have only **24 hours** to report it to the competent national CSIRT / ENISA. Engaging compliance law firms on an emergency retainer costs upwards of €1,200 to €2,500.

### The €9 Pro Incident Response Pack
The app provides an in-app purchase flow offering 6 production-grade legal and operational templates:
1. `NIS2-Article23-24h-Early-Warning-Template.md`: Mandatory initial filing for national CSIRTs.
2. `NIS2-Article23-72h-Incident-Notification-Template.md`: Detailed IoC, impact, and mitigation dossier.
3. `NIS2-Article23-Final-Report-1Month-Template.md`: Complete root cause analysis (RCA) and financial loss quantification.
4. `CRA-Article11-Actively-Exploited-Vulnerability-CSIRT-Notification.md`: Mandatory ENISA notification form.
5. `NIS2-Article20-Management-Board-Cybersecurity-Resolution.md`: Formal Board resolution to shield directors from personal liability.
6. `EU-SupplyChain-Vendor-Security-Questionnaire-25pt.md`: 25-point vendor questionnaire satisfying Article 21(2)(d).

### Checkout & Evaluation Flow
- Integrated with Stripe / Polar / LemonSqueezy payment buttons.
- Evaluation / Partner code redemption (`EUR-RESILIENCE-2026`) allowing reviewers to test instant unlock.
- Live syntax-highlighted document viewer with copy to clipboard, individual file downloads, and a bundled download of all 6 documents.

---

## 📦 File Inventory

| Path | Purpose |
|---|---|
| `index.html` | The single-file web application with embedded CSS, JS, SVG icons, and templates |
| `pro-templates/*.md` | 6 standalone markdown templates comprising the €9 Pro Pack |
| `build_saas.py` | Build script that embeds source templates into `index.html` |
| `README.md` | Public repository documentation, badges, and overview |
| `LICENSE` | MIT Open Source license |
| `REPORT.md` | This deployment and architecture report |

---

*Report prepared and submitted by Agent #16.*
