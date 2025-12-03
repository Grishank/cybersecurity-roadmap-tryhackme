# 🪟 Active Directory Basics — TryHackMe Room  
<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Active-Directory-Basics-Banner.png?raw=true" alt="Active Directory Basics Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Windows & AD Fundamentals  
**Date Completed:** Dec 2025  
**Room Link:** [Active Directory Basics Room](https://tryhackme.com/room/winadbasics)  
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  
This room covers the fundamentals of **Active Directory (AD)** — the central identity and authentication service used in most Windows enterprise environments. For SOC analysts, AD is critical because it controls user authentication, group memberships, privileged accounts, and audit events that indicate compromise or misuse.

---

## 🧭 2. Key Concepts Learned
- **Domain / Forest / Tree** — AD logical hierarchy & scope.  
- **Domain Controllers (DCs)** — systems that authenticate users and serve directory data.  
- **Organizational Units (OUs)** — logical containers for structuring objects and applying Group Policy.  
- **Users & Groups** — user accounts, service accounts, and nested groups for access control.  
- **Group Policy Objects (GPOs)** — centralized configuration enforcement for users and machines.  
- **Kerberos & NTLM** — primary authentication protocols; Kerberos is preferred.  
- **FSMO Roles & Replication** — special role holders and how AD replicates data across DCs.  
- **AD Audit Events** — which security events to monitor (account creation/deletion, group changes, privileged logins).

---

## 🔎 3. Practical Commands & Tools
- **ADUC (Active Directory Users and Computers)** — GUI for viewing users, groups, and OUs.  
- `nltest /dclist:<domain>` — list domain controllers.  
- `whoami /groups` — view current user's group memberships.  
- `net group "<GroupName>" /domain` — list members of a domain group.  
- `dsquery user -name "<username>*"` — find user objects (requires RSAT/tools).  
- Check **Event Viewer → Security** for AD-related events: account creation, group membership changes, Kerberos failures.  

---

## ⚠ 4. Blue-Team / SOC Observations
- **Monitor privileged account activity (Event IDs 4672, 4673)** — high-signal for misuse.  
- **Alert on group membership changes** — attackers often add accounts to privileged groups to escalate.  
- **Watch Kerberos failure events (4771, 4776)** — can indicate credential stuffing or replay attacks.  
- **Segregate DC logs** — Domain Controllers are high-value and require dedicated logging/alerts.  
- **Protect service accounts** — enforce least privilege, managed passwords, and monitoring for abnormal use.

---

## 🧾 5. What I Learned (Bullets)
- AD is the central identity layer for Windows enterprises — understanding it is essential for detection and response.  
- Privilege escalation often leverages group membership changes or AD object manipulation.  
- GPOs can both harden systems and be abused for persistence.  
- Monitoring specific AD event IDs greatly improves detection capability.  
- DCs must be treated as critical assets with elevated logging and protection.

---

## 💬 Key Takeaway
> *“Active Directory is the heart of enterprise identity — secure and monitor it closely to defend the entire environment.”*

---

## 📌 Next Steps
- Moving to Next modules of Cybersecurity 101 path
