<!--
  GRC Professional Profile – Niladri Biswas
  Governance, Risk, and Compliance Analyst Portfolio
-->

<div align="center">

# 🛡️ Niladri Biswas
### *Aspiring Cyber Risk, Governance & Compliance (GRC) Analyst*  

🚀 M.Tech Information Security (Graduated June 2026)  
🔗 **[LinkedIn](https://linkedin.com/in/niladribiswas-assurance)** &nbsp;|&nbsp; 📧 `niladri.assurance@gmail.com`  
📍 Naihati, West Bengal, India  

[![GRC](https://img.shields.io/badge/GRC-Governance%20Risk%20Compliance-0057A8?style=for-the-badge&logoColor=white)](https://github.com/Oracleo)
[![ISO 27001](https://img.shields.io/badge/ISO%2027001-2022-blue?style=for-the-badge&logo=iso)](https://www.iso.org/standard/27001)
[![NIST CSF](https://img.shields.io/badge/NIST-CSF%20v2.0-blueviolet?style=for-the-badge&logo=nist)](https://www.nist.gov/cyberframework)
[![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK%20Mapping-red?style=for-the-badge&logo=mitre)](https://attack.mitre.org/)

</div>

---

### 📊 Executive Summary

> *"I specialize in translating complex technical vulnerabilities and security events into **actionable business risk intelligence**."* 

As an Information Security graduate, my work is deeply grounded in **ISO 27001 Annex A** and **NIST CSF** frameworks. My GitHub portfolio is not just a collection of security labs—it is a **demonstration of the GRC lifecycle**.

Each repository contains a complete `/docs/` folder with **7 formal GRC artifacts**:
1.  **Executive Summary** (For senior leadership)
2.  **Scope & Methodology** (Audit-grade Terms of Reference)
3.  **Risk Register** (Business impact and CVSS/EPSS scoring)
4.  **Remediation Tracker** (Cost-Benefit Analysis for CISO approval)
5.  **Compliance Gap Analysis** (Mapping to ISO 27001, NIST, PCI DSS, GDPR)
6.  **Asset Business Criticality** (Contextualizing the target)
7.  **MITRE ATT&CK Mapping** (Adversary kill-chain analysis)

---

### 🧰 GRC Tooling & Frameworks Stack

<div align="center">

| **Risk & Governance** | **Technical & Security** | **Frameworks & Methodology** |
| :---: | :---: | :---: |
| ![](https://img.shields.io/badge/-Risk%20Registers-0057A8) | ![](https://img.shields.io/badge/-Nessus%20Essentials-00B4E0) | ![](https://img.shields.io/badge/-ISO%2027001-6A1B9A) |
| ![](https://img.shields.io/badge/-Business%20Impact%20Analysis-5C4033) | ![](https://img.shields.io/badge/-Burp%20Suite%20CE-FF6633) | ![](https://img.shields.io/badge/-NIST%20CSF-1976D2) |
| ![](https://img.shields.io/badge/-Cost%20Benefit%20Analysis-2E7D32) | ![](https://img.shields.io/badge/-Splunk%20Enterprise-65A637) | ![](https://img.shields.io/badge/-OWASP%20Top%2010-000000) |
| ![](https://img.shields.io/badge/-EPSS%20Scoring-7B1FA2) | ![](https://img.shields.io/badge/-Suricata%208.0.3-orange) | ![](https://img.shields.io/badge/-MITRE%20ATT%26CK-FF0000) |
| ![](https://img.shields.io/badge/-Third%20Party%20Risk%20Assess-512DA8) | ![](https://img.shields.io/badge/-Wireshark-1679A7) | ![](https://img.shields.io/badge/-Cyber%20Kill%20Chain-0D47A1) |

</div>

---

### 📁 GRC Portfolio Projects (Click to Expand)

I have documented **5 end-to-end GRC projects**. Each one focuses on a different domain of risk management.

<details>
<summary><b>🔴 P1 — Vulnerability Risk Assessment & Remediation (Nessus Essentials)</b></summary>
<br/>
<b>Objective:</b> Perform a network risk assessment on a legacy infrastructure (Metasploitable2) to produce a formal risk register.
<br/>
<b>Key Technical Outcomes:</b> 69 vulnerabilities identified (6 Criticals, CVSS 9.8-10.0) including Bind Shell Backdoor, CVE-2008-0166, and default VNC credentials.
<br/>
<b>GRC Artifacts Created:</b>
<ul>
  <li><code>03-Risk-Register.md</code> – Applied <b>CVSS v3.0 + EPSS</b> to prioritize a P1-P4 matrix.</li>
  <li><code>04-Remediation-Tracker.md</code> – Justified an <b>$11k remediation budget</b> to avoid a potential $1M breach.</li>
  <li><code>05-Compliance-Gap-Analysis.md</code> – Mapped directly to ISO 27001 A.8.8 and A.8.24.</li>
</ul>
<a href="https://github.com/Oracleo/GRC-P1-Vulnerability-Risk-Assessment-Nessus">🔗 View Full Repository →</a>
</details>

<details>
<summary><b>🟠 P2 — Web Application Risk Assessment (Burp Suite + OWASP)</b></summary>
<br/>
<b>Objective:</b> Conduct a manual web application risk assessment against a vulnerable app (DVWA) to support PCI DSS compliance efforts.
<br/>
<b>Key Technical Outcomes:</b> 4 High/Critical vulnerabilities identified: SQLi (9.8), XSS (7.3), Brute Force (7.5), and CSRF (6.5).
<br/>
<b>GRC Artifacts Created:</b>
<ul>
  <li><code>03-Risk-Register.md</code> – Risk scoring applied to the OWASP Top 10.</li>
  <li><code>04-Remediation-Tracker.md</code> – Recommended <b>SAST (Static Analysis)</b> integration into the SDLC.</li>
  <li><code>05-Compliance-Gap-Analysis.md</code> – Mapped findings to PCI DSS v4.0 Req 6.5 and GDPR Article 32.</li>
</ul>
<a href="https://github.com/Oracleo/GRC-P2-Web-Application-Risk-Assessment-OWASP">🔗 View Full Repository →</a>
</details>

<details>
<summary><b>🟡 P3 — Social Engineering & Incident Reporting (Email Forensics)</b></summary>
<br/>
<b>Objective:</b> Investigate a live phishing email to assess the Human Risk layer and third-party supply chain risks.
<br/>
<b>Key Technical Outcomes:</b> Discovered a <b>VirusTotal False Negative (0/93 detections)</b>. Traced the attack to a compromised Russian government subdomain (<code>rosreestr.ru</code>).
<br/>
<b>GRC Artifacts Created:</b>
<ul>
  <li><code>03-Risk-Register.md</code> – Escalated the missing DMARC policy to a <b>P1 Critical</b>.</li>
  <li><code>04-Remediation-Tracker.md</code> – Recommended a <b>$200 DMARC fix</b> to prevent a $100,000 BEC fraud.</li>
  <li><code>05-Compliance-Gap-Analysis.md</code> – Mapped to ISO 27001 A.6.3 (Awareness) and A.5.24 (Incident Mgmt).</li>
</ul>
<a href="https://github.com/Oracleo/GRC-P3-Social-Engineering-Risk-Assessment">🔗 View Full Repository →</a>
</details>

<details>
<summary><b>🟢 P4 — Security Control Monitoring & Validation (Splunk SIEM)</b></summary>
<br/>
<b>Objective:</b> Deploy a continuous access control monitoring tool (Splunk) to validate that authentication controls are producing audit evidence.
<br/>
<b>Key Technical Outcomes:</b> Ingested 978 Windows Event Logs. Built custom SPL to detect T1110 (Brute Force) with a <code>count >= 3</code> threshold.
<br/>
<b>GRC Artifacts Created:</b>
<ul>
  <li><code>03-Risk-Register.md</code> – Addressed the <b>Detective vs. Preventive Control Gap</b>.</li>
  <li><code>04-Remediation-Tracker.md</code> – Proposed a <b>$600 GPO/MFA upgrade</b> to neutralize the attack vector.</li>
  <li><code>07-MITRE-ATTACK-Mapping.md</code> – Mapped the detection to T1110.001 (Password Guessing).</li>
</ul>
<a href="https://github.com/Oracleo/GRC-P4-Security-Control-Monitoring-Splunk">🔗 View Full Repository →</a>
</details>

<details>
<summary><b>🔵 P5 — Network Threat Detection & Audit Evidence (Suricata + Wireshark)</b></summary>
<br/>
<b>Objective:</b> Validate the effectiveness of a network IDS (Suricata) and produce packet-level audit evidence for control testing.
<br/>
<b>Key Technical Outcomes:</b> Triggered 249 alerts. Independently validated 3,130 TCP SYN packets in Wireshark. <b>Honestly documented</b> one rule failing to fire due to an environmental limitation (no web server running).
<br/>
<b>GRC Artifacts Created:</b>
<ul>
  <li><code>03-Risk-Register.md</code> – Identified <b>IDS-only deployment</b> as a risk requiring SOAR integration.</li>
  <li><code>04-Remediation-Tracker.md</code> – Justified a <b>$650 fix</b> to prevent a $500,000 lateral movement breach.</li>
  <li><code>07-MITRE-ATTACK-Mapping.md</code> – Mapped the multi-stage attack to the Cyber Kill Chain (T1046, T1110).</li>
</ul>
<a href="https://github.com/Oracleo/GRC-P5-Network-Audit-Evidence-Suricata-Wireshark">🔗 View Full Repository →</a>
</details>

---

### 📜 Certifications & Licenses

| Certification | Issuer | Status |
| :--- | :--- | :--- |
| **Certified in Cybersecurity (CC)** | ISC2 | ✅ Active |
| **Security, Compliance & Identity Fundamentals (SC-900)** | Microsoft | 🔃 In Progress |
| **National Workshop on Cryptology** | IIT Bhilai (3-day On-Site) | ✅ Completed |
| **Cyber Security Awareness Workshop** | NCIIPC | ✅ Completed |
| **Introduction to Cybersecurity / Networking Essentials / Ethical Hacker** | Cisco Networking Academy | ✅ Completed |
| **Cloud Computing** | NPTEL – IIT Kharagpur | ✅ Completed |
| **Cloud Security and Emerging Technologies** | Cloud Security Alliance | ✅ Completed |
| **DevOps & Software Engineering Specialization** | IBM | ✅ Completed |

---

### 🎓 Education

- **M.Tech – Information Security** *[2024 – June 2026]*  
  *West Bengal University of Technology (MAKAUT)*

- **B.Tech – Computer Science & Engineering** *[2021 – 2024] (CGPA: 8.68)*  
  *Regent Education & Research Foundation Group of Institutions*

---

### 💼 My GRC Philosophy

> *"Security is not a product; it is a continuous governance cycle of Scoping → Assessing → Remediating → Documenting → Monitoring. My portfolio demonstrates my ability to execute and communicate every stage of this cycle to both technical teams and executive boards."*

<div align="center">

**_Available for GRC, Risk, and IT Audit roles._**

</div>
