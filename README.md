<div>
  <h1>Hi, I'm Gary Collins 👋</h1>
  <p><strong>Cybersecurity Professional | SOC Analyst | IT Security</strong></p>

  <p>
    <a href="mailto:garycollins0449@email.com"><img src="https://img.shields.io/badge/Email-garycollins0449%40email.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://www.linkedin.com/in/garyjosephcollins"><img src="https://img.shields.io/badge/LinkedIn-Gary%20Collins-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://github.com/GaryCollinsAI-Sec"><img src="https://img.shields.io/badge/GitHub-GaryCollinsAI--Sec-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

## Professional Summary

Detail-oriented **SOC-focused Cybersecurity Analyst** and graduate with hands-on security operations experience triaging, investigating, and documenting SIEM-generated alerts. Skilled in log correlation, endpoint event analysis, network defense, and vulnerability management using **Wazuh**, **Splunk**, and **Nessus**. 

Experienced in building virtual security environments that replicate enterprise SOC workflows to isolate threats, validate true positives, and reduce alert noise. Seeking an entry-level SOC Analyst, Security Analyst, or IT Security role focused on threat detection, incident response, and infrastructure hardening.

---

## 🛠️ Core Skills

<table>
  <tr>
    <td width="50%">
      <strong>🛡️ Security Operations</strong><br>
      SOC Monitoring • Incident Detection • Security Event Analysis • Log Analysis • Alert Triage • SIEM (Wazuh, Splunk) • IDS/IPS (Suricata) • Threat Detection • Vulnerability Management • Threat Investigation
    </td>
    <td width="50%">
      <strong>🌐 Networking & Infrastructure Security</strong><br>
      TCP/IP • DNS/DHCP • VLAN Segmentation • VPNs • pfSense Firewall • Network Traffic Analysis (Wireshark) • Lateral Movement Awareness
    </td>
  </tr>
  <tr>
    <td>
      <strong>💻 Systems & Hardening</strong><br>
      Windows 10/11 • Linux (Parrot OS, Ubuntu, Kali) • macOS • VirtualBox Lab Isolation
    </td>
    <td>
      <strong>⚙️ Security Tools & Scripting</strong><br>
      Wazuh • Nessus • Suricata • Wireshark • Nmap • Netcat • Metasploit Framework • Python • Bash • PowerShell • Golang • SQL
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <strong>📜 Compliance & Frameworks</strong><br>
      NIST SP 800-37 • NIST SP 800-53 • CIS Controls • PCI-DSS • OWASP Top 10 • CVSS Framework
    </td>
  </tr>
</table>

---

## 🛡️ Security Projects

- **Automated Incident Response Triage Tool (Ubuntu & Bash Scripting)**
  <br>
  https://github.com/GaryCollinsAI-Sec/Automated-Incident-Response-Triage-Tool  
  Developed a lightweight Linux forensic triage framework in Bash engineered for rapid live-system volatile data collection during active security incidents.
  - **Live System Triage:** Automates packet capture logging, active listening sockets (`ss`), process trees, and user authentication logs to capture volatile data before it is lost.
  - **Volatile Memory Hunting:** Implements lightweight hunting logic via `/proc` filesystem metadata to intercept deleted-but-running binaries, fileless malware techniques, and runtime evasion scripts.
  - **Adversary Simulation:** Validated detection capability using non-destructive simulation models (unlinked execution paths via masked process spaces) inside a network-isolated VirtualBox environment.
  - **Roadmap:** Phase 1 complete. Phase 2 actively optimizing output parsing and structuring automated SIEM/SOAR ingestion hooks.

- **Cross-Platform Security Monitoring Lab (Wazuh SIEM/XDR/EDR/PowerShell/Ubuntu/Windows)**
  <br>
  https://github.com/GaryCollinsAI-Sec/Cross-Platform-Security-Monitoring-Visibility-Lab  
  Built a SOC-style security monitoring environment for detecting, analyzing, and investigating simulated intrusion activity across Windows and Linux systems.
  - **Agent Deployment:** Installed and customized Wazuh agents across diverse endpoints to collect granular system and safety event telemetry.
  - **Rule Generation:** Created customized detection rules and decoders to alert on specific, high-risk security behaviors and defense-evasion tactics.
  - **Incident Log Mapping:** Correlated multi-host security log streams to piece together attack chains and identify systemic indicators of compromise (IOCs).

