# Wazuh-Windows-SOC-Lab
SOC L1 Home Lab for Windows Endpoint Threat Detection  &amp;  Incident Investigation using Wazuh, Sysmon, and Kali Linux.

# Windows Endpoint Threat Detection & Incident Investigation using Wazuh

This project demonstrates a practical SOC L1 workflow for detecting, investigating, and responding to suspicious activity on a Windows endpoint using Wazuh SIEM, Sysmon, and Kali Linux.

The lab is designed to simulate real-world SOC operations, including log collection, security event monitoring, alert analysis, attack simulation, IOC investigation, MITRE ATT&CK mapping, and incident documentation.

## 📌 1. Project Overview

This project demonstrates how a SOC L1 Analyst can:

- Monitor Windows endpoint security events
- Collect and analyze Windows Event Logs
- Use Sysmon for enhanced endpoint visibility
- Detect suspicious activities through Wazuh
- Investigate security alerts
- Analyze IPs, files, and other indicators of compromise
- Map detected activity to MITRE ATT&CK
- Document incidents and recommend remediation
- Validate SIEM detections through controlled attack simulations

## 🖥️ 2. Lab Environment

The lab consists of:

- Ubuntu Server → Wazuh Manager, Wazuh Indexer & Wazuh Dashboard
- Windows 11 Host → Wazuh Agent + Sysmon
- Kali Linux → Attack Simulation
- Wazuh → SIEM / Security Monitoring
- Sysmon → Endpoint Telemetry

## 🛠️ 3. Tools & Technologies

- Wazuh 4.14.7
- Sysmon
- Windows 11
- Ubuntu Server
- Kali Linux
- Wireshark
- VirusTotal
- MITRE ATT&CK

## 🏗️ 4. Lab Architecture

[Architecture diagram will be added here]

## 🚨 5. Detection Use Cases

### 5.1 Brute Force / Failed Login Detection
- Windows Event ID 4625
- Wazuh alert analysis
- Source IP investigation
- MITRE ATT&CK mapping

### 5.2 Suspicious PowerShell Activity
- Sysmon Process Creation
- PowerShell command-line analysis
- Wazuh detection

### 5.3 Suspicious File Creation
- Sysmon Event ID 11
- File path analysis
- Hash / IOC investigation

### 5.4 Suspicious Network Activity
- Sysmon network telemetry
- Destination IP analysis
- IOC investigation

## 🔎 6. Incident Investigation

Each detected incident is investigated using a SOC L1 workflow:

Detection → Triage → Investigation → IOC Analysis → MITRE Mapping → Severity Assessment → Recommended Response

## 📊 7. Evidence

Screenshots and supporting evidence are organized by individual incidents.

## 📝 8. Incident Reports

Detailed incident investigation reports are maintained for each detection scenario.

## 🎯 9. Skills Demonstrated

- SIEM Monitoring
- Log Analysis
- Windows Event Log Analysis
- Sysmon Analysis
- Alert Triage
- IOC Investigation
- MITRE ATT&CK
- Incident Documentation
- Basic Incident Response
- Network Security Monitoring

## 📚 10. Learning Outcome

This project demonstrates practical SOC L1 skills through a controlled home lab environment and simulated security incidents.
