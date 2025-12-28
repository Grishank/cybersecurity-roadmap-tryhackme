# 🪟 Windows Command Line — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Window-command-line-banner.png?raw=true" alt="Windows Command Line Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Command Line  
**Date Completed:** Dec 2025  
**Room Link:** [Windows Command Line](https://tryhackme.com/room/windowscommandline)                                    
**Status:** ✔ Completed  

---

## 🔑 1. Introduction  

Everyone prefers a **graphical user interface (GUI)** until they master the **command-line interface (CLI)**. While GUIs are intuitive and easy to explore, they often require multiple clicks and consume more system resources. In contrast, the command line allows faster interaction, automation, and precise control — all without leaving the keyboard.

This room introduces the **Windows Command Prompt (`cmd.exe`)**, the default command-line interpreter in Windows environments. For SOC analysts, CLI proficiency is essential for rapid investigation, troubleshooting, and system analysis, especially in restricted or remote environments.

---

## 🎯 2. Learning Objectives  

This room focused on using the Windows command line to:

- Display basic system information  
- Check and troubleshoot network configuration  
- Manage files and directories  
- Inspect running processes and system activity  

---

## 🧭 3. Key Concepts Learned  

- **CLI vs GUI** — CLIs are faster, scriptable, and resource-efficient compared to GUIs.  
- **System Information Commands** — quickly gather OS, user, and system details.  
- **Network Diagnostics** — inspect IP configuration and connectivity issues.  
- **File & Directory Management** — navigate, create, copy, and delete files via CLI.  
- **Process & Task Management** — identify running processes and active services.  
- **Automation Potential** — commands can be combined into batch scripts for repeated tasks.  

---

## 🔎 4. Important Commands Practiced  

### 📌 System Information
- `whoami` — identify the current logged-in user  
- `hostname` — display system hostname  
- `systeminfo` — detailed OS and hardware information  

### 🌐 Network Troubleshooting
- `ipconfig` — view IP configuration  
- `ping` — test network connectivity  
- `tracert` — trace packet path across networks  
- `netstat` — view active connections and listening ports  

### 📁 File & Disk Management
- `dir` — list directory contents  
- `cd` — change directory  
- `mkdir` / `rmdir` — create or remove directories  
- `copy` / `move` / `del` — manage files  

### ⚙ Task & Process Management
- `tasklist` — list running processes  
- `taskkill` — terminate a process by PID or name  

---

## ⚠ 5. Blue-Team / SOC Observations  

- **Command-line activity is highly valuable for detection** — attackers often rely on CLI tools during post-exploitation.  
- **Monitoring process creation (Event ID 4688)** helps detect suspicious command execution.  
- **Network commands (`netstat`, `ipconfig`)** are frequently used during lateral movement and reconnaissance.  
- **Living-off-the-Land (LOLBins)** often leverage built-in Windows commands instead of malware.  
- **CLI logs + command-line arguments** significantly improve threat detection accuracy.

---

## 🧾 6. What I Learned (Bullets)  

- Mastery of Windows CLI greatly improves investigation speed and efficiency.  
- Many forensic and incident response tasks can be performed without a GUI.  
- Windows commands provide immediate visibility into system and network state.  
- CLI usage is common in both legitimate admin activity and attacker behavior.  
- Understanding normal command usage helps detect abnormal or malicious patterns.

---

## 💬 Key Takeaway  

> *“The command line is a power tool — for administrators, defenders, and attackers alike. Knowing it well is critical for effective SOC operations.”*

---

## 📌 Next Steps  

- Continue with the next **Cybersecurity 101** command-line modules  
- Apply command-line knowledge to **SOC log analysis and investigations**  
- Correlate CLI activity with Windows Event Logs for detection use cases  


