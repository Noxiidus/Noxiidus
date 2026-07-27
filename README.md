# 👋 Hi, I'm Balázs — aka Noxidus

**Penetration Tester** · Hungary 🇭🇺

![Profile Views](https://komarev.com/ghpvc/?username=Noxiidus&color=9FEF00&style=for-the-badge&label=Profile+Views)

Working both sides of the fence — **red team** offensive testing and **blue team** digital
forensics.

Breaking into systems and investigating how someone else did it are the same skill viewed from two
directions. Attacking teaches me what artifacts get left behind; forensics teaches me what an
attacker forgets to clean up. I document both, because explaining an engagement or an investigation
is where the actual learning happens.

---

## ⚔️ Red Team

- **Penetration testing** — web application and network assessments
- **Reconnaissance & enumeration** — subdomain and vhost discovery, service fingerprinting, content discovery
- **Exploitation** — credential attacks, misconfiguration abuse, privilege escalation
- **Post-exploitation** — persistence mechanisms, lateral movement, cloud API abuse
- **Tooling** — small Python utilities for scanning and credential analysis

## 🛡️ Blue Team

- **Digital forensics** — Linux authentication logs, `wtmp`/`utmp` session artifacts, timeline reconstruction
- **Network forensics** — PCAP analysis, attack-chain reconstruction, exfiltration tracking
- **Malware analysis** — static ELF triage: symbol recovery, disassembly, C2 extraction
- **Threat intelligence** — correlating vendor reporting into actor profiles and MITRE ATT&CK mappings

---

## 🛠️ Skills

**Offensive**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=gnometerminal&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![ffuf](https://img.shields.io/badge/ffuf-2E2E2E?style=for-the-badge)
![Gobuster](https://img.shields.io/badge/Gobuster-00979D?style=for-the-badge)
![Amass](https://img.shields.io/badge/OWASP_Amass-1F6FEB?style=for-the-badge&logo=owasp&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-8B0000?style=for-the-badge)
![John the Ripper](https://img.shields.io/badge/John_the_Ripper-5A5A5A?style=for-the-badge)
![Hashcat](https://img.shields.io/badge/Hashcat-000000?style=for-the-badge)
![sqlmap](https://img.shields.io/badge/sqlmap-D9480F?style=for-the-badge)
![Hack The Box](https://img.shields.io/badge/Hack_The_Box-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)

**Defensive & Forensics**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![tcpdump](https://img.shields.io/badge/tcpdump-0B7285?style=for-the-badge)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C81D25?style=for-the-badge&logo=mitre&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma-3A7CA5?style=for-the-badge)
![Timesketch](https://img.shields.io/badge/Timesketch-4285F4?style=for-the-badge)
![plaso](https://img.shields.io/badge/plaso_(log2timeline)-2C3E50?style=for-the-badge)
![Ghidra](https://img.shields.io/badge/Ghidra-A6120D?style=for-the-badge)
![radare2](https://img.shields.io/badge/radare2-268BD2?style=for-the-badge)
![Capstone](https://img.shields.io/badge/Capstone_Engine-4B0082?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Web & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Tools & CI**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![mypy](https://img.shields.io/badge/mypy-2A6DB0?style=for-the-badge)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)

---

## 🧪 Security work

### [tracehound](https://github.com/Noxiidus/tracehound) · `Python` · `Blue Team` · **flagship**

A Linux DFIR triage toolkit, built from scratch.

**Twelve parsers** — seven log/event sources (`auth.log`, the utmp family, `lastlog`, shell
history, cron, systemd journal, and plaso super-timelines) plus five *state-artifact* parsers
(`/etc/passwd`, `/etc/group`, `sudoers`, `authorized_keys`, systemd units) — feed a
UTC-normalised timeline and a timeless `Fact` model. **20+ detection rules** turn them into
findings with MITRE ATT&CK mappings: credential attacks, persistence, privilege abuse, backdoor
accounts and SSH keys, and anti-forensics rules that reason about what is *missing*.

Runs the community's **Sigma** rules — a practical subset of the spec compiled onto its own
detection engine — and **exports to log2timeline/plaso CSV, Timesketch JSONL and Sigma**, so it
feeds Timesketch and a SIEM, not just its own reports. Plus **multi-host correlation** (lateral
movement, patient-zero, with honest clock-drift handling) and a **dependency-free POSIX
collector** that measures each host's clock and hashes evidence at collection time.

250+ tests, `mypy --strict`, `ruff`, CI across Python 3.10–3.12, full wiki documentation.

### [HTB Writeups](https://github.com/Noxiidus/HTB-Writeups) · `Red Team`
Walkthroughs from Hack The Box machines and challenges — enumeration, exploitation and privilege
escalation, documented end to end.

### [HTB Sherlock Writeups](https://github.com/Noxiidus/htb-sherlock-writeups) · `Blue Team`
DFIR investigations of retired Sherlocks: Linux log forensics, an OpenStack cloud compromise
reconstructed from packet captures, and OSINT threat-actor profiling. Written to show the reasoning,
not just the answers.

### [Simple Port Scanner](https://github.com/Noxiidus/Simple-Port-Scanner) · `Python`
A lightweight TCP port scanner built to understand socket programming and service enumeration from
the ground up.

### [Password Strength Checker](https://github.com/Noxiidus/Password-Strength-Checker) · `Python`
Evaluates password strength against common weakness patterns — a practical look at why length beats
complexity rules.

---

## 💻 Web projects

### [Crypto Price Tracker](https://github.com/Noxiidus/crypto-price-tracker) · `JavaScript`
Live cryptocurrency price tracking against a public API.

### [Weather App](https://github.com/Noxiidus/weather-app) · `HTML/CSS/JS`
Fully responsive, mobile-friendly weather client.

---

## 🎓 Certifications

[![Credly](https://img.shields.io/badge/Verify_on_Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white)](https://www.credly.com/users/noxidus)

| Certification | Issuer | Issued |
|---|---|---|
| **Google Cloud Cybersecurity Certificate** | Google Cloud | Jul 2026 |
| **[Google AI Professional Certificate](https://www.credly.com/badges/1f37596d-2abc-40c0-823d-6886291f4293)** | Google Career Certificates | Jul 2026 |
| **Google AI Essentials** | Google Career Certificates | Jul 2026 |
| **[Responsive Web Design](https://www.freecodecamp.org/certification/noxidus/responsive-web-design)** | freeCodeCamp | — |
| **[JavaScript Algorithms and Data Structures (v8)](https://www.freecodecamp.org/certification/noxidus/javascript-algorithms-and-data-structures-v8)** | freeCodeCamp | — |
| **[JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/certification/noxidus/javascript-algorithms-and-data-structures)** | freeCodeCamp | — |

<details>
<summary>Google AI Professional Certificate — component badges</summary>

AI Fundamentals · AI for App Building · AI for Brainstorming and Planning · AI for Content Creation ·
AI for Data Analysis · AI for Research and Insights · AI for Writing and Communicating

</details>

### Google AI Professional Certificate

![Google AI Professional Certificate](assets/google-ai-professional-certificate.png)

---

## 📊 GitHub Stats

![Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Noxiidus&theme=radical)
![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Noxiidus&theme=radical)
![Most-used Languages](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Noxiidus&theme=radical)
![Productive Time](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Noxiidus&theme=radical&utcOffset=1)

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/noxidus/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ankara.herho@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Noxiidus)
[![Credly](https://img.shields.io/badge/Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white)](https://www.credly.com/users/noxidus)

Always up for talking offensive security, forensics, or a good CTF. 🕵️

---

<sub>All security work shown here is performed in authorized lab environments and CTF platforms.</sub>
