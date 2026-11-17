# Project 1 — Build a Home Lab with Virtual Machines

> Source: [Code Zen Eduversity — SOC Analyst Projects For Freshers](https://codezeneduversity.com/soc-analyst-projects/) (Project 1 of 10)
>
> **Status:** [ ] Not started &nbsp; [ ] In progress &nbsp; [ ] Complete

---

## What This Project Is About

A home lab is a personal cybersecurity practice environment you build on your own computer. Every serious SOC Analyst fresher needs one to practise security tools safely. This project teaches system administration, networking basics, and how attackers and defenders interact on a network. It is the foundation for all nine later projects — do not skip it.

**What you will learn:**
- Installing and configuring operating systems
- Setting up virtual networks
- Managing multiple machines simultaneously
- Understanding how attackers and defenders interact in a network

---

## Tools You Will Need

| Tool | Purpose | Cost |
|------|---------|------|
| **VirtualBox** or **VMware Workstation Player** | Run multiple operating systems on one computer | Free |
| **Kali Linux** | Security testing / offensive techniques (attacker machine) | Free |
| **Ubuntu Server** | Lightweight Linux for server security practice | Free |
| **Windows 10/11 VM** | Most companies use Windows — essential for Windows security monitoring | Free evaluation version from Microsoft |

**Hardware note:** A laptop with 8 GB RAM is enough for a simple three-machine lab. Give each VM at least 2 GB RAM.

---

## Number of Deliverables

- **1 home lab** consisting of **3 virtual machines** (attacker, victim/target, monitoring/log server).
- **1 setup document** with screenshots, a network diagram, IP addresses, and the purpose of each machine.
- Add more systems only after you are comfortable with the basics.

---

## Action Steps

1. **Download and install VirtualBox** from the official website (or VMware Workstation Player).
2. **Download ISO files** for Kali Linux, Ubuntu Server, and Windows (evaluation versions are free from Microsoft).
3. **Create three virtual machines** with at least 2 GB RAM each:
   - Kali Linux → attacker / security-testing machine
   - Ubuntu Server → server / later SIEM host
   - Windows 10/11 → endpoint to monitor
4. **Configure network settings** so all three machines can communicate with each other (host-only or internal network is safest). Record each machine's IP address.
5. **Practise basic commands on each system** (ipconfig/ifconfig, ping, user listing, process listing, checking logs).
6. **Document your setup process** as you go — take screenshots at every major step.

---

## What to Produce / How to Showcase

- Create a detailed document with screenshots showing your **lab architecture**.
- Include a **network diagram**, **IP address table**, and **purpose of each machine**.
- Save configuration notes so you can reproduce the lab from scratch.
- Put this in a repo named something clear like `SOC-Home-Lab-Setup` with a README explaining purpose, tools, setup steps, and learnings.

**Pro tip from the source:** Many freshers make the mistake of building overly complex labs. Start simple with three machines. A well-documented, simple lab impresses recruiters more than a complex lab you cannot explain.

---

## Completion Checklist

- [ ] Virtualization software installed
- [ ] 3 VMs created with ≥2 GB RAM each
- [ ] All 3 machines can communicate; IPs recorded
- [ ] Basic commands practised on each OS
- [ ] Network diagram + screenshots captured
- [ ] Setup document written and saved
- [ ] I can explain every design choice in an interview
