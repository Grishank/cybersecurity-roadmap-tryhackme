# 🔓 John the Ripper: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/John-The-Ripper-The-Basics-banner.png?raw=true" alt="John the Ripper Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Cryptography  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/johntheripperbasics                                   
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

John the Ripper (JtR) is a powerful **password cracking tool** used to identify weak passwords by attempting to crack hashes.

For SOC analysts, it is important to understand how attackers **break passwords**, so they can detect weak authentication mechanisms and improve security.

---

## 🎯 2. Learning Objectives  

This room focused on understanding password cracking fundamentals, including:

- Basic terminology used in password cracking  
- Setting up John the Ripper  
- Cracking basic hashes  
- Cracking Windows authentication hashes  
- Cracking Linux (/etc/shadow) hashes  
- Using different cracking modes  
- Applying custom rules  
- Cracking password-protected files  

---

## 🧭 3. Key Concepts Learned  

- **Hash Cracking** — recovering passwords from hashes  
- **Wordlists** — list of possible passwords  
- **Brute Force** — trying all combinations  
- **Dictionary Attack** — using wordlists  
- **Rules** — modifying words to improve cracking  

---

## 🧠 4. Basic Terms  

- **Plaintext** — original password  
- **Hash** — encrypted password  
- **Cracking** — finding original password  
- **Wordlist** — list of passwords to try  

**SOC Perspective:**  
- Weak passwords are easily cracked  
- Strong password policies are critical  

---

## ⚙️ 5. Setting Up Your System  

- Install John the Ripper  
- Use pre-built wordlists (like rockyou.txt)  

**SOC Perspective:**  
- Common tool used by attackers  
- Useful for security testing  

---

## 🔓 6. Cracking Basic Hashes  

Command:

    john hash.txt

👉 Attempts to crack hashes using default methods  

**SOC Perspective:**  
- Demonstrates how fast weak hashes can be broken  

---

## 🪟 7. Cracking Windows Authentication Hashes  

- Targets NTLM hashes  

👉 Used in Windows systems  

**SOC Observation:**  
- NTLM hashes are common attack targets  
- Used in lateral movement attacks  

---

## 🐧 8. Cracking /etc/shadow Hashes  

- Linux password storage file  

👉 Requires combining passwd + shadow  

**SOC Perspective:**  
- Critical for Linux security  
- Misconfiguration can expose hashes  

---

## 🎯 9. Single Crack Mode  

- Uses user information (username, etc.)  
- Generates targeted guesses  

**SOC Observation:**  
- Very effective for weak passwords  

---

## ⚙️ 10. Custom Rules  

- Modify wordlists  

Examples:
- Add numbers  
- Change case  

👉 Makes attacks more powerful  

**SOC Perspective:**  
- Attackers rarely use plain wordlists  
- Rules increase success rate  

---

## 📦 11. Cracking Password Protected ZIP Files  

- Extract hash from ZIP  
- Use John to crack  

👉 Example use case  

**SOC Perspective:**  
- Common in forensic investigations  

---

## 📦 12. Cracking RAR Archives  

- Similar process to ZIP  
- Requires hash extraction  

**SOC Observation:**  
- Attackers may protect stolen data  

---

## 🔑 13. Cracking SSH Keys  

- Target encrypted private keys  

👉 If cracked → full access  

**SOC Perspective:**  
- Critical security risk  
- Strong passphrases required  

---

## ⚠ 14. Blue-Team / SOC Observations  

- Weak passwords are easily compromised  
- Hash cracking is a common attack technique  
- NTLM and /etc/shadow are key targets  
- Custom rules make attacks more effective  
- Password-protected files are not always secure  

---

## 🧾 15. What I Learned (Bullets)  

- John the Ripper is used to crack password hashes  
- Wordlists and rules improve cracking success  
- Windows and Linux hashes are common targets  
- Weak passwords can be cracked quickly  
- Password security is critical for system protection  

---

## 💬 Key Takeaway  

> “If a password can be guessed, it can be cracked — strong passwords and proper hashing are essential for security.”

---

## 📌 Next Steps  

- Practice with different hash types  
- Learn Hashcat (advanced cracking tool)  
- Study password attack techniques  
- Implement strong password policies  
