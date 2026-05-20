# 🔐 CAPA: The Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/CAPA-The-Basics-banner.png?raw=true" alt="CAPA The Basics Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Defensive Security Tooling  
**Difficulty:** Easy  
**Date Completed:** May 2026  
**Room Link:** https://tryhackme.com/room/capabasics  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **CAPA: The Basics** room introduces **CAPA**, a malware capability analysis tool developed by Mandiant/FLARE used to identify malicious behaviors and capabilities inside executable files.

Instead of simply showing raw code, CAPA helps analysts understand:
- What malware can do
- Which behaviors exist
- Which ATT&CK techniques are present
- Which suspicious capabilities are detected

The room focuses on:
- CAPA fundamentals
- Malware capability analysis
- MITRE ATT&CK mapping
- MAEC concepts
- Malware behavior catalogues
- Capability namespaces
- Understanding CAPA results

This room builds foundational knowledge required for:
- Malware analysis
- Threat hunting
- SOC investigations
- Incident response
- Reverse engineering workflows
- Threat intelligence analysis

---

# 🎯 Learning Objectives

- Understand what CAPA is
- Learn how CAPA works
- Understand malware capability analysis
- Learn MITRE ATT&CK mappings
- Understand MAEC classifications
- Learn capability namespaces
- Practice reading CAPA output
- Understand malware behavior detection

---

# 🧩 Task 1 — Introduction

CAPA is an automated malware capability detection tool.

It analyzes executable files and identifies:
- Suspicious behaviors
- Malware capabilities
- ATT&CK techniques
- API usage patterns
- Embedded malicious functionality

CAPA helps analysts quickly understand malware functionality without manually reversing every instruction.

---

# ⚙️ Task 2 — Tool Overview: How CAPA Works

CAPA works by analyzing:
- Binary files
- Functions
- Strings
- API calls
- Instructions
- Embedded behaviors

It uses predefined rules to match suspicious patterns and identify malicious capabilities.

## Common Analysis Targets

- Windows PE files
- Malware samples
- Suspicious executables
- Packed binaries
- Reverse engineering samples

---

# 🧠 Task 3 — Dissecting CAPA Results Part 1: General Information, MITRE and MAEC

One of the most important parts of CAPA output is the mapping to known threat frameworks.

## MITRE ATT&CK

CAPA can map detected behaviors to:
- Persistence
- Defense Evasion
- Credential Access
- Discovery
- Command & Control

This helps analysts understand attacker techniques quickly.

## MAEC

MAEC (Malware Attribute Enumeration and Characterization) helps standardize malware behavior descriptions.

CAPA uses MAEC categories to:
- Classify malware behavior
- Improve malware documentation
- Standardize analysis results

---

# 📚 Task 4 — Dissecting CAPA Results Part 2: Malware Behavior Catalogue

CAPA organizes detected malware behaviors into categories.

## Common Malware Behaviors

| Behavior | Description |
|---|---|
| File Creation | Creates or modifies files |
| Process Injection | Injects into other processes |
| Registry Modification | Changes Windows registry |
| Network Communication | Connects to remote hosts |
| Credential Access | Attempts credential theft |
| Persistence | Maintains long-term access |

---

# 🏷️ Task 5 — Dissecting CAPA Results Part 3: Namespaces

Namespaces help organize malware capabilities into logical groups.

## Examples of Namespaces

| Namespace | Purpose |
|---|---|
| host-interaction | System interaction |
| communication | Network communication |
| persistence | Persistence mechanisms |
| anti-analysis | Evasion techniques |
| execution | Code execution methods |

Namespaces improve:
- Malware categorization
- Analyst readability
- Threat investigation workflows

---

# 🚨 Task 6 — Dissecting CAPA Results Part 4: Capability

Capabilities represent what malware is able to perform.

Examples include:
- Keylogging
- Process injection
- Command execution
- File encryption
- Network beaconing
- Credential dumping

CAPA identifies these automatically using rule-based analysis.

---

# 🔍 Understanding CAPA Output

CAPA results commonly include:
- Capability names
- ATT&CK mappings
- Severity indicators
- Function locations
- Namespace categories
- Behavioral descriptions

This allows analysts to quickly prioritize suspicious functionality.

---

# 🛡️ SOC / Blue Team Perspective

CAPA is extremely valuable for SOC analysts because it helps:
- Understand malware behavior quickly
- Accelerate triage
- Improve incident investigations
- Identify attacker techniques
- Classify suspicious binaries
- Support malware reverse engineering

SOC teams commonly use CAPA for:
- Malware investigations
- Threat hunting
- IOC development
- Incident response
- Malware capability assessment

---

# ⚠️ Common Security Use Cases

- Malware triage
- Threat intelligence analysis
- Reverse engineering support
- ATT&CK mapping
- Suspicious executable analysis
- Behavioral malware detection
- Incident investigation

---

# 🔬 Key Concepts Learned

- CAPA fundamentals
- Malware capability analysis
- MITRE ATT&CK mapping
- MAEC classifications
- Capability namespaces
- Malware behavior catalogues
- Automated malware analysis
- Threat investigation workflows

---

# 💬 Key Takeaway

> “CAPA helps analysts quickly understand what malware is capable of doing by automatically identifying suspicious behaviors and mapping them to known attack techniques.”

---

# 🚀 Next Steps

- Practice malware capability analysis
- Learn basic reverse engineering
- Explore PE file analysis
- Study MITRE ATT&CK techniques
- Practice malware triage workflows
- Learn YARA and static analysis
- Combine CAPA with sandbox analysis
- Explore malware behavior detection tools
