# 🚀 Gobuster: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Gobuster-The-Basics-banner.png?raw=true" alt="Gobuster The Basics Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Offensive Security Tooling  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/gobusterthebasics  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **Gobuster: The Basics** room introduced **Gobuster**, a popular offensive security enumeration tool commonly used for:
- Directory discovery
- File enumeration
- Subdomain enumeration
- Virtual host enumeration

The room demonstrated how attackers and security professionals use wordlists to discover hidden resources on web servers.

---

# 🎯 Learning Objectives

- Understand what Gobuster is
- Learn Gobuster syntax
- Perform directory enumeration
- Discover hidden files and folders
- Perform subdomain enumeration
- Understand virtual host enumeration
- Learn practical web reconnaissance concepts

---

# ⚙️ Task 2 — Environment and Setup

The room explained:
- Wordlists
- Target setup
- Enumeration workflow
- Gobuster modes

## Common Requirements

- Target URL/IP
- Wordlist
- Correct enumeration mode

---

# 🛠️ Task 3 — Gobuster Introduction

Gobuster is written in Go and is widely used during:
- Web reconnaissance
- Pentesting
- Bug bounty hunting
- Attack surface discovery

## Common Gobuster Modes

| Mode | Purpose |
|---|---|
| dir | Directory brute forcing |
| dns | Subdomain enumeration |
| vhost | Virtual host discovery |

---

# 📂 Task 4 — Directory and File Enumeration

Directory brute forcing helps discover:
- Hidden directories
- Backup files
- Admin panels
- Sensitive resources

## Example Command

```bash
gobuster dir -u http://target-ip -w /usr/share/wordlists/dirb/common.txt
```

## Useful Parameters

| Parameter | Purpose |
|---|---|
| -u | Target URL |
| -w | Wordlist |
| -x | File extensions |
| -t | Threads |
| -k | Skip SSL verification |

---

# 🌐 Task 5 — Subdomain Enumeration

Gobuster can identify hidden subdomains.

## Example Command

```bash
gobuster dns -d example.com -w subdomains.txt
```

## What This Helps Discover

- Development environments
- Admin portals
- Internal services
- Forgotten subdomains

---

# 🖥️ Task 6 — VHost Enumeration

Virtual host enumeration helps discover:
- Hidden websites
- Internal applications
- Multiple hosted services

## Example Command

```bash
gobuster vhost -u http://target-ip -w vhosts.txt
```

---

# 🔍 Key Enumeration Concepts

Enumeration helps attackers and defenders:
- Identify attack surface
- Discover hidden content
- Detect exposed services
- Locate sensitive resources

Common findings:
- Admin dashboards
- Backup archives
- Login portals
- Test environments

---

# 🛡️ SOC / Blue Team Perspective

SOC analysts should monitor for:
- Large numbers of HTTP requests
- Sequential directory probing
- Suspicious wordlist activity
- Enumeration scans from single IPs

## Common Detection Indicators

- Repeated 404 responses
- Rapid URL requests
- Enumeration patterns
- Abnormal scanning behavior

---

# 🧾 Key Concepts Learned

- Gobuster basics
- Enumeration workflows
- Directory brute forcing
- Subdomain discovery
- VHost enumeration
- Web reconnaissance

---

# 💬 Key Takeaway

> “Enumeration is one of the most important phases in offensive security because hidden directories, files, and subdomains often expose sensitive functionality.”

---

# 🚀 Next Steps

- Practice advanced Gobuster usage
- Learn ffuf and dirsearch
- Study web reconnaissance techniques
- Explore OWASP Top 10
- Continue web security tooling rooms
