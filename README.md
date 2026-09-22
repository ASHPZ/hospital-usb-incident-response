# Hospital USB Security Analysis & Incident Response

## 🛡️ Project Overview
This project is a simulated cybersecurity exercise completed as part of the **Google Cybersecurity Professional Certificate**. It demonstrates fundamental incident response procedures, risk analysis, and the application of security controls when dealing with a potentially malicious hardware device (USB baiting).

## 📝 Scenario
As a security professional working for "Rhetorical Hospital," I discovered an abandoned USB flash drive in the employee parking lot. To safely investigate the contents without compromising the hospital's network, I utilized a secure virtualization workstation (sandbox environment) to mount and analyze the drive. 

## 🎯 Objectives
* Safely investigate unfamiliar hardware using an isolated virtual machine.
* Identify and classify sensitive data (PII) and corporate intelligence.
* Analyze threat vectors and understand the attacker mindset regarding social engineering and USB baiting.
* Propose actionable Security Controls (Technical, Operational, and Managerial) to mitigate organizational risk.

## 🔍 Key Findings
1. **Data Leakage Risk:** The drive contained a mix of unencrypted personal data (family photos, resumes) and highly sensitive corporate data (employee budget files, job applications).
2. **Threat Vectors:** An attacker could use this information for targeted spear-phishing, social engineering against hospital staff, or deploying ransomware via AutoRun features.
3. **Defense-in-Depth Strategy:** The report outlines specific mitigations, including disabling AutoPlay (Technical), enforcing device scanning (Operational), and improving Security Awareness Training (Managerial).

## 📄 Project Files
* [`Incident_Report.pdf`](./Incident_Report.pdf) - The professional summary detailing the contents, attacker mindset, and recommended security controls.

## 🛠️ Skills & Concepts Demonstrated
* Malware Isolation & Virtualization
* Risk Assessment & Mitigation
* Security Controls Mapping (Technical, Managerial, Operational)
* Data Loss Prevention (DLP) Concepts
* Incident Response Reporting

---
*Disclaimer: This is a fictional scenario created for educational purposes as part of the Coursera Google Cybersecurity certification program.*
