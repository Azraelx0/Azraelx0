## Hi, I'm Azraelx0 👋

Cybersecurity & networking student focused on **DFIR** and **red teaming**. Most of what I learn ends up as a writeup here: labs, home lab builds, and side projects that look at security from both sides.

---

### 🔬 Current Projects

**Network Sonification Framework** *(private, in progress)*
What does a malware infection *sound* like? This project turns real-world malware traffic captures into audio.
- **Part 1:** mapped packets directly to nature soundscapes (forest, coastal). I learned that raw packet-to-sound mapping mostly produces noise, because routine traffic drowns out the important events.
- **Part 2:** an adaptive music engine. Captures go through **Suricata** (ET Open rules) to build attack timelines, which then drive an adaptive score in **FMOD**. The research question: *can network traffic become music that sounds good without losing what it reveals about an attack?*
- Stack: Python · Suricata · FMOD · pcaps from WarmCookie, FormBook, and RMS RAT infections

**Multi-Agent Security Testbed** *(private, early stage)*
A local multi-agent AI environment for studying the risks that come with agentic systems: identity spoofing, agent collusion, prompt injection, and data poisoning. It includes orchestrator, retriever, and programming agents, plus a red team agent that tests the system and writes up its findings.
- Stack: Python · Ollama · local LLMs (Qwen)

---

### 📂 Coursework & Labs

| Repo | Focus |
|---|---|
| [SEC335](https://github.com/Azraelx0/SEC335) | **Ethical hacking:** Windows/Linux privesc, LOLBins, staging & exfil, initial access, full pentest report, web app exploitation (SQLi, XSS, IDOR, RCE, CSRF) |
| [SEC-350](https://github.com/Azraelx0/SEC-350) | **Network security controls:** VyOS firewalls, DMZ & segmentation, Wazuh, WAF, Zeek, jump boxes, VPN |
| [RangeOps](https://github.com/Azraelx0/RangeOps) | **Cyber range build:** Proxmox templating & API automation, vulnerable AD and web labs |
| [SYS320-01](https://github.com/Azraelx0/SYS320-01) | **Automation & scripting:** PowerShell/Bash for log parsing, IOC hunting, and automated reporting |

Also built: a multi-node **Elastic Stack** SIEM (Fleet, TLS, hot/cold ILM, Sysmon endpoints) and Cisco enterprise networks (OSPF, BGP, NAT, ACLs).

---

### 🛠️ Toolbox

**Offensive:** Metasploit · Burp Suite · sqlmap · Impacket · Responder · WinPEAS · John the Ripper
**Defensive / DFIR:** Elastic Stack · Wazuh · Suricata · Zeek · Sysmon · Wireshark
**Infrastructure:** Proxmox · VyOS · Cisco IOS · Windows Server / AD · Linux
**Languages:** Python · PowerShell · Bash
