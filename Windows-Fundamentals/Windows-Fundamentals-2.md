
# 🪟 Windows Fundamentals Part 2 (Completed ✅)

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Windows-Fundamentals-2.png?raw=true" alt="Windows Fundamentals Part 2 - TryHackMe Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Date Completed:** November 2025  
**Room Link:** https://tryhackme.com/room/windowsfundamentals2x0x  
**Status:** ✅ Completed  

---

## 🧠 What I Learned

### 🔹 1. Introduction
- Continued exploring core Windows management components.
- Learned how different system utilities interact with each other.

---

### 🔹 2. System Configuration (msconfig)
- Used **msconfig** to manage:
  - Boot options  
  - Startup services  
  - Diagnostic boot  
- Important for SOC when analyzing:
  - Suspicious services  
  - Unwanted startup programs  
  - Boot modifications by malware  

---

### 🔹 3. Changing UAC Settings
- Understood how to modify **User Account Control**.
- UAC levels determine:
  - How often admin prompts appear  
  - Whether elevation requires confirmation  
- Recognized how attackers try to **disable or bypass UAC**.

---

### 🔹 4. Computer Management
- Explored components inside Computer Management:
  - **Event Viewer**  
  - **Local Users & Groups**  
  - **Task Scheduler**  
  - **Disk Management**  
- Learned how SOC teams use it to check:
  - Unauthorized accounts  
  - Suspicious scheduled tasks  
  - Disk anomalies  

---

### 🔹 5. System Information (msinfo32)
- Used to gather:
  - Hardware info  
  - OS version  
  - BIOS details  
  - Drivers  
- Helps analysts confirm:
  - System integrity  
  - Hardware-based attacks  
  - Outdated components  

---

### 🔹 6. Resource Monitor
- Learned to analyze:
  - CPU usage  
  - Memory usage  
  - Disk activity  
  - Network connections  
- Helps detect:
  - Malicious processes consuming resources  
  - Strange connections (C2, reverse shells)  

---

### 🔹 7. Command Prompt
- Explored basic and important commands:
  - `ipconfig`  
  - `tasklist`  
  - `whoami`  
  - `net user`  
  - `systeminfo`  
- Learned why attackers often prefer **cmd.exe** for enumeration.

---

### 🔹 8. Registry Editor (regedit)
- Understood the structure:
  - HKEY_LOCAL_MACHINE (HKLM)  
  - HKEY_CURRENT_USER (HKCU)  
- Registry is used to:
  - Manage startup items  
  - Modify system behavior  
  - Persist malware  
- Critical for SOC incident response.

---

## ⚙️ Key Takeaways

> “Part 2 teaches the real tools SOC Analysts use daily — Event Viewer, Registry, system utilities, and command-line investigation.”

- System Configuration reveals suspicious startups  
- Registry is a major target for persistence  
- Resource Monitor detects stealthy malware  
- Computer Management centralizes all critical admin tools  

---

## 🧩 Next Steps

- Continue to **Windows Fundamentals Part 3** --

---
