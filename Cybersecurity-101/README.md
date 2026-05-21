# 🔐 Cybersecurity 101 — TryHackMe Path

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/THM-Cybersecurity-101.pdf?raw=true" alt="Cybersecurity-101" width="900"/>
</p>


This module contains all rooms completed from the **Cybersecurity 101** learning path on TryHackMe.  
It focuses on building core foundations in cybersecurity, research skills, threat understanding, Windows/AD fundamentals, and practical hands-on investigation concepts.

---

## 📘 Module 1 — Start Your Cybersecurity Journey

This module introduces the fundamentals of cybersecurity from both offensive and defensive perspectives, along with essential research/search skills.

### **Completed Rooms:**
- [Offensive Security Intro](../Introduction-to-Cybersecurity/Offensive-Security-Intro.md)  
- [Defensive Security Intro](../Introduction-to-Cybersecurity/Defensive-Security-Intro.md)  
- [Search Skills](./Start-Your-Cybersecurity-Journey/Search-Skills.md)

---

## 🐧 Module 2 — Linux Fundamentals

This module teaches the core concepts of Linux, navigation, permissions, essential commands, and system management — critical for every SOC analyst and ethical hacker.

### **Completed Rooms:**
- [Linux Fundamentals — Part 1](../Linux-Fundamentals/Linux-Fundamentals-part-1.md)  
- [Linux Fundamentals — Part 2](../Linux-Fundamentals/Linux-Fundamentals-part-2.md)  
- [Linux Fundamentals — Part 3](../Linux-Fundamentals/Linux-Fundamentals-part-3.md)

**Note:**  
These rooms were previously completed in the *Pre-Security Path* and fully documented in the dedicated Linux-Fundamentals module.  
They are referenced here to accurately map Cybersecurity 101 progression without duplicating content.

---

## 🪟 Module 3 — Windows & AD Fundamentals

This module covers Windows operating system basics, enterprise authentication concepts, and Active Directory — the backbone of identity management in most organizations.

### **Completed Rooms:**

#### **🔹 Windows Fundamentals (Completed Earlier — Linked)**  
- [Windows Fundamentals — Part 1](../Windows-Fundamentals/Part-1.md)  
- [Windows Fundamentals — Part 2](../Windows-Fundamentals/Part-2.md)  
- [Windows Fundamentals — Part 3](../Windows-Fundamentals/Part-3.md)

#### **🔹 Active Directory Basics (New Room in This Path)**  
- [Active Directory Basics](./Windows%20and%20Ad%20Fundamentals/Active-Directory-Basics.md)

**Note:**  
Windows Fundamentals 1, 2, and 3 were completed during the *Pre-Security Path* and are linked here for Cybersecurity 101 path completeness.  
Active Directory Basics is a new room specific to this path and is stored in the module folder.

---

## 💻 Module 4 — Command Line Fundamentals

This module focuses on mastering the **command-line interface (CLI)** and shell environments — critical skills for SOC analysts, incident responders, and defenders.  
It emphasizes speed, automation, scripting, and investigation across Windows and Linux systems.

### **Completed Rooms:**
- [Windows Command Line](./Command-Line/Windows-command-line.md)  
- [Windows PowerShell](./Command-Line/Windows-Powershell.md)  
- [Linux Shells](./Command-Line/Linux-Shells.md)

**Why this matters for SOC:**  
Command-line, PowerShell, and shell activity are heavily used during system administration *and* post-exploitation.  
Understanding normal shell behavior helps SOC analysts detect suspicious commands, scripts, privilege escalation attempts, and living-off-the-land attacks.

---

## 🌐 Module 5 — Networking Fundamentals

This module introduces the core networking concepts required for understanding how systems communicate and how attacks move across networks.

### **Completed Rooms:**
- [Networking Concepts](./Networking/Networking-Concepts.md)
- [Networking Essentials](./Networking/Networking-Essentials.md)
- [Networking Core Protocols](./Networking/Networking-Core-Protocols.md)
- [Networking Secure Protocols](./Networking/Networking-Secure-Protocols.md)
- [Wireshark: The Basics](./Networking/Wireshark-The-Basics.md)
- [Tcpdump: The Basics](./Networking/Tcpdump-The-Basics.md)
- [Nmap: The Basics](./Networking/Nmap-The-Basics.md)

**Why this matters for SOC:**  
Most attacks involve network activity. Understanding OSI layers, IP addressing, protocols, and encapsulation helps SOC analysts detect, triage, and investigate network-based threats effectively.

---

## 🔐 Module 6 — Cryptography & Password Security

