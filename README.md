# Penetration Testing Report – Metasploitable2

## Overview
This repository contains a complete Vulnerability Assessment and Penetration Testing (VA/PT) project performed on a Metasploitable2 virtual machine in a controlled lab environment.

The project demonstrates the full penetration testing lifecycle:
- Vulnerability Assessment
- Manual Validation
- Exploitation
- Impact Analysis
- Remediation Recommendations

## Target Environment
- Target: Metasploitable2 Virtual Machine
- Network Mode: Host-Only
- Authorization: Academic and skill development purposes only

## Tools Used
- Nessus Essentials – Vulnerability Assessment
- Nmap – Service Enumeration and Validation
- Metasploit Framework – Exploitation
- Kali Linux – Attacker Platform

## Key Findings
- Multiple critical vulnerabilities identified using Nessus
- Manual validation confirmed vulnerable services
- Successful exploitation of vsFTPd 2.3.4 resulted in root-level access

## Exploitation Summary
- Vulnerable Service: FTP (vsFTPd 2.3.4)
- Port: 21/tcp
- Result: Remote root shell obtained using Metasploit

## Repository Structure
- `Report/` – Final penetration testing report (PDF & DOCX)
- `Screenshots/` – Evidence screenshots
- `Tools_Used/` – Commands used during assessment
- `Scope_and_Disclaimer.md` – Legal and ethical disclaimer

## Disclaimer
This project was conducted in a controlled lab environment. The techniques demonstrated here are strictly for educational purposes. Unauthorized testing of systems without permission is illegal.

## Author
**Lokeshwar V**  
Cybersecurity Enthusiast | SOC Analyst Aspirant
