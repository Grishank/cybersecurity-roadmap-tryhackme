# 🌐 Networking Essentials — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Networking-Essentials-banner.png?raw=true" alt="Networking Essentials Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Networking  
**Date Completed:** Jan 2026  
**Room Link:** [Networking Essentials](https://tryhackme.com/room/networkingessentials)  
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Networking Essentials builds on foundational networking concepts and focuses on **how networks actually operate in real environments**. This room explains how devices automatically obtain network configurations, how systems communicate across layers, how connectivity issues are diagnosed, and how traffic is routed across networks.

For a SOC analyst, these concepts are **critical for understanding alerts, packet behavior, and network-based attacks**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding core networking mechanisms, including:

- How devices automatically obtain IP configurations  
- How IP addresses are resolved to MAC addresses  
- How connectivity issues are diagnosed using ICMP  
- How packets are routed across networks  
- How Network Address Translation (NAT) works  

---

## 🧭 3. Key Concepts Learned  

- **DHCP** — automatic IP configuration  
- **ARP** — IP-to-MAC address resolution  
- **ICMP** — network troubleshooting and diagnostics  
- **Routing** — forwarding packets between networks  
- **NAT** — translating private IPs to public IPs  

---

## ⚙ 4. DHCP — Give Me My Network Settings  

**DHCP (Dynamic Host Configuration Protocol)** automatically assigns:

- IP address  
- Subnet mask  
- Default gateway  
- DNS server  

**Why it matters:**  
Without DHCP, network configuration would be manual and error-prone.

**SOC Perspective:**  
Rogue DHCP servers can be used in **man-in-the-middle attacks** and must be monitored.

---

## 🔁 5. ARP — Bridging Layer 3 to Layer 2  

**ARP (Address Resolution Protocol)** maps:

- **IP Address (Layer 3)** ➜ **MAC Address (Layer 2)**

This allows devices to communicate within the same network.

**SOC Perspective:**  
ARP spoofing/poisoning is a common technique used to intercept traffic on local networks.

---

## 🛠 6. ICMP — Troubleshooting Networks  

**ICMP (Internet Control Message Protocol)** is used for:

- Connectivity checks (ping)  
- Error reporting  
- Network diagnostics  

Common ICMP messages:
- Echo Request / Echo Reply  
- Destination Unreachable  
- Time Exceeded  

**SOC Perspective:**  
ICMP can be abused for **reconnaissance and tunneling**, but blocking it entirely can break diagnostics.

---

## 🧭 7. Routing  

Routing determines **how packets travel from source to destination across different networks**.

- Routers use **routing tables**  
- Decisions are based on **destination IP addresses**  
- Can be static or dynamic  

**SOC Perspective:**  
Understanding routing paths helps trace **attack origins and lateral movement**.

---

## 🌍 8. NAT — Network Address Translation  

**NAT** allows multiple internal devices to share a single public IP address.

Types of NAT:
- Static NAT  
- Dynamic NAT  
- PAT (Port Address Translation)  

**SOC Importance:**  
NAT complicates attribution and makes **log correlation essential** during investigations.

---

## ⚠ 9. Blue-Team / SOC Observations  

- DHCP misuse can indicate rogue devices  
- ARP activity is critical for detecting MITM attacks  
- ICMP traffic may indicate scanning or tunneling  
- Routing knowledge helps in network-based incident response  
- NAT requires strong logging for accurate attribution  

---

## 🧾 10. What I Learned (Bullets)  

- How devices automatically join networks using DHCP  
- How ARP enables communication within local networks  
- How ICMP supports troubleshooting and diagnostics  
- How routing moves packets across networks  
- How NAT enables private networks to access the internet  

---

## 💬 Key Takeaway  

> *“Understanding how networks configure, communicate, and route traffic is essential for detecting, analyzing, and responding to security incidents.”*

---

## 📌 Next Steps  

- Continue remaining **Networking module rooms**  
- Apply concepts to packet analysis and SIEM logs  
- Study common network-based attack techniques  
- Correlate DHCP, ARP, and ICMP data during investigations  
