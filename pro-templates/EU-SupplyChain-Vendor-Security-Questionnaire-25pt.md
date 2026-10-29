# EU NIS2 & CRA SUPPLY CHAIN SECURITY QUESTIONNAIRE
## 25-POINT VENDOR & DIRECT SUPPLIER RISK ASSESSMENT
*Compliant with NIS2 Directive Article 21(2)(d) and Cyber Resilience Act (CRA) Third-Party Software Due Diligence.*

---

### INSTRUCTIONS FOR PROSPECTIVE / EXISTING VENDOR
Under **Directive (EU) 2022/2555 (NIS2)**, our organization is obligated to evaluate and monitor the cybersecurity practices of its direct suppliers and service providers. Please complete this 25-point audit within ten (10) business days.

- **Vendor Company Name**: [Vendor Legal Name]
- **Vendor Registration / VAT Number**: [Tax ID]
- **Product / Service Provided**: [Software, Cloud Service, Managed Service]
- **Assessment Completed By**: [Name, Title, Date]

---

### DOMAIN 1: GOVERNANCE & COMPLIANCE CERTIFICATIONS
1. **Security Certifications**: Does your organization hold valid ISO/IEC 27001, SOC 2 Type II, or C5 certifications?  
   - [ ] Yes *(Attach valid certificate)* | [ ] In progress | [ ] No
2. **Designated Security Lead**: Do you have a designated CISO or data security officer responsible for product security?  
   - [ ] Yes | [ ] No
3. **Third-Party Independent Audits**: Are independent external penetration tests conducted at least annually on systems servicing EU customers?  
   - [ ] Yes *(Provide executive summary)* | [ ] No
4. **GDPR & Data Residency**: Is customer data processed and stored strictly within the EU/EEA, or subject to valid adequacy mechanisms / SCCs?  
   - [ ] Yes | [ ] No

---

### DOMAIN 2: SOFTWARE SUPPLY CHAIN & SBOM (CRA ALIGNMENT)
5. **Software Bill of Materials (SBOM)**: Can your organization provide a machine-readable SBOM (CycloneDX or SPDX) for software deliverables?  
   - [ ] Yes | [ ] No
6. **Vulnerability Disclosure Policy**: Do you maintain a public Coordinated Vulnerability Disclosure (CVD) policy conforming to RFC 9116 (`security.txt`)?  
   - [ ] Yes | [ ] No
7. **Dependency Scanning in CI/CD**: Are automated dependency scanning and SAST/DAST tools embedded in your deployment pipelines?  
   - [ ] Yes | [ ] No
8. **Known Exploited Vulnerabilities (KEV)**: Do you have a formal SLA to patch actively exploited zero-days or CISA KEV flaws within 48 hours?  
   - [ ] Yes | [ ] No
9. **Tamper-Proof Code Delivery**: Are software releases cryptographically signed (e.g., Sigstore, GPG, Authenticode)?  
   - [ ] Yes | [ ] No

---

### DOMAIN 3: ACCESS CONTROL & IDENTITY MANAGEMENT
10. **Multi-Factor Authentication (MFA)**: Is phishing-resistant MFA mandatory across 100% of internal employees and contractors?  
    - [ ] Yes | [ ] No
11. **Principle of Least Privilege**: Are administrative permissions granted via Just-In-Time (JIT) access with automated session expiration?  
    - [ ] Yes | [ ] No
12. **Offboarding SLAs**: Are revoked employee access credentials systematically decommissioned within 4 hours of termination?  
    - [ ] Yes | [ ] No

---

### DOMAIN 4: ENCRYPTION & DATA PROTECTION
13. **Data Encryption in Transit**: Are all external and internal communications secured with TLS 1.3 (or strictly TLS 1.2+)?  
    - [ ] Yes | [ ] No
14. **Data Encryption at Rest**: Is all customer and configuration data encrypted at rest using AES-256 or equivalent cryptographic standards?  
    - [ ] Yes | [ ] No
15. **Key Management Isolation**: Are encryption keys managed in certified Hardware Security Modules (HSM) or dedicated KMS?  
    - [ ] Yes | [ ] No

---

### DOMAIN 5: INCIDENT HANDLING & NOTIFICATION SLAS (NIS2 ALIGNMENT)
16. **24-Hour Breach Notification SLA**: Do you contractually guarantee notification to our organization within 24 hours of detecting a suspected security incident?  
    - [ ] Yes | [ ] No
17. **Incident Response Playbook**: Do you maintain a tested incident response procedure updated within the last 12 months?  
    - [ ] Yes | [ ] No
18. **Forensic Evidence Preservation**: Are system audit logs immutably preserved for at least 12 months to facilitate forensic investigations?  
    - [ ] Yes | [ ] No

---

### DOMAIN 6: BUSINESS CONTINUITY & RESILIENCE
19. **Disaster Recovery RTO / RPO**: Are your Recovery Time Objective (RTO <= 4h) and Recovery Point Objective (RPO <= 1h) formally defined and tested?  
    - [ ] Yes | [ ] No
20. **Immutable Air-Gapped Backups**: Are production backups write-once-read-many (WORM) or physically isolated from ransomware threats?  
    - [ ] Yes | [ ] No
21. **Annual DR Tabletop Exercises**: Are disaster recovery and failover simulations conducted at least once per fiscal year?  
    - [ ] Yes | [ ] No

---

### DOMAIN 7: SUB-PROCESSOR & FOURTH-PARTY RISK
22. **Fourth-Party Tiering**: Do you maintain a public/updated inventory of all sub-processors and cloud infrastructure providers?  
    - [ ] Yes | [ ] No
23. **Contractual Security Flow-Down**: Do your sub-processor agreements legally enforce equivalent cybersecurity and audit clauses?  
    - [ ] Yes | [ ] No

---

### DOMAIN 8: PHYSICAL & OPERATIONAL HYGIENE
24. **Mandatory Employee Cyber Hygiene**: Do all staff receive mandatory phishing and security awareness training at least twice a year?  
    - [ ] Yes | [ ] No
25. **Right to Audit Clause**: Does your organization contractually permit on-site or third-party virtual security audits by our compliance officers?  
    - [ ] Yes | [ ] No

---

### VENDOR VERIFICATION & AUTHORIZATION
- Authorized Officer Name: _______________________
- Title: _______________________
- Company Stamp / Digital Signature: _______________________
- Date: `YYYY-MM-DD`