This module focuses on **data protection, encryption, hashing, and password security**, which are essential for securing systems and understanding how attackers break weak implementations.

### **Completed Rooms:**
- [Cryptography Basics](./Cryptography/Cryptography-Basics.md)
- [Public Key Cryptography Basics](./Cryptography/Public-Key-Cryptography-Basics.md)
- [Hashing Basics](./Cryptography/Hashing-Basics.md)
- [John the Ripper: The Basics](./Cryptography/John-The-Ripper-The-Basics.md)

**Why this matters for SOC:**  
Cryptography protects sensitive data, but weak implementations can be exploited.  
SOC analysts must understand encryption, hashing, and password attacks to detect breaches, analyze compromised credentials, and identify security weaknesses.

---

## 💣 Module 7 — Exploitation Basics

This module introduces **real-world vulnerabilities, exploitation techniques, and detection strategies**, helping bridge the gap between theory and practical security incidents.

### **Completed Rooms:**
- [Moniker Link (CVE-2024-21413)](./Exploitation-Basics/Moniker-Link-(CVE-2024-21413).md)
- [Metasploit Introduction](./Exploitation-Basics/Metasploit-Introduction.md)
- [Metasploit Exploitation](./Exploitation-Basics/Metasploit-Exploitation.md)
- [Metasploit Meterpreter](./Exploitation-Basics/Metasploit-Meterpreter.md)
- [Blue](./Exploitation-Basics/Blue.md)

**Why this matters for SOC:**  
Understanding how vulnerabilities are exploited allows SOC analysts to detect attacks, identify Indicators of Compromise (IoCs), and respond effectively to real-world threats.

## 🌍 Module 8 — Web Hacking Fundamentals

This module introduces the foundations of **web applications, HTTP communication, URLs, headers, and web security concepts** that are critical for both attackers and defenders.

### **Completed Rooms:**
- [Web Application Basics](./Web-Hacking/Web-Application-Basics.md)
- [Javascript Essentials](./Web-Hacking/Javascript-Essentials.md)
- [SQL Fundamentals](./Web-Hacking/SQL-Fundamentals.md)
- [Burp Suite: The Basics](./Web-Hacking/Burp-Suite-The-Basics.md)

 Why this matters for SOC:
Most modern attacks target web applications.  
Understanding HTTP requests, responses, headers, cookies, and web traffic helps SOC analysts investigate phishing, web exploitation, malicious requests, authentication abuse, and suspicious web activity.

---

## ⚔️ Module 9 — Offensive Security Tooling

This module focuses on **commonly used offensive security tools and authentication attack techniques** used during penetration testing and security assessments.

### **Completed Rooms:**
- [Hydra](./Offensive-Security-Tooling/Hydra.md)
- [Gobuster: The Basics](./Offensive-Security-Tooling/Gobuster-The-Basics.md)
- [Shells Overview](./Offensive-Security-Tooling/Shells-Overview.md)
- [SQLMAP: The Basics](./Offensive-Security-Tooling/SQLMAP-The-Basics.md)

**Why this matters for SOC:**  
SOC analysts must understand how attackers use offensive tools to perform password attacks, brute-force authentication services, and abuse weak credentials.  
Knowledge of these tools helps defenders detect suspicious login activity, credential attacks, password spraying, and brute-force attempts in enterprise environments.

---

## 🛡️ Module 10 — Defensive Security Fundamentals

This module introduces the foundations of **Security Operations Centers (SOC), defensive monitoring, incident response workflows, and security operations processes** used by blue teams.

### **Completed Rooms:**
- [SOC Fundamentals](./Defensive-Security/SOC-Fundamentals.md)
- [Digital Forensics Fundamentals](./Defensive-Security/Digital-Forensics-Fundamentals.md)
- [Incident Response Fundamentals](./Defensive-Security/Incident-Response-Fundamentals.md)
- [Logs Fundamentals](./Defensive-Security/Logs-Fundamentals.md)

**Why this matters for SOC:**  
This module directly focuses on real-world SOC operations and defensive security workflows.

It helps build understanding of:
- SOC team structure
- Alert triage
- Incident response lifecycle
- Security monitoring
- SIEM and EDR technologies
- Threat investigation processes

These are core skills required for:
- SOC Analyst Level 1
- Blue Team operations
- Incident response roles
- Security monitoring careers

---
---

## 🖥️ Module 11 — Security Solutions

This module focuses on **security monitoring platforms, SIEM technologies, defensive infrastructure, and centralized detection systems** used by SOC teams to detect and investigate cyber threats.

