# 🛡️ Windows 10 STIG Compliance – PowerShell Remediation Scripts

This repository contains PowerShell scripts developed by [Pukar Kafley](https://www.linkedin.com/in/pukar-kafley/) to remediate specific DISA STIG vulnerabilities for Windows 10 systems. Each script is named after the STIG ID it remediates and follows structured formatting for clarity, auditability, and automation.

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

---

## ⚙️ Usage

> Run scripts with **Administrator privileges**.  
> Ensure your execution policy permits scripts:
```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
