🛡️ SOC Analyst Portfolio

Aspiring SOC Analyst | Security Monitoring | Alert Triage | Incident Investigation

Welcome to my cybersecurity portfolio. This repository showcases my hands-on journey toward becoming a Security Operations Center (SOC) Analyst Level 1 through practical projects, security investigations, and technical documentation.

My focus is on developing the practical skills needed to investigate security alerts, analyze logs, identify suspicious activity, correlate evidence, and document incidents clearly.

---

📁 Repository Structure

Every folder follows one naming rule so the repo is easy to browse on GitHub: `NN-lowercase-kebab-case`. The number controls display order and the name describes the contents. Nested items use the same rule (`case-0x01`). Placeholder topic folders include a short `README.md` so Git tracks them and GitHub displays them.

| # | Folder | What it holds |
|---|--------|---------------|
| 01 | [`01-home-lab-with-virtual-machines/`](01-home-lab-with-virtual-machines/) | Virtual lab build — 3 VMs, diagram, IP plan |
| 02 | [`02-siem-tool-setup/`](02-siem-tool-setup/) | Splunk / ELK setup, dashboards, alerts |
| 03 | [`03-malware-analysis-sandbox/`](03-malware-analysis-sandbox/) | Safe sandbox setup and malware reports |
| 04 | [`04-phishing-detection-system/`](04-phishing-detection-system/) | Email header/static/dynamic analysis |
| 05 | [`05-log-analysis-real-datasets/`](05-log-analysis-real-datasets/) | Investigation write-ups from real log data |
| 06 | [`06-incident-response-playbook/`](06-incident-response-playbook/) | IR playbooks and response procedures |
| 07 | [`07-network-traffic-monitoring/`](07-network-traffic-monitoring/) | Traffic capture and monitoring reports |
| 08 | [`08-vulnerability-assessment/`](08-vulnerability-assessment/) | Scanning, findings, and remediation report |
| 09 | [`09-threat-intelligence-reports/`](09-threat-intelligence-reports/) | Threat intel and actor/profile reports |
| 10 | [`10-security-investigation-documentation/`](10-security-investigation-documentation/) | Full end-to-end investigations |
| 11 | [`11-network-analysis/`](11-network-analysis/) | 15 case-based PCAP investigations (`case-0x01` → `case-0x15`) |
| 12 | [`12-learning-notes/`](12-learning-notes/) | LetsDefend SOC Analyst path — 25 numbered sections + templates |
| 13 | [`13-cloud-forensics/`](13-cloud-forensics/) | Placeholder — cloud environment investigations |
| 14 | [`14-detection-engineering/`](14-detection-engineering/) | Placeholder — Sigma/YARA/Splunk detection rules |
| 15 | [`15-endpoint-forensics/`](15-endpoint-forensics/) | Placeholder — host and memory investigations |
| 16 | [`16-malware-analysis/`](16-malware-analysis/) | Placeholder — static/dynamic malware deep-dives |
| 17 | [`17-network-forensics/`](17-network-forensics/) | Placeholder — network forensics deep-dives |
| 18 | [`18-threat-hunting/`](18-threat-hunting/) | Placeholder — hypothesis-driven hunts |
| 19 | [`19-threat-intelligence/`](19-threat-intelligence/) | Placeholder — CTI reports and IOC collections |

Progress:

- [ ] 01–10 Hands-on projects (0/10)
- [ ] 11 Network Analysis cases (0/15)
- [ ] 12 LetsDefend learning path (0/25)

---

🎯 Career Objective

To develop the technical and analytical skills required for an entry-level SOC Analyst role, with a focus on:

- Security Information and Event Management (SIEM)
- Security alert triage and investigation
- Windows Event Logs and endpoint monitoring
- Phishing email analysis
- Network traffic and packet analysis
- Threat detection and investigation
- Incident documentation and escalation
- MITRE ATT&CK framework mapping

---

🔬 Featured Projects

01. 🖥️ Mini SOC Monitoring Lab

Focus: Security monitoring and SIEM deployment

Building a security monitoring environment using Wazuh SIEM and a Windows endpoint to collect security logs and investigate alerts.

Planned deliverables:

- Lab architecture and setup documentation
- Endpoint log collection
- SIEM dashboards and alert evidence
- Monitoring environment documentation

🔗 Project: "View Repository" (YOUR-REPOSITORY-LINK)

02. 🚨 SIEM Alert Triage and Authentication Investigations

Focus: Alert triage and authentication monitoring