- **Enterprise Network Security Lab (pfSense / VLANs / IDS/IPS/ Wireshark)**
  <br>
  https://github.com/GaryCollinsAI-Sec/Enterprise-Network-and-Security-Lab  
  Designed an enterprise-style segmented network using VLANs and pfSense firewall rules to enforce isolation and test intrusion containment.
  - **VLAN Isolation:** Designed a secure network segmentation scheme dividing corporate infrastructure into strict, isolated department zones.
  - **Traffic Control:** Authored granular pfSense firewall access control lists (ACLs) to strictly implement a policy of least-privilege network communication.
  - **IDS/IPS Deployment:** Tailored Suricata signature inspection policies to dynamically identify and drop malicious packets over boundary interfaces.

- **Vulnerability Management Lab (Nessus / CVSS / Metasploitable 2 / Ubuntu Linux)**
  <br>
  https://github.com/GaryCollinsAI-Sec/Vulnerability-Management-Lab  
  Performed full vulnerability lifecycle analysis including scanning, risk prioritization, remediation, and validation using CVSS scoring.
  - **Credentialed Scanning:** Executed deep, credentialed endpoint asset scans with Nessus to capture missing patches and structural weaknesses.
  - **Risk Prioritization:** Evaluated and stack-ranked raw exploit risks by aligning CVSS scores with practical business impact.
  - **Remediation Validation:** Applied configuration patches and system modifications, conducting secondary verification scans to assure threat removal.

- **Identity & Access Security Lab (Microsoft Entra ID / Azure)**
  <br>
  https://github.com/GaryCollinsAI-Sec/Identity-Access-Security-Lab  
  Implemented Zero Trust identity controls using MFA, RBAC, and Conditional Access policies in a cloud-based environment.
  - **Conditional Access:** Configured risk-based login blockades and step-up authentication checks targeting suspicious user sign-in locations.
  - **RBAC Enforce:** Defined fine-grained Role-Based Access Control assignments to minimize credential exposure across production resources.
  - **Audit Auditing:** Reviewed Entra ID enterprise access logs to discover access patterns and trace identity configuration drifts.

- **Purple Team Security Lab (Kali / Metasploitable 2 / pfSense)**
  <br>
  https://github.com/GaryCollinsAI-Sec/Purple-Team-Security-Lab 
  Conducted controlled attack and defense simulations to evaluate exploitation paths, network segmentation, and remediation effectiveness.
  - **Attack Simulation:** Performed targeted exploit scenarios using Metasploit to map out internal pivoting routes and credential risks.
  - **Defensive Tuning:** Adjusted endpoint auditing profiles and host detection points to catch network scanning and brute-force events.
  - **Hardening:** Applied secure configuration standard adjustments to close persistent remote execution gaps and unneeded service pathways.

- **IT Help Desk & Ticketing Operations Lab (Spiceworks / Incident Workflow Simulation)**
  <br>
  https://github.com/GaryCollinsAI-Sec/Enterprise-Help-Desk-Ticketing-Environment-Spiceworks-  
  Built a structured IT support environment simulating enterprise help desk and incident handling workflows.
  - **Simulated Support:** Managed end-user support scenarios including VPN issues, authentication failures, and endpoint troubleshooting.
  - **Ticket Triage:** Implemented ticket triage, prioritization, and escalation workflows based on issue severity.
  - **SLA Management:** Applied SLA-based response logic to prioritize critical system and access-related incidents.
  - **Documentation:** Documented incidents to support structured troubleshooting and resolution tracking.



---

## 🎓 Education & Certifications

### 🎓 Education
* **M.S. Cyber Engineering** — University of the Cumberlands *(Expected 2026)*
* **B.S. Computer Science** — Colorado State University Global *(2024)*
* **A.S. Computer Science** — Yuba College *(2021)*

### 📜 Certifications
* **CompTIA Security+** *(In Progress, Expected 06/2026)*
* **Cisco Certified Network Associate (CCNA)** *(In Progress, Expected 06/2026)*
* **Google Cybersecurity Professional Certificate** *(In Progress, Expected 06/2026)*

---

<div align="center">
  <p><em>"Securing infrastructure, hardening systems, and engineering autonomous defense lines."</em></p>
</div>
