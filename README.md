# CodeAlpha_Task-4
# Task 4: Network Intrusion Detection System (IDS) using Suricata

This project sets up Suricata IDS on Windows with custom rules to detect suspicious network traffic.

## Files Included
- `suricata.yaml` – Suricata configuration file
- `emerging-all.rules` – Custom rules file with alerts for ICMP, HTTP, DNS, etc.
- `fast.log` – Sample alert log file (includes simulated alerts)
- `screenshots/` – Evidence of setup and testing (interface list, ping test, alerts)
- `README.md` – This file

## Setup Overview
- Installed Suricata 7.0.10 MSI on Windows
- Configured Suricata to use custom rules
- Created rules to detect ICMP ping, suspicious HTTP user agents, DNS queries, and port scans
- Tested using ping and sample traffic
- Collected logs and screenshots for documentation

---
