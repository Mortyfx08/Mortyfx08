# Hello, I'm Morty 👋

<div id="badges">
  <a href="https://www.linkedin.com/in/mourad-lmselah-25a26b2b7/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>

## 🕵️‍♂️ Brief Introduction
I am a defense-oriented cybersecurity professional with a strict focus on the Blue Team and SOC Analyst tracks. I prioritize practical, hands-on experience over pure theory, specializing in incident response, proactive CTI hunting, and SOC workflows. My methodology is anchored in industry frameworks like MITRE ATT&CK, CAR, and D3FEND, supported by a solid foundation in Linux and Windows AD system administration.

## 🎯 Objective
To continually architect robust defensive infrastructure and streamline SOC workflows through **automated incident response** and **dynamic CTI feed fetching**. I aim to balance defensive deployments (like SIEMs and honeypots) with a deep understanding of offensive tactics, innovating security operations by **analyzing malware and malicious emails**, and building custom security tools via vibe coding.

## 🛠️ Skills & Associated Projects
* **CTI Hunting & Incident Response** - <a href="[Link to your CTI project repo]">Threat Hunting Lab</a>
* **Security Information and Event Management (SIEM)** - <a href="[Link to your SIEM project repo]">Custom SIEM Deployment</a>
* **Automated IR & Malware Analysis** - <a href="[Link to your malware/phishing repo]">Email & Malware Sandboxing</a>
* **Defensive Architecture** - <a href="[Link to your honeypot project repo]">Interactive Honeypot Network</a>
* **Vibe Coding Security Tools** - <a href="[Link to your vibe coding repo]">Automated Log Analyzer</a>
* **System Administration** - <a href="[Link to your AD lab repo]">Active Directory & Linux Home Lab</a>

## 💻 Tools

### SIEM & SOAR
At the core of my defensive strategy is the deployment and management of robust centralized logging and response architectures. I leverage platforms like Splunk, Elastic, and Wazuh to aggregate, parse, and correlate massive volumes of log data across diverse enterprise environments. By integrating these SIEMs with SOAR solutions such as Shuffle, TheHive, and Cortex, I actively automate triage pipelines and incident response playbooks. This seamless orchestration between detection and response significantly reduces both the mean time to detect (MTTD) and mean time to respond (MTTR) against active threats. 

<img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" alt="Splunk"/> <img src="https://img.shields.io/badge/Elastic-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elastic"/> <img src="https://img.shields.io/badge/Wazuh-00AEEF?style=for-the-badge&logo=wazuh&logoColor=white" alt="Wazuh"/> <img src="https://img.shields.io/badge/TheHive-FFCC00?style=for-the-badge&logo=security&logoColor=black" alt="TheHive"/> <img src="https://img.shields.io/badge/Cortex-555555?style=for-the-badge&logo=linux&logoColor=white" alt="Cortex"/> <img src="https://img.shields.io/badge/Shuffle-0084FF?style=for-the-badge&logo=alltrails&logoColor=white" alt="Shuffle"/>

### Threat Intelligence
To stay ahead of evolving adversary tactics, I actively integrate external Cyber Threat Intelligence (CTI) into my daily SOC workflows. Utilizing platforms like MISP, I aggregate and curate indicators of compromise (IOCs), dynamically enriching them with contextual data from sources like VirusTotal and AbuseIPDB. This automated CTI feed fetching allows me to hunt proactively across the network, translating global threat intelligence into localized, actionable detection rules mapped directly to the MITRE ATT&CK framework.

<img src="https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white" alt="VirusTotal"/> <img src="https://img.shields.io/badge/AbuseIPDB-005571?style=for-the-badge&logo=data&logoColor=white" alt="AbuseIPDB"/> <img src="https://img.shields.io/badge/MISP-E74C3C?style=for-the-badge&logo=security&logoColor=white" alt="MISP"/>

### Forensics
When an incident escalates, I apply rigorous digital forensics and incident response (DFIR) methodologies to uncover the full scope of a breach. My approach involves capturing and analyzing volatile memory using tools like DumpIt and Volatility to hunt for advanced evasion techniques, such as process hollowing and injected threads. I also utilize Velociraptor for rapid, scalable artifact collection across endpoints, alongside utilities like CyberChef to decode and reconstruct obfuscated payloads, ensuring a comprehensive understanding of the attacker's footprint.

