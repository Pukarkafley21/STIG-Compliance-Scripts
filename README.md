# 🛡️ Windows STIG Compliance Scripts

PowerShell scripts to automate the remediation of **Security Technical Implementation Guide (STIG)** settings on Windows systems. This project helps achieve compliance with industry security standards (DISA STIGs), improving the overall security posture of your environment.

---

## 📌 Overview

This repository contains PowerShell scripts that:

- Audit Windows settings against STIG compliance requirements
- Automatically remediate non-compliant configurations
- Generate compliance reports
- Can be used in automated deployment pipelines (e.g., Intune, SCCM, or GPO startup scripts)

---

## 📜 Remediation Scripts

### 🔒 `WN10-00-000175` – Disable Secondary Logon Service
Disables the Secondary Logon service (`seclogon`), which allows users to run programs with alternate credentials — a potential vector for credential theft.
➡️ [View Script](https://github.com/Pukarkafley21/STIG-Compliance-Scripts-WN10/blob/main/WN10-00-000175.ps1)

---

### 🛡️ `WN10-AC-000005` – Configure Account Lockout Duration
Sets the account lockout duration to at least 15 minutes to mitigate brute-force password attacks on local accounts.
➡️ [View Script](https://github.com/Pukarkafley21/STIG-Compliance-Scripts-WN10/blob/main/WN10-AC-000005.ps1)

---

### 🌐 `WN10-CC-000238` – Prevent Certificate Error Overrides in Microsoft Edge
Configures Microsoft Edge to block users from bypassing SSL/TLS certificate warnings, protecting against man-in-the-middle attacks.
➡️ [View Script](https://github.com/Pukarkafley21/STIG-Compliance-Scripts-WN10/blob/main/WN10-CC-000238%20.ps1)

