# Project 7 — Simulate Network Traffic Monitoring

> Source: [Code Zen Eduversity — SOC Analyst Projects For Freshers](https://codezeneduversity.com/soc-analyst-projects/) (Project 7 of 10)
>
> **Status:** [ ] Not started &nbsp; [ ] In progress &nbsp; [ ] Complete

---

## What This Project Is About

Network traffic monitoring helps SOC Analysts detect suspicious communications between systems. Attackers use networks to steal data, communicate with command servers, and spread malware. Learning to analyze network traffic gives you visibility into threats that logs alone cannot reveal.

**What you will learn:**
- Capturing and analyzing network packets
- Identifying normal versus suspicious traffic patterns
- Recognizing common attack signatures in network data
- Using protocol analysis to understand communications

---

## Tools You Will Need

| Tool | Purpose | Cost |
|------|---------|------|
| **Wireshark** | Network protocol analyzer (most popular) | Free |
| **tcpdump** | Command-line packet capture on Linux | Free |
| **Zeek (formerly Bro)** | Generates detailed logs from network traffic | Free |
| **NetworkMiner** | Extracts files and images from captured traffic | Free |
| **Malware Traffic Analysis** | Source of packet captures containing real attacks | Free |

---

## Number of Deliverables

- **5 network traffic analysis reports** for five different scenarios. Each includes packet captures, analysis methodology, screenshots of key findings, what the traffic reveals about attacker behaviour, and recommended defensive actions.
- **1 complete investigation report** on a malicious PCAP from Malware Traffic Analysis answering: What happened? What systems were affected? What malware was involved? What IOCs did you discover?

---

## Action Steps

1. **Install Wireshark** on your home lab machine.
2. **Generate different types of network traffic** by browsing websites, downloading files, and using various applications.
3. **Capture traffic and practise identifying protocols:** HTTP, HTTPS, DNS, FTP, SSH.
4. **Download sample packet captures containing attacks** from Malware Traffic Analysis.
5. **Analyze malicious traffic to identify indicators of compromise** — infected host, contacted domains/IPs, extracted files, C2 communications.
6. **Write five analysis reports** and one full investigation report.

### Types of suspicious traffic to look for

- Connections to known malicious IP addresses or domains
- Unusual amounts of data leaving the network (data exfiltration)
- Traffic on non-standard ports for common protocols
- Repeated failed connection attempts (scanning behaviour)
- Unencrypted credentials being transmitted

---

## What to Produce / How to Showcase

- A repo like `Network-Traffic-Analysis` with five scenario folders and one deep-dive investigation.
- Include PCAPs (ensure they contain no personal data), filter expressions used, IOC tables, and annotated screenshots.
- Explain what defensive actions you would recommend (block IP, disable protocol, isolate host, etc.).

---

## Completion Checklist

- [ ] Wireshark installed on lab machine
- [ ] Normal traffic generated and captured (HTTP/HTTPS/DNS/FTP/SSH identified)
- [ ] Attack PCAPs downloaded from Malware Traffic Analysis
- [ ] IOCs extracted from malicious traffic
- [ ] 5 traffic analysis reports written
- [ ] 1 complete malicious-PCAP investigation report written
