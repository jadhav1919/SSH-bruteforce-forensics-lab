# SSH Brute-Force Forensics Lab

> End-to-end SSH brute-force attack simulation, evidence collection, packet analysis, and forensic investigation in an isolated virtual lab.

---

## Overview

This project demonstrates the complete lifecycle of an SSH authentication attack in a controlled lab environment. It begins with reconnaissance and password attacks, followed by successful SSH authentication, evidence collection, packet analysis, log analysis, and concludes with a forensic investigation report.

The lab is intended for cybersecurity students, penetration testers, and digital forensics learners who want practical experience with both offensive and defensive security techniques.

---

## Objectives

- Perform SSH reconnaissance and enumeration.
- Generate custom password wordlists.
- Simulate SSH brute-force attacks.
- Gain authorized SSH access using test credentials.
- Simulate secure file transfer.
- Capture network traffic.
- Collect authentication logs.
- Analyze packets and system logs.
- Produce a forensic investigation report.

---

## Lab Environment

| Component | Description |
|-----------|-------------|
| Attacker Machine | Kali Linux |
| Target Machine | Parrot Security OS |
| Protocol | SSH |
| Network | Isolated Virtual Lab |

---

## Tools Used

### Reconnaissance

- Nmap
- Masscan
- RustScan
- Hping3

### Password Attacks

- Crunch
- Hydra
- CUPP
- CeWL
- Metasploit Framework

### SSH Access

- OpenSSH
- SSHPass
- SCP
- Rsync

### Evidence Collection & Analysis

- tcpdump
- tshark
- Wireshark
- journalctl
- last
- lastb
- sha256sum

---

## Project Workflow

```text
Reconnaissance
      │
      ▼
SSH Enumeration
      │
      ▼
Password Wordlist Generation
      │
      ▼
SSH Brute-Force Attack
      │
      ▼
Successful SSH Login
      │
      ▼
File Transfer (SCP / Rsync)
      │
      ▼
Packet Capture
      │
      ▼
Log Collection
      │
      ▼
Packet & Log Analysis
      │
      ▼
Forensic Investigation Report
```

---

## Repository Contents

| File | Description |
|------|-------------|
| 01-Recon-and-SSH-Preparation.pdf | Reconnaissance, enumeration, and attack preparation |
| 02-SSH-Attack-and-Evidence.pdf | SSH attack execution and evidence collection |
| 03-SSH-Packet-and-Log-Analysis.pdf | Packet and log analysis |
| 04-SSH-Forensic-Report.pdf | Complete forensic investigation report |


## Learning Outcomes

After completing this project you will understand:

- How attackers identify SSH services.
- How password attacks are performed.
- How SSH authentication works.
- How to capture and analyze network traffic.
- How to examine Linux authentication logs.
- How to correlate network and host evidence.
- How to document a forensic investigation.

## Disclaimer

This project was created solely for educational purposes inside an isolated virtual lab environment. All attacks were performed against machines owned and controlled by the author. Do not perform these techniques against systems without explicit authorization.


## Author

**Jadhav Sai**

B.Tech Computer Science (Cybersecurity)

GitHub: https://github.com/jadhav1919
