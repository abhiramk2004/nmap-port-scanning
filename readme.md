# Network Reconnaissance Report (/20 Network)

## Overview
A complete Nmap-based reconnaissance was performed on a /20 network covering 4096 IP addresses. Twelve active devices were detected, including multiple Windows and Android hosts.

## Host Breakdown
- **1 Windows 7**
- **6 Windows 11**
- **2 Android 15**
- **1 Android 14**
- **1 Android 11**
- **1 Android 13**

## Vulnerability Overview

### Windows 7
- EternalBlue (MS17-010)
- SMBv1 enabled
- RDP brute-force exposure
- Deprecated cryptographic support

### Windows 11
- SMB and WinRM exposure
- Possible weak NTLM authentication
- Open RPC ports (135, 445)
- Remote registry services enabled

### Android Devices
- Possible exposed ADB ports (5555)
- OEM debug services
- App-level vulnerabilities
- Outdated OS risks (especially Android 11)

## Files Included
- **scan_results.txt** – raw simulated Nmap output
- **Task_Report.txt** – detailed report of findings

## Notes
This simulation is intended for ethical cybersecurity learning and internal network auditing only. Never scan networks without permission.
