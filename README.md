
# 🔐 Web Application Penetration Testing – Week 4

## Networkwalks Internship | Web Application Security Report

A practical cybersecurity learning project focused on Web Application Vulnerability Assessment and Penetration Testing (VAPT). This project documents the assessment workflow, tools, security observations, and remediation recommendations.

---

## 👨‍💻 Author

**Aritra Pal**  
Cyber Crime Investigator and Fraud Analyser  
Cybersecurity Student | Ethical Hacking | Web Application Security

---

## 🎯 Project Overview

- **Project Name:** Web Application Penetration Testing
- **Internship:** Networkwalks
- **Project Week:** Week 4
- **Assessment Type:** Web Application VAPT
- **Reference Website:** https://medirozahospital.com/
- **Operating System:** Kali Linux

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Nmap | Network scanning and service identification |
| Burp Suite | Web application request and response analysis |
| Gobuster | Directory and endpoint discovery |
| PDF2John | PDF password-hash extraction for authorized auditing |
| John the Ripper | Password-strength auditing |
| Kali Linux | Security testing environment |

---

## 📦 Installation and Setup

Update Kali Linux packages:

```bash
sudo apt update
sudo apt upgrade
```

Install Nmap:

```bash
sudo apt install nmap
```

Install Gobuster:

```bash
sudo apt install gobuster
```

Install John the Ripper:

```bash
sudo apt install john
```

Check installed tools:

```bash
nmap --version
gobuster --version
john --version
```

---

## 🔍 Project Workflow

### Step 1: Scope and Authorization

Confirm written permission, approved targets, and testing boundaries before performing any security assessment.

### Step 2: Reconnaissance

Collect permitted information about the target and identify the approved assessment scope.

### Step 3: Network Scanning

Use Nmap in an authorized lab or on systems you are permitted to assess.

Command reference:

```bash
nmap --help
```

### Step 4: Web Application Analysis

Use Burp Suite to review HTTP requests and responses in a controlled testing environment.

### Step 5: Directory Enumeration

Check Gobuster syntax and options:

```bash
gobuster dir --help
```

### Step 6: Password Security Review

Use PDF2John and John the Ripper only for files and password hashes you own or have permission to audit.

```bash
john --help
```

### Step 7: Documentation

Record the assessment process, observations, screenshots, and security recommendations in the project report.

---

## 📌 Findings Summary

The reference report discusses the following security concerns:

### 1. SQL Injection / Authentication Concern

The source report describes a potential SQL-injection-related authentication issue.

**Potential Impact:**
- Authentication bypass
- Unauthorized access
- Data confidentiality risks

### 2. Sensitive Information Disclosure

The source report describes sensitive information exposure through a legacy website or database area.

**Potential Impact:**
- Privacy risks
- Information leakage
- Possible misuse of exposed data

Note: These findings are summarized from the reference report and have not been independently verified by this repository's author.

---

## 🛡️ Security Recommendations

- Use parameterized queries and prepared statements.
- Validate user input on the server side.
- Apply least-privilege database permissions.
- Implement strong authentication and authorization.
- Remove or restrict exposed legacy resources.
- Keep software and frameworks updated.
- Monitor application logs for suspicious activity.
- Protect sensitive information.
- Perform authorized retesting after remediation.

---

## 📚 Learning Outcomes

- Understanding web application security assessment
- Learning common VAPT tools
- Understanding authentication and input-validation risks
- Identifying sensitive information exposure
- Preparing professional security reports
- Practicing responsible and authorized security testing

---

## 📁 Project Structure

```text
NW-WK4-Penetration-Testing-Report/
│
├── README.md
├── Report.pdf
└── Screenshots/
    ├── assessment-overview.png
    └── evidence.png
```

Add screenshots only if they are your own or authorized for publication. Redact credentials, personal data, and sensitive target details.

---

## ⚠️ Disclaimer

This project is intended for educational and defensive cybersecurity purposes only.

Perform security testing only on systems you own or have explicit written authorization to assess. Do not access, modify, or disclose sensitive information without permission.

The reference report does not grant permission to test its target website.

---

## 👨‍💻 Author

**Aritra Pal**  
Cyber Crime Investigator and Fraud Analyser

Cybersecurity Student | Ethical Hacking | Web Application Security

**Learn • Test Responsibly • Document • Secure**
