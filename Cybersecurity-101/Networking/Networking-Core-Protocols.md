
# 🌐 Networking Core Protocols — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Networking-Core-Protocols-banner.png?raw=true" alt="Networking Core Protocols Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Networking  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/networkingcoreprotocols
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Networking Core Protocols focuses on the essential protocols that power communication across the internet. These protocols define how data is transmitted, received, and interpreted between devices.

For SOC analysts, understanding these protocols is critical because most cyber attacks leverage or abuse these communication methods.

---

## 🎯 2. Learning Objectives  

This room focused on understanding fundamental networking protocols, including:

- How DNS resolves domain names to IP addresses  
- How WHOIS provides domain registration details  
- How HTTP/HTTPS enables web communication  
- How FTP transfers files across networks  
- How email protocols (SMTP, POP3, IMAP) function  

---

## 🧭 3. Key Concepts Learned  

- DNS — translates domain names into IP addresses  
- WHOIS — provides ownership and registration information for domains  
- HTTP/HTTPS — protocols for accessing websites  
- FTP — protocol for transferring files  
- SMTP/POP3/IMAP — protocols for sending and receiving emails  

---

## 🌍 4. DNS — Remembering Addresses  

DNS (Domain Name System) converts:

    google.com → IP Address

👉 Acts like a phonebook of the internet  

**SOC Perspective:**  
DNS traffic is commonly used in:
- Malware communication  
- Data exfiltration  
- Command & Control (C2) activity  

---

## 🔍 5. WHOIS  

WHOIS provides information about:

- Domain owner  
- Registration details  
- Expiry dates  

**SOC Use:**  
- Investigating suspicious domains  
- Identifying threat actors  
- Tracking phishing domains  

---

## 🌐 6. HTTP(S) — Accessing the Web  

- HTTP — unencrypted web communication  
- HTTPS — encrypted using SSL/TLS  

**SOC Perspective:**  
- HTTP traffic is easily inspected  
- HTTPS hides content but metadata is still useful  

---

## 📂 7. FTP — Transferring Files  

FTP (File Transfer Protocol) is used to:

- Upload/download files  

❌ Not secure (no encryption)  

**SOC Observation:**  
- Can be used for data exfiltration  
- Often replaced by secure alternatives  

---

## 📧 8. SMTP — Sending Email  

SMTP (Simple Mail Transfer Protocol) is used to:

- Send emails between servers  

**SOC Perspective:**  
- Used in phishing campaigns  
- Email spoofing attacks  

---

## 📥 9. POP3 — Receiving Email  

POP3 (Post Office Protocol v3):

- Downloads emails to local device  
- Removes them from server  

**SOC Note:**  
- Less flexible  
- Limited synchronization  

---

## 🔄 10. IMAP — Synchronizing Email  

IMAP (Internet Message Access Protocol):

- Keeps emails on server  
- Syncs across multiple devices  

**SOC Perspective:**  
- More common in modern environments  
- Useful in forensic investigations  

---

## ⚠ 11. Blue-Team / SOC Observations  

- DNS logs are critical for detecting malicious domains  
- HTTP/HTTPS traffic reveals user behavior patterns  
- FTP can indicate unauthorized data transfers  
- Email protocols are heavily abused in phishing attacks  
- WHOIS helps in threat intelligence and attribution  

---

## 🧾 12. What I Learned (Bullets)  

- Core protocols enable all internet communication  
- DNS is essential for domain resolution and is often abused  
- HTTP and HTTPS differ in security and visibility  
- FTP is insecure and risky in modern environments  
- Email protocols are major attack vectors  

---

## 💬 Key Takeaway  

> “Understanding core networking protocols allows analysts to detect, analyze, and respond to threats at the communication level.”

---

## 📌 Next Steps  

- Continue with Networking Secure Protocols  
- Learn packet analysis using Wireshark  
- Study how attackers abuse these protocols  
- Correlate protocol activity with security alerts  
