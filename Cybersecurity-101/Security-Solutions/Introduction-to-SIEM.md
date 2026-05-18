# 📊 Introduction to SIEM — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Introduction-to-SIEM-banner.png?raw=true" alt="Introduction to SIEM Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Defensive Security  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/introtosiem  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **Introduction to SIEM** room introduces the fundamentals of **Security Information and Event Management (SIEM)** systems and explains how SOC teams use SIEM platforms for centralized monitoring, log analysis, detection, and incident investigation.

The room focuses on:
- SIEM fundamentals
- Centralized log collection
- Log ingestion
- Alerting workflows
- Event correlation
- Investigation processes
- SOC monitoring operations

This room builds core blue-team skills required for:
- SOC Analysts
- Security Analysts
- Incident Responders
- Threat Hunters

---

# 🎯 Learning Objectives

- Understand what SIEM is
- Learn why SIEM platforms are important
- Understand log ingestion and correlation
- Learn alerting and investigation workflows
- Understand centralized monitoring
- Explore practical SIEM usage concepts

---

# 📖 Task 1 — Introduction

SIEM stands for:

- **Security Information and Event Management**

A SIEM platform helps organizations:
- Collect logs
- Centralize monitoring
- Detect threats
- Correlate events
- Investigate incidents
- Generate alerts

---

# 🌐 Task 2 — Logs Everywhere, Answers Nowhere

Modern organizations generate huge volumes of logs from:
- Servers
- Endpoints
- Firewalls
- Applications
- Web servers
- Authentication systems

Without SIEM:
- Logs remain scattered
- Investigations become difficult
- Threat visibility is reduced

## Problems Without Centralization

- Massive log volume
- Manual investigation complexity
- Delayed detection
- Poor visibility
- Slow incident response

---

# ❓ Task 3 — Why SIEM?

SIEM platforms help defenders:
- Detect suspicious behavior
- Correlate events
- Generate alerts
- Investigate incidents faster
- Improve visibility across environments

## Main SIEM Benefits

| Benefit | Purpose |
|---|---|
| Centralized Logging | Single monitoring platform |
| Correlation | Connect related events |
| Alerting | Detect threats automatically |
| Investigation | Faster analysis |
| Reporting | Compliance and auditing |

---

# 📥 Task 4 — Log Sources and Ingestion

SIEM platforms collect logs from multiple sources.

## Common Log Sources

- Windows Event Logs
- Linux Logs
- Firewall Logs
- IDS/IPS Logs
- Authentication Logs
- Proxy Logs
- Web Server Logs
- Cloud Logs

## Ingestion Process

1. Log generation  
2. Log collection  
3. Parsing and normalization  
4. Storage  
5. Correlation and analysis  

---

# 🚨 Task 5 — Alerting Process and Analysis

SIEM platforms generate alerts based on suspicious activity.

## Common Detection Examples

- Multiple failed logins
- Impossible travel logins
- Malware indicators
- Suspicious PowerShell usage
- Unauthorized access attempts

## Investigation Workflow

1. Alert generated  
2. Alert triage  
3. Investigation  
4. Escalation  
5. Response actions  

---

# 🧪 Task 6 — Lab Work

The practical section demonstrated:
- Basic SIEM workflows
- Event investigation
- Alert analysis
- Log review
- Security monitoring concepts

## Skills Practiced

- Reviewing alerts
- Understanding log correlation
- Investigating suspicious activity
- Security monitoring workflow
- SIEM navigation concepts

---

# 🛡️ SOC / Blue Team Perspective

SIEM platforms are one of the most important technologies inside a SOC.

SOC analysts use SIEMs daily to:
- Monitor security events
- Investigate alerts
- Correlate logs
- Identify attacker behavior
- Detect suspicious activity

## Common SOC Use Cases

- Brute-force detection
- Malware investigation
- Phishing investigation
- Privilege escalation detection
- Lateral movement analysis

---

# 🧾 Key Concepts Learned

- SIEM fundamentals
- Centralized logging
- Log ingestion
- Event correlation
- Alert generation
- Security monitoring
- Investigation workflows
- SOC operations

---

# 💬 Key Takeaway

> “SIEM platforms transform massive amounts of security logs into actionable alerts and investigations that help SOC teams detect and respond to cyber threats efficiently.”

---

# 🚀 Next Steps

- Practice SIEM investigations
- Learn Splunk fundamentals
- Explore Microsoft Sentinel
- Study event correlation
- Learn threat hunting basics
- Continue SOC Level 1 path
