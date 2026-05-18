# 🔥 Firewall Fundamentals — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Firewall-Fundamentals-banner.png?raw=true" alt="Firewall Fundamentals Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Security Solutions  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/firewallfundamentals  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **Firewall Fundamentals** room introduces the core concepts of firewalls, firewall rules, packet filtering, and host-based firewall management in both Windows and Linux environments.

The room focuses on:
- Firewall purpose and architecture
- Types of firewalls
- Firewall rules and filtering
- Windows Defender Firewall
- Linux iptables firewall
- Network traffic control

This room builds foundational knowledge required for:
- SOC monitoring
- Network defense
- Threat containment
- Security hardening
- Traffic filtering analysis

---

# 🎯 Learning Objectives

- Understand what firewalls do
- Learn different types of firewalls
- Understand firewall rule logic
- Learn Windows Defender Firewall basics
- Learn Linux iptables fundamentals
- Understand inbound and outbound filtering
- Learn how firewalls help prevent attacks

---

# 🛡️ Task 1 — What Is the Purpose of a Firewall

A firewall is a security control that monitors and filters network traffic based on defined rules.

## Main Purposes

- Block unauthorized access
- Allow legitimate traffic
- Monitor network connections
- Enforce security policies
- Reduce attack surface

## Firewall Placement

Firewalls can exist:
- On endpoints
- On servers
- On routers
- On enterprise network boundaries
- In cloud environments

---

# 🔥 Task 2 — Types of Firewalls

Different firewall types provide different levels of inspection and protection.

## Common Firewall Types

| Firewall Type | Purpose |
|---|---|
| Packet Filtering Firewall | Filters packets using IPs and ports |
| Stateful Firewall | Tracks active connections |
| Proxy Firewall | Inspects traffic through an intermediary |
| Next-Generation Firewall (NGFW) | Deep packet inspection and advanced protection |
| Host-Based Firewall | Protects individual systems |

---

# 📜 Task 3 — Rules in Firewalls

Firewall rules determine whether traffic is:
- Allowed
- Blocked
- Logged

## Common Rule Parameters

- Source IP
- Destination IP
- Protocol
- Port number
- Direction
- Action

## Example Concepts

| Rule Example | Purpose |
|---|---|
| Allow TCP 443 | Permit HTTPS traffic |
| Block Port 23 | Prevent Telnet access |
| Allow Internal Network | Permit trusted traffic |

---

# 🪟 Task 4 — Windows Defender Firewall

Windows Defender Firewall is the built-in firewall solution in Microsoft Windows.

## Key Features

- Inbound filtering
- Outbound filtering
- Profile-based protection
- Logging capabilities
- Rule customization

## Windows Firewall Profiles

| Profile | Usage |
|---|---|
| Domain | Corporate environments |
| Private | Trusted networks |
| Public | Untrusted networks |

## Example PowerShell Command

```powershell
Get-NetFirewallProfile
```

## Example CMD Command

```cmd
netsh advfirewall show allprofiles
```

---

# 🐧 Task 5 — Linux iptables Firewall

iptables is a Linux firewall utility used to manage packet filtering rules.

## Common Chains

| Chain | Purpose |
|---|---|
| INPUT | Incoming traffic |
| OUTPUT | Outgoing traffic |
| FORWARD | Routed traffic |

## Example Commands

### View Rules

```bash
sudo iptables -L
```

### Allow SSH

```bash
sudo iptables -A INPUT -p tcp --dport 22 -j ACCEPT
```

### Drop Traffic

```bash
sudo iptables -A INPUT -j DROP
```

---

# 🛡️ SOC / Blue Team Perspective

Firewalls are critical security controls used to:
- Block malicious traffic
- Prevent unauthorized access
- Limit attacker movement
- Detect suspicious network behavior
- Enforce segmentation policies

SOC analysts commonly investigate:
- Blocked connections
- Port scanning attempts
- Suspicious outbound traffic
- Unauthorized remote access
- Firewall log alerts

---

# 🚨 Common Threats Firewalls Help Mitigate

- Port scanning
- Remote exploitation
- Malware communication
- Unauthorized access
- Lateral movement
- Brute-force attacks

---

# 🧾 Key Concepts Learned

- Firewall fundamentals
- Traffic filtering
- Firewall rule logic
- Windows Defender Firewall
- Linux iptables basics
- Inbound vs outbound filtering
- Network security enforcement

---

# 💬 Key Takeaway

> “Firewalls are one of the first lines of defense in cybersecurity, helping control network traffic and reduce exposure to attacks.”

---

# 🚀 Next Steps

- Learn IDS/IPS fundamentals
- Study SIEM alerting
- Explore network segmentation
- Learn packet analysis with Wireshark
- Practice firewall rule investigation
- Study enterprise network security
