# ctf_3
This report documents the step-by-step exploitation of the WestWild Boot2Root CTFmachine. 
# WestWild Boot2Root CTF Report

## 📌 Overview

This repository contains the documentation of the successful exploitation of the **WestWild Boot2Root Capture The Flag (CTF)** machine. The objective was to perform penetration testing on the target machine, gain root privileges, capture all available flags, and document every stage of the attack.

The exercise was performed in a controlled virtual lab environment for educational purposes.

---

## 🎯 Objectives

- Perform reconnaissance on the target system
- Enumerate available services
- Exploit vulnerabilities to gain initial access
- Escalate privileges to root
- Capture all flags
- Perform basic post-exploitation tasks
- Document the complete penetration testing process

---

## 🖥️ Lab Environment

### Attacker Machine
- Kali Linux

### Target Machine
- Ubuntu 14.04.6 LTS
- Hostname: WestWild

---

## 🛠️ Tools Used

- Nmap
- smbclient
- SSH
- Base64
- Linux Command Line Utilities
- Nano Editor
- Apache2
- User Management Commands

---

## 📖 Attack Methodology

The penetration testing process followed these phases:

1. Reconnaissance
2. Port Scanning
3. SMB Enumeration
4. Initial Access
5. Credential Discovery
6. SSH Login
7. Privilege Escalation
8. Root Access
9. Flag Capture
10. Post Exploitation
11. System Enumeration

---

## 🔍 Key Activities

- Network scanning using Nmap
- SMB share enumeration
- Anonymous SMB access
- Base64 decoding
- SSH authentication
- Credential harvesting
- Privilege escalation using sudo
- Root flag retrieval
- Web server exploration
- User management
- System configuration review

---

## 🏁 Flags Captured

### Flag 1
Obtained from the SMB share after decoding the Base64 content.

### Flag 2
Captured after obtaining root privileges.

---

## 🔒 Vulnerabilities Identified

- Anonymous SMB share access
- Sensitive credentials stored in readable files
- Weak password management
- Misconfigured sudo permissions
- Poor privilege separation

---

## 📚 Learning Outcomes

This project demonstrates practical experience in:

- Information Gathering
- Network Enumeration
- SMB Enumeration
- Credential Exploitation
- Linux Privilege Escalation
- Post Exploitation
- Linux User Management
- Penetration Testing Methodology
- Capture The Flag (CTF) Workflow

---

## ⚠️ Disclaimer

This report was created solely for educational and cybersecurity training purposes. All testing was conducted in a controlled lab environment. The techniques described should only be performed on systems for which explicit authorization has been obtained.

---

## 👨‍💻 Author

**Name:** Swapnil Suneel Muradunde

**SRN:** R25DE184

**Course:** MCA – 1st Year

**Section:** D

**University:** REVA University, Bengaluru

**Date:** June 2026

---

## 📄 Report

The complete step-by-step report is available in the attached PDF document.
