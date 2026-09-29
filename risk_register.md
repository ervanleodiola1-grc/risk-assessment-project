# Qualitative Risk Register — CloudScale Technologies

Below are five core scenarios evaluated during the risk assessment. Risk levels are derived prior to applying new security controls (Inherent Risk).

| Risk ID | Risk Scenario | Threat Event | Vulnerability | Likelihood | Impact | Overall Risk Level |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **RISK-01** | Account Takeover | Phishing attack targets employee credentials to access cloud environment. | Lack of enforced Multi-Factor Authentication (MFA). | High | High | **CRITICAL** |
| **RISK-02** | Ransomware / Data Loss | Unencrypted employee laptop is infected with malware via email link. | Absence of Endpoint Detection & Response (EDR) software. | High | Medium | **HIGH** |
| **RISK-03** | Unauthorized Cloud Access | Former employee retains access to internal systems after departure. | No formal employee offboarding procedure or offboarding checklist. | Medium | High | **HIGH** |
| **RISK-04** | Service Outage | AWS Cloud database becomes corrupted during a software update. | Automated database backups are not configured or tested regularly. | Low | High | **MEDIUM** |
| **RISK-05** | Sensitive Data Leak | Employee shares customer data over an unencrypted, public Wi-Fi network. | No requirement or tool for Virtual Private Network (VPN) usage on remote devices. | Medium | Low | **LOW** |

---

### Risk Level Legend
* 🔴 **CRITICAL:** Immediate remediation required (within 7–14 days).
* 🟠 **HIGH:** Remediation required within 30 days.
* 🟡 **MEDIUM:** Remediation required within 60–90 days.
* 🟢 **LOW:** Accept risk or remediate during routine updates.
