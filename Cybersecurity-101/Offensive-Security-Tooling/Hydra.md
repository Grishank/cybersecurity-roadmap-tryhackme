# 🐉 Hydra — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Hydra-banner.png?raw=true" alt="Hydra Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Password Attacks & Authentication  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/hydra  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **Hydra** room introduced the basics of using **THC Hydra**, a fast and popular password brute-forcing tool used during penetration testing and security assessments.

The room focused on:
- Hydra fundamentals
- Password attacks
- Login brute forcing
- Service authentication attacks
- Syntax and command usage

This room builds foundational understanding for:
- Password security testing
- Authentication attacks
- Credential auditing
- SOC detection use cases

---

# 🎯 Learning Objectives

- Understand what Hydra is
- Learn Hydra syntax
- Perform authentication attacks
- Understand brute-force workflows
- Learn common Hydra modules
- Recognize password attack indicators

---

# 🌍 Task 1 — Hydra Introduction

Introduced Hydra as a tool used for:
- Online password attacks
- Login brute forcing
- Credential testing

## Supported Services

Hydra supports many protocols including:
- SSH
- FTP
- HTTP
- SMB
- RDP
- Telnet

---

# ⚡ Task 2 — Using Hydra

Learned how Hydra commands are structured and executed.

## Basic Hydra Syntax

```bash
hydra -l username -P passwords.txt ssh://<target-ip>
```

## Important Parameters

| Parameter | Purpose |
|---|---|
| -l | Single username |
| -L | Username list |
| -p | Single password |
| -P | Password list |
| -t | Number of threads |
| -V | Verbose output |

---

# 🔐 Example Attack Workflow

## SSH Brute Force Example

```bash
hydra -l admin -P rockyou.txt ssh://10.10.10.10
```

## HTTP POST Login Example

```bash
hydra -l admin -P passwords.txt 10.10.10.10 http-post-form "/login:user=^USER^&pass=^PASS^:F=incorrect"
```

---

# 🛡️ Security Concepts Learned

- Weak passwords are easily brute forced
- Password reuse increases risk
- Login services must implement protections
- Multi-factor authentication improves security

---

# 🛡️ SOC / Blue Team Perspective

SOC analysts should monitor for:
- Repeated failed login attempts
- High authentication request volume
- Login attempts from unusual IPs
- Multiple username enumeration attempts

## Common Detection Indicators

- Brute-force patterns
- Password spraying
- Credential stuffing
- Rapid authentication failures

---

# 🧾 Key Concepts Learned

- Hydra basics
- Authentication attacks
- Password brute forcing
- Common service attacks
- Hydra syntax
- Credential attack workflows

---

# 💬 Key Takeaway

> “Weak passwords remain one of the most common attack vectors, and tools like Hydra demonstrate how quickly exposed authentication services can be abused.”

---

# 🚀 Next Steps

- Learn password spraying techniques
- Study account lockout mechanisms
- Explore MFA protections
- Practice detecting brute-force attacks
- Continue authentication security rooms
