# Hi, I'm Badr JAKOUT 👋

### Cybersecurity engineering student · SOC · SOAR automation · Detection engineering

> 🎯 **Looking for a 6-month PFE internship starting February 2027**

I build and test security operations end to end: from detection and alert triage to automated response, in labs I design myself and during two internships. Most recently I built a SOC chain where an LLM agent does first-level triage and a deterministic guardrail decides what actually happens.

---

## 💼 Experience

### Cybersecurity intern — SOAR & Artificial Intelligence
**Devoteam | Cyber Trust** · Casablanca · *July – September 2026*
- Built an end-to-end SOC chain where an **LLM agent** performs level-1 triage and returns a structured assessment (classification, severity, confidence, MITRE ATT&CK technique). The model informs, the code decides.
- Deployed **TheHive** and **Cortex** for case management and observable enrichment, fed by Suricata (WAN/LAN/DMZ), Elasticsearch and ElastAlert2.
- Developed a custom **Cortex responder** that applies containment on pfSense, only after a deterministic guardrail approves, then verifies the result on the firewall itself.
- Validated the whole chain on **13 MITRE ATT&CK techniques**, including one autonomous containment and one correct refusal to act on an internal source.

### Cybersecurity intern — SIEM & vulnerability analysis
**Groupe SONASID** · El Jadida · *July – August 2025*
- Deployed and administered the **Wazuh SIEM** for real-time monitoring, with custom detection rules and incident handling.
- Simulated a complete attack cycle on the same network (OSINT, Nessus, WPScan, exploitation, post-exploitation), then detected and documented it phase by phase.
- Designed a segmented network on QEMU/KVM with pfSense and Windows Server 2019 (Active Directory).

---

## 🚀 Top 6 projects

| # | Project | What I did |
|---|---|---|
| 1 | **Segmented SOC infrastructure & attack simulation** | LAN/DMZ/WAN network with pfSense, Suricata deep inspection, Wazuh SIEM and a Python honeypot in the DMZ. Full red team chain (living-off-the-land phishing through an internal SMTP relay, multithreaded Python keylogger), entirely detected on the blue side. |
| 2 | [**Cloud Attack Range**](https://github.com/b4d33r/Cloud-Attack-Range-Detection) | Local AWS cyber range built with Terraform and LocalStack: deliberately misconfigured IAM roles and a vulnerable app exposing an SSRF. IAM privilege escalation simulated with Stratus Red Team, CloudTrail forwarding and Wazuh detection rules, measured on detection delay. |
| 3 | **Information Security Policy (PSSI), GlobalMantics** | Complete policy for a simulated company: organizational context, asset classification, risk analysis (ISO 27001, EBIOS RM), security objectives and a prioritized action plan with owners and follow-up indicators. |
| 4 | **ISO 27001 ISMS support, GlobalMantics** | 34 assets inventoried, gap assessment on clauses 4 to 10 and the 93 Annex A controls (average maturity 2.1/5 before treatment, 3.4/5 after), 18 risks (ISO 27005), 14 corrective actions and a Statement of Applicability (82 controls kept, 11 excluded with justification). |
| 5 | **Secure CI/CD pipeline (DevSecOps)** | GitHub Actions on a Terraform project: fmt, validate and plan, static analysis (Semgrep), dependency and infrastructure scans (Trivy, Checkov), secret detection (Gitleaks) and Docker build, to catch vulnerabilities before production. |
| 6 | **IP backbone pentest on virtualized infrastructure** | QEMU/KVM platform simulating an IP backbone (LAN/DMZ/WAN) with pfSense, virtual switches and inter-VLAN routing. Nmap and Nessus scans, exploitation of firewall misconfigurations, VPN policy checks, and a report with executive summary, CVSS scores and remediation advice. |

Also: [SafeByte](https://github.com/b4d33r/SafeByte) (CLI password manager with AES-GCM encryption and Argon2 hashing), a [multithreaded port scanner](https://github.com/b4d33r/multithreaded_port_scanner) in Python, and a task management web app (PHP/MySQL).

---

## 🛠️ Skills

| Area | Tools |
|---|---|
| **Detection & response** | Wazuh, Elastic Stack, Suricata, TheHive, Cortex, MITRE ATT&CK, OWASP Top 10 |
| **Offensive security** | Nmap, Nessus, Burp Suite, Metasploit, WPScan, Wireshark |
| **Cloud & automation** | AWS, Terraform, LocalStack, Docker, GitHub Actions, Python, Bash |
| **Systems & networks** | Linux, Windows Server, Active Directory, pfSense, QEMU/KVM |
| **Governance & compliance** | ISO 27001, ISO 27005, EBIOS RM (notions), PSSI, risk assessment |
| **AI for security** | LLM agent design with the Anthropic API, prompt engineering, deterministic guardrails |

---

## 🎓 Education

- **Engineering degree: Smart Networks & Cybersecurity** · ENSA Khouribga · 2024 – 2027 (Bac+5)
- **Integrated preparatory cycle** · ENSA Khouribga · 2022 – 2024
- **Baccalauréat, Physical Sciences, with highest honors** · 2022

## 🏆 Certifications & distinctions

- 🥇 **1st place CTF**, NetCom Days 7.0 (Web, Cryptography, Forensics)
- 🌍 **30+ CTF competitions**, including 23 international events on [CTFtime](https://ctftime.org/team/360737) (2024 – 2025): ASIS CTF Finals (73rd), SECCON, GlacierCTF, LakeCTF, LA CTF and WorldWide CTF
- 🎯 CTF designer and organizer, NetCom Days 6.0
- 🛡️ **[TryHackMe](https://tryhackme.com/p/b4d33r) top 3%**: CompTIA Pentest+ and Jr Penetration Tester paths, Web Fundamentals
- Cisco: CCNA (Switching, Routing and Wireless Essentials), Network Security, Introduction to Cybersecurity
- AWS Academy Cloud Foundations · Red Hat System Administration I (RH124) · TCM Security Linux 100

## 🗣️ Languages

Arabic (native) · French (fluent) · English (fluent)

---

## 📫 Contact

- 📧 [jakoutbadr20@gmail.com](mailto:jakoutbadr20@gmail.com)
- 🔗 [linkedin.com/in/badr-jakout](https://www.linkedin.com/in/badr-jakout/)
- 🛡️ [TryHackMe: b4d33r](https://tryhackme.com/p/b4d33r) (top 3%)
- 🚩 [CTFtime: b4d33r](https://ctftime.org/team/360737)
- 🐙 [github.com/b4d33r](https://github.com/b4d33r)
