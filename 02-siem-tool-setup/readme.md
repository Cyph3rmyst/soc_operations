# Project 2 — Set Up a SIEM Tool (Splunk or ELK Stack)

> Source: [Code Zen Eduversity — SOC Analyst Projects For Freshers](https://codezeneduversity.com/soc-analyst-projects/) (Project 2 of 10)
>
> **Prerequisite:** Project 1 (home lab with three VMs)
>
> **Status:** [ ] Not started &nbsp; [ ] In progress &nbsp; [ ] Complete

---

## What This Project Is About

SIEM (Security Information and Event Management) tools are the heart of every Security Operations Center. SOC Analysts spend most of their time working with SIEM platforms to detect threats and investigate security incidents. Over 80% of SOC Analyst job descriptions require SIEM experience, so this is the highest-value project in the list.

**What you will learn:**
- Collecting logs from multiple sources
- Creating search queries to find security events
- Building dashboards for security monitoring
- Understanding how real SOC teams detect threats

---

## Tools You Will Need

Choose **one** of these two paths:

| Path | Tools | Notes |
|------|-------|-------|
| **Splunk** | **Splunk Free** | Free version processes up to 500 MB/day — perfect for learning |
| **ELK Stack** | **Elasticsearch, Logstash, Kibana** + **Filebeat** | Completely free and open source; many companies use it |

You will also use the Windows, Kali, and Ubuntu VMs from Project 1.

---

## Number of Deliverables

- **1 working SIEM** receiving logs from at least the Windows and Kali VMs.
- **1 dashboard** showing failed login attempts and network connections.
- **At least 2 alerts** for suspicious activity (e.g. multiple failed logins, unusual network traffic).
- **1 short video walkthrough** of your SIEM setup + **1 blog post** explaining your configuration choices.

---

## Action Steps — Splunk Path

1. Download Splunk Free from the official Splunk website.
2. Install Splunk on your **Ubuntu Server VM**.
3. Configure your **Windows and Kali machines to send logs to Splunk** (Splunk Universal Forwarder / syslog).
4. Learn basic **SPL (Search Processing Language)** queries — start with searches like failed logins (`EventCode=4625`) grouped by source IP.
5. Create a simple **dashboard** showing failed login attempts and network connections.

### Action Steps — ELK Stack Path

1. Install **Elasticsearch** on your Ubuntu Server.
2. Install **Logstash** to collect and process logs.
3. Install **Kibana** for visualization and searching.
4. Configure **Filebeat** on the other machines to forward logs.
5. Build **visualizations** showing security-relevant events.

---

## What to Produce / How to Showcase

- Record a short **video walkthrough** of your SIEM setup.
- Demonstrate how you created **alerts for suspicious activities** like multiple failed logins or unusual network traffic.
- Write a **blog post** explaining why you chose your configuration.
- Save all queries, alert definitions, and dashboard exports in a repo named e.g. `SIEM-Home-Lab-Setup`.

---

## Completion Checklist

- [ ] SIEM installed on Ubuntu VM
- [ ] Windows and Kali VMs forwarding logs successfully
- [ ] Basic SPL / KQL queries written and saved
- [ ] Dashboard created (failed logins + network connections)
- [ ] At least 2 alerts configured and tested
- [ ] Video walkthrough recorded
- [ ] Blog post / README written
