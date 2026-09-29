# Risk Mitigation & Remediation Action Plan

This plan outlines the specific security controls chosen to reduce inherent risk down to an acceptable level (Residual Risk).

---

### 1. Account Takeover Prevention (RISK-01)
* **Risk Response Strategy:** Mitigate
* **Recommended Security Control:** Enforce Phishing-Resistant MFA across all Google Workspace and AWS cloud accounts.
* **Framework Alignment:** NIST CSF v2.0 PR.AA-01 (Identity & Access Management)
* **Priority:** Critical (Phase 1)
* **Owner:** Lead Systems Administrator

### 2. Endpoint Protection Implementation (RISK-02)
* **Risk Response Strategy:** Mitigate
* **Recommended Security Control:** Deploy centralized Endpoint Detection and Response (EDR) agents to all company-issued laptops. Enforce full-disk encryption (BitLocker / FileVault).
* **Framework Alignment:** NIST CSF v2.0 PR.PS-01 (Endpoint Security)
* **Priority:** High (Phase 1)
* **Owner:** IT Support Lead

### 3. Offboarding & Access Governance (RISK-03)
* **Risk Response Strategy:** Mitigate
* **Recommended Security Control:** Establish a standard Operating Procedure (SOP) requiring HR to notify IT immediately upon employee termination to revoke Single Sign-On (SSO) credentials within 2 hours.
* **Framework Alignment:** NIST CSF v2.0 PR.AA-02 (Access Control)
* **Priority:** High (Phase 2)
* **Owner:** HR & IT Operations

### 4. Automated Backup & Recovery Setup (RISK-04)
* **Risk Response Strategy:** Mitigate
* **Recommended Security Control:** Enable daily AWS snapshot backups with off-site retention policies and run quarterly recovery testing drills.
* **Framework Alignment:** NIST CSF v2.0 RC.RP-01 (Recovery Planning)
* **Priority:** Medium (Phase 2)
* **Owner:** DevOps Engineer

### 5. Secure Remote Access Policy (RISK-05)
* **Risk Response Strategy:** Accept / Mitigate
* **Recommended Security Control:** Issue an Acceptable Use Policy (AUP) requiring remote employees to connect via company VPN when using public Wi-Fi.
* **Framework Alignment:** NIST CSF v2.0 PR.IR-01 (Infrastructure Resilience)
* **Priority:** Low (Phase 3)
* **Owner:** Security & Compliance Officer
