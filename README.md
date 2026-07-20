<div align="center">

# Niladri Biswas
### Entry-Level GRC & Cyber Risk Consultant | Risk Assessment · Compliance Mapping · Audit-Ready Documentation

**M.Tech in Information Security** (MAKAUT, 2026) · Naihati, West Bengal, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/niladribiswas-assurance)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:niladri.assurance@gmail.com)
[![ISO 27001](https://img.shields.io/badge/ISO%2027001-2022-1679A7?style=for-the-badge)](https://www.iso.org/standard/27001)
[![NIST CSF](https://img.shields.io/badge/NIST-CSF%20v2.0-6f42c1?style=for-the-badge)](https://www.nist.gov/cyberframework)
[![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-red?style=for-the-badge)](https://attack.mitre.org/)

</div>

---

### 📌 Quick Pitch

> I translate raw technical findings into board-ready risk decisions. Five simulated engagements, five different attack surfaces — network, web app, human, endpoint, and perimeter — each documented as a complete **11-artifact GRC audit suite**: Executive Summary, Dashboard, Risk Register, Compliance Gap Analysis, Cost-Benefit Remediation Tracker, MITRE ATT&CK Mapping, Residual Risk Sign-Off, and Lessons Learned.
>
> No corporate experience yet — but every repository below is built the way a Big Four analyst's workpapers would be: reconciled numbers, defensible CVSS/EPSS scoring, and honest reporting of testing limitations rather than inflated coverage claims.

---

## 📊 Portfolio at a Glance

| # | Engagement | Attack Surface | Headline Finding | Cost-Benefit Case |
|:-:|:--|:--|:--|:--|
| 01 | Vulnerability Risk Assessment | Network / Legacy Server | 69 findings, 6 Critical (CVSS 9.8–10.0) incl. Bind Shell Backdoor | **$11K** remediation vs. **$1.1M+** breach exposure |
| 02 | Web Application Security Assessment | Application Layer | SQLi (CVSS 9.8), XSS, Brute Force, CSRF | **$800** code fix vs. **€20M** GDPR exposure |
| 03 | Social Engineering & Email Forensics | Human / Third-Party | VirusTotal false negative (0/93) on live phishing IOC | **$200** DMARC policy vs. **$100K** BEC exposure |
| 04 | SIEM Control Monitoring | Identity & Access | Custom SPL detection, 978 events ingested, T1110.001 validated | **$600** MFA/lockout vs. **$500K** breach exposure |
| 05 | Network IDS Control Validation | Perimeter / Detection | 250 alerts, 100% true-positive rate, one gap *honestly* disclosed | **$650** SOAR automation vs. **$500K** exposure |

*Every number above is pulled directly from each repository's Risk Register and Remediation Tracker — reconciled, not rounded for effect.*

---

## 🛠️ Core GRC & Security Competencies

<div align="center">

| Governance & Risk | Technical & Detection | Frameworks & Communication |
|:--|:--|:--|
| Risk Assessment & Prioritization (CVSS v3.1, EPSS) | SIEM Concepts & Monitoring (Splunk) | ISO 27001:2022 Annex A & NIST CSF v2.0 |
| Risk Registers & Cost-Benefit Analysis | Network IDS (Suricata) + Packet Analysis (Wireshark) | MITRE ATT&CK Threat-Informed Defense |
| Compliance Gap Analysis & Audit Evidence | Web App Security Testing (Burp Suite, OWASP WSTG) | Executive Reporting for Non-Technical Stakeholders |
| Residual Risk Sign-Off & Governance Cycles | Email/Header Forensics & IOC Enrichment | Incident Documentation & Escalation Workflows |

</div>

---

## 📂 GRC Portfolio — 5 Simulated Engagements

Each repository is structured to mirror a real consulting audit file. Click a project to see how raw technical output becomes formal business risk.

<details>
<summary><b>🔴 01 — Vulnerability Risk Assessment</b> <i>(Nessus Essentials · Nmap · Kali Linux)</i></summary>
<br>

**Repo:** [`GRC-Project-01-Risk-Based-Vulnerability-Assessment`](https://github.com/Oracleo/GRC-Project-01-Risk-Based-Vulnerability-Assessment)

**Scenario:** Unauthenticated external scan of a legacy HR/payroll gateway (`hr-legacy-01.internal.local`) handling EU employee PII for a simulated FinTech/HRTech firm.

**What I did:**
- Ran a two-phase methodology — Nmap attack-surface mapping, then a full Nessus Essentials scan — and reconciled 69 total findings (6 Critical / 3 High / 4 Medium / 3 Low / 53 Informational).
- Scored every actionable finding with real CVSS v3.1/v2 vectors — not just a number, the full vector string — plus EPSS where a CVE existed, and a labeled qualitative score where it didn't.
- Mapped the top 5 findings to MITRE ATT&CK (T1133, T1078, T1557, T1552.004) with adversary-action narratives, not just technique IDs.
- Built a Cost-Benefit Remediation Tracker justifying an **~$11K** spend against **$1.1M+** in modeled breach cost (GDPR fines, IR, legal).

**Key artifact:** `05-Risk-Register.md` — the master register every other document traces back to.

</details>

<details>
<summary><b>🟠 02 — Web Application Security Assessment</b> <i>(Burp Suite CE · OWASP WSTG · DVWA)</i></summary>
<br>

**Repo:** [`GRC-Project-02-Web-Application-Security-Assessment`](https://github.com/Oracleo/GRC-Project-02-Web-Application-Security-Assessment)

**Scenario:** Manual black-box assessment of a simulated customer self-service portal (`CustomerHub`) for a FinTech lender processing 250,000+ consumer records.

**What I did:**
- Manually tested every input vector per the OWASP WSTG methodology (no automated scanner) using Burp Suite Community Edition — found and validated SQL Injection (CVSS 9.8), Brute Force/Auth Weakness, Reflected XSS, and CSRF.
- Mapped every finding to ISO 27001 Annex A, NIST CSF, PCI DSS v4.0 Requirement 6.5, and GDPR Article 32 in one Compliance Gap Analysis.
- Documented a full Residual Risk lifecycle — inherent risk → proposed control → residual risk → formal CISO sign-off.

**Key artifact:** `07-Compliance-Gap-Analysis.md` — direct line from technical flaw to regulatory citation.

</details>

<details>
<summary><b>🟡 03 — Social Engineering & Email Forensics</b> <i>(Header Analysis · VirusTotal · AbuseIPDB · WHOIS)</i></summary>
<br>

**Repo:** [`GRC-Project-03-Social-Engineering-Risk-Assessment`](https://github.com/Oracleo/GRC-Project-03-Social-Engineering-Risk-Assessment)

**Scenario:** Investigated a real, reported Advance Fee Fraud (419) phishing email — SPF fail, no DKIM, no DMARC.

**What I did:**
- Manually validated email authentication failures and traced the relay to a compromised subdomain of a legitimate Russian government domain (`rosreestr.ru`) — abusing domain reputation to bypass filters.
- Caught and documented a **VirusTotal false negative** (0/93 vendor detections) — proved the case for malicious intent using authentication-failure correlation instead of trusting the automated tool.
- Mapped the full kill chain to MITRE ATT&CK, correctly distinguishing Initial Access (T1566) from Resource Development (T1585.002 — registering the collection email account).
- Built the business case for a **~$200** DMARC `p=reject` policy against a modeled **$100K+** BEC exposure.

**Key artifact:** `00-Incident-Report.md` — the audit-grade write-up an actual SOC analyst would file.

</details>

<details>
<summary><b>🟢 04 — SIEM Security Control Monitoring</b> <i>(Splunk Enterprise · Windows Event Logs · SPL)</i></summary>
<br>

**Repo:** [`GRC-Project-04-SIEM-Security-Control-Monitoring-and-Risk-Assessment`](https://github.com/Oracleo/GRC-Project-04-SIEM-Security-Control-Monitoring-and-Risk-Assessment)

**Scenario:** Deployed Splunk to validate a detective control against brute-force attacks on a simulated financial-services Windows endpoint.

**What I did:**
- Ingested 978 Windows Security Events (EventCode 4625) via Universal Forwarder and built a working SPL detection (`stats count by Account_Name | where count >= 3`) that correctly flagged both a standard and a privileged account.
- Identified the real gap the detection exposed: a fully operational *detective* control sitting on top of an absent *preventive* control (no lockout, no MFA) — and made that distinction the centerpiece of the executive narrative.
- Mapped the attack to MITRE ATT&CK T1110 / T1110.001 under the correct Credential Access tactic, and justified a **~$600** lockout + MFA rollout against a **$500K** privileged-account-compromise scenario.

**Key artifact:** `11-Lessons-Learned.md` — "a detective control on a broken preventive control just alerts you to your own failure."

</details>

<details>
<summary><b>🔵 05 — Network Control Validation</b> <i>(Suricata IDS · Wireshark · MITRE ATT&CK)</i></summary>
<br>

**Repo:** [`GRC-Project-05-Network-Control-Validation-and-Risk-Assessment`](https://github.com/Oracleo/GRC-Project-05-Network-Control-Validation-and-Risk-Assessment)

**Scenario:** Deployed Suricata (48,701 Emerging Threats rules + 5 custom rules) and validated it against a simulated Reconnaissance → Scanning → Credential Access kill chain.

**What I did:**
- Ran a live multi-stage attack (ICMP sweep → Nmap SYN scan → SSH brute force) and independently corroborated every triggered alert against a raw Wireshark packet capture — 250 total alerts, 100% true-positive rate on triggered rules.
- **Documented one custom rule that did *not* fire** — an HTTP User-Agent rule with no live web service to test against — as an honest environmental limitation rather than omitting it or faking a pass. This is the differentiator I lead every interview with.
- Mapped the kill chain end-to-end to MITRE ATT&CK (T1595.001 → T1046 → T1110.001), correctly placing Network Service Discovery under the Discovery tactic rather than Reconnaissance.
- Proposed a **~$650** SOAR automation investment to convert detection into active blocking.

**Key artifact:** `03-Scope-Methodology.md` §3.5 — the constraint disclosed in plain language, with the fix already scoped.

</details>

---

## 🎓 Education

| Degree | Institution | Year | Result |
|:--|:--|:-:|:--|
| **M.Tech, Information Security** | MAKAUT, West Bengal | 2026 | Completed |
| **B.Tech, Computer Science** | Regent Education & Research Foundation | — | CGPA 8.68 |

## 📜 Certifications & Training

| Certification | Issuer | Status |
|:--|:--|:-:|
| Certified in Cybersecurity (CC) | ISC2 | ✅ Active |
| Security, Compliance & Identity Fundamentals (SC-900) | Microsoft | 🔄 In Progress |
| National Workshop on Cryptology | IIT Bhilai | ✅ Completed |
| Cyber Security Awareness Workshop | NCIIPC | ✅ Completed |
| Cloud Computing (Elite Certification) | NPTEL – IIT Kharagpur | ✅ Completed |
| Introduction to Cybersecurity / Networking | Cisco Networking Academy | ✅ Completed |
| DevOps & Software Engineering Specialization | IBM | ✅ Completed |

---

## 💡 How I Work

> I don't run a scan and hand over a PDF. I ask what the finding costs the business if it's ignored, what it costs to fix, and who signs off on the difference. Every repository above ends the same way every real engagement should: a documented decision, not just a list of bugs.

<div align="center">

**Open to entry-level GRC Analyst, Cyber Risk Analyst, and IT Audit roles — Anywhere.**

</div>
