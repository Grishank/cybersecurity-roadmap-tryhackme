# 🦈 Wireshark: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Wireshark-The-Basics-banner.png?raw=true" alt="Wireshark Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Networking  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/wiresharkthebasics                                                           
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Wireshark is a powerful **network protocol analyzer** used to capture and inspect network traffic in real time. It allows analysts to see exactly what data is moving across a network.

For SOC analysts, Wireshark is essential for **investigating suspicious traffic, detecting attacks, and understanding network behavior**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding Wireshark fundamentals, including:

- Understanding how Wireshark captures packets  
- Learning the Wireshark interface  
- Understanding packet structure (dissection)  
- Navigating through captured traffic  
- Applying filters to analyze specific traffic  

---

## 🧭 3. Key Concepts Learned  

- **Packet Capture (PCAP)** — recorded network traffic  
- **Packet Dissection** — breaking down packets into layers  
- **Filtering** — narrowing down traffic for analysis  
- **Protocol Analysis** — understanding communication details  

---

## 🛠 4. Tool Overview  

Wireshark interface consists of:

- **Packet List Pane** — shows captured packets  
- **Packet Details Pane** — shows protocol layers  
- **Packet Bytes Pane** — raw data (hex + ASCII)  

**SOC Perspective:**  
- Helps identify suspicious connections  
- Visualizes network communication clearly  

---

## 📦 5. Packet Dissection  

Each packet is broken into layers:

- Frame  
- Ethernet  
- IP  
- TCP/UDP  
- Application (HTTP, DNS, etc.)

👉 This follows the **OSI/TCP-IP model**

**SOC Perspective:**  
- Helps identify malicious payloads  
- Understands how attacks are structured  

---

## 🧭 6. Packet Navigation  

- Scroll through captured packets  
- Follow streams (TCP stream analysis)  
- Identify source & destination  

**SOC Use:**  
- Track attacker communication  
- Reconstruct sessions  

---

## 🔍 7. Packet Filtering  

Filters help isolate traffic:

Examples:

    ip.addr == 192.168.1.1  
    http  
    dns  
    tcp.port == 80  

**SOC Perspective:**  
- Quickly find malicious traffic  
- Reduce noise in large captures  

---

## ⚠ 8. Blue-Team / SOC Observations  

- Packet analysis reveals hidden attacks  
- Filters are essential for efficient investigation  
- Encrypted traffic limits visibility  
- Wireshark is powerful but requires skill  
- Used heavily in incident response  

---

## 🧾 9. What I Learned (Bullets)  

- Wireshark captures and analyzes network traffic  
- Packets can be broken into layers for analysis  
- Filtering is key to finding relevant data  
- Network traffic tells the full story of an attack  
- Packet analysis is a core SOC skill  

---

## 💬 Key Takeaway  

> “Packets never lie — analyzing network traffic reveals the true story behind every cyber attack.”

---

## 📌 Next Steps  

- Continue with Tcpdump: The Basics  
- Practice analyzing PCAP files  
- Learn advanced Wireshark filters  
- Study real-world network attack scenarios  
