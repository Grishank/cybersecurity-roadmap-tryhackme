# 🛡️ IDS Fundamentals — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/IDS-Fundamentals-banner.png?raw=true" alt="IDS Fundamentals Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Security Solutions  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/idsfundamentals  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **IDS Fundamentals** room introduces the core concepts of Intrusion Detection Systems (IDS), their role in defensive security, and practical usage of the **Snort IDS** platform.

The room focuses on:
- IDS fundamentals
- Types of IDS
- Signature-based detection
- Network monitoring
- Snort basics
- IDS rule concepts
- Traffic analysis

This room builds foundational knowledge required for:
- SOC monitoring
- Threat detection
- Security alerting
- Network defense
- SIEM investigation
- Intrusion analysis

---

# 🎯 Learning Objectives

- Understand what an IDS is
- Learn the types of IDS
- Understand how IDS detects threats
- Learn Snort basics
- Understand IDS rules and alerts
- Learn traffic monitoring concepts
- Understand defensive network visibility

---

# 🚨 Task 1 — What Is an IDS

An **Intrusion Detection System (IDS)** monitors network or host activity to identify suspicious behavior and potential attacks.

## Main Goals of IDS

- Detect malicious activity
- Generate security alerts
- Monitor network traffic
- Identify attack patterns
- Support incident response

## Important Note

An IDS:
- Detects threats
- Alerts defenders

But usually does **not automatically block traffic**.

---

# 🔍 Task 2 — Types of IDS

Different IDS solutions monitor different environments and behaviors.

## Common IDS Types

| IDS Type | Purpose |
|---|---|
| Network IDS (NIDS) | Monitors network traffic |
| Host IDS (HIDS) | Monitors individual systems |
| Signature-Based IDS | Detects known attack patterns |
| Anomaly-Based IDS | Detects abnormal behavior |

---

# 🐷 Task 3 — IDS Example: Snort

The room introduced **Snort**, one of the most widely used open-source IDS platforms.

## Snort Features

- Packet inspection
- Rule-based detection
- Traffic logging
- Alert generation
- Protocol analysis

## Snort Detection Flow

1. Capture traffic
2. Analyze packets
3. Compare against rules
4. Generate alerts

---

# ⚙️ Task 4 — Snort Usage

The room demonstrated basic Snort operation and IDS workflows.

## Common Snort Commands

### Run Snort in IDS Mode

```bash
sudo snort -A console -q -c /etc/snort/snort.conf -i eth0
```

### Read PCAP File

```bash
snort -r capture.pcap
```

### Test Configuration

```bash
snort -T -c /etc/snort/snort.conf
```

---

# 📡 IDS Detection Concepts

IDS systems can detect:
- Port scanning
- Malware traffic
- Exploit attempts
- Brute-force attacks
- Suspicious payloads
- Protocol abuse

## Example Indicators

| Activity | Possible Detection |
|---|---|
| Multiple failed logins | Brute-force attack |
| Large scans | Reconnaissance |
| Malicious signatures | Known malware |
| Suspicious traffic spikes | Network anomaly |

---

# 🛡️ SOC / Blue Team Perspective

IDS platforms are heavily used inside SOC environments for:
- Real-time monitoring
- Alert generation
- Threat detection
- Security investigations
- Incident response support

SOC analysts commonly investigate:
- Snort alerts
- Suspicious connections
- Reconnaissance activity
- Malware communication
- Exploit traffic patterns

---

# 🔥 IDS vs IPS

| IDS | IPS |
|---|---|
| Detects attacks | Detects and blocks attacks |
| Passive monitoring | Active protection |
| Generates alerts | Can stop malicious traffic |

---

# 🧾 Key Concepts Learned

- IDS fundamentals
- Types of IDS
- Snort basics
- Signature-based detection
- Traffic monitoring
- IDS alerts
- Threat detection workflows

---

# 💬 Key Takeaway

> “Intrusion Detection Systems help defenders identify malicious activity early by monitoring network and system behavior for suspicious patterns.”

---

# 🚀 Next Steps

- Learn IPS concepts
- Study Snort rules deeply
- Practice PCAP analysis
- Explore Suricata IDS
- Learn SIEM alert correlation
- Study threat hunting workflows
