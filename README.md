<p align="center">
  <img src="assets/profile-banner.svg" alt="Sean Blue Team profile banner" width="100%" />
</p>

<h1 align="center">Hey, I'm Sean</h1>

<h3 align="center">Threat Hunter & blue team investigator</h3>

<p align="center">
  <a href="https://seanfrvr.github.io/" target="_blank"><img src="https://img.shields.io/badge/PORTFOLIO-8A6A45?style=for-the-badge&logo=githubpages&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/sean-ngwengwe-04354b3bb" target="_blank"><img src="https://img.shields.io/badge/LINKEDIN-0072B1?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

## Brief Intro

My work sits where threat hunting, detection, and incident investigation meet. I build hands on security labs that generate real telemetry, uncover security gaps, and turn suspicious activity into evidence backed investigations. That work spans SIEM analysis, endpoint telemetry, network forensics, incident response, and cloud security.

### Currently focused on

![Security+](https://img.shields.io/badge/Security%2B-In_Progress-7E57C2?style=for-the-badge&logo=comptia&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-2F81F7?style=for-the-badge&logo=microsoft&logoColor=white)

## 🔎 Featured Case Files

### 01 Network Detection & Packet Forensics

**Raw packets to detection engineering and automated triage**

Reconstructed suspicious traffic from PCAPs, correlated findings with Zeek and Suricata, identified a detection coverage gap, wrote a custom IDS rule, validated it against the same preserved evidence, and built TraceHound to automate first pass PCAP triage.

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Zeek](https://img.shields.io/badge/Zeek-2E3440?style=for-the-badge&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF6C35?style=for-the-badge&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

[Open Case File](https://github.com/Seanfrvr/Network-Detection-and-Packet-Forensics-home-lab)

### 02 Azure Identity Detection & Correlation

**Entra telemetry to a tuned Sentinel incident**

Built an Azure identity investigation around privilege assignment and user creation activity, reconstructed the sequence in KQL, converted the relationship into a scheduled Sentinel analytic rule, deployed it through the Microsoft SecurityInsights REST API, replayed fresh activity, found duplicate alerting, tuned the rule, and validated one clean alert and one incident.

![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-5E5CE6?style=for-the-badge&logo=microsoft&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-2F81F7?style=for-the-badge&logo=microsoft&logoColor=white)
![Log Analytics](https://img.shields.io/badge/Log_Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Cloud Shell](https://img.shields.io/badge/Azure_Cloud_Shell-0078D4?style=for-the-badge&logo=gnubash&logoColor=white)

[Open Case File](https://github.com/Seanfrvr/Azure-Identity-Detection-Correlation-Home-Lab)

### 03 Detection Engineering & Response

**Live endpoint telemetry through detection and SOAR response**

Built a self contained SOC lab with Sysmon, Wazuh, Atomic Red Team, Shuffle, VirusTotal and Slack. Tested credential access, persistence and PowerShell activity, investigated raw telemetry, identified detection logic gaps, recovered broken services during the work, and validated the response pipeline end to end.

![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=for-the-badge&logo=wazuh&logoColor=white)
![Sysmon](https://img.shields.io/badge/Sysmon-167DAA?style=for-the-badge&logo=windows11&logoColor=white)
![Atomic Red Team](https://img.shields.io/badge/Atomic_Red_Team-A53B32?style=for-the-badge&logo=redcanary&logoColor=white)
![Shuffle SOAR](https://img.shields.io/badge/Shuffle_SOAR-8A6A45?style=for-the-badge&logo=shuffle&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white)

[Open Case File](https://github.com/Seanfrvr/Detection-Engineering-and-Response-HL)

### 04 Threat Hunting with Splunk

**Threat hunting across endpoint, authentication and cloud logs**

Investigated encoded PowerShell activity, Linux SSH brute force behaviour and AWS CloudTrail identity activity in Splunk using BOTSv3. The work focuses on SPL construction, payload decoding, IoC handling, cloud identity analysis and evidence backed defensive recommendations.

![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![SPL](https://img.shields.io/badge/SPL-000000?style=for-the-badge&logo=splunk&logoColor=white)
![CyberChef](https://img.shields.io/badge/CyberChef-4285F4?style=for-the-badge&logo=google&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-7E2C26?style=for-the-badge&logo=mitre&logoColor=white)

[Open Case File](https://github.com/Seanfrvr/Threat-hunting-with-splunk-HL)

## 🧰 Investigation Stack

> Tools and platforms I have strong knowledge of, backed by practical use across my case files. Each project shows how I apply them during investigations.

### SIEM & Investigation

![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=for-the-badge&logo=wazuh&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-2F81F7?style=for-the-badge&logo=microsoft&logoColor=white)

### Endpoint & Detection

![Sysmon](https://img.shields.io/badge/Sysmon-167DAA?style=for-the-badge&logo=windows11&logoColor=white)
![Atomic Red Team](https://img.shields.io/badge/Atomic_Red_Team-A53B32?style=for-the-badge&logo=redcanary&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-7E2C26?style=for-the-badge&logo=mitre&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Network Detection & Forensics

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Zeek](https://img.shields.io/badge/Zeek-2E3440?style=for-the-badge&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF6C35?style=for-the-badge&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

### Cloud Security

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-5E5CE6?style=for-the-badge&logo=microsoft&logoColor=white)
![Log Analytics](https://img.shields.io/badge/Log_Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS CloudTrail](https://img.shields.io/badge/AWS_CloudTrail-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

### Response & Enrichment

![Shuffle SOAR](https://img.shields.io/badge/Shuffle_SOAR-8A6A45?style=for-the-badge&logo=shuffle&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=for-the-badge&logo=virustotal&logoColor=white)

## More Work

### Google Cloud Data Breach Incident Response

Investigated and remediated a cloud breach scenario using Security Command Center, Compute Engine, Cloud Storage and VPC Firewall. The work covered containment, hardened rebuild, storage access control, least privilege network access and PCI DSS aligned remediation.

[Open Project](https://github.com/Seanfrvr/gcp-data-breach-incident-response)

## What I care about

I care about what the evidence can actually prove. I try to separate suspicious behaviour from confirmed impact, telemetry gaps from detection gaps, and tool output from analyst conclusion. My projects are built around that mindset.

<p align="center">
  <a href="https://seanfrvr.github.io/" target="_blank"><img src="https://img.shields.io/badge/View_Portfolio-8A6A45?style=for-the-badge&logo=githubpages&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/sean-ngwengwe-04354b3bb" target="_blank"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0072B1?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>
