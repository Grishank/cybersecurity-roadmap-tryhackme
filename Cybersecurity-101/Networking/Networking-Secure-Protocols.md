# 🔐 Networking Secure Protocols — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Networking-Secure-Protocols-banner.png?raw=true" alt="Networking Secure Protocols Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Networking  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/networkingsecureprotocols
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Networking Secure Protocols focuses on how modern networks **protect data during transmission using encryption**. These protocols are secure versions of traditional communication methods and are essential for maintaining confidentiality, integrity, and security.

For SOC analysts, understanding secure protocols is critical because attackers often **hide malicious activity within encrypted traffic**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding secure communication protocols, including:

- How TLS provides encryption for data in transit  
- How HTTPS secures web communication  
- How secure email protocols protect messages  
- How SSH enables secure remote access  
- How SFTP and FTPS secure file transfers  
- How VPNs protect network communication  

---

## 🧭 3. Key Concepts Learned  

- **TLS** — provides encryption for secure communication  
- **HTTPS** — secure version of HTTP  
- **SMTPS/POP3S/IMAPS** — secure email protocols  
- **SSH** — secure remote access protocol  
- **SFTP/FTPS** — secure file transfer protocols  
- **VPN** — encrypted tunnel for secure communication  

---

## 🔒 4. TLS — Transport Layer Security  

**TLS** is the core protocol that provides:

- Encryption  
- Data integrity  
- Secure communication  

👉 Used in HTTPS, FTPS, email security  

**SOC Perspective:**  
- Protects data from interception  
- Harder to inspect malicious traffic  

---

## 🌐 5. HTTPS — Secure Web Communication  

- HTTP → unencrypted  
- HTTPS → encrypted using TLS  

**SOC Perspective:**  
- Protects sensitive data (passwords, banking info)  
- Attackers may hide traffic inside HTTPS  

---

## 📧 6. SMTPS, POP3S, IMAPS — Secure Email  

Secure versions of email protocols:

- **SMTPS** — sending email securely  
- **POP3S** — receiving email securely  
- **IMAPS** — syncing email securely  

**SOC Observation:**  
- Encryption protects content  
- Phishing still possible  

---

## 🧑‍💻 7. SSH — Secure Remote Access  

**SSH (Secure Shell)** is used to:

- Remotely access systems securely  
- Replace insecure Telnet  

**SOC Perspective:**  
- Common target for brute-force attacks  
- Used by both admins and attackers  

---

## 📂 8. SFTP & FTPS — Secure File Transfer  

- **SFTP** — runs over SSH  
- **FTPS** — uses TLS  

👉 Both secure file transfer  

**SOC Observation:**  
- Used for legitimate file transfer  
- Also used for data exfiltration  

---

## 🌍 9. VPN — Virtual Private Network  

**VPN** creates:

- Encrypted tunnel between user and network  

👉 Protects data over public networks  

**SOC Perspective:**  
- Hides user activity  
- Can be abused to bypass monitoring  

---

## ⚠ 10. Blue-Team / SOC Observations  

- Encryption protects data but reduces visibility  
- Attackers often hide traffic inside HTTPS  
- SSH brute-force attempts are common  
- VPNs can hide attacker location  
- Secure protocols still require monitoring  

---

## 🧾 11. What I Learned (Bullets)  

- Secure protocols use encryption to protect data  
- TLS is the foundation of most secure communications  
- HTTPS secures web traffic but limits visibility  
- Secure email protocols protect messages but not intent  
- VPNs and SSH are powerful but can be abused  

---

## 💬 Key Takeaway  

> “Encryption protects data, but it can also hide threats — making visibility and monitoring essential for SOC analysts.”

---

## 📌 Next Steps  

- Continue with Wireshark: The Basics  
- Learn packet analysis and traffic inspection  
- Study encrypted traffic patterns  
- Understand how attackers hide in secure protocols  