<img src="https://img.shields.io/badge/Velociraptor-4A90E2?style=for-the-badge&logo=v&logoColor=white" alt="Velociraptor"/> <img src="https://img.shields.io/badge/Volatility-4B275F?style=for-the-badge&logo=linux&logoColor=white" alt="Volatility"/> <img src="https://img.shields.io/badge/DumpIt-FF0000?style=for-the-badge&logo=windows&logoColor=white" alt="DumpIt"/>

### Network Security & Endpoint (IDS/IPS/Firewall)
Securing the perimeter and monitoring internal traffic is critical to denying lateral movement and data exfiltration. I design and configure robust network defenses using pfSense for enterprise routing and Snort for intrusion detection and prevention (IDS/IPS) to actively drop malicious packets. On a granular level, I perform deep packet inspection using Wireshark to identify anomalous network behavior. At the endpoint level, I deploy and tune Sysmon across Windows environments to gain high-fidelity telemetry into process creation, network connections, and critical file modifications.

<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark"/> <img src="https://img.shields.io/badge/Snort_IDS/IPS-EF3B24?style=for-the-badge&logo=s&logoColor=white" alt="Snort"/> <img src="https://img.shields.io/badge/pfSense-000000?style=for-the-badge&logo=pfsense&logoColor=white" alt="pfSense"/> <img src="https://img.shields.io/badge/Sysmon-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Sysmon"/> 

### Malware & Email Analysis 
In the realm of Malware and Email Analysis, my focus is on safely dissecting malicious payloads and initial access vectors to extract actionable threat intelligence. I approach email investigations methodically, analyzing headers and utilizing utilities like CyberChef to decode obfuscated scripts and malicious attachments. When examining the malware itself, I employ rigorous static analysis techniques, leveraging tools like **Ghidra** and **PEStudio**. To observe the malware's true behavior, I execute dynamic analysis within isolated, custom-built sandbox environments like **FlareVM** and **REMnux**. By utilizing sandboxing platforms like **ANY.RUN** and **Hybrid Analysis**, I actively monitor for advanced adversary techniques and C2 network callbacks, translating my findings into robust, automated detection rules.

<img src="https://img.shields.io/badge/ANY.RUN-005571?style=for-the-badge&logo=any.run&logoColor=white" alt="ANY.RUN"/> <img src="https://img.shields.io/badge/Hybrid_Analysis-000000?style=for-the-badge&logo=falcon&logoColor=white" alt="Hybrid Analysis"/> <img src="https://img.shields.io/badge/FlareVM-FF4006?style=for-the-badge&logo=fire&logoColor=white" alt="FlareVM"/> <img src="https://img.shields.io/badge/REMnux-000000?style=for-the-badge&logo=linux&logoColor=white" alt="REMnux"/> <img src="https://img.shields.io/badge/Ghidra-000000?style=for-the-badge&logo=c&logoColor=white" alt="Ghidra"/> <img src="https://img.shields.io/badge/PEStudio-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="PEStudio"/><img src="https://img.shields.io/badge/CyberChef-005571?style=for-the-badge&logo=c&logoColor=white" alt="CyberChef"/>

### Vibe Coding & Automation
I believe that the most effective defenders are also builders. To bridge gaps in traditional tooling and eliminate repetitive SOC tasks, I heavily engage in vibe coding—rapidly prototyping and deploying custom security applications. Whether it is writing Python scripts to parse complex forensic artifacts, utilizing Go for high-performance network monitoring, or building full-fledged APIs and web dashboards with FastAPI, I continuously engineer automated solutions that empower the defense team and streamline security operations.
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>

### Infrastructure & Virtualisation
A robust defense begins at the architectural level. I specialize in designing, deploying, and managing scalable virtualized environments using Proxmox to host comprehensive SOC labs and isolated threat-hunting networks. My system administration expertise spans across diverse Linux distributions and Windows Server environments, with a strong focus on configuring and securing Active Directory domains. By engineering these enterprise-grade topologies from the bare metal up, I ensure a highly controlled, realistic foundation for deploying critical security appliances, interactive honeypots, and secure malware sandboxes.

<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/> <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows Server"/> <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" alt="Proxmox"/>

## 📁 Projects
* [**BOT-DEFENDER SAAS APP**](https://github.com/Mortyfx08/bot-defender-ts) - A modern, production-ready Shopify embedded app for bot protection, built with Next.js, Polaris, App Bridge, Express, MongoDB, and Redis.
