<div align="center">

# 🛡️ Hazvinei Nomatter Masiya
### **Cybersecurity Analyst | Security Operations | Detection & Response**

[![Live Portfolio](https://img.shields.io/badge/🌐_Live_Portfolio-000000?style=for-the-badge&logo=githubpages&logoColor=white)](https://hnmasiya.github.io/cybersecurity-portfolio/)
[![LinkedIn](https://img.shields.io/badge/🔗_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hazvinei-masiya)
[![GitHub](https://img.shields.io/badge/💻_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hnmasiya)

</div>

---

### 📌 Professional Summary

IT professional with **9+ years of enterprise infrastructure experience** transitioning into dedicated cybersecurity engineering and Security Operations (SOC). Currently pursuing a **BSc in Computer Science**, combining formal academic study with deep practical expertise in managing business-critical enterprise Windows environments, Active Directory, access control, system hardening, and network security.

Combines broad systems engineering experience with independently developed, evidence-backed cybersecurity labs covering SIEM detection engineering, log analysis, threat hunting, network forensics, and security automation.

---

### 🌐 Featured Cybersecurity Portfolio

> **Evidence-Backed Security Portfolio:** Practical demonstrations of security monitoring, log analysis, detection engineering, incident investigation, web security, and infrastructure automation.

👉 **[Open My Live Cybersecurity Portfolio](https://hnmasiya.github.io/cybersecurity-portfolio/)**

---

### 🛠️ Technical Stack & Security Tooling

<div align="center">

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.kernel.org/)
[![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/evalcenter/evaluate-windows-server-2022)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)](https://www.splunk.com/)
[![Wireshark](https://img.shields.io/badge/Wireshark-167DA4?style=for-the-badge&logo=wireshark&logoColor=white)](https://www.wireshark.org/)
[![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)

</div>

| Domain | Technical Stack & Capabilities |
|---|---|
| **Security Operations & SOC** | SIEM (Wazuh, Splunk), Alert Triage, Log Analysis, Incident Investigation, MITRE ATT&CK |
| **Detection Engineering** | Custom YARA Rules, SPL Queries, Windows Event Log Analysis, System Hardening |
| **Network Security & DFIR** | Wireshark, PCAP Analysis, Nmap, Network Traffic Analysis, Evidence Preservation |
| **Systems & Infrastructure** | Active Directory, Windows Server, Linux (Ubuntu/Debian), Access Control (PoLP) |
| **Automation & Cloud** | Python 3, Bash, PowerShell, GCP (VPC, IAM), Terraform |

---

### 🔎 Featured Security Projects & Codebases

* **[Active Directory Security Log Parser](https://github.com/hnmasiya/ad-security-log-parser)**  
  *Python security tooling focused on Windows Security Event Log analysis (Event ID 4728, 4732, 4756) and privileged group-change detection.*
* **[Wazuh SIEM Detection Engineering](https://github.com/hnmasiya/wazuh-siem-detection-lab)**  
  *Custom Wazuh detection rules mapped to the MITRE ATT&CK framework, log analysis, and automated active responses.*
* **[GCP Secure Multi-Tier VPC](https://github.com/hnmasiya/gcp-terraform-secure-vpc)**  
  *Terraform-based cloud security architecture with strict IAM policies, custom VPC firewall rules, and zero public ingress.*
* **[Cybersecurity Evidence Repository](https://github.com/hnmasiya/cybersecurity-portfolio)**  
  *Central repository hosting PCAP analysis, Nmap scans, OWASP assessments, and custom SPL/YARA detection signatures.*

---

### 🔍 Incident Investigation & SOC Write-Ups

<details>
<summary><b>1. Network Forensics: Wireshark PCAP Investigation (Click to Expand)</b></summary>

* **Objective:** Identify cleartext credential exposure and malicious scanning activity across an enterprise subnetwork.
* **Findings:** Identified unencrypted HTTP POST traffic transmitting user credentials (`Event ID: DFIR-0912`), isolated malicious port scans targeting port 445 (SMB) originating from host `192.168.1.105`.
* **Remediation:** Enforced TLS 1.3 across web endpoints and implemented dynamic drop rules on the perimeter firewall.
</details>

<details>
<summary><b>2. SIEM Triage: Brute-Force & Privilege Escalation Alerting (Click to Expand)</b></summary>

* **Objective:** Investigate recurring Event ID 4625 (Failed Logon) spikes detected by Wazuh SIEM.
* **Findings:** Traced 450+ failed Kerberos logon attempts in under 3 minutes targeting Domain Admin accounts, followed by a single successful Event ID 4624 login from an unmanaged internal host.
* **Remediation:** Executed host isolation via Wazuh Active Response agent, reset domain admin credentials, and enabled MFA enforcement.
</details>

<details>
<summary><b>3. Threat Hunting: YARA Signature Development for Web Shell Detection (Click to Expand)</b></summary>

* **Objective:** Craft custom YARA rules to detect obfuscated PHP web shells deployed on compromised web servers.
* **Findings:** Wrote a multi-string condition rule matching `eval(base64_decode(...))` and suspicious system calls (`system`, `passthru`, `exec`).
* **Remediation:** Integrated YARA rule into endpoint detection scanners, preventing persistence on web infrastructure.
</details>

---

### 🎓 Education & Industry Certifications

* 🎓 **Bachelor of Science (BSc) in Computer Science** *(In Progress)*
* 📜 **Diploma in Information Technology** — *Macmaine School of Computing*
* 🛡️ **CompTIA Security+ Certified**
* 🥇 **Google Cybersecurity Professional Certificate**
* 💻 **Google IT Support Professional Certificate**

---

### 📈 GitHub Profile Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=hnmasiya&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hnmasiya&layout=compact&theme=tokyonight&hide_border=true" />

</div>
