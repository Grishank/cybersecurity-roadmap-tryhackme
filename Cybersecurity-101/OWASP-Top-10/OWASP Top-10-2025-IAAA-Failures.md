# 🕸️ OWASP Top 10 2025: IAAA Failures — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/OWASP-Top-10-2025-IAAA-Failures-banner.png?raw=true" alt="OWASP Top 10 2025 IAAA Failures Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** OWASP Top 10 (2025)  
**Module:** IAAA Failures  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/owasptop102025one  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **OWASP Top 10 2025: IAAA Failures** room introduces security weaknesses related to the **IAAA model**:

- Identification
- Authentication
- Authorization
- Accountability

The room explains how modern web applications fail in these areas and how those failures map to OWASP Top 10 categories such as:
- A01: Broken Access Control
- A07: Authentication Failures
- A09: Logging & Monitoring Failures

This room builds foundational knowledge required for:
- Web application security
- Access control security
- Authentication security
- SOC investigations
- Security monitoring
- Defensive web security analysis

---

# 🎯 Learning Objectives

- Understand the IAAA model
- Learn Broken Access Control concepts
- Understand Authentication Failures
- Learn Logging & Alerting Failures
- Explore web application security risks
- Understand accountability and monitoring
- Learn secure access management principles

---

# 🧩 Task 1 — Introduction

Modern web applications rely heavily on:
- User identification
- Authentication systems
- Access controls
- Logging mechanisms

Failures in these areas can lead to:
- Unauthorized access
- Account compromise
- Privilege escalation
- Undetected attacks
- Data breaches

The room introduces how these weaknesses appear in real-world applications.

---

# 🔐 Task 2 — What is IAAA?

IAAA stands for:

| Component | Purpose |
|---|---|
| Identification | Recognize a user or entity |
| Authentication | Verify identity |
| Authorization | Control permissions |
| Accountability | Track actions and events |

These concepts form the foundation of secure application design.

---

# 🚫 Task 3 — A01: Broken Access Control

Broken Access Control occurs when users can:
- Access unauthorized resources
- Escalate privileges
- Bypass restrictions
- Access other users’ data

## Common Examples

- IDOR vulnerabilities
- Missing role validation
- Forced browsing
- Privilege escalation
- Insecure admin access

## Security Risks

Broken Access Control may lead to:
- Sensitive data exposure
- Unauthorized actions
- Administrative compromise
- Full application takeover

---

# 🔑 Task 4 — A07: Authentication Failures

Authentication Failures occur when authentication systems are weak or improperly implemented.

## Common Causes

- Weak passwords
- Missing MFA
- Poor session management
- Credential stuffing vulnerabilities
- Default credentials
- Insecure password reset mechanisms

## Common Attacks

| Attack | Description |
|---|---|
| Brute Force | Repeated password guessing |
| Credential Stuffing | Using leaked credentials |
| Session Hijacking | Stealing active sessions |
| Password Spraying | Trying common passwords |

Strong authentication controls are critical for protecting user accounts.

---

# 📋 Task 5 — A09: Logging & Alerting Failures

Logging and monitoring failures occur when organizations cannot:
- Detect attacks
- Track suspicious behavior
- Investigate incidents
- Generate proper alerts

Poor visibility allows attackers to remain hidden for longer periods.

---

# 🚨 Common Logging Failures

- Missing audit logs
- Incomplete event recording
- Weak monitoring
- Delayed alerting
- Poor SIEM integration
- Lack of incident visibility

## Why Logging Matters

Proper logging helps:
- Detect intrusions
- Support incident response
- Investigate attacks
- Improve accountability
- Monitor suspicious behavior

---

# 🛡️ Secure Access Control Principles

Good security practices include:
- Least privilege
- Role-based access control (RBAC)
- Multi-factor authentication
- Session expiration
- Secure password policies
- Proper audit logging

These controls reduce the likelihood of IAAA failures.

---

# 🌐 Web Application Security Perspective

IAAA failures are among the most dangerous web application risks because they directly impact:
- User accounts
- Sensitive data
- Administrative systems
- Application trust

Many real-world breaches occur because of:
- Weak authentication
- Poor access control
- Insufficient logging

---

# 🛡️ SOC / Blue Team Perspective

SOC analysts rely heavily on logging and authentication visibility to:
- Detect attacks
- Identify account compromise
- Monitor suspicious access
- Investigate insider threats
- Respond to incidents

Blue Teams commonly monitor:
- Failed login attempts
- Privilege escalation
- Suspicious session activity
- Access control violations
- Authentication anomalies

---

# ⚠️ Common Security Use Cases

- Web application hardening
- Authentication security
- Access control validation
- SIEM monitoring
- Incident investigation
- Threat detection engineering
- Identity management
- Audit logging implementation

---

# 🔑 Key Concepts Learned

- IAAA model
- Broken Access Control
- Authentication Failures
- Logging & Alerting Failures
- Access management
- Accountability principles
- Session security
- Web application defense

---

# 💬 Key Takeaway

> “Strong identification, authentication, authorization, and accountability controls are critical for protecting web applications from unauthorized access and undetected attacks.”

---

# 🚀 Next Steps

- Study IDOR vulnerabilities
- Learn secure authentication practices
- Explore session management security
- Practice web application testing
- Learn SIEM monitoring workflows
- Study RBAC implementation
- Explore OWASP Top 10 vulnerabilities
- Practice defensive web security analysis
