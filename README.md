# Project 1: Enterprise Risk Assessment & Risk Register

## Executive Summary
This project simulates a qualitative cybersecurity risk assessment for **CloudScale Technologies**, a fictional 30 person SaaS startup that processes sensitive customer data in the cloud. Using principles from **NIST SP 800-30** , this project identifies organizational risks, evaluates their potential impact, and outlines mitigation plans to reduce business exposure.

---

## Fictional Company Profile
* **Company Name:** CloudScale Technologies
* **Industry:** SaaS / Cloud Solutions
* **Employee Count:** 30 remote employees
* **Core Assets:** AWS Cloud Infrastructure, Customer Database, Employee Laptops
* **Primary Compliance Target:** ISO 27001 / SOC 2 Type II

---

## Methodology (NIST SP 800-30 Alignment)
The assessment followed a four-step framework:
1. **Asset Identification:** Mapping critical systems, data, and users.
2. **Threat & Vulnerability Identification:** Pinpointing potential threat events and systemic weaknesses.
3. **Risk Analysis & Scoring:** Determining Likelihood and Impact on a simple 3x3 matrix (Low, Medium, High).
4. **Risk Response & Mitigation:** Selecting controls (Accept, Avoid, Mitigate, Transfer) and assigning ownership.

---

## Risk Evaluation Matrix

| Likelihood / Impact | Low Impact | Medium Impact | High Impact |
| :--- | :--- | :--- | :--- |
| **High Likelihood** | Medium Risk | High Risk | **Critical Risk** |
| **Medium Likelihood** | Low Risk | Medium Risk | High Risk |
| **Low Likelihood** | Low Risk | Low Risk | Medium Risk |

---

## Key Deliverables Included
* `risk_register.md`: Detailed qualitative risk log with risk IDs, descriptions, and scores.
* `remediation_plan.md`: Action items, assigned control frameworks, and implementation priorities.

---

## Key Takeaways
* Remote startups face high operational risks around credential management and unmanaged endpoint devices.
* Implementing Multi-Factor Authentication (MFA) and automated cloud backups provides the highest return on security investment (ROSI) for early-stage companies.
