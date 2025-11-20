# 🪟 Windows Fundamentals Part 1 (Completed ✅)

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Windows-Fundamentals-1.png?raw=true" alt="Windows Fundamentals Part 1 - TryHackMe Proof" width="900"/>
</p>

**Platform:** TryHackMe  
**Date Completed:** November 2025  
**Room Link:** https://tryhackme.com/room/windowsfundamentals1xbx  
**Status:** ✅ Completed  

---

## 🧠 What I Learned

### 🔹 1. Windows Editions
- Understood major Windows editions:
  - **Home**, **Pro**, **Enterprise**, **Education**
- Learned why **Enterprise** is most used in corporate/SOC environments due to advanced security and Group Policy features.

---

### 🔹 2. The Desktop (GUI)
- Explored the main UI components: **Taskbar**, **Start Menu**, **Search**, **System Tray**.
- GUI helps analysts quickly inspect:
  - Running applications
  - Installed programs
  - User sessions

---

### 🔹 3. Introduction to Windows
- Understood how Windows manages:
  - **Processes**
  - **Threads**
  - **Services**
- Gained a basic understanding of how Windows differs from Linux in structure and permissions.

---

### 🔹 4. The File System
- Explored important directories:
  - `C:\Users\`
  - `C:\Program Files\`
  - `C:\Windows\`
  - `C:\Windows\System32\`
- Learned how malware often hides in:
  - `AppData\Roaming`
  - `Temp`
  - Suspicious `.exe` files inside unusual folders

---

### 🔹 5. The Windows\System32 Folder
- System32 is the **core of Windows OS**, containing critical executables:
  - `cmd.exe`
  - `powershell.exe`
  - `taskmgr.exe`
  - `regedit.exe`
  - `svchost.exe`
- SOC analysts monitor this folder for tampering or unexpected file changes.

---

### 🔹 6. User Accounts, Profiles & Permissions
- Learned differences between:
  - Standard User
  - Administrator
  - SYSTEM (highest privilege)
- Understood user profiles stored in:
  - `C:\Users\<username>`
- Attackers often create **backdoor accounts** after compromise.

---

### 🔹 7. User Account Control (UAC)
- UAC prevents unauthorized admin-level changes.
- Attackers often attempt UAC bypass using:
  - Auto-elevating executables
  - Signed Windows binaries
  - Registry tricks

---

### 🔹 8. Settings & the Control Panel
- Learned where to find:
  - Network settings
  - Firewall configuration
  - Installed apps
  - Startup programs
- Important for both IT and SOC troubleshooting.

---

## ⚙️ Key Takeaways

> “To investigate Windows attacks, you must first understand how Windows normally behaves.”

- Windows file structure is essential for detecting abnormalities.
- **System32** is the heartbeat of Windows — any modification is a red flag.
- Knowing user accounts + permissions = understanding attack surface.
- UAC is a critical protection layer attackers try to bypass.

---

## 🧩 Next Steps

- Continue to **Windows Fundamentals Part 2** --

---

