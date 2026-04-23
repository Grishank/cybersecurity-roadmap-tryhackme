# 🔑 Hashing Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Hashing-Basics-banner.png?raw=true" alt="Hashing Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Cryptography  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/hashingbasics                              
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Hashing is a process of converting data into a **fixed-length string (hash value)** using a mathematical function. Unlike encryption, hashing is **one-way**, meaning it cannot be reversed back to the original data.

For SOC analysts, hashing is essential for **password security, integrity checking, and detecting compromised data**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding hashing fundamentals, including:

- How hash functions work  
- Why storing passwords in plaintext is insecure  
- How hashing secures password storage  
- Identifying different hash types  
- Understanding password cracking techniques  
- Using hashing for integrity verification  

---

## 🧭 3. Key Concepts Learned  

- **Hash Function** — converts data into hash value  
- **Hash Value** — fixed-length output  
- **One-Way Function** — cannot be reversed  
- **Salt** — random data added before hashing  
- **Hash Collision** — two inputs produce same hash  

---

## 🔐 4. Hash Functions  

Common hash algorithms:

- MD5  
- SHA-1  
- SHA-256  

👉 Same input → same hash  
👉 Small change → completely different hash  

**SOC Perspective:**  
- Used in authentication and file verification  
- Weak hashes (MD5, SHA-1) are insecure  

---

## ❌ 5. Insecure Password Storage  

Storing passwords as plaintext:

- Easily readable  
- Easily stolen  

**SOC Observation:**  
- Major security risk  
- Common cause of data breaches  

---

## 🔒 6. Secure Password Storage  

Passwords should be:

- Hashed  
- Salted  

👉 Example:

    password + salt → hash  

**SOC Perspective:**  
- Prevents attackers from easily cracking passwords  
- Salt protects against rainbow table attacks  

---

## 🔍 7. Recognising Password Hashes  

Different hashes have patterns:

- MD5 → 32 characters  
- SHA-1 → 40 characters  
- SHA-256 → 64 characters  

**SOC Use:**  
- Identify hash types during investigations  

---

## 💥 8. Password Cracking  

Methods:

- Brute Force  
- Dictionary Attack  
- Rainbow Tables  

**SOC Perspective:**  
- Weak passwords are easily cracked  
- Strong hashing slows attackers  

---

## 📦 9. Hashing for Integrity Checking  

Used to verify:

- Files  
- Downloads  
- System data  

👉 If hash changes → file modified  

**SOC Perspective:**  
- Detect tampering  
- Ensure file integrity  

---

## ⚠ 10. Blue-Team / SOC Observations  

- Hashing is critical for password security  
- Weak algorithms are vulnerable  
- Salting improves security  
- Hashes help detect file changes  
- Password attacks are very common  

---

## 🧾 11. What I Learned (Bullets)  

- Hashing converts data into fixed-length values  
- It is a one-way process  
- Passwords should never be stored in plaintext  
- Salting improves security  
- Hashing is used for integrity verification  

---

## 💬 Key Takeaway  

> “Hashing protects sensitive data, but its effectiveness depends on strong algorithms and proper implementation.”

---

## 📌 Next Steps  

- Learn advanced hashing (bcrypt, Argon2)  
- Practice password cracking tools  
- Study hash-based attacks  
- Understand secure authentication systems  
