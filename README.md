# Hi, I'm [Your Name] 👋

### SOC Analyst | Threat Detection | Incident Response

I monitor, investigate, and respond to security threats. I enjoy turning raw logs into clear answers: finding what happened, how far it spread, and how to stop it from happening again.

📍 [EGYPT] · 🌐 Open to [remote / relocation / on-site] roles
📫 [mahmoud0548331473@gmail.com] · 💼 [https://www.linkedin.com/in/mahmoud-attia-a8b4b921b/]

---

## 🛡️ What I Do

- Triage and investigate alerts in [Splunk / Sentinel / QRadar / Elastic / Wazuh]
- Analyze phishing emails, suspicious logins, malware activity, and network traffic
- Write detection rules mapped to the MITRE ATT&CK framework
- Document incidents with clear timelines, IOCs, and recommendations
- [Add something specific you do, e.g. "Reduced false positives by tuning X rules"]

## 🧰 Technical Skills

| Area | Tools & Experience |
|------|--------------------|
| **SIEM & Monitoring** | Splunk, Elastic SIEM, IBM QRadar, FortiSIEM, Security Onion |
| **Network Analysis** | Wireshark, Zeek, Suricata, Snort, Sguil (DNS/HTTP traffic analysis) |
| **Network Security** | Cisco routing, switching, AAA, ACLs (CCNA labs); FortiGate and FortiAnalyzer log monitoring |
| **SOAR & Automation** | n8n, Cortex XSOAR, FortiSOAR; Python and JavaScript; REST API integrations (VirusTotal, Gmail) |
| **Systems** | Windows, Ubuntu, Kali; Windows Event Logs, PowerShell logging, Active Directory activity |
| **Threat Intel & Analysis** | VirusTotal, Hybrid Analysis, CyberChef |
| **Frameworks** | MITRE ATT&CK, severity-based incident triage |

## 📂 Featured Projects

### 🤖 [n8n SOC Alert Triage & SOAR Automation Lab](link)
`n8n` `Python` `REST APIs` `VirusTotal API` `Gmail API`
Built an automated SOAR workflow that pulls alerts from a security monitoring platform via REST API,
extracts IPv4 IOCs with Python, filters out private, reserved, and trusted IPs,
enriches the remaining public IPs with VirusTotal, scores them with risk-based conditional logic,
and emails an escalation through Gmail when a malicious or suspicious indicator is found.
**Goal:** cut manual Level 1 investigation work and speed up escalation.

### 🔎 [Network Threat Hunting: Ursnif to TrickBot Infection Chain](link)
`Security Onion` `Sguil` `Wireshark`
Correlated Sguil alerts with PCAPs to identify the infected host and reconstruct the full infection chain.
Documented the timeline, IOCs, and response recommendations in an incident report.
**ATT&CK:** T1105, T1036.008, T1071.001

### 📧 [Phishing and PCAP Investigation: FormBook and TeamViewer RAT](link)
`Security Onion` `Zeek` `Kibana` `Wireshark` `CyberChef`
Analyzed 2 phishing emails mapped to 4 PCAPs.
Identified a FormBook stealer and a Word/OLE downloader that installed a TeamViewer RAT.
Traced C2 over DNS/HTTP and separated confirmed from suspected activity using IOCs enriched in VirusTotal and Hybrid Analysis.
**ATT&CK:** T1566.001, T1204.002, T1219

### ⚔️ [Detection Engineering: Attack Simulation in Elastic SIEM](link)
`Elastic Stack` `Metasploit` `KQL`
Simulated a Meterpreter reverse shell, SYSTEM privilege escalation, 
and C2 exfiltration in an isolated multi-VM lab. Wrote 3 KQL detection rules,
including PowerShell script block logging (Event ID 4104).
**ATT&CK:** T1059.001, T1134.001, T1041

## 🎓 Certifications

-[Fortinet NSE 4– Certified in FortiOS (Fortinet)]
-[Fortinet NSE 6– FortiSIEM 7.4 Analyst (Fortinet)]
- 🔄 *In progress:* [SC-200,CDSA]

## 📂 Featured Projects

| Project | What it shows |
|---------|---------------|
| [**Detection Rules**](link) | [X] Sigma/SPL/KQL rules mapped to ATT&CK, with testing notes |
| [**Phishing Investigation**](link) | Full email analysis, IOC extraction, and incident report |
| [**Home SOC Lab**](link) | Wazuh/Splunk lab with attack simulation and custom detections |
| [**IOC Enrichment Script**](link) | Python tool that checks IPs/hashes against threat intel APIs |
| [**IR Playbooks**](link) | Step-by-step response guides for common incidents |

## 🧪 Currently Working On

- [Example: Studying for BTL1 / SC-200]
- [Example: Completing the CyberDefenders blue team path]

## 🏆 Practice Platforms

· [TryHackMe: Top 1%]  [https://sl1nk.com/tkwupnr]
· [CyberDefenders]  [https://cyberdefenders.org/p/mahmoud7atia]
. [HackTheBox]  [https://profile.hackthebox.com/profile/019ed5a9-947f-70cc-a2af-ca1a2ba5ab7a?utm_medium=copy_url]
