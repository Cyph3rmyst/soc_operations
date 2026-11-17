# Project 5 — Practice Log Analysis with Real Datasets

> Source: [Code Zen Eduversity — SOC Analyst Projects For Freshers](https://codezeneduversity.com/soc-analyst-projects/) (Project 5 of 10)
>
> **Status:** [ ] Not started &nbsp; [ ] In progress &nbsp; [ ] Complete

---

## What This Project Is About

Log analysis forms the foundation of SOC operations. Security teams analyze logs from firewalls, servers, applications, and endpoints to detect suspicious activities. Practising with real datasets prepares you for the investigative work SOC Analysts perform daily. Interviewers frequently ask questions like "How would you find all failed login attempts in a Windows log?" — this project makes those answers easy.

**What you will learn:**
- Reading and interpreting different log formats
- Identifying patterns that indicate security incidents
- Using command-line tools for log processing
- Correlating events across multiple log sources

---

## Tools You Will Need

| Tool | Purpose |
|------|---------|
| **Linux CLI: grep, awk, sed, cut** | Processing text-based logs |
| **Windows Event Viewer** | Analyzing Windows security logs |
| **Chainsaw** (by WithSecure) | Fast Windows event log analysis |
| **Zeek (formerly Bro)** | Open-source network analysis framework generating detailed connection logs |
| **Your SIEM from Project 2** | Optional: import dataset and query with SPL/KQL |

### Where to find practice datasets

- **OTRF Security Datasets** (Open Threat Research Forge) — free datasets designed for security research
- **CICIDS datasets** — labelled datasets with both normal and attack traffic
- **Boss of the SOC (BOTS)** — Splunk datasets with realistic attack scenarios

---

## Number of Deliverables

- **3 complete log analysis investigations.** Each must include: dataset used, methodology, key findings, and recommendations.
- Include screenshots of your queries and the evidence you discovered.

---

## Action Steps

1. **Download a practice dataset** from one of the sources above.
2. **Import the logs** into your SIEM tool, or analyze them directly with command-line tools.
3. **Search for specific indicators:** failed authentication attempts, unusual outbound connections, privilege escalation events.
4. **Create a timeline of events** showing how an attack progressed.
5. **Write an investigation report** summarizing your findings, with methodology, evidence screenshots, and recommendations.
6. Repeat with two more datasets/scenarios covering different attack types.

### Useful starting points

- Count failed logins per source IP from a Windows Security log (Event ID 4625).
- Find unique external IPs connecting to internal hosts from firewall/Zeek logs.
- Correlate a successful login (4624) following a burst of failures from the same IP.

---

## What to Produce / How to Showcase

- A repo like `Log-Analysis-Investigations` with three folders, one per investigation.
- Each: `README.md` (dataset, methodology, findings, recommendations), queries/commands used, timeline table, and redacted evidence screenshots.
- Practise explaining your commands out loud — employers test this in interviews.

---

## Completion Checklist

- [ ] 3 datasets/scenarios selected and downloaded
- [ ] Logs imported into SIEM or analyzed via CLI
- [ ] Failed auth, unusual outbound, privilege escalation searches run
- [ ] Timeline of attack progression built for each
- [ ] 3 investigation reports written with findings + recommendations
- [ ] Evidence screenshots captured and included
