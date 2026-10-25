<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Moad Morchid — // SECBYMORCHID">
</p>

<p align="center">
  <a href="https://linkedin.com/in/moad-morchid" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0B0F17?style=flat-square&logo=linkedin&logoColor=38BDF8&labelColor=161F30" alt="LinkedIn"></a>
  &nbsp;
  <a href="mailto:moad.morchid.cybersec@gmail.com"><img src="https://img.shields.io/badge/Email-0B0F17?style=flat-square&logo=gmail&logoColor=38BDF8&labelColor=161F30" alt="Email"></a>
  &nbsp;
  <a href="https://github.com/secbymorchid?tab=repositories"><img src="https://img.shields.io/badge/Repositories-0B0F17?style=flat-square&logo=github&logoColor=38BDF8&labelColor=161F30" alt="GitHub Repositories"></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Status-Open_to_Internships-0B0F17?style=flat-square&logo=target&logoColor=38BDF8&labelColor=161F30" alt="Operational Status">
</p>

---

### `// 01. EXECUTIVE_SUMMARY & GOVERNANCE_PROFILE`

<table>
  <tr>
    <td width="60%" valign="top">

#### 🏛️ Executive Profile & Academic Foundation
Engineering student in **Management and Governance of Information Systems (MGSI)** at the **National School of Applied Sciences - Oujda (ENSAO)**.

My profile bridges high-level **Information Systems Governance & Enterprise Architecture** with hands-on **SecOps & Cyber Defense**. I translate strategic governance frameworks (ISO/IEC 27001, NIST CSF, EBIOS RM, and GDPR Recital 49) into measurable, enforceable technical security controls.

* **Strategic Alignment:** Connecting C-level risk posture and business continuity with technical implementations.
* **Systems Urbanization:** Designing modular, resilient enterprise data models and workflows with Merise, UML, and CASE tools.
* **Hands-on Technical Rigor:** Validated through offensive CTF championships (**1st Place — Red Phoenix CTF 2026**), automated log telemetry pipelines, and containerized deception environments.

    </td>
    <td width="40%" valign="top">

#### 📡 Operational Telemetry & Focus
```text
[IDENTITY]       Moad Morchid (// SECBYMORCHID)
[INSTITUTION]    MGSI @ ENSA Oujda
[ROLE TARGET]    IT & Cyber Project Manager / GRC
[AVAILABILITY]   Open to Internships & Projects
```

* **Governance & Risk:** GRC Frameworks, Risk Assessment (EBIOS RM), Security Auditing
* **Project Delivery:** Agile/Scrum, IS Architecture (UML, Merise, SAP PowerDesigner)
* **Technical Defense:** SOC Analysis, Threat Detection, Python & Bash Security Automation

    </td>
  </tr>
</table>

---

### `// 02. CORE_COMPETENCY_MATRIX`

<table>
  <tr>
    <td width="33.33%" valign="top">

#### 🛡️ Risk, Governance & Compliance (GRC)
* **IS Governance:** Strategic alignment of IT systems with business risk appetites.
* **Risk Management:** Risk assessment methodologies (EBIOS RM, ISO 27005).
* **Frameworks & Standards:** ISO/IEC 27001, NIST CSF, and PSSI policy authoring.
* **Regulatory Compliance:** RGPD / GDPR (specifically *Recital 49* for cybersecurity processing).
* **Auditing:** Internal security controls verification and compliance tracking.

<br>

<kbd>ISO 27001</kbd> <kbd>EBIOS RM</kbd> <kbd>RGPD</kbd> <kbd>GRC</kbd>

    </td>
    <td width="33.33%" valign="top">

#### 📐 IT & Cyber Project Management (MGSI)
* **IS Urbanization:** Enterprise application mapping & functional architecture.
* **Data & Process Modeling:** Conceptual & logical models using Merise & UML.
* **CASE Tooling:** SAP PowerDesigner, StarUML, JMerise, GanttProject.
* **Delivery Methodologies:** Agile (Scrum / Kanban), Waterfall / PMBOK foundations.
* **Project Governance:** Scope definition, risk registers, and technical specifications.

<br>

<kbd>Agile/Scrum</kbd> <kbd>Merise</kbd> <kbd>UML</kbd> <kbd>PowerDesigner</kbd>

    </td>
    <td width="33.33%" valign="top">

#### ⚙️ SecOps & Technical Controls
* **SOC & Telemetry:** Log parsing, anomaly extraction, and SIEM data ingestion.
* **OS & Hardening:** Linux system administration, service isolation, iptables/UFW.
* **Security Automation:** Tooling in Python & Bash for automated audit routines.
* **Network Auditing:** Concurrency scanning, banner grabbing, and socket programming.
* **Deception Technology:** Multi-tier Cowrie honeypots & MITRE ATT&CK mapping.

