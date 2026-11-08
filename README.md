# Cyber Security Portfolio & Interactive Lab Hub

> Welcome! Explore my threat detection labs, custom SIEM alert configurations, incident response write-ups, and security engineering vault:

👉 **[Launch Interactive Portfolio →](https://your-website-link-here.com)**

## Hello, I'm Jude

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/chinaza-ibekwe-490883398)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://your-website-link-here.com)

If you asked me growing up if I would ever find my niche in tech, I wouldn't have believed you. My foundation is in Business Administration, where my focus was purely on the bottom line—maximizing profit and minimizing costs. Then I discovered cybersecurity, and everything clicked. Today, I bridge the gap between business strategy and technical security, understanding firsthand why executives often view security as a heavy cost center and how to align technical defense with business reality.

## Objective

As much as I love the technical thrill of threat detection and SOC analysis, I know that being an analyst is my foundation, not my final stop. My long-term vision as an African technologist is to step into the CISO role and co-found tech companies of my own. Right now, I am spending my time deeply embedded in the technical trenches—building SIEM labs, analyzing logs, and engineering alerts—so that as I protect and lead organizations, I can prove that security doesn't just take from the bottom line; it protects the entire business.

---

## Technical Skills

* **SIEM & Detection Engineering:** Splunk Enterprise (SPL), Custom Alert Configuration & Scheduling, Security Dashboard Engineering, Log Aggregation, Windows Security Event Logs (`4624`, `4625`, `4720`, `4946`, `4688`), Sysmon
* **Endpoint & Email Protection (EDR / SEG):** 
  * **EDR (Endpoint Detection & Response):** Host Isolation, Process & LOLBin Telemetry, LSASS Memory/Credential Dumping Detection (Mimikatz), Endpoint Reimaging & Triage
  * **SEG (Secure Email Gateway):** Phishing Header Analysis, SPF/DKIM/DMARC Verification, Malicious Attachment & URL Sandboxing, Inbox Search & Purge
* **Network & Infrastructure Security:** Wireshark, Nmap, Windows Defender Firewall Hardening, Active Directory Security, Linux (Kali / Ubuntu), Virtualization (VMware Workstation Pro)
* **Threat Intelligence & IR Frameworks:** MITRE ATT&CK, NIST SP 800-61 (Incident Response Lifecycle), Lockheed Martin Cyber Kill Chain, CIS Benchmarks, GSMA Telecom Security Baselines
* **Governance, Risk & Business Strategy:** Business Continuity (BCP) & Disaster Recovery (DRP), Risk Management (Acceptance, Transfer, Mitigation), Cost-Benefit Security Alignment, Principle of Least Privilege, Separation of Duties

---

## Featured SOC Investigations & Detection Labs

### 1. SIEM Alert Configuration & Dashboard Engineering
| Lab / Engineering Task | MITRE ATT&CK ID | Technical Scope & Configuration | Link |
| :--- | :--- | :--- | :--- |
| **Scheduled Alert: Rogue Account Creation** | `T1136.001` (Persistence) | Configured an hourly scheduled Splunk alert (`EventCode=4720`) monitoring `subject_user` authorization and escalating to Triggered Alerts for immediate SOC triage. | [View Alert Lab →](#) |
| **SOC Dashboard: Windows Activity & Firewall Monitoring** | `T1562.004` (Defense Evasion) | Built a multi-panel Splunk dashboard tracking failed/successful logons (`LogonType`, `EventCode=4624/4625`) and critical Windows Firewall exception additions (`EventCode=4946`). | [View Dashboard Lab →](#) |

### 2. Threat Investigations & Incident Response
| Investigation Case Study | MITRE ATT&CK Mapping | Triage & IR Lifecycle Summary | Link |
| :--- | :--- | :--- | :--- |
| **Ransomware & Domain Controller Compromise** | `T1566` • `T1053` • `T1078` • `T1018` • `T1021` • `T1074` • `T1486` | Mapped a full intrusion from a phishing PDF and LOLBin execution to AV impairment, `nslookup` discovery, RDP lateral movement, `1.7z` data staging, and ransomware impact. | [View Case Study →](#) |
| **Endpoint Backdoor & Privilege Escalation Triage** | `T1078` • `T1136` • `T1562` | Investigated compromised credentials (`kporter`) creating an unauthorized `evil` account and modifying firewall rules; executed NIST containment, eradication, and recovery steps. | [View Case Study →](#) |
| **Incident CoCanDa — Threat Investigation** | NIST IR Lifecycle | End-to-end forensic investigation, indicator analysis, and executive remediation reporting. | [View Report →](./Security-Report) |
