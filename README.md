Automated-SOC-Architecture-Wazuh-Shuffle-Suricata
A comprehensive, end-to-end Automated Security Operations Center (SOC) framework. This project integrates Wazuh (SIEM/XDR), Shuffle (SOAR), and Suricata (IDS) to automate threat detection, indicator enrichment via external APIs, and active incident response.
Project Overview:
This repository documents the architecture and deployment of a fully automated SOC environment designed to minimize Time to Respond (TTR). By leveraging open-source tools and API integrations, the system identifies malicious activity and executes defensive playbooks without manual intervention.

Key Features:
SIEM/XDR Integration: Centralized log management and event correlation using Wazuh. 
Network Defense: Real-time network traffic analysis and alert generation with Suricata.
SOAR Workflows: Automated incident orchestration using Shuffle to connect security tools.
Threat Intelligence Enrichment: Automated IOC lookups using VirusTotal and AbuseIPDB APIs.
Active Response: Automatic IP blocking (iptables) and host-level containment (PowerShell/Bash) for threats like SSH brute-forcing and malware execution.
Tech StackWazuh: Detection and Endpoint Security.
Suricata: Network Intrusion Detection (IDS).
Shuffle: Security Orchestration, Automation, and Response (SOAR).
Operating Systems: Windows Server 2022, Bodhi Linux (Ubuntu-based).
Languages: PowerShell, Bash, Python (for custom API hooks).DocumentationThe full technical breakdown, including architecture diagrams and step-by-step implementation details, is available in the uploaded pdf.
