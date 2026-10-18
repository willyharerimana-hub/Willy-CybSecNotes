# Cyber Security Journal

## Day 1 - LetsDefend Log Analysis
Analyzed suspicious login attempts from Tor Exit Node.

### 1. Raw Log Detection
![Raw Log](screenshots/raw-log-analysis-letsdefend.png)
Found brute force: Failed password for invalid user admin from 192.168.1.45

### 2. Investigation - Source IP Analysis
![Source IP](screenshots/source-ip-analysis.png)
- Q1: Source IP 193.161.85.64 accessed malicious URL
- Q2: DNS log with port 443

**Skills:** Log Analysis, Threat Hunting, SIEM
