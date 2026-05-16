# 🔐 Cybersecurity 101 — TryHackMe Path

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

**Why this matters for SOC:**  
Most modern attacks target web applications.  
Understanding HTTP requests, responses, headers, cookies, and web traffic helps SOC analysts investigate phishing, web exploitation, malicious requests, authentication abuse, and suspicious web activity.

---

## 🎯 Status
✔ **Modules 1–7 Completed**

---

## 🚀 Next Steps
Continue with the remaining rooms in the **Cybersecurity 101** path to strengthen detection, investigation, exploitation awareness, and real-world SOC analysis skills.