A collection of 10 investigations involving authentication and account-related alerts, including suspicious login patterns and potential account compromise.

Planned deliverables:

- 10 documented investigations
- SIEM queries and alert evidence
- Investigation conclusions
- False-positive analysis and escalation decisions

🔗 Project: "View Repository" (YOUR-REPOSITORY-LINK)

03. 📧 Phishing Email Investigation Casebook

Focus: Email security and phishing analysis

Five investigations using safe sample emails or public training datasets to assess potentially malicious emails and distinguish phishing from legitimate activity.

Planned deliverables:

- Five documented email investigations
- Email evidence and indicators of compromise (IOCs)
- Investigation verdicts
- Recommended actions

🔗 Project: "View Repository" (YOUR-REPOSITORY-LINK)

04. 🌐 Network Traffic and PCAP Investigations

Focus: Network security analysis

Five investigations using Wireshark and public packet-capture datasets to examine suspicious network activity.

Planned deliverables:

- Five documented investigations
- Packet analysis evidence
- Relevant Wireshark filters
- Findings and investigation reports

🔗 Project: "View Repository" (YOUR-REPOSITORY-LINK)

05. 💻 Endpoint Threat Investigation and Detection

Focus: Endpoint telemetry and threat detection

Five investigations using Windows Event Logs and Sysmon telemetry to investigate suspicious endpoint behavior and develop custom SIEM detections.

Planned deliverables:

- Five endpoint investigations
- Relevant event-log evidence
- Custom detection rules
- Detection testing results

🔗 Project: "View Repository" (YOUR-REPOSITORY-LINK)

06. 🔎 Realistic Multi-Source Security Investigation

Focus: Log correlation and incident investigation

Five investigations using realistic public security datasets, correlating multiple evidence sources such as endpoint events, authentication logs, and network telemetry.

Planned deliverables:

- Five multi-source investigations
- Correlated event timelines
- Evidence-based findings
- Investigation reports

Potential data sources:

- "OTRF Security Datasets" (https://github.com/OTRF/Security-Datasets)
- "Splunk Boss of the SOC v3" (https://github.com/splunk/botsv3)

🔗 Project: "View Repository" (YOUR-REPOSITORY-LINK)

07. 🏆 End-to-End SOC Incident Response Capstone

Focus: Complete security investigation and incident response

Six comprehensive investigations combining SIEM alerts, endpoint evidence, network telemetry, and incident response documentation.

Planned deliverables:

- Six end-to-end investigations
- Incident timelines and evidence records
- Severity assessments and escalation decisions
- Incident reports and response recommendations
- Relevant MITRE ATT&CK mappings
- Lessons learned and detection improvements

Reference: "MITRE ATT&CK" (https://attack.mitre.org/)

🔗 Project: "View Repository" (YOUR-REPOSITORY-LINK)

---

🧰 Tools and Technologies

Category| Tools
SIEM| Wazuh
Endpoint monitoring| Windows Event Logs, Sysmon
Network analysis| Wireshark
Threat framework| MITRE ATT&CK
Investigation data| Public security datasets
Documentation| Markdown, Git, GitHub

Tools and technologies listed here represent my project toolkit; my proficiency will be demonstrated through the linked work.

---

📊 Portfolio Roadmap

Project| Target investigations| Status
Mini SOC Monitoring Lab| 0 standalone| 🔄 Planned
SIEM Alert Triage| 10| 🔄 Planned
Phishing Casebook| 5| 🔄 Planned
Network / PCAP Analysis| 5| 🔄 Planned
Endpoint Investigation| 5| 🔄 Planned
Multi-Source Investigation| 5| 🔄 Planned
SOC Capstone| 6| 🔄 Planned
Total| 36| In progress

Project statuses will be updated as the work is completed and documented.

---

📁 Investigation Documentation

Each investigation will be documented with relevant information, such as:

- Case objective and scope
- Data sources and supporting evidence
- Investigation findings
- Conclusion and confidence level
- Recommended actions or escalation
- Limitations and lessons learned

The exact documentation will vary according to the project and the available evidence.

---

🔐 Responsible Security Practice

All projects will use authorized lab environments, safe sample data, or publicly available datasets permitted for analysis.

No unauthorized access, testing against third-party systems, or disclosure of confidential information is intended.

---

📫 Connect

- LinkedIn: <>

---

This portfolio documents my ongoing development toward an entry-level SOC Analyst role. Each project will be updated with completed work, evidence, and findings as it progresses.
