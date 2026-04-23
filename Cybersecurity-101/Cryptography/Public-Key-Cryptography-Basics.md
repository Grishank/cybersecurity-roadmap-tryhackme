# 🔐 Public Key Cryptography Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Public-Key-Cryptography-Basics-banner.png?raw=true" alt="Public Key Cryptography Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Cryptography  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/publickeycrypto                                                          
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Public Key Cryptography (Asymmetric Encryption) is a method of securing data using **two keys: a public key and a private key**. It enables secure communication without sharing secret keys beforehand.

For SOC analysts, this concept is critical because it is widely used in **HTTPS, SSH, VPNs, and digital signatures**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding asymmetric cryptography, including:

- How public and private keys work  
- Common uses of asymmetric encryption  
- Understanding RSA algorithm basics  
- Learning Diffie-Hellman key exchange  
- Understanding SSH security  
- Digital signatures and certificates  
- Introduction to PGP and GPG  

---

## 🧭 3. Key Concepts Learned  

- **Public Key** — shared openly  
- **Private Key** — kept secret  
- **Encryption/Decryption** — using key pairs  
- **Digital Signature** — verifying authenticity  
- **Certificates** — proving identity  

---

## 🔐 4. Common Use of Asymmetric Encryption  

Asymmetric encryption is used for:

- Secure communication (HTTPS)  
- Authentication (SSH login)  
- Key exchange  

👉 Public key encrypts, private key decrypts  

**SOC Perspective:**  
- Used in most secure systems  
- Misuse or key theft can compromise security  

---

## 🔢 5. RSA  

**RSA** is one of the most widely used algorithms.

- Based on large prime numbers  
- Used for encryption and digital signatures  

**SOC Perspective:**  
- Strong if implemented correctly  
- Weak keys can be broken  

---

## 🔁 6. Diffie-Hellman Key Exchange  

Used to:

- Securely exchange keys over insecure network  

👉 Creates shared secret without sending it directly  

**SOC Perspective:**  
- Used in secure connections  
- Vulnerable if parameters are weak  

---

## 🧑‍💻 7. SSH — Secure Remote Access  

SSH uses:

- Public/private key authentication  

👉 More secure than passwords  

**SOC Observation:**  
- Common target for attacks  
- Key-based login preferred  

---

## 🪪 8. Digital Signatures and Certificates  

- Verify identity and authenticity  
- Ensure data integrity  

👉 Used in HTTPS certificates  

**SOC Perspective:**  
- Detect fake or expired certificates  
- Important for trust validation  

---

## 🔑 9. PGP and GPG  

Used for:

- Secure email encryption  
- File encryption  

👉 Uses public/private key system  

**SOC Observation:**  
- Strong encryption tool  
- Used for secure communication  

---

## ⚠ 10. Blue-Team / SOC Observations  

- Asymmetric encryption is widely used in secure systems  
- Private key security is critical  
- Certificates must be validated properly  
- Weak implementations create vulnerabilities  
- Encryption does not eliminate risk  

---

## 🧾 11. What I Learned (Bullets)  

- Public and private keys enable secure communication  
- RSA and Diffie-Hellman are key algorithms  
- Digital signatures verify authenticity  
- Certificates establish trust  
- PGP/GPG provide strong encryption  

---

## 💬 Key Takeaway  

> “Public key cryptography enables secure communication without shared secrets — but its strength depends on protecting private keys.”

---

## 📌 Next Steps  

- Learn hashing algorithms (SHA, MD5)  
- Study digital certificates in depth  
- Understand SSL/TLS handshake  
- Explore real-world cryptographic attacks  
