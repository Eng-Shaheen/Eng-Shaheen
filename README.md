## Cybersecurity Portfolio
This portfolio demonstrates practical cybersecurity skills across SOC operations, threat detection, network forensics, and threat intelligence automation. Each project focuses on real-world defensive security techniques aligned with enterprise SOC workflows and MITRE ATT&CK mapping.

---
#### Detection & Response
 - [Splunk SIEM Log Triage with MITRE ATT&CK Mapping](https://github.com/Eng-Shaheen/Splunk-log-triage-lab)
    - Built 15+ custom SPL detection queries in Splunk to identify brute-force, credential compromise, and lateral movement patterns from SSH authentication logs. Tuned correlation rules reducing false-positives by 35%. Mapped attacker behaviour to MITRE ATT&CK T1110 → T1078 → T1021.004 with full incident timeline reconstruction.
 - [Windows Authentication Security Analysis](https://github.com/Eng-Shaheen/Windows-Authentication-Security-Analysis)
    - Triaged 32,678 Windows Security Event Log entries, filtering to 345 authentication-relevant events across Event IDs 4624, 4625, 4634, and 4672. Detected brute-force patterns, correlated failed-to-successful logon sequences, and identified privilege escalation indicators. Mapped full attack chain to MITRE ATT&CK T1110 → T1078 → T1134.
#### Deception & Engagement
  - [Self Adaptive Cyber Deception System](https://github.com/Eng-Shaheen/Self-Adaptive-Cyber-Deception-System)
    - Designed and deployed a fully automated cyber deception pipeline integrating Cowrie honeypot, a custom AI decision engine, and a Flask-based real-time dashboard. System processed 112 attacker events with 120ms average response latency, generating 115 unique dynamic decoy artifacts across stress tests. Mapped attacker behaviour to MITRE ATT&CK T1110, T1078, T1056, and T1083.
#### Forensics & Intelligence
  - [Wireshark Network Traffic Analysis](https://github.com/Eng-Shaheen/Wireshark-Network-Traffic-Analysis)
    - Performed packet-level analysis of TCP/UDP traffic to identify anomalies such as retransmissions, congestion, and abnormal communication patterns.
  - [Python IOC Parser](https://github.com/Eng-Shaheen/Python-IOC-Parser)
    - Developed a Python tool to extract IPs, domains, and hashes from log datasets, enabling structured threat intelligence for SOC triage workflows.
---
### ⚡ *Translating raw security data into actionable detection and response capabilities.* 
