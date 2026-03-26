# 👋 Hi, I'm Prakriti Dhungel

### Aspiring Security Analyst | Blue Team | SOC | Network Security

I'm a cybersecurity student actively building hands-on skills in threat detection, network traffic analysis, and incident response. This portfolio documents my real investigative work — every report here reflects actual analysis I performed, not just theory.

---

## 🎯 Goal

To secure a **Security Analyst / Tier 1 SOC Analyst** role where I can contribute to threat detection, incident response, and network defense operations.

---

## 🛠️ Skills & Tools

| Category | Tools / Skills |
|----------|---------------|
| **Network Analysis** | Wireshark, NetworkMiner |
| **Threat Intelligence** | VirusTotal, AbuseIPDB |
| **SIEM** | Familiar with SIEM concepts and alert triage workflows |
| **Scripting** | Python (packet analyzer, automation scripts) |
| **Operating Systems** | Linux, Windows |
| **Networking** | TCP/IP, DNS, ARP, HTTP/S, DHCP, Kerberos |
| **Documentation** | Incident reports, IOC tracking, investigation notes |

---

## 📜 Certifications

- 🔄 **CompTIA Security+** — In Progress
- 🔄 **TryHackMe SOC Level 1** — In Progress

---

## 📁 Projects & Investigations

### 🔬 1. Custom Network Packet Analyzer — Python
Built a packet sniffer from scratch using Python and Scapy that captures and analyzes live network traffic.

**What it does:**
- Captures raw TCP/UDP/ICMP packets in real time
- Parses and displays source/destination IPs, ports, and protocol types
- Detects ARP spoofing by flagging gratuitous ARP replies and IP-to-MAC conflicts
- Flags potential port scans based on SYN packet volume thresholds
- Logs all captures to JSON for later analysis

**Skills demonstrated:** Raw socket programming, protocol parsing, defensive detection logic, Python scripting

---

### 🔍 2. SOC Incident Investigations — Malware Traffic Analysis

Real-world malware PCAP analysis exercises sourced from [malware-traffic-analysis.net](https://malware-traffic-analysis.net) — a widely used training resource in the SOC community maintained by a Palo Alto Unit 42 threat researcher. Each exercise uses actual captured malware traffic.

---

#### 📄 2026-02-28 — NetSupport Manager RAT (Easy As 123)

| Field | Details |
|-------|---------|
| **Malware** | NetSupport Manager RAT |
| **C2 Server** | 45.131.214[.]85 |
| **C2 Port** | TCP 443 |
| **Infected Host** | 10.1.28[.]88 — DESKTOP-TEYQ2NR |
| **Compromised User** | brolf (Becka Rolf) |
| **Tools Used** | Wireshark |
| **Detection Time** | 2026-02-28 19:55 UTC |

**What I did:**
- Analyzed PCAP triggered by SIEM signature hits for NetSupport RAT
- Identified C2 beaconing pattern to external IP over TCP 443
- Extracted victim hostname, MAC address, and user account from DHCP, NBNS, and Kerberos traffic
- Documented full incident report with IOCs and remediation recommendations

📂 [View Full Incident Report](./2026-02-28-NetSupportRAT/)

---

## 🧠 What I'm Currently Learning

- Deeper SIEM workflows and alert correlation logic
- Threat hunting methodologies
- Log analysis (Windows Event Logs, Sysmon)
- Expanding Python scripts for automated IOC extraction from PCAPs

---

## 📬 Connect With Me

- 💼 [LinkedIn](#) ← https://www.linkedin.com/in/prakriti-dhungel-860b11160/
- 📧 [Email](#) ← prakritidhungel@my.unt.edu

---

*This portfolio is actively updated as I complete new investigations and build new tools. Every piece of work here is my own.*
