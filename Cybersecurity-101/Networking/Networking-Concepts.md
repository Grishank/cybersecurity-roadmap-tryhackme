# 🌐 Networking Concepts — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Networking-Concepts-banner.png?raw=true" alt="Networking Concepts Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Networking  
**Date Completed:** Dec 2025  
**Room Link:** [Networking Concepts](https://tryhackme.com/room/networkingconcepts)  
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Networking is the backbone of all modern computing. Every login attempt, file transfer, web request, or attack relies on network communication. For SOC analysts, understanding networking concepts is **non-negotiable**, as most security incidents either originate from or propagate through networks.

This room introduces the **fundamental networking models and protocols** that explain how data moves from one system to another.

---

## 🎯 2. Learning Objectives  

This room focused on building strong networking foundations, including:

- Understanding how data flows through networks  
- Learning the OSI and TCP/IP models  
- Understanding IP addressing and subnetting  
- Differentiating TCP and UDP  
- Understanding encapsulation  
- Introducing basic network services like Telnet  

---

## 🧭 3. Key Concepts Learned  

- **Networks** — collections of interconnected devices that communicate using protocols.  
- **Clients & Servers** — roles in network communication.  
- **Protocols** — rules that define how data is transmitted and received.  
- **Ports** — logical endpoints used by services and applications.  
- **Packets** — units of data transmitted across networks.

---

## 🧱 4. OSI Model  

The **OSI (Open Systems Interconnection) model** explains how data flows through a network in **7 layers**:

1. **Physical** — cables, signals  
2. **Data Link** — MAC addresses, switching  
3. **Network** — IP addressing and routing  
4. **Transport** — TCP/UDP, ports  
5. **Session** — session management  
6. **Presentation** — encoding, encryption  
7. **Application** — user-facing protocols (HTTP, FTP, SMTP)

**SOC Perspective:**  
OSI layers help analysts **pinpoint where an issue or attack is occurring**.

---

## 🌐 5. TCP/IP Model  

The **TCP/IP model** simplifies networking into **4 layers**:

- **Network Interface**  
- **Internet**  
- **Transport**  
- **Application**

This model is more practical and aligns closely with how modern networks operate.

---

## 🧮 6. IP Addresses & Subnetting  

- **IP Address** — unique identifier for a device on a network  
- **IPv4 vs IPv6** — address formats  
- **Private vs Public IPs** — internal vs internet-facing  
- **Subnets** — dividing networks for efficiency and security  

**SOC Importance:**  
Understanding IP ranges helps distinguish **internal activity vs external threats**.

---

## 🔄 7. TCP vs UDP  

| Protocol | Characteristics | SOC Relevance |
|--------|----------------|---------------|
| **TCP** | Reliable, connection-based | Used by SSH, HTTP, HTTPS |
| **UDP** | Fast, connectionless | Used by DNS, streaming, some attacks |

**SOC Note:**  
Attackers may abuse **UDP for floods** and **TCP for stealthy access**.

---

## 📦 8. Encapsulation  

Encapsulation is the process of **wrapping data with protocol information** as it moves down the network stack.

Each layer adds its own header, allowing the receiving system to correctly interpret the data.

**SOC Perspective:**  
Packet inspection relies on understanding encapsulation to detect malicious traffic.

---

## ⚠ 9. Telnet (Insecure Protocol)**  

- Transmits data in **plain text**  
- No encryption  
- Easily sniffed  

**SOC Observation:**  
Any Telnet usage in modern environments should be considered **high risk**.

---

## ⚠ 10. Blue-Team / SOC Observations  

- Network visibility is essential for detection and response  
- Many attacks exploit **misconfigured networks**  
- OSI/TCP-IP models help with **incident triage**  
- Cleartext protocols are dangerous  
- Network logs are critical SOC data sources

---

## 🧾 11. What I Learned (Bullets)  

- Networking concepts explain how all cyber activity occurs  
- OSI and TCP/IP models help structure troubleshooting  
- IP addressing is key for identifying attackers  
- TCP and UDP behave very differently during attacks  
- Strong networking knowledge improves SOC investigations

---

## 💬 Key Takeaway  

> *“Every cyber attack leaves network traces — understanding networking is the foundation of effective SOC detection and response.”*

---

## 📌 Next Steps  

- Continue with next **Networking module rooms**  
- Apply networking knowledge to log analysis  
- Learn how attacks manifest at different OSI layers  
- Correlate network traffic with security alerts  


