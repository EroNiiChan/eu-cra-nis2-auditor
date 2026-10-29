# EU NIS2 DIRECTIVE — ARTICLE 23(4)(a)
## 24-HOUR EARLY WARNING INCIDENT NOTIFICATION TEMPLATE
*For submission to National CSIRT / Competent Authority within 24 hours of becoming aware of a significant incident.*

---

### CONFIDENTIALITY & LEGAL NOTICE
This notification is submitted pursuant to **Article 23(4)(a) of Directive (EU) 2022/2555 (NIS2 Directive)**. The information contained herein represents early-stage factual data based on initial triage and may be updated or refined in the subsequent 72-hour notification.

---

### SECTION 1: NOTIFYING ENTITY IDENTIFICATION
1. **Entity Legal Name**: [Insert Full Registered Company Name]
2. **National Registration Number (VAT / Commercial Register)**: [e.g., FR12345678901 / DE987654321]
3. **NIS2 Entity Classification**: 
   - [ ] Essential Entity (Annex I Sector)
   - [ ] Important Entity (Annex II Sector)
4. **Primary Sector / Sub-sector**: [e.g., Digital Infrastructure / Cloud Computing Services / Managed Service Provider]
5. **Headquarters Member State**: [e.g., Germany / France / Netherlands / Ireland]
6. **Designated Point of Contact for Incident Coordination**:
   - **Full Name**: [CISO / Incident Commander Name]
   - **Role / Title**: [e.g., Chief Information Security Officer]
   - **Direct Telephone (24/7)**: [+XX XXX XXXXXXX]
   - **Secure Email**: [security@company.eu / ciso@company.eu]
   - **PGP Fingerprint / Secure Channel**: [Insert PGP Key ID or Signal / Matrix Handle]

---

### SECTION 2: INCIDENT TIMELINE (UTC)
1. **Initial Point of Detection**: `YYYY-MM-DD HH:MM UTC`
2. **Time Entity Became Aware of Significant Impact**: `YYYY-MM-DD HH:MM UTC`
3. **Submission Timestamp**: `YYYY-MM-DD HH:MM UTC` *(Must be <= 24 hours from Awareness)*
4. **Estimated Incident Occurrence / Breach Start**: `YYYY-MM-DD HH:MM UTC` *(or Unknown)*

---

### SECTION 3: EARLY TRIAGE ASSESSMENT (ARTICLE 23(4)(a) MANDATORY ELEMENTS)
1. **Suspected Cause of Incident**:
   - [ ] Suspected Unlawful / Malicious Act (e.g., Ransomware, Advanced Persistent Threat, Unauthorized Intrusion, DDoS)
   - [ ] Software / System Vulnerability (e.g., 0-Day exploit, supply chain dependency compromise)
   - [ ] Technical / Infrastructure Failure (e.g., Power outage, cloud region failure, telecommunications disruption)
   - [ ] Human Error / Misconfiguration
   - [ ] Under Active Investigation (Preliminary evidence inconclusive)

2. **Cross-Border Impact Assessment**:
   - Could the incident have an impact on the provision of services in other EU Member States?
   - [ ] **YES** — Affected Member States: [List countries, e.g., DE, FR, NL, ES]
   - [ ] **NO** — Impact strictly confined to single national territory
   - [ ] **PENDING ANALYSIS** — Cross-border scope currently being evaluated

3. **Nature of Affected Systems / Services**:
   - Description of critical services degraded or compromised: [e.g., Customer Auth API, EU Datacenter Kubernetes Cluster, Production Database]
   - Number of affected users / client organizations (approximate): [e.g., 5,000 users / 45 corporate clients]

4. **Severity Indicators Triggering NIS2 Significance Threshold (Article 23(3))**:
   - [ ] Severe operational disruption of services (RTO > 4 hours)
   - [ ] Financial loss incurred or anticipated exceeds €[XX,000]
   - [ ] Suspected personal data breach / GDPR Article 33 report triggered in parallel
   - [ ] Potential material / physical damage or safety hazard

---

### SECTION 4: INITIAL CONTAINMENT & REMEDIATION MEASURES
- **Immediate containment actions taken**:
  1. [e.g., Network isolation of affected subnet `10.14.0.0/16` at 03:15 UTC]
  2. [e.g., Revocation of compromised API tokens and root credentials]
  3. [e.g., Standby disaster recovery environment initiated in secondary region]
- **External Assistance Engaged**:
  - [ ] External Incident Response Forensics Firm: [Firm Name]
  - [ ] Cloud Infrastructure Provider Security Team: [AWS / Azure / GCP / Hetzner]
  - [ ] Law Enforcement / Cyber Police contacted: [Case Reference # if applicable]

---

### SECTION 5: COMMITMENT FOR SUBSEQUENT NOTIFICATIONS
- **72-Hour Intermediate Notification Due Date**: `YYYY-MM-DD HH:MM UTC`
- **Authorized Signatory**:
  - Name: [CISO / Managing Director]
  - Signature / Digital Verification: [Digital Signature]
  - Date & Time: [Timestamp]
