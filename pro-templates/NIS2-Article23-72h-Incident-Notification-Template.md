# EU NIS2 DIRECTIVE — ARTICLE 23(4)(b)
## 72-HOUR INCIDENT NOTIFICATION TEMPLATE
*For submission to National CSIRT / Competent Authority within 72 hours of becoming aware of a significant incident.*

---

### CONFIDENTIALITY & LEGAL NOTICE
Submitted pursuant to **Article 23(4)(b) of Directive (EU) 2022/2555**. This document updates the 24-Hour Early Warning previously registered under CSIRT Incident Reference: **[INSERT CSIRT TICKET #]**.

---

### SECTION 1: INCIDENT OVERVIEW & REVISED TRIAGE
1. **Entity Name & Reference ID**: [Company Name] | [National Registration ID]
2. **CSIRT Reference Case ID**: [From 24h Early Warning receipt]
3. **Date & Time of this Update**: `YYYY-MM-DD HH:MM UTC`
4. **Current Status of Incident**:
   - [ ] Ongoing — Active threat eradication in progress
   - [ ] Contained — Threat isolated, systems operating in restricted/safe mode
   - [ ] Eradicated — Malicious artifacts removed, recovery undergoing verification
   - [ ] Restored — Normal operational baselines recovered

---

### SECTION 2: INITIAL SEVERITY & IMPACT ASSESSMENT
1. **Impact Categorization**:
   - **Service Availability**: [e.g., Total outage 3.5 hours; 40% degraded throughput for 18 hours]
   - **Data Confidentiality**: [ ] Confirmed breach [ ] Suspected exfiltration [ ] No evidence of breach
   - **Data Integrity**: [ ] Data altered / encrypted [ ] No unauthorized modification detected
2. **Quantitative Impact**:
   - Number of affected natural persons / data subjects: [Count]
   - Number of affected enterprise customers / third-party entities: [Count]
   - Geographical distribution of impact across EU Member States: [List countries and impact level]
3. **Financial & Operational Impact Estimates**:
   - Direct response costs to date: €[XX,000]
   - Business interruption loss estimate: €[XX,000]

---

### SECTION 3: TECHNICAL DETAILS & INDICATORS OF COMPROMISE (IoCs)
1. **Attack Vector / Root Vulnerability**:
   - [ ] Exploitation of known vulnerability: [CVE-XXXX-XXXXX]
   - [ ] Zero-day software flaw in [Product / Dependency Name]
   - [ ] Credential stuffing / compromise of administrative account (MFA bypass or absent)
   - [ ] Phishing / Social Engineering vector
   - [ ] Third-Party / Vendor supply chain compromise: [Specify Vendor]
2. **Indicators of Compromise (IoCs) for CSIRT Dissemination**:
   - **Malicious IP Addresses**: `[e.g., 198.51.100.23, 203.0.113.88]`
   - **File Hashes (SHA-256)**: `[e.g., e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855]`
   - **C2 Domains / URIs**: `[e.g., bad-c2-update.example.com]`
   - **Attacker Tactics, Techniques, and Procedures (MITRE ATT&CK)**: `[e.g., T1190, T1059.001, T1078]`

---

### SECTION 4: MITIGATION MEASURES IMPLEMENTED & PLANNED
1. **Containment Measures**:
   - Network segmentation and firewall egress filtering updated
   - Global session invalidation and enterprise-wide password resets performed
   - Emergency software patch deployed across infrastructure
2. **Business Continuity & Redundancy Execution**:
   - Cold/Warm standby failover activated at `HH:MM UTC`
   - Verified immutable backups restored; integrity checks validated

---

### SECTION 5: STAKEHOLDER & REGULATORY NOTIFICATIONS
- **GDPR Article 33/34 Data Protection Authority (DPA)**:
  - [ ] Notified on [Date] / Reference: [DPA Ticket #]
  - [ ] Not applicable (no personal data involved)
- **Affected Customers / End Users**:
  - [ ] Customer advisory issued on [Date]
  - [ ] Notification pending forensic certainty

---

### SECTION 6: NEXT MILESTONES
- **Final Incident Report Due Date**: `YYYY-MM-DD` *(Within 1 month of incident resolution)*
- **Contact for Technical Inquiries**: [Forensic Lead / Security Ops Manager]
