# SOC Active Directory Detection Lab using MITRE ATT&CK & Atomic Red Team

## 📌 Overview

This project demonstrates a SOC monitoring lab built on Active Directory environment. The lab simulates real-world attacks using Atomic Red Team and maps detections to the MITRE ATT&CK framework using Splunk SIEM.

The objective is to detect attacker behavior in an Active Directory network and analyze logs centrally using Splunk.

---

## 🎯 Objectives

* Build Active Directory SOC lab
* Simulate attacks using Atomic Red Team
* Detect malicious activity in Splunk
* Map detections to MITRE ATT&CK
* Practice SOC monitoring workflow

---

## 🛠️ Tools & Technologies

* Splunk SIEM
* Windows Server (Active Directory)
* Splunk Universal Forwarder
* Windows 10 Client
* Kali Linux Attacker
* Atomic Red Team
* MITRE ATT&CK Framework

---

## 🌐 Lab Network

* Network: 192.168.230.0/24
* Splunk Server: 192.168.230.130
* Active Directory: 192.168.230.135
* Kali Linux: 192.168.230.131
* Windows 10: 192.168.230.132

---

## 🏗️ Architecture
<img src="https://raw.githubusercontent.com/Prashant42125/SOC-AD-AND-MITRE-ATTACK-MONITORING/main/SOC-AD-MITRE-MONITORING.png" width="900">

---

## ⚙️ Workflow

1. Kali Linux simulates attacks
2. Windows 10 joined to Active Directory
3. Atomic Red Team executes attack techniques
4. Windows logs generated
5. Splunk Universal Forwarder sends logs
6. Splunk collects and indexes data
7. Alerts mapped to MITRE ATT&CK
8. SOC analysis performed

---

## 🔍 Attack Simulation

* Credential Access
* Privilege Escalation
* Lateral Movement
* Persistence
* Discovery

Using:
Atomic Red Team Tests

---

## 📊 Detection

Splunk detects:

* Failed logins
* Privilege escalation
* PowerShell execution
* Suspicious authentication
* Lateral movement attempts

---

## 🧠 MITRE ATT&CK Mapping

Example Techniques:

* T1110 – Brute Force
* T1059 – Command Execution
* T1003 – Credential Dumping
* T1021 – Remote Services
* T1087 – Account Discovery

---

## 📚 Skills Demonstrated

* Active Directory Monitoring
* SIEM Detection Engineering
* MITRE ATT&CK Mapping
* Atomic Red Team Testing
* SOC Threat Hunting

---

## 👤 Author

Prashant
CEHv13 | SOC Analyst | Blue Team
