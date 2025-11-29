# 🕵️‍♂️ Search Skills — TryHackMe Room  
<img src="../assets/images/Search-Skills.png" width="900"/>

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Start Your Cybersecurity Journey  
**Date Completed:** Nov 2025  
**Room Link:** https://tryhackme.com  
**Status:** ✔ Completed  

---

## 🔍 1. Introduction  
This room focuses on one of the most important abilities in cybersecurity: **finding the right information quickly and accurately**. Search skills are essential for SOC analysts, penetration testers, threat hunters, and OSINT researchers.

You learn how to search smarter — not harder — using advanced operators, targeted engines, and professional research techniques.

---

## 🧪 2. Evaluation of Search Results  
Not all search results are trustworthy.  
The room teaches how to evaluate:

- **Source credibility** (official > community > random blogs)  
- **Timeliness** (newer is often more accurate for vulnerabilities)  
- **Relevance** (context vs. your exact use case)  
- **Authority** (vendors, trusted researchers, security orgs)  

Key point: *Quality matters more than quantity.*

---

## 🔎 3. Search Engines (Core OSINT Skill)  
The room explains how to use standard search engines like Google and Bing more effectively.

Learned:

- Keyword combinations for accurate results  
- Boolean operators (`AND`, `OR`, `" "` exact match)  
- Filtering by site (`site:`)  
- Filtering by file type (`filetype:`)  
- Excluding results (`-keyword`)  
- Using advanced operators to dig deeper  

Examples:

```
"windows event id 4625" site:microsoft.com
nmap cheat sheet filetype:pdf
best soc analyst blogs -reddit
```

---

## 🔍 4. Specialized Search Engines  
Used for cybersecurity-focused investigations:

### **🔸 Shodan**  
- Finds internet-exposed devices/services  
- Used for recon, asset discovery, vulnerability checks  

### **🔸 Censys**  
- Similar to Shodan but more detailed certificate & service data  

### **🔸 PublicWWW**  
- Search websites by source code, JS snippets, tracking IDs  

### **🔸 DuckDuckGo / StartPage**  
- Privacy-focused; good for OSINT without tracking  

---

## ⚠ 5. Vulnerabilities & Exploits Search  
Learned how to look up:

### **🔹 CVEs (Common Vulnerabilities & Exposures)**  
Sources:
- MITRE CVE Database  
- NVD (National Vulnerability Database)  
- Exploit-DB  
- Rapid7 AttackerKB  
- SecurityFocus  
- Vendor advisories (Microsoft, Apache, Cisco, etc.)

### Example search:
```
CVE-2021-41773 apache exploit
site:nvd.nist.gov CVE-2022-30190
```

This helps when investigating alerts or researching threats.

---

## 📄 6. Technical Documentation  
Critical for SOC & Pentesting:

Learned how to search for:
- API documentation  
- RFCs (Internet standards)  
- Vendor security docs  
- Official Windows & Linux manuals (`man` pages)  
- GitHub repositories for tools  

Examples:

```
windows event log documentation site:microsoft.com
nmap timing templates docs
```

---

## 🌐 7. Social Media OSINT  
Search skills extend to social platforms:

- Twitter/X (threat intel & zero-day news)  
- Reddit (sysadmin & cybersecurity communities)  
- GitHub (public PoCs, scripts)  
- LinkedIn (company tech stacks, employee data)  

Search examples:

```
intitle:"hacked" site:reddit.com
exploit poc "CVE-2023" github
```

---

## 🧠 Key Takeaway  
> “In cybersecurity, the person who finds information fastest wins.”

Good search skills = faster investigations, quicker detection, stronger OSINT, and better decision-making.

---

## 📌 Next Steps  
- Continue with the next module in Cybersecurity 101  
- Apply advanced search techniques during recon, research, and SOC investigations  

