# Project 4 — Create a Phishing Detection System

> Source: [Code Zen Eduversity — SOC Analyst Projects For Freshers](https://codezeneduversity.com/soc-analyst-projects/) (Project 4 of 10)
>
> **Status:** [ ] Not started &nbsp; [ ] In progress &nbsp; [ ] Complete

---

## What This Project Is About

Phishing attacks remain the most common way attackers compromise organizations. SOC Analysts regularly analyze suspicious emails to protect employees from credential theft and malware infections. Building this project teaches you email security fundamentals and threat analysis techniques. Entry-level analysts often begin their careers by investigating employee phishing reports, so demonstrating this skill shows recruiters you are ready for real SOC work from day one.

**What you will learn:**
- Analyzing email headers to trace message origins
- Identifying malicious URLs and attachments
- Recognizing social engineering tactics
- Creating detection rules for common phishing patterns

---

## Tools You Will Need

| Tool | Purpose | Cost |
|------|---------|------|
| **PhishTool (free community edition)** | Purpose-built phishing email analysis | Free tier |
| **URLScan.io** | Scans suspicious links and reveals redirect chains / page details | Free |
| **MXToolbox** | Email header and DNS record analysis | Free |
| **Google Admin Toolbox** | Decodes and analyzes email headers step by step | Free |
| **PhishTank** | Source of real phishing examples for research | Free |

---

## Number of Deliverables

- A portfolio of **10–15 analyzed phishing emails**. For each: red flags identified, tools used, and final verdict.
- **1 one-page guide** summarizing common phishing indicators based on your research.
- **1 checklist or decision tree** for identifying phishing emails.

---

## Action Steps

1. **Collect sample phishing emails** from public datasets such as PhishTank (or your spam folder — redact personal data).
2. **Extract and analyze email headers** to identify sender information, routing paths, and authentication results (SPF/DKIM/DMARC).
3. **Examine URLs** using URLScan.io: check the real destination vs. displayed text, redirect chains, and reputation. Do not click links directly.
4. **Inspect attachments** safely (hashes, file type, sandbox if needed).
5. **Document common patterns** across multiple phishing samples.
6. **Create a simple checklist or decision tree** for identifying phishing emails, and a one-page indicator guide.

### Common phishing indicators to look for

- Sender email address does not match the claimed organization
- Urgent language pressuring immediate action
- Suspicious links that do not match the displayed text
- Grammar and spelling mistakes in professional communications
- Requests for sensitive information like passwords or banking details

---

## What to Produce / How to Showcase

- A repo like `Phishing-Analysis-Portfolio` with one analysis file per email.
- Each analysis: raw header excerpt (redacted), IOC table, red flags, verdict (malicious/suspicious/benign), confidence, and user-facing recommendation.
- Add your one-page guide and decision tree as a PDF/image in the repo and share on LinkedIn.

---

## Completion Checklist

- [ ] 10–15 phishing emails collected (redacted)
- [ ] Headers decoded and authentication results checked
- [ ] URLs analyzed with URLScan.io (no direct clicking)
- [ ] IOCs documented per email
- [ ] Verdict + confidence recorded per email
- [ ] One-page indicator guide written
- [ ] Checklist / decision tree created
