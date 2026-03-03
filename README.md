# 🎯 Saimon "Archont" Alvarez | Cybersecurity Student & Aspiring Red Teamer

<div align="center">

╔═══════════════════════════════════════════════════════════════╗
║   "The best defense is understanding the offense"             ║
╚═══════════════════════════════════════════════════════════════╝

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/viktor-pylypenko-2a8893369/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:v.pilipenko2005@gmail.com)

**Location:** Prague, Czech Republic 🇨🇿  
**Status:** Cybersecurity Student | Open to Internships & Junior Positions  
**Languages:** English (Professional) | Czech (Fluent) | Russian/Ukranian (Native)
</div>

---

## 👨‍💻 About Me

Cybersecurity student at **[Prague Collegue]** specializing in **penetration testing**, **using LLM pipelines**, and **red team operations**. Currently transitioning from hospitality management to offensive security with hands-on experience in CTF competitions and practical security research.

**What drives me:**
- 🔍 Breaking systems to understand how they work
- 🛡️ Building secure solutions through adversarial thinking
- 📚 Continuous learning through real-world attack scenarios
- 🌐 Contributing to open-source security tools

**Current Focus:** Preparing for **OSCP** | Active in CTF competitions | Building home security lab

---

## 🛠️ Technical Arsenal

### Operating Systems & Environments
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Programming & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Security Tools & Frameworks

**Reconnaissance & OSINT**
• nmap • Sublist3r • theHarvester • Shodan • Wireshark

**Web Application Security**
• Burp Suite • SQLmap • XSStrike • Nikto • DirBuster

**Network Exploitation**
• Metasploit • Netcat • tcpdump • iptables • Aircrack-ng

**Password Cracking & Forensics**
• John the Ripper • Hashcat • Hydra • Volatility

**Specialized Skills**
- 🔐 Active Directory exploitation & Kerberos attacks
- 🌐 DNS/DHCP manipulation & network pivoting
- 📡 IoT security (ESP32, Flipper Zero modifications)
- 🐳 Docker-based security lab environments
- 🔍 Malware analysis (trojans, worms, payload development)

---

## 🎯 Featured Projects

### 🔴 Red Team Operations

#### 1️⃣ [Active Directory Pentest Lab](https://github.com/Gr3y-foX/pen_test_kali)
**Full attack chain simulation in isolated Windows environment**

- Kerberoasting & AS-REP roasting attacks
- BloodHound path analysis for privilege escalation
- Pass-the-Hash & Pass-the-Ticket techniques
- Golden Ticket & Silver Ticket generation
- Certificate abuse via ESC1/ESC8 vulnerabilities

**Tech Stack:** Windows Server 2022 | PowerShell | Impacket | Rubeus | Mimikatz  
**Detection Focus:** Event ID 4768, 4769, 4624 correlation

---

#### 2️⃣ [Network WireShark Toolkit](https://github.com/Gr3y-foX/simple_trafic_analyze)
**Python-based .pcap traffic analysis & visualization tool**

- Parses Wireshark capture files and extracts IP/TCP/UDP/DNS layer statistics
- Builds interactive network connection graphs (Top-20 flows via NetworkX)
- Generates multi-panel charts: protocol distribution, top IPs, ports & connections
- IP geolocation enrichment via ip-api.com with geographic scatter map output
- Auto-generates reports in both `.txt` and styled `.html` formats

**Tech Stack:** Python 3 | Scapy | NetworkX | Matplotlib | Seaborn | Pandas | Requests  
**Use Case:** Post-capture traffic forensics & visual network flow analysis

---

#### 3️⃣ [WiFi Security Checker](https://github.com/Gr3y-foX/WiFi_chekcer)
**Educational WiFi vulnerability assessment & brute-force simulation tool**

- WPA/WPA2 password brute-force simulation with wordlist support (Python)
- Enhanced bruteforcer with configurable timing, retry logic & result logging
- Brute-force protection module demonstrating password complexity impact
- Password strength visualizer — shows time-to-crack across different entropy levels
- Security assessment with actionable hardening recommendations (WPA3, SSID hygiene, etc.)

**Tech Stack:** Python 3 | JavaScript / Node.js | React Native  
**Use Case:** WiFi security awareness & hands-on lab demos for educational environments

---

### 🔧 Hardware & IoT Projects

