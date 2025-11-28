# 🧩 OSI Model (Completed ✅)

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/OSI-model.png?raw=true" alt="OSI Model - TryHackMe Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Date Completed:** November 2025  
**Room Link:** https://tryhackme.com/room/osimodelzi  
**Status:** ✅ Completed  

---

### 🧠 What I Learned

#### 🔹 1. What Is the OSI Model?
- A conceptual model that standardizes how different systems communicate across networks.  
- Divided into **7 layers**, each with its own role in data transmission.  
- Helps SOC analysts understand **where** network issues or attacks occur.

---

### 🔹 2. Layer-by-Layer Breakdown

#### **Layer 1 — Physical**
- Deals with actual electrical signals, cables, connectors, WiFi signals.  
- Tools: NICs, hubs, repeaters  
- SOC relevance: cable issues, physical tampering

#### **Layer 2 — Data Link**
- Responsible for **frames**, MAC addresses, switching.  
- Switches operate at this layer.  
- SOC relevance: ARP spoofing, MAC flooding attacks.

#### **Layer 3 — Network**
- IP addresses, routing, packets.  
- Routers operate here.  
- SOC relevance: IP spoofing, routing manipulation, firewall logs.

#### **Layer 4 — Transport**
- TCP vs UDP  
- Ports & session control  
- SOC relevance: SYN flood, DoS attacks, port scanning.

#### **Layer 5 — Session**
- Manages sessions between devices.  
- Responsible for establishing and maintaining communication sessions.  
- SOC relevance: session hijacking techniques.

#### **Layer 6 — Presentation**
- Encryption, encoding, compression.  
- Example: SSL/TLS  
- SOC relevance: TLS downgrade attacks.

#### **Layer 7 — Application**
- User-facing protocols: HTTP, DNS, SSH, SMTP  
- SOC relevance: web attacks (SQL injection, XSS), DNS manipulation.

---

### 🔹 3. Practical OSI Game  
- Matched packets to the correct OSI layer.  
- Improved ability to categorize logs/events based on their origin.  

---

### ⚙️ Key Takeaways  
> “The OSI model is the map of the internet — understanding it makes troubleshooting and threat analysis 10× easier.”

---

### 🧩 Next Steps  
- Review **Packets and Frames** to understand deeper network flow.  
- Continue practicing port/protocol mapping (essential for SOC).  
- Build muscle memory of which attacks occur on each layer.

---

