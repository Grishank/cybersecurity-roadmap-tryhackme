# 🕸️ OWASP Top 10 2025: Application Design Flaws — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/OWASP-Top-10-2025-Application-Design-Flaws-banner.png?raw=true" alt="OWASP Top 10 2025 Application Design Flaws Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** OWASP Top 10 (2025)  
**Module:** Application Design Flaws  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/owasptop102025two  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **OWASP Top 10 2025: Application Design Flaws** room focuses on major web application weaknesses caused by insecure design decisions, poor configurations, weak cryptography, and vulnerable software supply chains.

The room explains important OWASP categories including:
- A02: Security Misconfigurations
- A03: Software Supply Chain Failures
- A04: Cryptographic Failures
- A06: Insecure Design

This room builds foundational knowledge required for:
- Secure web application design
- Threat modeling
- Defensive web security
- Secure software development
- SOC investigations
- Security architecture analysis

---

# 🎯 Learning Objectives

- Understand application design flaws
- Learn Security Misconfiguration risks
- Understand Software Supply Chain Failures
- Learn Cryptographic Failure concepts
- Explore Insecure Design weaknesses
- Understand secure application architecture
- Learn defensive web security principles

---

# 🧩 Task 1 — Introduction

Modern applications rely on:
- Secure configurations
- Trusted software dependencies
- Proper cryptography
- Secure architecture design

Weaknesses in these areas can lead to:
- Data breaches
- Unauthorized access
- Malware infections
- Supply chain attacks
- System compromise

The room explains how insecure design choices create exploitable vulnerabilities.

---

# ⚙️ Task 2 — A02: Security Misconfigurations

Security Misconfiguration occurs when systems are improperly configured or left insecure by default.

## Common Examples

- Default credentials
- Open cloud storage
- Verbose error messages
- Unnecessary services enabled
- Weak security headers
- Exposed admin panels

## Risks

Security misconfigurations may allow attackers to:
- Gain unauthorized access
- Leak sensitive data
- Escalate privileges
- Discover internal systems

---

# 📦 Task 3 — A03: Software Supply Chain Failures

Software Supply Chain Failures involve vulnerabilities introduced through:
- Third-party libraries
- Dependencies
- Package managers
- Vendor software
- CI/CD pipelines

Modern applications depend heavily on external software components.

---

# ⚠️ Common Supply Chain Risks

| Risk | Description |
|---|---|
| Vulnerable Libraries | Outdated or insecure dependencies |
| Dependency Confusion | Malicious package substitution |
| Compromised Vendors | Trusted software becomes malicious |
| Malicious Updates | Backdoored software releases |

## Real-World Impact

Supply chain attacks can affect:
- Thousands of organizations
- Entire software ecosystems
- Enterprise infrastructure

---

# 🔐 Task 4 — A04: Cryptographic Failures

Cryptographic Failures occur when sensitive data is improperly protected.

## Common Causes

- Weak encryption
- Deprecated algorithms
- Hardcoded secrets
- Poor key management
- Unencrypted communication
- Improper certificate validation

---

# 🧠 Why Cryptography Matters

Proper cryptography protects:
- Passwords
- Sensitive data
- API communication
- User sessions
- Financial information

Weak cryptography can lead to:
- Data theft
- Credential exposure
- Session compromise
- Privacy violations

---

# 🏗️ Task 5 — A06: Insecure Design

Insecure Design occurs when applications are built without proper security planning.

Unlike coding bugs, insecure design flaws often originate during:
- Architecture planning
- Feature design
- Business logic creation
- Workflow implementation

---

# 🚨 Common Insecure Design Issues

- Missing threat modeling
- Weak business logic
- Lack of rate limiting
- Insecure workflows
- Weak access control design
- Missing abuse prevention

## Secure Design Principles

| Principle | Purpose |
|---|---|
| Least Privilege | Restrict unnecessary access |
| Secure Defaults | Safer default configurations |
| Defence-in-Depth | Multiple security layers |
| Threat Modeling | Identify risks early |
| Input Validation | Prevent malicious input |

---

# 🌐 Web Application Security Perspective

Application design flaws are dangerous because they affect:
- Entire architectures
- Core application workflows
- Authentication systems
- Sensitive business logic

Many vulnerabilities cannot be fully fixed later if the original design is insecure.

---

# 🛡️ SOC / Blue Team Perspective

SOC analysts often investigate attacks caused by:
- Misconfigured systems
- Vulnerable dependencies
- Weak encryption
- Poor security architecture

Blue Teams monitor for:
- Exploitation attempts
- Dependency vulnerabilities
- Misconfigured services
- Sensitive data exposure
- Suspicious application behavior

---

# ⚠️ Common Security Use Cases

- Web application hardening
- Dependency management
- Secure architecture review
- Threat modeling
- Cryptographic validation
- Secure CI/CD pipelines
- Vulnerability management
- Security configuration auditing

---

# 🔑 Key Concepts Learned

- Security Misconfigurations
- Software Supply Chain Failures
- Cryptographic Failures
- Insecure Design
- Secure architecture principles
- Dependency security
- Threat modeling
- Defensive web security

---

# 💬 Key Takeaway

> “Secure applications require strong architecture, secure configurations, trusted dependencies, and proper cryptographic protections from the very beginning of development.”

---

# 🚀 Next Steps

- Study secure web application architecture
- Learn dependency vulnerability management
- Explore threat modeling methodologies
- Practice secure configuration auditing
- Learn modern cryptography basics
- Explore CI/CD security
- Study secure software development lifecycle (SSDLC)
- Practice defensive web application analysis
