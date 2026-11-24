🔐 Web Application Penetration Testing – Week 4
Networkwalks Internship | Web Application Security Report
A learning-focused documentation project based on the Week 4 web application penetration-testing report in the reference repository. It summarizes the assessment scope, tools, methodology, reported observations, risk discussion, and security recommendations.
Author: Aritra Pal
Role: Cyber Crime Investigator and Fraud Analyser
Focus: Cybersecurity | Web Application Security | Ethical Hacking

🎯 Project Overview
- Project: Web Application Penetration Testing
- Reference target stated in the source report: https://medirozahospital.com/
- Program: Networkwalks Internship
- Assessment type: Web Application VAPT
- Report file: Report.pdf
This README is a project summary for learning and documentation. Use the report and evidence supplied with the project to verify details before presenting them as your own findings.
🛠️ Tools Mentioned in the Reference Project
Tool	Purpose
Nmap	Network scanning and port/service enumeration
Burp Suite / Browser	Reviewing web application requests and responses
Gobuster	Directory and endpoint enumeration
PDF2John	Password-hash auditing workflow for permitted PDF files
John the Ripper	Password-strength auditing of hashes you are authorized to test
Kali Linux	Security testing environment


🧰 Command Reference
The original repository's README identifies the tools and their purposes, but does not publish full terminal command lines. These are safe help/reference commands to check tool syntax before working in an authorized lab:
nmap --help
gobuster dir --help
john --help
For the GUI tools, open Burp Suite or your browser and use the project only within the written scope and with test accounts. Do not run tests against a real website unless you have explicit permission.
🔍 Assessment Workflow
1. Scope and authorization – Confirm written permission, approved hosts, and testing boundaries.
2. Network reconnaissance – Review permitted network exposure using approved tools.
3. Application mapping – Identify application pages, roles, login flows, and inputs.
4. Security review – Assess authentication, input handling, and information exposure safely.
5. Evidence documentation – Record observations and screenshots while protecting personal data.
6. Risk assessment – Explain likelihood, impact, and severity based on verified evidence.
7. Remediation – Recommend practical fixes and defensive controls.
8. Retesting – Verify fixes only after authorization.
📌 Findings Summary
The reference README reports these categories:
1. SQL Injection / Authentication Concern
The source report describes a potential SQL-injection-related authentication issue.

Security impact discussed: possible authentication bypass and unauthorized access.
2. Sensitive Information Disclosure
The source report describes sensitive information exposed through a legacy website/database area.

Security impact discussed: potential confidentiality and privacy risks.
These are summaries of the reference report, not independent findings verified by this repository's author. Review the supplied report and evidence, and do not claim to have personally reproduced an issue unless you did so with authorization.

🛡️ Recommended Remediation
- Use parameterized queries and prepared statements.
- Validate input on the server side.
- Apply least-privilege database permissions.
- Enforce strong authentication and authorization.
- Remove or restrict exposed legacy resources.
- Keep frameworks, libraries, and database components updated.
- Review logs for unexpected access.
- Avoid storing or publishing sensitive personal information.
- Conduct an authorized retest after fixes.
📚 Learning Outcomes
- Understanding a structured web application security assessment
- Familiarity with common security-testing tools
- Reviewing authentication and input-handling risks
- Recognizing sensitive information exposure
- Writing clear findings and remediation recommendations
- Maintaining scope, authorization, and evidence integrity
📁 Project Structure
NW-WK4-Penetration-Testing-Report/
├── README.md
└── Report.pdf
Keep Report.pdf in the repository if you have permission to share it. Add screenshots only when they are yours or authorized for publication, and redact credentials, personal data, and sensitive host details.
⚠️ Disclaimer
This repository is for educational and defensive cybersecurity documentation. Test only systems you own or have explicit written authorization to assess. Do not access, alter, or disclose data without permission. The source report's authorization statement should not be treated as permission for anyone else to test the referenced website.
👨‍💻 Author
Arti Pal
Cyber Crime Investigator and Fraud Analyser
Cybersecurity Student | Ethical Hacking | Web Application Security

Learning by identifying security risks responsibly, documenting evidence, and recommending improvements.
