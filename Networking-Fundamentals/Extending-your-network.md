# 🌐 Extending Your Network (Completed ✅)

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Extending-your-network.png?raw=true" alt="Extending Your Network - TryHackMe Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Date Completed:** November 2025  
**Room Link:** https://tryhackme.com/room/extendingyournetwork  
**Status:** ✅ Completed  

---

### 🧠 What I Learned

#### 🔹 1. Introduction to Port Forwarding  
- Understood how external users/services reach internal machines behind a NAT router.  
- Learned how routers map:  
  - **External Port → Internal IP + Port**  
- Identified that misconfigured port forwarding is a **huge security risk**.  
- Cybersecurity relevance:  
  - Attackers often scan forwarded ports to find exposed services.  

---

#### 🔹 2. Firewalls 101  
- Understood the difference between:  
  - **Packet filtering firewalls**  
  - **Stateful firewalls**  
  - **Application-level firewalls**  
- Learned how firewalls enforce rules based on:  
  - Source IP  
  - Destination IP  
  - Ports  
  - Protocols  
- Gained clarity on how SOC Analysts analyze firewall logs.

---

#### 🔹 3. Practical — Firewall  
- Configured simple firewall rules in the simulated environment.  
- Allowed/blocked specific ports based on the task.  
- Verified dropped vs allowed traffic.  
- Reinforced the importance of **least privilege rule design**.

---

#### 🔹 4. VPN Basics  
- Learned how VPNs create secure encrypted tunnels over the internet.  
- Understood key concepts:  
  - Encryption  
  - Encapsulation  
  - Tunneling  
  - Authentication  
- Learned why VPNs protect against:  
  - Man-in-the-middle attacks  
  - Sniffing  
  - ISP-level surveillance

---

#### 🔹 5. LAN Networking Devices  
- Covered common hardware:
  - **Routers**
  - **Switches**
  - **Access Points**
  - **Modems**
- Understood how each operates at different OSI layers.  
- Learned how combining them extends a LAN securely.

---

#### 🔹 6. Practical — Network Simulator  
- Built a mini network in the TryHackMe simulator.  
- Connected devices, tested routing, and validated packet flow.  
- Understood the relationship between IP addressing, routing, and device roles.

---

### ⚙️ Key Takeaways
> “A strong network is built by applying the right tools — firewalls, VPNs, routers, and secure port-forwarding.”

Understanding these fundamentals is key for any SOC, blue team, or cybersecurity role.

---

### 🧩 Next Steps
- Move on to **Networking Challenges / Advanced Rooms** if needed.  
- Practice firewall rule-writing on Linux (iptables, ufw).  
- Test VPNs (OpenVPN / WireGuard) in home lab or VM environment.  


---

