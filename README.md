# Nmap Security Scan Report 😃
**Target**: Local Machine (127.0.0.1)  
**Date**: $(date 2025-06-07)  

## Critical Findings
![Scan Results](https://github.com/eshan661/nmap-security-scan/blob/main/scan%20results.png)

## Vulnerable Ports
| Port | Service | Risk |
|------|---------|------|
| 135 | MSRPC | 🔴 High |
| 445 | SMB | 🔴 High |
| 5357 | WSDAPI | 🟠 Medium |
| 5432 | PostgreSQL | 🟠 Medium |

## Immediate Actions
1. Block ports 135/445 in Windows Firewall
2. Disable unused services
3. Scan regularly for open ports

## Full Results
[View Raw Scan Data](nmap_scan_results.txt)
## Demo Video  
[![Watch Demo](https://www.loom.com/share/3109805f4b834dffbd8bbdea0964bed4?sid=2fa66cec-cea7-4a70-850e-bbd380e9e765)  