<br>

<kbd>Linux</kbd> <kbd>Bash</kbd> <kbd>Python</kbd> <kbd>SIEM</kbd> <kbd>MITRE ATT&CK</kbd>

    </td>
  </tr>
</table>

---

### `// 03. TECHNICAL_CONTROLS & FEATURED_PROJECTS`

<table>
  <tr>
    <td width="50%" valign="top">

#### 01. Automated SSH Brute-Force Detection & Intelligence Pipeline
> **Governance Objective:** Continuous Access Monitoring & Incident Telemetry *(ISO 27001 A.8.16)*

* **Architecture:** Custom lightweight SIEM automating extraction of authentication anomalies from Linux logs.
* **Implementation:** Employs Bash, `grep`, and `awk` for high-throughput regex parsing, warehousing normalized telemetry into relational SQLite for threat hunting and compliance audit trails.
* **Key Outcome:** Bridges unstructured OS logs with actionable threat intelligence and structured SQL reporting.

<kbd>Bash</kbd> <kbd>awk</kbd> <kbd>SQLite</kbd> <kbd>SIEM</kbd> <kbd>Log Auditing</kbd>

🔗 [**Inspect Pipeline Repository ↗**](https://github.com/secbymorchid/Automated-SSH-Brute-Force-Detection-Intelligence-Pipeline)

    </td>
    <td width="50%" valign="top">

#### 02. Multi-Threaded Network Port & Service Auditor
> **Governance Objective:** Attack Surface Visibility & Unauthorized Asset Discovery *(ISO 27001 A.8.8 / A.8.9)*

* **Architecture:** High-concurrency network auditor designed for rapid attack surface reconnaissance.
* **Implementation:** Utilizes Python's native `socket`, `threading`, and `queue` primitives to perform parallel TCP handshakes, banner grabbing, and service identification across target IP subnets.
* **Key Outcome:** Automated asset discovery and baseline compliance checking with zero third-party dependencies.

<kbd>Python 3</kbd> <kbd>Sockets</kbd> <kbd>Threading</kbd> <kbd>Asset Discovery</kbd> <kbd>Recon</kbd>

🔗 [**Inspect Security Automation Repository ↗**](https://github.com/secbymorchid/python-drills)

    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### 03. Enterprise SSH Honeypot & Threat Intelligence Stack
> **Governance Objective:** Deception Architecture & Lawful Telemetry Processing *(RGPD Recital 49 & ISO 27001 A.8.20)*

* **Architecture:** Three-tier defense-in-depth enclave (Host > VM > Docker sandbox) running an enterprise Cowrie honeypot.
* **Implementation:** Automated ETL pipeline ingesting high-velocity NDJSON logs, enriching attacker IPs with MaxMind GeoIP2, and mapping adversary commands directly to the **MITRE ATT&CK Enterprise Matrix**.
* **Key Outcome:** Dual-tier Streamlit & Kibana dashboards delivering executive risk reports and real-time SOC analyst visibility.

<kbd>Cowrie</kbd> <kbd>Docker</kbd> <kbd>MITRE ATT&CK</kbd> <kbd>RGPD</kbd> <kbd>Streamlit</kbd>

🔗 [**Inspect Honeypot Stack Repository ↗**](https://github.com/secbymorchid/ssh-honeypot-project)

    </td>
    <td width="50%" valign="top">

#### 04. Red Phoenix CTF 2026 Writeups (1st Place Champion)
> **Governance Objective:** Practical Vulnerability Assessment, Reverse Engineering & Incident Triage

* **Architecture:** Curated technical solutions and exploit analysis from the 2026 National Competition (ENSAO).
* **Implementation:** Solved across 30 complex scenarios spanning **Reverse Engineering, Cryptography, Web Security, Forensics, and OSINT**, finishing **1st Place with 6,750 points**.
* **Key Outcome:** Demonstrates deep analytical problem-solving, rapid vulnerability identification, and structured technical documentation under high-pressure conditions.

<kbd>1st Place 🏆</kbd> <kbd>Reverse Engineering</kbd> <kbd>Cryptography</kbd> <kbd>Forensics</kbd>

🔗 [**Inspect CTF Solutions Repository ↗**](https://github.com/secbymorchid/RPCTF2026)

    </td>
  </tr>
</table>

---

### `// 04. CERTIFICATIONS, LABS & CONTINUOUS TRAINING`

<table>
  <tr>
    <td width="50%" valign="top">

#### 📜 Google Cybersecurity Professional Certificate
* **Domain Focus:** SIEM Management, SOC Workflows, Incident Response, Network Hardening, SQL & Python Automation.
* **Application:** Applied industry-standard playbooks and packet analysis for corporate threat detection.

    </td>
    <td width="50%" valign="top">

#### 🌐 Cisco Networking Academy
* **Domain Focus:** Introduction to Cybersecurity, Network Topologies, Layer 2–7 Protocol Analysis, Security Architectures.
* **Application:** Foundation for secure network zoning and infrastructure segmentation.

    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### 🎯 TryHackMe Hands-on Security Pathways
* **Domain Focus:** SOC Level 1 Pathways, Network Security, Threat Hunting, Attack & Defense Scenarios.
* **Application:** Practical operational training on live adversary emulation and defensive triage.

    </td>
    <td width="50%" valign="top">

#### 🐧 Linux & Shell Engineering Laboratories
* **Domain Focus:** Linux internals, process management, permissions, and command-line automation.
* **Track:** [OverTheWire Bandit Solutions Walkthrough](https://github.com/secbymorchid/bandit-walkthrough) & pwn.college Linux Luminarium.

    </td>
  </tr>
</table>

---

### `// 05. UNIFIED TECH & GOVERNANCE ARSENAL`

<p align="center">
  <b>IS Governance, Architecture & Project Management</b><br>
  <img src="https://img.shields.io/badge/ISO_27001-0B0F17?style=flat-square&logo=security&logoColor=38BDF8&labelColor=161F30" alt="ISO 27001">
  <img src="https://img.shields.io/badge/EBIOS_RM-0B0F17?style=flat-square&logo=target&logoColor=38BDF8&labelColor=161F30" alt="EBIOS RM">
  <img src="https://img.shields.io/badge/Merise_%2F_UML-0B0F17?style=flat-square&logo=diagram-next&logoColor=38BDF8&labelColor=161F30" alt="Merise / UML">
  <img src="https://img.shields.io/badge/SAP_PowerDesigner-0B0F17?style=flat-square&logo=sap&logoColor=38BDF8&labelColor=161F30" alt="SAP PowerDesigner">
  <img src="https://img.shields.io/badge/StarUML-0B0F17?style=flat-square&logo=uml&logoColor=38BDF8&labelColor=161F30" alt="StarUML">
  <img src="https://img.shields.io/badge/JMerise-0B0F17?style=flat-square&logo=databricks&logoColor=38BDF8&labelColor=161F30" alt="JMerise">
  <img src="https://img.shields.io/badge/Agile_%2F_Scrum-0B0F17?style=flat-square&logo=jira&logoColor=38BDF8&labelColor=161F30" alt="Agile / Scrum">
  <img src="https://img.shields.io/badge/GanttProject-0B0F17?style=flat-square&logo=clockify&logoColor=38BDF8&labelColor=161F30" alt="GanttProject">
  <img src="https://img.shields.io/badge/Git_%26_GitHub-0B0F17?style=flat-square&logo=github&logoColor=38BDF8&labelColor=161F30" alt="Git & GitHub">
</p>

<p align="center">
  <b>SecOps, Operating Systems & Automation</b><br>
  <img src="https://img.shields.io/badge/Linux_%2F_Ubuntu-0B0F17?style=flat-square&logo=ubuntu&logoColor=38BDF8&labelColor=161F30" alt="Linux Ubuntu">
  <img src="https://img.shields.io/badge/Kali_Linux-0B0F17?style=flat-square&logo=kalilinux&logoColor=38BDF8&labelColor=161F30" alt="Kali Linux">
  <img src="https://img.shields.io/badge/Bash_Shell-0B0F17?style=flat-square&logo=gnubash&logoColor=38BDF8&labelColor=161F30" alt="Bash">
  <img src="https://img.shields.io/badge/Python_3-0B0F17?style=flat-square&logo=python&logoColor=38BDF8&labelColor=161F30" alt="Python">
  <img src="https://img.shields.io/badge/SQLite_%2F_SQL-0B0F17?style=flat-square&logo=sqlite&logoColor=38BDF8&labelColor=161F30" alt="SQLite">
  <img src="https://img.shields.io/badge/Wireshark-0B0F17?style=flat-square&logo=wireshark&logoColor=38BDF8&labelColor=161F30" alt="Wireshark">
  <img src="https://img.shields.io/badge/Docker-0B0F17?style=flat-square&logo=docker&logoColor=38BDF8&labelColor=161F30" alt="Docker">
  <img src="https://img.shields.io/badge/TryHackMe-0B0F17?style=flat-square&logo=tryhackme&logoColor=38BDF8&labelColor=161F30" alt="TryHackMe">
</p>

---

<p align="center">
  <sub><code>// SECBYMORCHID — BRIDGING INFORMATION SYSTEMS GOVERNANCE &amp; TECHNICAL SECURITY OPERATIONS</code></sub>
</p>
