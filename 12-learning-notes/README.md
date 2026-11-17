# LetsDefend — SOC Analyst Learning Path Notes

> Official path: [SOC Analyst Learning Path](https://app.letsdefend.io/path/soc-analyst-learning-path) — **25 steps**, role: Security Analyst, level: Medium.
> [Help Center overview](https://help.letsdefend.io/en/articles/8739085-soc-analyst-learning-path) · [Forum thread](https://forum.letsdefend.io/t/about-the-soc-analyst-learning-path/27)

This folder is a note-taking workspace matching the official path, step for step. Each section folder has its
own README, lesson/analysis notes, quiz or question review, and — where the path includes labs — individual
alert triage worksheets and challenge reports.

---

## How to use it

1. Open the section folder in order (01 → 25) and read its `README.md`.
2. Take lesson notes in `lessons.md` using the [lesson template](00-templates/lesson-note-template.md).
3. For each SOC alert, copy the [alert triage worksheet](00-templates/alert-triage-template.md) into `practice/`. Worksheets are already pre-created with the official alert IDs.
4. For each challenge, fill the pre-created `challenge-*.md` worksheet in `practice/` using the [challenge report template](00-templates/challenge-report-template.md).
5. After the quiz, record scores and missed questions in `quiz-review.md`.
6. Lab sections (11, 24, 25) also have a `lab-build-log.md`.

**Note-taking convention:** every investigation ends with a **verdict**, a **priority with one reason**, and an
**escalation/handover note** — the four Tier 1 moves: spot → check → decide → hand over.

---

## Path index (25 sections)

| # | Section | Type | Workload | Notes |
|---|---|---|---|---|
| 01 | [SOC Fundamentals](01-soc-fundamentals/README.md) | course | 9 lessons · 11 lesson questions · 1 quiz | Introduction to SOC · SOC Types and Roles… |
| 02 | [Cyber Kill Chain](02-cyber-kill-chain/README.md) | course | 9 lessons · 13 lesson questions · 1 quiz | Introduction to Cyber Kill Chain · Cyber Kill Chain Steps… |
| 03 | [MITRE ATT&CK Framework](03-mitre-attck-framework/README.md) | course | 8 lessons · 19 lesson questions · 1 quiz | Introduction · Introduction to MITRE… |
| 04 | [Phishing Email Analysis](04-phishing-email-analysis/README.md) | course | 7 lessons · 11 lesson questions · 4 SOC alerts · 1 challenge · 1 quiz | Introduction to Phishing · Information Gathering… |
| 05 | [Detecting Web Attacks](05-detecting-web-attacks/README.md) | course | 9 lessons · 27 lesson questions · 6 SOC alerts · 2 challenges | Introduction · Why Detecting Web Attacks Important… |
| 06 | [Detecting Web Attacks - 2](06-detecting-web-attacks-2/README.md) | course | 4 lessons · 12 lesson questions | Detecting Open Redirection Attacks · Detecting Directory Traversal Attacks… |
| 07 | [Investigate Web Attack](07-investigate-web-attack/README.md) | challenge | 7 questions | A standalone challenge: investigate detected web attacks in depth usin… |
| 08 | [How to Investigate a SIEM Alert?](08-how-to-investigate-a-siem-alert/README.md) | course | 7 lessons · 20 lesson questions | Introduction to SIEM Alerts · Detection… |
| 09 | [Malware Analysis Fundamentals](09-malware-analysis-fundamentals/README.md) | course | 7 lessons · 13 lesson questions · 3 SOC alerts · 3 challenges · 1 quiz | Introduction to Malware Analysis · How Malware Analysis Help SOC Analysts… |
| 10 | [SA - Malware - Event ID: 77](10-sa-malware-event-id-77/README.md) | alert | 1 SOC alert investigation (no lessons/quiz) | A hands-on SOC alert investigation in the LetsDefend monitoring/practi… |
| 11 | [Dynamic Malware Analysis](11-dynamic-malware-analysis/README.md) | course | 9 lessons · 17 lesson questions · 3 SOC alerts · 2 challenges · 1 quiz | What will you have learned at the end of the training? · What is Dynamic Malware Analysis?… |
| 12 | [MSHTML](12-mshtml/README.md) | challenge | 5 questions | The 2021 MSHTML 0-day challenge. Four malicious Office documents are p… |
| 13 | [Malicious Document Analysis](13-malicious-document-analysis/README.md) | course | 5 lessons · 14 lesson questions · 3 challenges | Introduction to Malicious Document File Analysis · Static Malicious Document Analysis… |
| 14 | [Security Solutions](14-security-solutions/README.md) | course | 13 lessons · 28 lesson questions · 1 quiz | Introduction to Security Solutions · Intrusion Detection System (IDS)… |
| 15 | [Network Log Analysis](15-network-log-analysis/README.md) | course | 9 lessons · 33 lesson questions · 5 challenges · 1 quiz | Introduction to Network Log Analysis · Generic Log Analysis (Netflow)… |
| 16 | [SIEM 101](16-siem-101/README.md) | course | 5 lessons · 8 lesson questions · 1 quiz | SIEM Introduction · Log Collection… |
| 17 | [Incident Management 101](17-incident-management-101/README.md) | course | 6 lessons · 5 lesson questions · 1 quiz | Introduction to Incident Management · Basic Definitions About Incident Management… |
| 18 | [Splunk](18-splunk/README.md) | course | 11 lessons · 14 lesson questions | Introduction to Splunk · Splunk Installation on Windows… |
| 19 | [Cyber Threat Intelligence](19-cyber-threat-intelligence/README.md) | course | 8 lessons · 20 lesson questions · 1 SOC alert · 1 quiz | Introduction to CTI · CTI Lifecycle… |
| 20 | [VirusTotal for SOC Analysts](20-virustotal-for-soc-analysts/README.md) | course | 5 lessons · 8 lesson questions · 1 quiz | Introduction to VirusTotal for SOC Analysts · File Analysis with VirusTotal… |
| 21 | [SA - Malware - Event ID: 76](21-sa-malware-event-id-76/README.md) | alert | 1 SOC alert investigation (no lessons/quiz) | A second hands-on malware alert investigation in the LetsDefend monito… |
| 22 | [IT Security Basis for Corporates](22-it-security-basis-for-corporates/README.md) | course | 10 lessons · 4 lesson questions · 1 quiz | Introduction to IT Security Basis for Corporates · Inventory… |
| 23 | [Detecting Brute Force Attacks](23-detecting-brute-force-attacks/README.md) | course | 8 lessons · 4 lesson questions · 1 challenge · 1 quiz | Introduction to Detecting Brute Force Attacks · Brute Force Attacks… |
| 24 | [Building a Malware Analysis Lab](24-building-a-malware-analysis-lab/README.md) | course | 6 lessons · 10 lesson questions | Building a Malware Analysis Lab · Installing the VirtualBox… |
| 25 | [Building a SOC Lab at Home](25-building-a-soc-lab-at-home/README.md) | course | 5 lessons · 5 lesson questions | pfSense · Active Directory… |

---

## Overall progress

| # | Section | Lessons / analysis | Alerts | Challenges | Quiz / questions | Badge |
|---|---|---|---|---|---|---|
| 01 | SOC Fundamentals | [ ] | — | — | [ ] | [ ] |
| 02 | Cyber Kill Chain | [ ] | — | — | [ ] | [ ] |
| 03 | MITRE ATT&CK Framework | [ ] | — | — | [ ] | [ ] |
| 04 | Phishing Email Analysis | [ ] | [ ] | [ ] | [ ] | [ ] |
| 05 | Detecting Web Attacks | [ ] | [ ] | [ ] | [ ] | [ ] |
| 06 | Detecting Web Attacks - 2 | [ ] | — | — | [ ] | [ ] |
| 07 | Investigate Web Attack | [ ] | — | [ ] | [ ] | [ ] |
| 08 | How to Investigate a SIEM Alert? | [ ] | — | — | [ ] | [ ] |
| 09 | Malware Analysis Fundamentals | [ ] | [ ] | [ ] | [ ] | [ ] |
| 10 | SA - Malware - Event ID: 77 | [ ] | [ ] | — | [ ] | [ ] |
| 11 | Dynamic Malware Analysis | [ ] | [ ] | [ ] | [ ] | [ ] |
| 12 | MSHTML | [ ] | — | [ ] | [ ] | [ ] |
| 13 | Malicious Document Analysis | [ ] | — | [ ] | [ ] | [ ] |
| 14 | Security Solutions | [ ] | — | — | [ ] | [ ] |
| 15 | Network Log Analysis | [ ] | — | [ ] | [ ] | [ ] |
| 16 | SIEM 101 | [ ] | — | — | [ ] | [ ] |
| 17 | Incident Management 101 | [ ] | — | — | [ ] | [ ] |
| 18 | Splunk | [ ] | — | — | [ ] | [ ] |
| 19 | Cyber Threat Intelligence | [ ] | [ ] | — | [ ] | [ ] |
| 20 | VirusTotal for SOC Analysts | [ ] | — | — | [ ] | [ ] |
| 21 | SA - Malware - Event ID: 76 | [ ] | [ ] | — | [ ] | [ ] |
| 22 | IT Security Basis for Corporates | [ ] | — | — | [ ] | [ ] |
| 23 | Detecting Brute Force Attacks | [ ] | — | [ ] | [ ] | [ ] |
| 24 | Building a Malware Analysis Lab | [ ] | — | — | [ ] | [ ] |
| 25 | Building a SOC Lab at Home | [ ] | — | — | [ ] | [ ] |

---

## Reusable templates

- [structured lesson notes](00-templates/lesson-note-template.md)
- [Tier 1 alert investigation worksheet](00-templates/alert-triage-template.md)
- [challenge analysis report](00-templates/challenge-report-template.md)
- [quiz score and missed-question log](00-templates/quiz-review-template.md)
- [lab build/configuration log](00-templates/lab-build-log-template.md)

## External resources

- [LetsDefend path](https://app.letsdefend.io/path/soc-analyst-learning-path)
- [Help Center: SOC Analyst Learning Path](https://help.letsdefend.io/en/articles/8739085-soc-analyst-learning-path)
- [Forum: About the SOC Analyst Learning Path](https://forum.letsdefend.io/t/about-the-soc-analyst-learning-path/27)
- [LetsDefend walkthroughs](https://app.letsdefend.io/tutorial/walkthroughs)
- [MITRE ATT&CK Map](https://app.letsdefend.io/mitre-attack)
- [LetsDefend dictionary](https://app.letsdefend.io/tutorial/dictionary)
