# 🟧 Burp Suite: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Burp-Suite-The-Basics-banner.png?raw=true" alt="Burp Suite The Basics Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Web Hacking Fundamentals  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/burpsuitebasics  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **Burp Suite: The Basics** room introduced the fundamentals of using **Burp Suite** for web application testing and traffic analysis.

The room focused on:
- Burp Suite interface
- Proxying web traffic
- Intercepting HTTP requests
- HTTPS proxying
- Site mapping
- Browser integration
- Web request analysis

This room builds the foundation required for:
- Web application testing
- HTTP request manipulation
- Web vulnerability analysis
- Security traffic inspection
- Web penetration testing basics

---

# 🎯 Learning Objectives

- Understand what Burp Suite is
- Learn Burp Community Edition features
- Configure Burp proxy settings
- Intercept and analyze web traffic
- Use Burp browser integration
- Understand HTTPS proxying
- Explore site mapping and targeting

---

# 🌍 Task 1 — Introduction

Introduced Burp Suite as one of the most widely used web security testing tools.

## Key Takeaways

- Burp Suite is used for web application testing
- Commonly used by penetration testers and security analysts
- Allows inspection and modification of HTTP traffic

---

# 🛠️ Task 2 — What is Burp Suite

Learned about the purpose and architecture of Burp Suite.

## Main Functions

- Intercept web traffic
- Analyze requests and responses
- Modify HTTP traffic
- Discover vulnerabilities

---

# ⚙️ Task 3 — Features of Burp Community

Explored the main tools included in Burp Community Edition.

## Important Components

| Component | Purpose |
|---|---|
| Proxy | Intercept traffic |
| Repeater | Replay requests |
| Intruder | Automated testing |
| Decoder | Encode/decode data |
| Comparer | Compare requests |

---

# 💻 Task 4 — Installation

Covered the installation and setup process.

## Important Setup Concepts

- Java requirement
- Browser proxy configuration
- Local proxy listener
- Certificate installation

---

# 📊 Task 5 — The Dashboard

Learned how the Burp dashboard provides:
- Alerts
- Activity overview
- Event logging
- Status information

---

# 🧭 Task 6 — Navigation

Explored Burp Suite's interface and navigation.

## Tabs Covered

- Dashboard
- Proxy
- Target
- Repeater
- Intruder

---

# ⚡ Task 7 — Options

Learned how Burp settings control:
- Proxy listeners
- Interception rules
- Browser behavior
- SSL settings

---

# 🌐 Task 8 — Introduction to the Burp Proxy

Focused on intercepting browser traffic.

## Key Concepts

- Requests pass through Burp Proxy
- Traffic can be modified before reaching the server
- Analysts can inspect headers, cookies, and parameters

---

# 🦊 Task 9 — Connecting Through the Proxy (FoxyProxy)

Learned how FoxyProxy simplifies browser proxy management.

## Key Takeaways

- Easy proxy switching
- Browser traffic routing
- Faster testing workflow

---

# 🗺️ Task 10 — Site Map and Issue Definitions

Explored how Burp automatically maps websites.

## Site Map Benefits

- Discover application structure
- Identify endpoints
- Track requests and responses

---

# 🌍 Task 11 — The Burp Suite Browser

Learned about Burp’s built-in Chromium browser.

## Benefits

- Preconfigured proxy settings
- Easier HTTPS interception
- Simplified testing workflow

---

# 🎯 Task 12 — Scoping and Targeting

Focused on limiting testing scope.

## Why Scope Matters

- Prevents accidental testing of unrelated targets
- Organizes assessments
- Helps manage larger applications

---

# 🔒 Task 13 — Proxying HTTPS

Learned how Burp handles encrypted HTTPS traffic.

## Key Concepts

- Burp performs SSL/TLS interception
- Browser must trust Burp certificate
- HTTPS traffic becomes visible for analysis

---

# 💥 Task 14 — Example Attack

Demonstrated practical request interception and modification.

## Skills Practiced

- Capturing requests
- Editing parameters
- Forwarding modified traffic
- Analyzing responses

---

# 🛡️ SOC / Blue Team Perspective

Burp Suite knowledge helps analysts:
- Understand attacker workflows
- Investigate malicious HTTP traffic
- Analyze web requests and responses
- Detect suspicious parameters and payloads

Common attacks analyzed with Burp:
- SQL Injection
- Cross-Site Scripting (XSS)
- Authentication bypass
- Session attacks
- Parameter tampering

---

# 🧾 Key Concepts Learned

- Burp Suite fundamentals
- Proxy configuration
- HTTP interception
- HTTPS inspection
- Browser integration
- Site mapping
- Web request analysis
- Basic web attack workflows

---

# 💬 Key Takeaway

> “Understanding Burp Suite is essential for web security because it allows analysts to inspect, manipulate, and understand how web applications communicate.”

---

# 🚀 Next Steps

- Learn Burp Repeater in depth
- Practice HTTP request manipulation
- Study OWASP Top 10
- Learn authentication testing
- Explore web vulnerability exploitation
- Continue advanced web hacking rooms
