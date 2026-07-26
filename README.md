# SOC Investigation Lab Using Nmap and Wireshark

## Overview

This project demonstrates a basic Security Operations Center (SOC) investigation workflow inside a controlled virtual environment.

The project focuses on network reconnaissance, service enumeration, vulnerability identification, packet analysis, and security reporting.

---

## Lab Environment

- Kali Linux (Attacker Machine)
- Metasploitable 2 (Target Machine)
- VMware Workstation

---

## Tools Used

- Nmap
- Wireshark
- Netstat
- FTP Client
- SSH

---

## Project Activities

### 1. Network Connectivity Testing
- Verified communication using ICMP ping.

### 2. Service Enumeration
- Used Nmap to identify open ports and running services.

### 3. Operating System Detection
- Performed OS fingerprinting using Nmap.

### 4. Vulnerability Assessment
- Used Nmap NSE scripts to identify security weaknesses.

### 5. FTP Security Investigation
- Tested anonymous FTP access.

### 6. SSH Security Analysis
- Investigated SSH accessibility and configuration.

### 7. Packet Analysis
- Analysed ICMP, SYN, SYN/ACK and RST packets using Wireshark.

---

## Key Findings

- Anonymous FTP login enabled
- Weak SSH configurations
- Multiple exposed services
- Outdated system components

---

## Skills Developed

- Network scanning
- Vulnerability assessment
- Linux administration
- Packet analysis
- Security documentation
- SOC investigation workflow

---

## Disclaimer

This project was performed in an isolated virtual lab environment for educational purposes only.
