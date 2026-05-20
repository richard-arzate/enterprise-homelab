# Enterprise Homelab Project

## Overview

This repository documents the design, implementation, and security hardening of an enterprise-style homelab environment built for hands-on IT administration, networking, virtualization, and cybersecurity training.

## Project Purpose

This homelab was built to simulate a small enterprise IT and cybersecurity environment. The goal was to gain hands-on experience with systems administration, network segmentation, firewall configuration, Active Directory, virtualization, vulnerability scanning, and security validation.

This project supports entry-level IT, help desk, systems administration, network support, SOC analyst, and cybersecurity analyst career preparation.

The project simulates a segmented enterprise environment using:

- Active Directory
- VLAN segmentation
- Zone-based firewalling
- Windows Server administration
- Linux systems administration
- Vulnerability assessment
- Virtualization
- DNS management
- Network discovery and enumeration

---

## Environment Preview

### Active Directory Environment

![Active Directory](active-directory/DC01%20Users%3AEmployees%20Screenshot.png)

### Vulnerability Scanning

![Nessus Scan](vulnerability-scanning/Nessus%20My%20Basic%20Network%20Scan%20Screenshot.png)

### Kali Linux Enumeration

![Kali Enumeration](vulnerability-scanning/Kali%20Linux%20nmap%20Scan%20Screenshot.png)

---

## Infrastructure Overview

### Hypervisor
- Proxmox VE

### Virtual Machines
- Windows Server 2022 (DC01)
- Windows 11 Pro Client VM
- Kali Linux VM
- Windows 11 Main Workstation VM

### Networking Stack
- UniFi Dream Machine Pro Max
- UniFi Switch Pro Max 24 PoE
- UniFi U7 Pro Max

### Security Tools
- Nessus Essentials
- Nmap
- Windows Defender Firewall
- UniFi Zone-Based Firewall Policies

---

## Repository Sections

| Section | Description |
|---|---|
| active-directory | Active Directory deployment, users, groups, DNS, and Group Policy |
| firewall-rules | UniFi firewall policies and inter-VLAN access control |
| network-segmentation | VLAN architecture and segmented network design |
| virtualization | Proxmox virtualization infrastructure and virtual machines |
| vulnerability-scanning | Nessus and Nmap enumeration and vulnerability assessment |
| diagrams | Network diagrams and infrastructure visuals |

Each section contains documentation, screenshots, and configuration examples related to that specific area of the homelab environment.

---

## VLAN Architecture

| VLAN | Purpose | Subnet |
|---|---|---|
| 10 | Management | 10.10.10.0/29 |
| 20 | Trusted | 10.10.20.0/25 |
| 30 | Work | 10.10.30.0/29 |
| 40 | IoT | 10.10.40.0/26 |
| 50 | Gaming | 10.10.50.0/29 |
| 60 | Lab | 10.10.60.0/24 |
| 70 | Guest | 10.10.70.0/25 |
| 80 | Printer | 10.10.80.0/29 |

---

## Key Features

### Active Directory
- Organizational Units (OUs)
- Security Groups
- User Management
- Administrative Delegation
- Group Policy Management

### Network Segmentation
- Zone-based firewall architecture
- Inter-VLAN isolation
- Trusted-to-management access controls
- Guest and IoT isolation

### Vulnerability Management
- Nessus vulnerability scanning
- Host discovery scans
- Internal network enumeration
- Nmap service discovery

### Virtualization
- Multi-VM enterprise lab environment
- VLAN-aware virtual networking
- Isolated lab infrastructure

---

## Screenshots

### UniFi Network Overview
![UniFi Overview](screenshots/UniFi%20WiFi,%20Networks,%20and%20Internet%20GUI.png)

---

### UniFi Topology View
![UniFi Topology](screenshots/UniFi%20Topology%20View%20Screenshot.png)

---

### UniFi Zone Matrix
![Zone Matrix](screenshots/UniFi%20Zone%20Matrix%201%3A2%20Screenshot.png)

---

### Active Directory Users and Organizational Units
![AD Users](screenshots/DC01%20Users%3AEmployees%20Screenshot.png)

---

### Active Directory Security Groups
![AD Groups](screenshots/DC01%20Groups%20Screenshot.png)

---

### Group Policy Restrictions
![GPO](screenshots/DC01%20Baseline%20User%20Restrictions%20Screenshot.png)

---

### DNS Manager
![DNS](screenshots/AD%20DNS%20Screenshot.png)

---

### Firewall Policies
![Firewall Rules](screenshots/Firewall%20Rules%201%3A2%20Screenshot.png)

---

### Kali Linux Enumeration
![Nmap Scan](screenshots/Kali%20Linux%20nmap%20Scan%20Screenshot.png)

---

### Nessus Vulnerability Scanning
![Nessus](screenshots/Nessus%20My%20Basic%20Network%20Scan%20Screenshot.png)

---

## Skills Demonstrated

- Active Directory Administration
- Windows Server Administration
- Linux Administration
- VLAN Configuration
- Firewall Policy Management
- Network Segmentation
- Vulnerability Assessment
- DNS Administration
- Virtualization
- Enterprise Networking
- Troubleshooting
- Security Hardening

---

## Future Improvements

- SIEM integration
- Windows event forwarding
- Sysmon deployment
- ELK stack integration
- IDS/IPS monitoring
- Automated vulnerability reporting
- Active Directory attack simulations
