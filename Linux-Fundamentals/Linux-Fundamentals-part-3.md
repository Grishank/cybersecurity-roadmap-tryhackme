# 🐧 Linux Fundamentals Part 3 (Completed ✅)

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Linux-Fundamentals-3.png?raw=true" 
       alt="Linux Fundamentals Part 3 Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Room Link:** https://tryhackme.com/room/linuxfundamentalspart3  
**Status:** ✅ Completed  

---

### 🧠 What I Learned
- Learned how to **deploy and access** a Linux machine reliably for real-world cybersecurity labs.  
- Understood how **terminal text editors** (especially `nano`) work for creating and modifying configuration files — a core skill in Linux administration and security.  
- Explored essential **utilities** that help in data manipulation:  
  - `wc` → count lines, words, characters  
  - `sort` → sort data alphabetically or numerically  
  - `uniq` → remove duplicate lines  
  - `cut` → extract specific columns from text  
  These tools are heavily used in log analysis and pipeline workflows.  
- Gained understanding of **process management**:
  - `ps` → list running processes  
  - `top` → realtime process + resource usage  
  - `kill` → terminate a process  
  These skills are critical for system monitoring and stopping malware or suspicious programs.  
- Learned **automation basics** using cron jobs — scheduling tasks like backups, scans, and maintenance.  
- Understood **package management** (`apt`):  
  - `apt update` → refresh package list  
  - `apt install` → install software  
  - `apt upgrade` → update system packages  
  This is essential for securing systems by keeping tools and dependencies updated.  
- Explored **system logs** inside `/var/log` — the heart of incident response, troubleshooting, and monitoring.
  - `/var/log/auth.log` → login attempts  
  - `/var/log/syslog` → system messages  
  - `/var/log/dpkg.log` → installed packages  
  Understanding logs is a fundamental SOC analyst skill.

---

### 🧩 Key Concepts
- Text editors are used for configuration, scripting, and system-level edits.  
- Utilities like `sort`, `uniq`, and `cut` help analyze and filter large text files and logs.  
- Processes represent all running programs, and knowing how to list, inspect, and kill them is vital for security.  
- Cron jobs automate repetitive tasks like scanning, updating, or monitoring.  
- Package managers keep systems secure with timely updates and installation of required tools.  
- Logs are one of the most important sources of truth in cybersecurity investigations.

---
