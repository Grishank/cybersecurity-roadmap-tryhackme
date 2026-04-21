# 🛰️ Nmap: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Nmap-The-Basics-banner.png?raw=true" alt="Nmap Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Networking  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/nmap                                                              
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Nmap (Network Mapper) is a powerful tool used for **network discovery and security scanning**. It helps identify active hosts, open ports, running services, and potential vulnerabilities.

For SOC analysts, Nmap is important for understanding how attackers **scan and gather information before launching attacks**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding Nmap fundamentals, including:

- Discovering active hosts on a network  
- Scanning ports to identify open services  
- Detecting service versions  
- Understanding scan speed and timing  
- Controlling output formats  

---

## 🧭 3. Key Concepts Learned  

- **Host Discovery** — finding active devices  
- **Port Scanning** — identifying open ports  
- **Service Detection** — identifying running services  
- **Timing Control** — adjusting scan speed  
- **Output Formats** — saving scan results  

---

## 🌐 4. Host Discovery — Who Is Online  

Basic command:

    nmap -sn 192.168.1.0/24

👉 Identifies live hosts without scanning ports  

**SOC Perspective:**  
- Detects active devices  
- Used by attackers for reconnaissance  

---

## 🚪 5. Port Scanning — Who Is Listening  

Basic command:

    nmap 192.168.1.1

👉 Scans for open ports  

Common ports:
- 80 → HTTP  
- 443 → HTTPS  
- 22 → SSH  

**SOC Perspective:**  
- Open ports = potential attack entry points  

---

## 🔍 6. Version Detection — Extract More Information  

Command:

    nmap -sV 192.168.1.1

👉 Detects service versions  

**SOC Perspective:**  
- Helps identify outdated/vulnerable services  
- Useful for vulnerability analysis  

---

## ⚡ 7. Timing — How Fast is Fast  

Command:

    nmap -T4 192.168.1.1

👉 Controls scan speed  

- T0 → very slow  
- T5 → very fast  

**SOC Observation:**  
- Fast scans = noisy  
- Slow scans = stealthy  

---

## 📊 8. Output — Controlling What You See  

Save output:

    nmap -oN result.txt 192.168.1.1  

Other formats:
- Normal  
- XML  
- Grepable  

**SOC Perspective:**  
- Helps in reporting and analysis  
- Used for documentation  

---

## ⚠ 9. Blue-Team / SOC Observations  

- Nmap is widely used for reconnaissance  
- Open ports expose services to attacks  
- Version detection helps identify vulnerabilities  
- Scan timing affects detectability  
- Logs may reveal scanning attempts  

---

## 🧾 10. What I Learned (Bullets)  

- Nmap is used for network scanning and discovery  
- Host discovery identifies active systems  
- Port scanning reveals exposed services  
- Version detection shows detailed service info  
- Scan speed impacts stealth and detection  

---

## 💬 Key Takeaway  

> “Before any attack, reconnaissance happens — and tools like Nmap reveal the attack surface of a network.”

---

## 📌 Next Steps  

- Practice scanning different targets  
- Learn advanced Nmap scans (SYN, UDP)  
- Study how attackers use Nmap  
- Detect Nmap scans in logs  
