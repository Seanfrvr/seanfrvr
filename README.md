<div align="center">

# CASE FILE: SEAN

### Security Analyst | Threat Hunting & Detection Engineering

`STATUS: ACTIVE` &nbsp; `HANDLE: Seanfrvr` &nbsp; `CURRENT FILE: Detection Engineering & Response HL`

I build hands on security labs, investigate telemetry, and document the reasoning behind each finding. My strongest interests are threat hunting and detection engineering, with foundational cloud security knowledge across identity, logging, and infrastructure security.

<a href="https://seanfrvr.github.io/">
  <img src="https://img.shields.io/badge/OPEN_CASE_FILE-PORTFOLIO-6B4F32?style=for-the-badge&labelColor=2A2013" alt="Portfolio" />
</a>
<a href="https://www.linkedin.com/in/sean-ngwengwe-04354b3bb/">
  <img src="https://img.shields.io/badge/LinkedIn-SEAN-8A6A45?style=for-the-badge&labelColor=2A2013" alt="LinkedIn" />
</a>

</div>

---

## 01 // Current Investigation

### Detection Engineering & Response Home Lab

`ACTIVE FILE` `PRIVATE WHILE IN PROGRESS`

A live SOC lab built around real endpoint telemetry instead of sample alerts. I am using it to move beyond simply seeing detections and focus on how telemetry becomes useful detection logic and response actions.

**Current stack**

`Wazuh` `Sysmon` `Atomic Red Team` `Mimikatz` `Shuffle SOAR` `VirusTotal` `Slack`

**What I am working on**

- Generating attack telemetry through adversary emulation
- Hunting activity in Wazuh and validating what the endpoint actually recorded
- Mapping findings to MITRE ATT&CK
- Identifying detection gaps when telemetry exists but alert logic is weak
- Building automated enrichment and response workflows
- Documenting failures, troubleshooting, recovery, and investigation decisions as part of the project

> The repository will be made public when the investigation is ready to be presented as a complete case file.

---

## 02 // Closed Case File

### [Threat Hunting with Splunk Home Lab](https://github.com/Seanfrvr/Threat-hunting-with-splunk-HL)

`CLOSED` `3 INVESTIGATIONS ATTACHED`

Built a Splunk Enterprise home lab using the BOTSv3 dataset and investigated multiple attack scenarios with SPL, event correlation, payload analysis, and MITRE ATT&CK mapping. Each hunt is documented from the initial activity through the final finding and defensive recommendations.

| File | Investigation | ATT&CK |
| :--- | :--- | :--- |
| **01** | [Encoded PowerShell Execution](https://github.com/Seanfrvr/Threat-hunting-with-splunk-HL/blob/main/scenarios/scenario-1-powershell.md) | `T1059.001` `T1140` |
| **02** | [Linux SSH Brute Force](https://github.com/Seanfrvr/Threat-hunting-with-splunk-HL/blob/main/scenarios/scenario-2-ssh-bruteforce.md) | `T1110.001` `T1087` |
| **03** | [AWS CloudTrail S3 Exposure](https://github.com/Seanfrvr/Threat-hunting-with-splunk-HL/blob/main/scenarios/scenario-3-aws-cloudtrail.md) | `T1078` `T1530` |

**Evidence demonstrated**

`Splunk` `BOTSv3` `CyberChef` `VirusTotal` `Windows Logs` `Linux Authentication Logs` `AWS CloudTrail` `MITRE ATT&CK`

---

## 03 // Investigation Toolkit

**Investigation & SIEM**  
`Splunk` `Wazuh` `Sysmon` `Wireshark` `Linux`

**Detection & Response**  
`Atomic Red Team` `MITRE ATT&CK` `Shuffle SOAR` `VirusTotal`

**Cloud Security Foundations**  
`AWS CloudTrail` `IAM` `Google Cloud` `Terraform`

---

## 04 // How I Work

```text
BUILD THE LAB
     ↓
GENERATE OR INGEST TELEMETRY
     ↓
HUNT THE ACTIVITY
     ↓
VALIDATE THE EVIDENCE
     ↓
MAP THE BEHAVIOR
     ↓
IDENTIFY DETECTION GAPS
     ↓
DOCUMENT THE INVESTIGATION
```

I prefer projects that show the investigation process rather than a finished screenshot with no explanation. The goal is to make it clear what I observed, why I pivoted, what the evidence supported, and what I would improve defensively.

---

<div align="center">

### CASE FILE INDEX

[Portfolio](https://seanfrvr.github.io/) · [Threat Hunting with Splunk](https://github.com/Seanfrvr/Threat-hunting-with-splunk-HL) · [LinkedIn](https://www.linkedin.com/in/sean-ngwengwe-04354b3bb/)

`Threat Hunting` `Detection Engineering` `Security Operations` `Cloud Security Foundations`

</div>
