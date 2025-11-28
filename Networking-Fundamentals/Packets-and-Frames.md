# 📦 Packets and Frames (Completed ✅)

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Packets-and-Frames.png?raw=true" alt="Packets and Frames - TryHackMe Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Date Completed:** November 2025  
**Room Link:** https://tryhackme.com/room/packetsframes  
**Status:** ✅ Completed  

---

### 🧠 What I Learned

#### 🔹 1. What Are Packets and Frames?
- **Frames** operate at **Layer 2 (Data Link)**  
- **Packets** operate at **Layer 3 (Network)**  
- A frame contains:
  - Destination & source MAC  
  - EtherType  
  - Payload  
  - FCS (Frame Check Sequence)

- A packet contains:
  - Source & destination IP  
  - TTL  
  - Protocol (TCP/UDP)  
  - Payload  

#### Why it matters:
Packets = logical addressing (IP)  
Frames = physical addressing (MAC)  
Understanding both is **key for SOC log analysis**.

---

#### 🔹 2. TCP/IP — The Three-Way Handshake
Learned how TCP establishes reliable connections:

1. **SYN** → Client wants to connect  
2. **SYN/ACK** → Server acknowledges  
3. **ACK** → Client finalizes  

This handshake is the base of:
- SSH  
- HTTPS  
- FTP  
- Any TCP communication

**SOC relevance:**  
Detect SYN floods, abnormal handshake attempts, scanning.

---

#### 🔹 3. Practical — Handshake
- Followed packet flow in a simulated environment  
- Observed each handshake step  
- Identified normal vs suspicious TCP patterns  

---

#### 🔹 4. UDP/IP
- Connectionless, faster protocol  
- No handshake  
- No reliability mechanisms  
- Used by DNS, VoIP, TFTP  

**SOC note:**  
UDP is commonly abused in amplification attacks (DNS/NTP).

---

#### 🔹 5. Ports 101 (Practical)
Practiced identifying services using:
- TCP port numbers  
- UDP port numbers  

Examples learned:
- 22 → SSH  
- 80 → HTTP  
- 443 → HTTPS  
- 53 → DNS  
- 3389 → RDP

This helps in:
- Identifying malicious services  
- Detecting port scanning  
- Understanding incoming traffic

---

### ⚙️ Key Takeaways
> “Packets show **where** the data is going. Frames show **how** it gets there.”

Understanding packet vs frame structure is the foundation of network forensics.

---

### 🧩 Next Steps
- Move to **Extending Your Network** (next TryHackMe room).  
- Start practicing Wireshark filters:  
  - `ip.addr == x.x.x.x`  
  - `tcp.port == 80`  
  - `udp`  
- Study packet captures (PCAPs) to identify real-world attack patterns.

---
