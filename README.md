# Viktor aka "Grey Fox" 
## Cybersecurity Student, looking for Security Auditor internship

<div align="center">
<pre>
╔═══════════════════════════════════════════════════════════════╗
║   "The best defence is understanding the offence"             ║
╚═══════════════════════════════════════════════════════════════╝
</pre>
</div>

**Location:** Prague, Czech Republic 🇨🇿  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/viktor-pylypenko-2a8893369/)
[![Email](https://img.shields.io/badge/Email-ProtonMail-6D4AFF?style=for-the-badge&logo=protonmail)](mailto:fox-division-grey-fox@protonmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Gr3y--foX-181717?style=for-the-badge&logo=github)](https://github.com/Gr3y-foX)
</div>

## About me

Second-year cybersecurity student based in Prague, focused on security auditing, network assessment, vulnerability analysis, and offensive security workflows and system hardening.

Current areas of work:
- Linux/macOS hardening
- Penetration testing methodology
- Security automation tooling in Python and Bash for MacOS/Linux OS
- Home-lab infrastructure, monitoring, and defensive testing
- CTF practice on HackTheBox and TryHackMe

I am currently targeting **OSCP in Q4 2026** and looking for internship or junior opportunities in security.

## 🔭 Current Focus
- **macOS/Linux hardening** — Making on hardening tool, following standards: NIST SP 800-53, CIS Benchmark
- **Active Directory** attack chains: Kerberoasting, BloodHound, Pass-the-Hash, Golden Ticket
- **Home security lab** — Raspberry Pi 4, OpenWRT, Suricate IDS, GreenBone SIEM, Docker, PiHole
- **Hardware/IoT penetration testing** — Flipper Zero (SubGHz, NFC, BadUSB), ESP32

<div align="center">

## Languages:
`English C1` `Czech B2` `Russian Native` `Ukrainian Native`
</div>

***

## 🛠️ Technical Skills

**Operating Systems**
`Kali Linux` `Ubuntu/Debian` `macOS` `OpenWRT` `Windows Server 2022`

**Offensive Security**
`Metasploit` `Rubeus` `Mimikatz` `Burp Suite` `SQLmap` `Hydra` `John the Ripper` `Hashcat` `Aircrack-ng`

**Recon & OSINT**
`nmap` `theHarvester` `Sublist3r` `Shodan` `Wireshark` `tcpdump`

**Infrastructure & Defense**
`Docker` `iptables` `Tailscale VPN` `WireGuard` `SSH funnelling` `Suricate` `GreenBone/OpenVAS` `Lynis` `brew-vulns/pip-audit` 

**Networking CCNA-level** — `routing` `switching` `VLANs` `wireless security`

**Frameworks**
`MITRE ATT&CK` `OWASP Top 10` `Cyber Kill Chain` `CIS Controls` `NIST SP 800-53`

**Scripting & Dev**
`Python` `Bash` `Swift`

***

## 🚀 Projects

### 1. 🦊 [Foxhole-MacOS — macOS Security Hardening Toolkit](https://github.com/Gr3y-foX)
`Python` `Bash` `Lynis` `Bash` `PF` `DNSCrypt` `Privoxy` `Lynis` `Objective-See` `macOS 13+`

**Automated audit pipeline for host security checks**  

Modular hardening toolkit aligned with **NIST SP 800-53** (AC-17, SC-7, SI-3, CM-6) and **CIS macOS Benchmark**. 
Automates Application Firewall enforcement, stealth mode, privacy-focused system defaults.
Deploys security tooling (Objective-See suite, Lynis, pip-audit, brew-vulns). 
Separates base install from advanced PF/DNS/proxy controls for client-specific profiles.

***

### 2. [Active Directory Pentest Lab](https://github.com/Gr3y-foX/pen_test_kali)
`Windows Server 2022 | PowerShell | Impacket | Rubeus | Mimikatz`

Full attack chain simulation in isolated AD environment:
- Kerberoasting & AS-REP Roasting
- BloodHound path analysis for privilege escalation
- Pass-the-Hash / Pass-the-Ticket
- Golden Ticket & Silver Ticket generation
- Certificate abuse via ESC1/ESC8

Detection correlation: Event IDs 4768, 4769, 4624.

***

### 3. [Raspberry Pi Home Security Lab]
`Python | Flask | Docker  | Tor | ngrok | Greenbone | Suricata` 

Self-hosted offensive/defensive research platform:
- **Web Interceptor** — Flask honeypot capturing browser fingerprints, HTTP headers, session metadata → SQLite; includes `.onion` hidden service via Tor
- **Webhook Automation** — Flask + ngrok bridge for zero-touch `git pull` on GitHub push events
- NAS storage, packet capture, dashboards, and segmented lab services
- Tailscale VPN SSH gateway with IP whitelist enforcement and auto-blacklisting via iptables
- GreenBone SIEM + Suricata IPS/IDS integration; VLAN segmentation for isolated lab VMs
- Honeypot experimentation and automated backup / hook pipelines

***

### 4. [Network Wireshark Toolkit](https://github.com/Gr3y-foX/simple_trafic_analyze)
`Python` `Scapy` `NetworkX` `Matplotlib` `Pandas`
> Python-based .pcap analysis & visualization tool

- Parses Wireshark captures, extracts IP/TCP/UDP/DNS layer statistics
- Builds interactive network graphs (Top-20 flows via NetworkX) and protocol distribution charts
- IP geolocation enrichment + geographic scatter map output
- Auto-generates `.txt` and styled `.html` reports

***

### 5. [WiFi_chekcer](https://github.com/Gr3y-foX/WiFi_chekcer) — WiFi Security Assessment Tool
`Python` `JavaScript / Node.js`
> Educational WPA/WPA2 vulnerability assessment tool

- Brute-force simulation with wordlist support, configurable timing, retry logic, result logging
- Password strength visualizer — time-to-crack across entropy levels
- Security assessment with hardening recommendations (WPA3, SSID hygiene)

***

### 6. [web-interogatter](https://github.com/Gr3y-foX/web-interogatter) — Flask Honeypot Server
`Python` `Flask` `SQLite` `Tor` `Docker`
> Passive client reconnaissance research platform
- Captures browser fingerprints, HTTP headers, cookies, session IDs, device/OS metadata → SQLite
- Tor integration via SOCKS5 + auto-provisioned `.onion` hidden service
- Admin panel for reviewing intercepted sessions and generating reports

***

### 7. [macOS-Security-and-Privacy-Guide-modded-Fox-Division](https://github.com/Gr3y-foX/macOS-Security-and-Privacy-Guide-modded-Fox-Division)

> Opinionated, interactive macOS hardening helper inspired by  
> [drduh/macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide).

***


## 🎓 Education & Certifications

### Education

| Institution | Degree | Period |
|---|---|---|
| Prague College | BSc Cybersecurity | 2025 – Present |

Relevant coursework:
- Network security
- Artificial intelligence
- Penetration testing methodologies
- Cybersecurity defense
- Cyber law and GDPR-related topics

| Institution | Degree | Period |
|---|---|---|
| Vysoká škola polytechnická Jihlava | Finance & Risk Management | 2022 – 2024 |

Relevant background:
- Risk assessment frameworks
- Audit procedures
- Business systems analysis

## Certifications

### Cisco Networking Academy

- CCNA: Switching, Routing, and Wireless Essentials — `Completed (2025)`
- Cyber Threat Management — `Completed (2026)`
- Cybersecurity Essentials — `Completed (2025)`
- Endpoint Security — `Completed (2026)`
- Python Essentials 1 & 2 — `Completed (2025)`
- Creating Compelling Reports — `Completed (2026)`

### IBM / Coursera

- Ethical Hacking with Open Source Tools — `Completed 2026`
- Security Analytics — Intermediate — `Completed 2026`

### In Progress / Target

- OSCP — `Target: Q4 2026`
- CISA — `Target: Q4 2026`
- Ethical Hacking Essentials (EHE) — `Target: Q3 2026`

***

## 🏆 CTF & Competitive Hacking

- **HackTheBox Academy** — Web Security path (4 machines owned, target: 10+)
- **TryHackMe** — Wreath: multi-pivot network penetration
- Active monitoring: MITRE ATT&CK updates, CVE database, ISO/IEC 27001:2022

***

## 💼 Experience

**Sales Associate & IT Systems Assistant** | Bross Trading S.R.O., Prague | 2023 – Q1 2025
- Administered CRM access controls and user permission management
- Conducted authorized phishing simulations for internal security awareness
- Performed security hygiene assessments of internal workflows

**Security Researcher & Tool Developer** | Self-Directed | 2024 – Present
- Built and maintain home offensive security lab (Raspberry Pi 4, OpenWRT, Docker)
- Developed 4+ open-source security tools published on GitHub
- Conducted 10+ pro-bono security audits for SMBs and educational organizations
- Team lead on LLM-based OSINT startup project (team of 6+, EU GDPR compliance)

***

## 🤝 Open To

- 🔴 Red Team / Penetration Testing Internships
- 🔵 Junior Security Analyst/Auditor positions
- 🤝 Collaboration on open-source security tools
- 🎓 Mentorship from experienced security professionals

***

<div align="center">

---
</div>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Gr3y-foX&color=red&style=flat-square&label=Profile+Views)

</div>
