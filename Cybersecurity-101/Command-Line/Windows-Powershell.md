# 🪟 Windows PowerShell — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Windows-Powershell-banner.png?raw=true" alt="Windows PowerShell Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Command Line  
**Date Completed:** Dec 2025  
**Room Link:** [Windows Powershell](https://tryhackme.com/room/windowspowershell)                                             
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Windows PowerShell is a **powerful command-line shell and scripting language** built on the .NET framework. Unlike the traditional Windows Command Prompt, PowerShell works with **objects instead of plain text**, making it significantly more powerful for automation, administration, and investigation tasks.

For SOC analysts and defenders, PowerShell is a **double-edged sword** — widely used by system administrators, but also heavily abused by attackers for reconnaissance, lateral movement, and post-exploitation activity.

---

## 🎯 2. Learning Objectives  

This room focused on understanding PowerShell fundamentals and how it can be used to:

- Navigate and manage the file system  
- Retrieve system and network information  
- Filter, sort, and manipulate data using pipelines  
- Perform real-time system analysis  
- Understand basic PowerShell scripting concepts  

---

## 🧭 3. Key Concepts Learned  

- **Cmdlets** — PowerShell commands follow a `Verb-Noun` structure (e.g., `Get-Process`).  
- **Object-Based Output** — unlike CMD, PowerShell outputs structured objects.  
- **Pipelines (`|`)** — pass output from one cmdlet to another for filtering and analysis.  
- **Aliases** — shortcuts like `ls`, `dir`, `cat` mapped to PowerShell cmdlets.  
- **Scripting Basics** — automation using `.ps1` scripts.  
- **Administrative Power** — PowerShell can fully control the Windows environment.

---

## 🔎 4. Important Commands Practiced  

### 📌 System & Process Information
- `Get-Process` — list running processes  
- `Get-Service` — view system services and their state  
- `Get-ComputerInfo` — detailed system information  

### 🌐 Network Information
- `Get-NetIPAddress` — view IP configuration  
- `Test-Connection` — PowerShell version of ping  
- `Get-NetTCPConnection` — view active TCP connections  

### 📁 File System Navigation
- `Get-ChildItem` — list directory contents  
- `Set-Location` — change directory  
- `New-Item` / `Remove-Item` — create or delete files and folders  

### 🔄 Piping, Filtering & Sorting
- `Where-Object` — filter output  
- `Select-Object` — choose specific properties  
- `Sort-Object` — sort command output  

---

## ⚠ 5. Blue-Team / SOC Observations  

- **PowerShell is heavily abused by attackers** because it is built into Windows and trusted.  
- **Monitoring PowerShell logs (Event IDs 4103, 4104)** is critical for detection.  
- **Encoded commands and obfuscation** are common attacker techniques.  
- **Living-off-the-Land attacks** often rely on PowerShell instead of custom malware.  
- PowerShell activity provides **high-fidelity telemetry** when logging is enabled.

---

## 🧾 6. What I Learned (Bullets)  

- PowerShell is far more powerful than traditional CMD.  
- Object-based output enables advanced filtering and automation.  
- Many administrative tasks can be automated with minimal scripting.  
- Attackers frequently leverage PowerShell for stealthy operations.  
- Understanding normal PowerShell usage is essential for detecting abuse.

---

## 💬 Key Takeaway  

> *“PowerShell is one of the most powerful tools in Windows — mastering it is essential for both defense and detection in modern SOC environments.”*

---

## 📌 Next Steps  

- Continue with remaining **Cybersecurity 101** command-line rooms  
- Correlate PowerShell activity with Windows Event Logs  
- Learn common **PowerShell attack patterns** and detection strategies  
- Apply PowerShell knowledge to SOC investigations and automation

