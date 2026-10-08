# Windows Incident Response Investigation

## Project Overview

This project demonstrates a practical Windows-based incident response investigation using built-in PowerShell commands and Windows security logs.

The investigation focused on collecting and analysing system information, running processes, network connections, startup applications, Windows Event Logs and Windows Defender events.

## Objectives

* Collect Windows system information
* Analyse running processes
* Review active network connections
* Investigate startup applications
* Review Windows System Event Logs
* Analyse Windows Defender operational events
* Identify potential indicators of compromise
* Document findings and risk assessment

## Tools Used

* Windows PowerShell
* Windows Event Viewer / Event Logs
* Windows Defender
* Get-Process
* Get-NetTCPConnection
* Get-CimInstance
* Get-WinEvent
* PowerShell system-information commands

## Investigation Process

1. System information collection
2. Running process analysis
3. Network connection analysis
4. Startup program analysis
5. Windows System Event Log review
6. Windows Defender event review
7. Evidence documentation
8. Risk assessment and final incident assessment

## Key Findings

The investigation identified several legitimate Windows and third-party applications.

A local loopback connection associated with 3CXSoftphone was identified and assessed as low concern because the communication occurred between 127.0.0.1 addresses.

AnyDesk was identified as a startup application. Because remote-access software can potentially be abused, it was flagged for verification rather than classified as malicious.

No confirmed indicators of compromise were identified from the available evidence.

## Risk Assessment

**Overall Risk: LOW**

The available evidence did not provide sufficient information to confirm that the system had been compromised.

## Evidence Collected

* System information screenshot
* Running process analysis
* Network connection analysis
* Startup program analysis
* System event timeline
* Windows Defender event analysis
* Incident response report

## Skills Demonstrated

* Incident Response
* Windows Security
* PowerShell
* Process Analysis
* Network Analysis
* Event Log Analysis
* Security Monitoring
* Evidence Collection
* IOC Identification
* Risk Assessment
* Security Documentation

## Disclaimer

This project was performed for educational and portfolio purposes on a Windows system. No unauthorized access or malicious activity was performed.
