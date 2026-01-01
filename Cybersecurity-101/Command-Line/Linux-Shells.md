# 🐧 Linux Shells — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Linux-Shells-banner.png?raw=true" alt="Linux Shells Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Command Line  
**Date Completed:** Dec 2025  
**Room Link:** [Linux Shells](https://tryhackme.com/room/linuxshells)
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

A **Linux shell** is the interface that allows users to interact with the operating system by executing commands, scripts, and programs. It acts as a bridge between the user and the Linux kernel.

For SOC analysts, understanding Linux shells is critical because attackers frequently rely on shells for **post-exploitation**, **persistence**, **privilege escalation**, and **command execution** during real-world attacks.

---

## 🎯 2. Learning Objectives  

This room focused on understanding Linux shells and their role in scripting and system interaction, including:

- What a shell is and how users interact with it  
- Different types of Linux shells  
- Basic shell scripting concepts  
- How scripts execute commands automatically  
- Practical use cases through hands-on exercises  

---

## 🧭 3. Key Concepts Learned  

- **Shell as an Interpreter** — shells interpret and execute user commands.  
- **Interactive vs Non-Interactive Shells** — direct user input vs script execution.  
- **Common Linux Shells** — Bash, Sh, Zsh, Fish, etc.  
- **Shell Environment** — variables, PATH, and execution context.  
- **Shell Scripts** — files containing a sequence of commands executed in order.  
- **Shebang (`#!/bin/bash`)** — defines which shell should execute the script.

---

## 🔎 4. Types of Linux Shells  

- **Bash (Bourne Again Shell)** — default shell on most Linux systems.  
- **Sh (Bourne Shell)** — original Unix shell, minimal and portable.  
- **Zsh** — advanced shell with auto-completion and customization.  
- **Fish** — user-friendly shell with scripting differences.  

From a SOC perspective, **Bash is the most commonly abused shell** in attacks.

---

## ⚙ 5. Shell Scripting Basics  

Key scripting components covered:
- Variables and user input  
- Conditional statements (`if`, `else`)  
- Loops  
- Executing system commands from scripts  
- File permissions (`chmod +x script.sh`)  

Scripts allow **automation**, but attackers also use them to:
- Chain commands  
- Maintain persistence  
- Execute malicious logic stealthily  

---

## 🧪 6. Practical Exercise (Locker Script)  

The room included a hands-on exercise demonstrating:
- Script creation  
- Conditional logic  
- User input handling  
- Execution flow  

This exercise shows how even **simple scripts** can control system behavior — highlighting why scripts must be monitored in production environments.

---

## ⚠ 7. Blue-Team / SOC Observations  

- **Shell access often indicates post-exploitation** activity.  
- **Suspicious scripts** can be used for persistence or data exfiltration.  
- **Command history (`.bash_history`)** is a valuable forensic artifact.  
- **Monitoring shell execution** helps detect abnormal behavior.  
- Attackers frequently use **living-off-the-land techniques** via shells.

---

## 🧾 8. What I Learned (Bullets)  

- Linux shells are fundamental to system interaction and automation.  
- Different shells provide different capabilities and syntax.  
- Shell scripts can automate both legitimate admin tasks and malicious actions.  
- Understanding shell behavior helps identify attacker activity.  
- Shell knowledge is essential for SOC investigation and detection.

---

## 💬 Key Takeaway  

> *“If an attacker has a shell, they have control. Monitoring shell activity is essential for effective detection and response.”*

---

## 📌 Next Steps  

- Continue with remaining **Cybersecurity 101** command-line modules  
- Correlate shell usage with Linux authentication and process logs  
- Learn detection techniques for suspicious shell commands and scripts  
- Apply shell knowledge to SOC investigations and threat hunting  

