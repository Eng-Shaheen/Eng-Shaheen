## Cybersecurity Portfolio
- This portfolio documents hands-on cybersecurity work across SOC detection engineering, threat deception, network forensics, and automation. Every project is built on real tools, real data, and real investigative methodology - aligned to enterprise SOC workflows and MITRE ATT&CK. No CTF writeups. No theory. Just practical defensive security work.

---
#### Detection & Response
-  [Microsoft Sentinel SIEM - Cloud Detection Lab (Azure)](https://github.com/Eng-Shaheen/Microsoft-Sentinel-SIEM-Lab)
    - Deployed Microsoft Sentinel on Azure with a dedicated resource group and Log Analytics workspace. Configured the cloud-native SIEM environment, explored the ASIM normalisation schema, and queried Azure AD authentication error codes using KQL - including account lockouts (50053), incorrect passwords (50056), disabled accounts (50057), and conditional access policy violations (53003).
 - [Splunk SIEM Detection Engineering & Log Triage - MITRE ATT&CK Mapped](https://github.com/Eng-Shaheen/Splunk-log-triage-lab)
    - Built 15+ custom SPL detection queries in Splunk to identify brute-force, credential compromise, and lateral movement patterns from SSH authentication logs. Tuned correlation rules reducing false-positives by 35%. Mapped attacker behaviour to MITRE ATT&CK T1110 → T1078 → T1021.004 with full incident timeline reconstruction.
 - [Windows Authentication Security Analysis - MITRE ATT&CK Mapped](https://github.com/Eng-Shaheen/Windows-Authentication-Security-Analysis)
    - Triaged 32,678 Windows Security Event Log entries, filtering to 345 authentication-relevant events across Event IDs 4624, 4625, 4634, and 4672. Detected brute-force patterns, correlated failed-to-successful logon sequences, and identified privilege escalation indicators. Mapped full attack chain to MITRE ATT&CK T1110 → T1078 → T1134.
#### Deception & Engagement
  - [Self-Adaptive Cyber Deception System - AI-Driven Honeypot](https://github.com/Eng-Shaheen/Self-Adaptive-Cyber-Deception-System)
    - Designed and deployed a fully automated cyber deception pipeline integrating Cowrie honeypot, a custom AI decision engine, and a Flask-based real-time dashboard. System processed 112 attacker events with 120ms average response latency, generating 115 unique dynamic decoy artifacts across stress tests. Mapped attacker behaviour to MITRE ATT&CK T1110, T1078, T1056, and T1083.
#### Forensics & Intelligence
  - [Wireshark Network Traffic Analysis - TCP Anomaly Detection](https://github.com/Eng-Shaheen/Wireshark-Network-Traffic-Analysis)
    - Analysed two PCAP datasets using Wireshark and tshark CLI across 202-packet and 900-packet captures. Detected 3 TCP retransmissions, 4 duplicate ACKs, and 107 RST events using targeted display filters. Validated all findings via tshark command-line - documenting cause-and-effect chain from congestion to packet loss. Zero window negative result analytically confirmed network congestion as root cause.
  - [Python IOC Parser & SOC Automation - Threat Indicator Extraction](https://github.com/Eng-Shaheen/Python-IOC-Parser)
    - Built a Python regex-based IOC extraction tool parsing raw logs for IPs, domains, MD5 and SHA256 hashes with de-duplication and frequency counting. Extended dataset extracted 2 malicious IPs, 5 suspicious domains including payload.exe and bad-malware-site.com, and 2 file hashes. Frequency delta analysis between datasets enabled immediate SOC threat prioritisation.
---
### ⚡ *Built in a lab. Ready for production.* 