#### 4️⃣ [Flipper Zero Custom Firmware](https://github.com/Gr3y-foX/flipper-custom-fw)
**Enhanced Flipper Zero capabilities with extended range**

\begin{itemize}
\item Custom antenna modifications for 433/868 MHz
\item SubGHz signal replay optimization
\item NFC/RFID clone protection bypass research
\item BadUSB payload library for penetration testing
\end{itemize}

**Tech Stack:** C | FreeRTOS | STM32 | CC1101  
**Use Case:** Physical security assessment tools

---

#### 5️⃣ [Raspberry Pi Security Lab]
**Self-hosted security research platform on Raspberry Pi**

- **[Web Interceptor](https://github.com/Gr3y-foX/web-interogatter)** — Flask-based honeypot server that captures browser fingerprints, HTTP headers, cookies, session IDs, device/OS metadata and stores all intercepts in SQLite
- Tor integration for full traffic anonymization via SOCKS5 proxy + auto-provisioned `.onion` hidden service
- Multi-tier logging system: 4 independent rotating log files (by size & time) + SQLite backend for structured analysis
- Admin web panel for reviewing intercepted sessions and generating reports
- **[Webhook Automation](https://github.com/Gr3y-foX/RPI-webhook-automatization)** — Flask + ngrok bridge for automatic `git pull` on GitHub push events, enabling zero-touch remote deployments to the Pi
- Docker-containerized deployment for both services with isolated execution environments
- **[VPN base authentification]
- Using TailScale VPN bridhe for secure and private logging in SSH with full logging and auto blocking IP if doesnt in white list
- Defense against BruteForce - using Python script on small password attempts before put IP on blacklist in IpTable

**Tech Stack:** Python 3 | Flask | SQLite | Tor / SOCKS5 | ngrok | Docker  
**Use Case:** Passive client reconnaissance research & automated Pi deployment pipeline


---

## 📊 CTF & Competitive Hacking

### Recent Achievements
ctf_stats = {
    "platforms": ["HackTheBox", "TryHackMe", "PicoCTF"],
    "boxes_pwned": 47,
    "badges_earned": 12,
    "favorite_category": "Web Exploitation",
    "current_rank": "Hacker (HTB) / Top 5% (THM)"
}

### Notable CTF Write-ups
- 🏆 **[HTB - Academy]** - OSINT to RCE exploitation chain
- 🏆 **[THM - Wreath]** - Multi-pivot network penetration
- 🏆 **[PicoCTF 2025]** - Web exploitation series (Top 100)

---

## 🎓 Academic Background

### 🏫 University Education
**Collegue "Prague College" — *master degree*
📚 Faculty of Social Sciences | Andragogy & Education Research
`2024 – present` | Prague, Czech Republic

> Focus areas: cybersecurity, implimintation AI and automated pipelines

### 🏅 Security Certifications (In Progress / Planned)
- [x] Cisco Networking Academy (NetAcad) - Completed:
  Computer Hardware Basics (2025) - Hardware security fundamentals and system architecture
  Cyber Threat Management (2025) - Threat intelligence, incident response, attack lifecycle
- [ ] Cisco Networking Academy (NetAcad) - In Progress:
  Cybersecurity Essentials (2025) - Network security, cryptography, access control
  Endpoint Security (2025) - Device hardening, malware analysis, threat protection
  Introduction to Cybersecurity (2025) - Security principles, CIA triad, defense strategies
- [ ] **OSCP** (Offensive Security Certified Professional) - *Q3 2026*
- [ ] **eJPT** (eLearnSecurity Junior Penetration Tester) - *Q2 2026*
- [ ] **CEH** (Certified Ethical Hacker) - *2027*
- [ ] **CompTIA Security+** (Self-study completed)
- [ ] **EC-Council** Certifications: Ethical Hacking Essentials (EHE) - *Q4 2026*
- [ ] **IBM Ethical** Hacking with Open Source Tools - Penetration testing with open-source frameworks - *Q4 2026*     

### 📖 Continuous Learning
- Active on HackTheBox Academy (Web Security path)
- Following MITRE ATT&CK framework updates
- ISO/IEC 27001:2022 standard review
- CVE database monitoring & exploitation research

---

### 🔐 Cybersecurity Education
**Self-directed & Institutional Training** | `2024 – present`

| Domain | Topics Covered |
|---|---|
| 🌐 Network Security | DNS/DHCP, routing, ARP, packet analysis |
| 🕸️ Web Application | SQLi, XSS, CSRF, OWASP Top 10 |
| 🐧 Linux & Systems | Hardening, sysadmin, privilege escalation |
| 📦 Containerization | Docker security, deployment, isolation |
| 🔎 OSINT | Passive recon, footprinting, data aggregation |

---

### 💼 Professional Background
**Hotel Director** — *Hospitality Management* | Prague, CZ
> Managed operations, security protocols, and team coordination.
> Transitioning career focus toward cybersecurity & red team operations.

---

### 🌍 Languages
![Czech](https://img.shields.io/badge/Czech-Fluent-blue?style=flat-square)
![English](https://img.shields.io/badge/English-Professional-green?style=flat-square)
![Russian](https://img.shields.io/badge/Russian-Native-red?style=flat-square)
![Ukrainian](https://img.shields.io/badge/Ukrainian-Native-red?style=flat-square)

---

## 🔬 Security Research Interests

\begin{itemize}
\item \textbf{Active Directory Security:} Kerberos protocol vulnerabilities, trust relationship abuse
\item \textbf{Web Application Security:} Modern authentication bypass techniques, API security
\item \textbf{Network Protocols:} DNS exfiltration, VLAN hopping, ARP poisoning countermeasures
\item \textbf{IoT \& Embedded Systems:} Firmware analysis, hardware debugging, wireless protocols
\item \textbf{Malware Development:} Payload obfuscation, AV evasion, C2 infrastructure
\end{itemize}

**Current Research Project:**  
*"Detection strategies for modern Kerberoasting attacks in enterprise environments"*

---

## 💼 Work Experience Transition

**Former:** Director at Small Hotel (Prague)  
- Team leadership & operations management
- Crisis response & problem-solving under pressure
- Client communication in multinational environment

**Former:** Team leader of startup project basing on LLM OSINT
- Team leadership & operations management
- Legal adjustments under rules of EU law and GDPR
- Recruiting and working with workers
- expierience in role of Project Manager and teamleadership group of 6 people


**Transitioning to:** Cybersecurity field  
- Applying structured thinking from hospitality to security operations
- Strong communication skills for stakeholder reporting
- Experience managing high-pressure situations

---

## 📈 GitHub Statistics

<div align="center">

![Archont's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Gr3y-foX&show_icons=true&theme=dark&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Gr3y-foX&layout=compact&theme=dark&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Gr3y-foX&theme=dark&hide_border=true)

</div>

---

## 🎯 Current Goals (2026)

\begin{enumerate}
\item Complete OSCP certification (Target: Q3 2026)
\item Contribute to 3+ open-source security tools
\item Participate in 10+ CTF competitions
\item Publish 5 detailed security research blog posts
\item Land first cybersecurity internship/junior position
\end{enumerate}

---

## 🤝 Open to Opportunities

I'm actively seeking:
- 🔴 **Red Team / Penetration Testing Internships**
- 🔵 **Junior Security Analyst positions**
- 🎓 **Mentorship from experienced security professionals**
- 💼 **Freelance security assessment projects**
- 🤝 **Collaboration on open-source security tools**

---

## 📫 Let's Connect

contact = {
    "email": "v.pilipenko2005@gmail.com",
    "linkedin": "[linkedin.com/in/saimon-archont-alvarez](https://www.linkedin.com/in/viktor-pylypenko-2a8893369/)",
    "location": "Prague, Czech Republic",
    "availability": "Open to remote & on-site opportunities",
    "response_time": "< 24 hours"
}

**Preferred Contact:** LinkedIn for professional inquiries | Email for project collaboration and open for suggestion and advises

---

## 🎓 Philosophy

> *"In cybersecurity, every vulnerability is a lesson, every exploit is a story, and every defense is a commitment to protecting what matters. I don't just break systems—I understand them, respect them, and help make them stronger."*

---

<div align="center">

### ⚡ Fun Facts

- 🌙 Prefer night coding sessions (peak focus: 22:00-02:00)
- 📚 Reading: *"The Hacker Playbook 3"* & philosophy (MNiccolò Machiavelli)
- 🎮 Hobbies: Anime, hardware tinkering, reverse engineering
- 🚗 Recently passed Czech driving test (Group B)
- 🐧 Linux enthusiast since 2022

---

**Last Updated:** March 2026

![Profile Views](https://komarev.com/ghpvc/?username=Gr3y-foX&color=red&style=flat-square&label=Profile+Views)

</div>