### **Completed Rooms:**
- [Introduction to SIEM](./Security-Solutions/Introduction-to-SIEM.md)
- [Firewall Fundamentals](./Security-Solutions/Firewall-Fundamentals.md)
- [IDS Fundamentals](./Security-Solutions/IDS-Fundamentals.md)
- [Vulnerability Scanner Overview](./Security-Solutions/Vulnerability-Scanner-Overview.md)

**Why this matters for SOC:**  
SIEM platforms and defensive technologies are some of the most important systems used inside modern Security Operations Centers.

This module helps build understanding of:
- Centralized log collection
- Event correlation
- Alert generation
- Security monitoring workflows
- Threat detection pipelines
- Investigation and triage processes
- Defensive network protection
- Vulnerability management

These concepts are essential for:
- SOC Analyst Level 1
- Security monitoring roles
- Threat detection operations
- SIEM investigation workflows
- Blue Team analysis

---

## 🛠️ Module 12 — Defensive Security Tooling

This module focuses on **practical defensive security tools used during investigations, monitoring, analysis, and threat detection workflows** inside SOC environments.

### **Completed Rooms:**
- [CyberChef: The Basics](./Defensive-Security-Tooling/CyberChef-The-Basics.md)
- [CAPA: The Basics](./Defensive-Security-Tooling/CAPA-The-Basics.md)
- [REMnux: Getting Started](./Defensive-Security-Tooling/REMnux-Getting-Started.md)
- [FlareVM: Arsenal of Tools](./Defensive-Security-Tooling/FlareVM-Arsenal-of-Tools.md)

**Why this matters for SOC:**  
Defensive security analysts rely heavily on specialized tools to investigate suspicious activity and analyze malicious data efficiently.

This module helps build understanding of:
- Data decoding and transformation
- Payload analysis
- IOC extraction
- Threat investigation workflows
- Security data analysis
- Malware and phishing investigation support

These concepts are essential for:
- SOC Analyst Level 1
- Threat investigation workflows
- Blue Team operations
- Malware analysis support
- Incident response analysis
- Threat intelligence operations

---

## 🔐 Module 13 — Build Your Cyber Security Career

This module focuses on **foundational cybersecurity concepts, security principles, organizational security awareness, risk management, and defensive security models** that form the core mindset required for cybersecurity careers.

### **Completed Rooms:**
- [Security Principles](./Build-Your-Cyber-Security-Career/Security-Principles.md)
- [Training Impact on Teams](./Build-Your-Cyber-Security-Career/Training-Impact-on-Teams.md)

**Why this matters for SOC:**  
SOC analysts and cybersecurity professionals must understand core security concepts, organizational security culture, and defensive models before handling real-world incidents and investigations.

This module helps build understanding of:
- CIA Triad
- DAD Triad
- Defence-in-Depth
- Zero Trust
- Threat vs Risk
- Security awareness training
- Organizational security culture
- Security models
- Least privilege
- Layered security architecture

---

## 🌐 Module 14 — OWASP Top 10 (2025)

This module focuses on **modern web application security risks, authentication weaknesses, access control vulnerabilities, and logging failures** based on the OWASP Top 10 (2025).

### **Completed Rooms:**
- [OWASP Top 10 2025: IAAA Failures](./OWASP-Top-10/OWASP-Top-10-2025-IAAA-Failures.md)
- [OWASP Top 10 2025: Application Design Flaws](./OWASP-Top-10/OWASP-Top-10-2025-Application-Design-Flaws.md)
- [OWASP Top 10 2025: Insecure Data Handling](./OWASP-Top-10/OWASP-Top-10-2025-Insecure-Data-Handling.md)

**Why this matters for SOC:**  
SOC analysts frequently investigate web application attacks involving broken access control, authentication abuse, privilege escalation, and weak monitoring.

This module helps build understanding of:
- IAAA model
- Broken Access Control
- Authentication Failures
- Logging & Alerting Failures
- Session security
- Access management
- Accountability principles
- Web application defense

These concepts are essential for:
- SOC Analyst Level 1
- Web application security monitoring
- Threat detection engineering
- SIEM investigations
- Incident response
- Authentication security
- Identity and access management
- Defensive web security analysis

---

## 🎯 Status
✔ **Modules 1–14 Completed**

---

## 🚀 Next Steps
Continue with the remaining rooms in the **Cybersecurity 101** path to strengthen:
- Detection and monitoring
- Threat investigation
- Incident response
- Exploitation awareness
- Authentication security
- Web security analysis
- SIEM operations
- Threat detection engineering
- Malware investigation
- Defensive tooling workflows
- Security architecture concepts
- Risk management practices
- Access control security
- Web attack detection
- Real-world SOC analyst skills
