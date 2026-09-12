# Home SOC Lab

## Overview

This project demonstrates a Windows-based SOC home lab built to practice security monitoring, threat detection, and incident investigation.

The lab uses **Splunk Enterprise** as the SIEM and **Sysmon** for detailed Windows endpoint logging. A **Kali Linux VM** is also used to simulate network reconnaissance against the Windows endpoint.

The project includes five detection scenarios:

1. Windows Reconnaissance Detection
2. Suspicious PowerShell Detection
3. Persistence Detection
4. Suspicious File Execution Detection
5. Network Reconnaissance Detection using Nmap

## Lab Environment

- Windows 10 VM — Monitored endpoint
- Kali Linux VM — Attack simulation
- Splunk Enterprise — SIEM and log analysis
- Sysmon — Windows endpoint telemetry
- Nmap — Network reconnaissance
- Oracle VirtualBox — Virtualization platform
