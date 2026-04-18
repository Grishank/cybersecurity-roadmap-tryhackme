# 🧪 Tcpdump: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Tcpdump-The-Basics-banner.png?raw=true" alt="Tcpdump Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Networking  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/tcpdump                                       
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Tcpdump is a powerful **command-line packet analyzer** used to capture and inspect network traffic directly from the terminal. It is lightweight, fast, and widely used in real-world environments.

For SOC analysts, tcpdump is essential for **quick packet capture, remote analysis, and troubleshooting without GUI tools**.

---

## 🎯 2. Learning Objectives  

This room focused on understanding tcpdump fundamentals, including:

- Capturing network traffic using tcpdump  
- Understanding basic packet capture commands  
- Applying filtering expressions  
- Using advanced filtering techniques  
- Displaying and saving captured packets  

---

## 🧭 3. Key Concepts Learned  

- **Packet Capture** — capturing live network traffic  
- **Filtering Expressions** — selecting specific traffic  
- **Interface Selection** — choosing network interface  
- **PCAP Files** — saving captured data for analysis  

---

## 🛠 4. Basic Packet Capture  

Basic command:

    tcpdump

Common usage:

    tcpdump -i eth0

👉 Captures packets from a specific interface  

**SOC Perspective:**  
- Useful for real-time monitoring  
- Quick investigation tool  

---

## 🔍 5. Filtering Expressions  

Examples:

    tcpdump host 192.168.1.1  
    tcpdump port 80  
    tcpdump tcp  

👉 Filters traffic based on conditions  

**SOC Perspective:**  
- Helps isolate suspicious traffic  
- Reduces unnecessary data  

---

## ⚙️ 6. Advanced Filtering  

Examples:

    tcpdump tcp and port 80  
    tcpdump src host 192.168.1.1  
    tcpdump dst port 443  

👉 Combine filters for precision  

**SOC Perspective:**  
- Detect targeted attacks  
- Analyze specific communication patterns  

---

## 📊 7. Displaying Packets  

Options:

    tcpdump -v  
    tcpdump -vv  
    tcpdump -vvv  

👉 Increasing verbosity shows more details  

Save packets:

    tcpdump -w capture.pcap  

Read saved file:

    tcpdump -r capture.pcap  

---

## ⚠ 8. Blue-Team / SOC Observations  

- Tcpdump is fast and efficient for live capture  
- Ideal for remote servers without GUI  
- Filtering is critical to avoid overload  
- Often used in incident response  
- Works well with Wireshark for deeper analysis  

---

## 🧾 9. What I Learned (Bullets)  

- Tcpdump captures network traffic via command line  
- Filters help isolate useful data  
- Advanced filtering improves investigation accuracy  
- PCAP files allow offline analysis  
- Tcpdump is essential for real-world SOC work  

---

## 💬 Key Takeaway  

> “Tcpdump provides fast, low-level visibility into network traffic — making it a powerful tool for real-time investigation.”

---

## 📌 Next Steps  

- Continue with Nmap: The Basics  
- Practice capturing and filtering traffic  
- Analyze tcpdump captures in Wireshark  
- Learn advanced tcpdump expressions  
