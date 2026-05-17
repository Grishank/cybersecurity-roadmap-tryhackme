# 💉 SQLMap: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/SQLMap-The-Basics-banner.png?raw=true" alt="SQLMap The Basics Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Offensive Security Tooling  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/sqlmapthebasics  
**Status:** ✔ Completed  

---

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/SQLMAP-The-Basics-badge.png?raw=true" alt="SQLMap Badge" width="300"/>
</p>

---

# 🧠 Room Overview

The **SQLMap: The Basics** room introduced:
- SQL Injection (SQLi)
- Automated SQL exploitation
- Database enumeration
- SQLMap usage
- Vulnerability testing concepts

The room demonstrated how attackers automate SQL injection attacks against vulnerable web applications.

This knowledge is critical for:
- Web security testing
- SOC investigations
- Vulnerability analysis
- Threat detection

---

# 🎯 Learning Objectives

- Understand SQL Injection
- Learn how SQLMap works
- Automate SQLi exploitation
- Enumerate databases
- Extract data from vulnerable applications
- Understand offensive tooling workflows
- Recognize SQLi attack indicators

---

# 🌍 Task 1 — Introduction

The room introduced SQLMap as:
- An automated SQL injection tool
- A database exploitation framework
- A popular offensive security utility

SQLMap can:
- Detect SQL injection
- Extract databases
- Dump tables
- Enumerate users
- Gain deeper database access

---

# 💥 Task 2 — SQL Injection Vulnerability

SQL Injection occurs when user input is improperly sanitized.

## Example Vulnerable Query

```sql
SELECT * FROM users WHERE username = 'admin';
```

Attackers can manipulate queries to:
- Bypass authentication
- Extract sensitive data
- Modify databases
- Execute malicious actions

## Common SQLi Types

| Type | Description |
|---|---|
| Error-Based | Uses database errors |
| Union-Based | Combines query results |
| Blind SQLi | Uses true/false conditions |
| Time-Based | Uses delayed responses |

---

# 🤖 Task 3 — Automated SQL Injection Tool

SQLMap automates:
- Injection testing
- Database enumeration
- Data extraction
- Vulnerability detection

## Basic SQLMap Syntax

```bash
sqlmap -u "http://target.com/page.php?id=1"
```

## Common Parameters

| Parameter | Purpose |
|---|---|
| -u | Target URL |
| --dbs | List databases |
| --tables | List tables |
| --dump | Dump data |
| -D | Select database |
| -T | Select table |

---

# 🧪 Task 4 — Practical Exercise

The room included practical interaction with a vulnerable web application.

## Skills Practiced

- Identifying injectable parameters
- Running SQLMap scans
- Enumerating databases
- Extracting table data
- Understanding automated exploitation

## Example Enumeration Commands

### Enumerate Databases

```bash
sqlmap -u "http://target-ip/item.php?id=1" --dbs
```

### List Tables

```bash
sqlmap -u "http://target-ip/item.php?id=1" -D users --tables
```

### Dump Table Data

```bash
sqlmap -u "http://target-ip/item.php?id=1" -D users -T accounts --dump
```

---

# 🛡️ SOC / Blue Team Perspective

SOC analysts should monitor for:
- SQL error messages
- Unusual database queries
- Injection payload patterns
- Excessive HTTP parameter testing
- Automated scanning behavior

## Common SQLi Indicators

- `' OR 1=1 --`
- UNION SELECT payloads
- Abnormal query responses
- Time-delay attacks
- Repeated parameter fuzzing

---

# 🔍 Security Risks of SQL Injection

SQL Injection can lead to:
- Credential theft
- Database compromise
- Sensitive data exposure
- Authentication bypass
- Full application compromise

---

# 🧾 Key Concepts Learned

- SQL Injection fundamentals
- SQLMap basics
- Automated exploitation
- Database enumeration
- SQLi attack types
- Offensive web tooling
- Detection concepts

---

# 💬 Key Takeaway

> “SQL injection remains one of the most dangerous web vulnerabilities because a single insecure input can expose entire databases and sensitive organizational data.”

---

# 🚀 Next Steps

- Practice manual SQL Injection
- Learn Burp Suite Intruder
- Study OWASP Top 10
- Explore advanced SQLMap usage
- Continue web exploitation rooms
