# 🔐 Cryptography Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Cryptography-Basics-banner.png?raw=true" alt="Cryptography Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101   
**Module:** Cryptography  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/cryptographybasics                     
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Cryptography is the practice of **securing information by transforming it into an unreadable format**. It ensures that sensitive data remains protected during storage and transmission.

For SOC analysts, cryptography is essential because it helps understand **how data is protected and how attackers may attempt to bypass or exploit encryption mechanisms**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding cryptography fundamentals, including:

- Why cryptography is important  
- Converting plaintext into ciphertext  
- Understanding historical encryption methods  
- Learning modern encryption types  
- Understanding basic mathematical concepts behind cryptography  

---

## 🧭 3. Key Concepts Learned  

- **Plaintext** — original readable data  
- **Ciphertext** — encrypted unreadable data  
- **Encryption** — converting plaintext → ciphertext  
- **Decryption** — converting ciphertext → plaintext  
- **Cipher** — algorithm used for encryption  

---

## 🔐 4. Importance of Cryptography  

Cryptography ensures:

- **Confidentiality** — data remains private  
- **Integrity** — data is not altered  
- **Authentication** — verifies identity  

**SOC Perspective:**  
- Protects sensitive information  
- Used in secure communication (HTTPS, VPNs)  
- Attackers may attempt to break weak encryption  

---

## 🔄 5. Plaintext to Ciphertext  

Example:

    HELLO → KHOOR

👉 Data is transformed using an algorithm (cipher)

**SOC Perspective:**  
- Helps understand how data is secured  
- Important for analyzing encrypted traffic  

---

## 🏛 6. Historical Ciphers  

Examples:

- Caesar Cipher  
- Substitution Cipher  

👉 Simple encryption methods used in the past  

**SOC Observation:**  
- Easily breakable with modern tools  
- Useful for understanding basic concepts  

---

## 🔐 7. Types of Encryption  

### 🔑 Symmetric Encryption
- Same key for encryption & decryption  
- Fast and efficient  

### 🔑 Asymmetric Encryption
- Public key + Private key  
- More secure but slower  

**SOC Perspective:**  
- Used in HTTPS, SSH, VPNs  
- Key management is critical  

---

## ➗ 8. Basic Math in Cryptography  

Cryptography relies on:

- Modular arithmetic  
- Large prime numbers  

👉 Math makes encryption secure  

**SOC Note:**  
- Strong math = strong encryption  
- Weak implementation = vulnerable system  

---

## ⚠ 9. Blue-Team / SOC Observations  

- Encryption protects data but may hide threats  
- Weak ciphers can be broken easily  
- Key management is a major security concern  
- Encrypted traffic still requires monitoring  
- Cryptography is widely used in all secure systems  

---

## 🧾 10. What I Learned (Bullets)  

- Cryptography secures data through encryption  
- Plaintext and ciphertext are core concepts  
- Historical ciphers help understand basics  
- Symmetric and asymmetric encryption differ in usage  
- Mathematics is the foundation of secure encryption  

---

## 💬 Key Takeaway  

> “Cryptography protects data, but its strength depends on proper implementation and key security.”

---

## 📌 Next Steps  

- Learn hashing and digital signatures  
- Study real-world encryption protocols  
- Understand how attackers break weak encryption  
- Explore tools used for cryptographic analysis  
