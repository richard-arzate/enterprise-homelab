# Enterprise IT & Cybersecurity Homelab

## Overview
This project documents the design, implementation, and management of an enterprise-style homelab environment built for hands-on IT administration, networking, virtualization, and cybersecurity training.

The lab was designed to strengthen practical skills in:
- Systems administration
- Active Directory management
- Network segmentation
- Virtualization
- Firewall configuration
- Vulnerability scanning
- Network troubleshooting
- Security analysis

---

## Technologies Used

### Networking & Infrastructure
- UniFi Ecosystem
- UniFi Dream Machine Pro Max
- UniFi Switching
- UniFi Wireless Access Point
- VLAN Segmentation
- Firewall Policies
- TCP/IP
- DNS
- DHCP

### Virtualization
- Proxmox VE

### Operating Systems
- Windows Server
- Windows 11 Pro
- Kali Linux

### Security & Monitoring
- Nessus
- Wireshark
- Nmap
- Vulnerability Scanning
- Penetration Testing
- Traffic Analysis

### Directory Services
- Active Directory
- User and Group Management
- Access Control

---

## Environment Overview

This homelab was built to simulate a small enterprise IT and cybersecurity environment for hands-on learning and security testing.

The environment includes:
- UniFi networking infrastructure with VLAN segmentation and firewall policies
- Wireless and wired network isolation for Trusted, Guest, IoT, Work, Lab, and Management networks
- Proxmox virtualization hosting multiple Windows and Linux virtual machines
- A Windows Server Active Directory environment for user and group administration
- Windows 11 virtual machines simulating endpoint systems and administrative workstations
- A Kali Linux virtual machine used for penetration testing and network analysis within the isolated lab environment
- Vulnerability scanning and monitoring using Nessus and Wireshark

---

## Network Architecture

### VLAN Segmentation
The network environment is segmented into multiple VLANs to improve security, isolation, and management.

Configured networks include:
- Management Network
- Trusted Network
- Work Network
- Guest Network
- IoT Network
- Lab Network
- Gaming Network
- Printer Network

### Firewall Configuration
Firewall rules were implemented to:
- Restrict unnecessary inter-VLAN communication
- Isolate insecure or untrusted devices
- Control access between lab and production-style networks
- Improve overall network security posture
- Monitor and validate network traffic behavior

---

## Virtual Machines

### Windows Server
Used to simulate enterprise infrastructure services including:
- Active Directory
- User and Group Management
- Administrative management and configuration
- Access Control testing

### Windows 11 Pro (Lab Endpoint System)
Used within the Lab network to simulate enterprise user workstations for:
- User and administrator account testing
- Active Directory connectivity and administration
- Network connectivity validation
- Access control and permissions testing
- Enterprise-style workstation and user environment simulation

### Windows 11 Pro (Main Workstation)
Used as a primary workstation on the Trusted network for:
- Studying IT and cybersecurity concepts
- Accessing the UniFi management interface
- Managing VLANs and firewall configurations
- Watching training and troubleshooting content
- Running Nessus vulnerability scans
- General day-to-day workstation usage

### Kali Linux
Used within the isolated lab environment for:
- Network analysis
- Vulnerability assessment
- Penetration testing
- Security validation
- Firewall and segmentation testing

---

## Security Configuration
Security-focused configurations implemented within the environment include:
- Inter-VLAN firewall rules
- Network isolation policies
- Vulnerability scanning workflows
- Segmentation testing
- Traffic monitoring and analysis
- Administrative access control

---

## Skills Demonstrated
- Systems Administration
- Active Directory Administration
- Network Troubleshooting
- VLAN Configuration
- Firewall Configuration
- Virtualization Management
- Vulnerability Assessment
- Technical Documentation
- Security Analysis
- Network Segmentation

---

## Future Improvements
Planned future improvements include:
- Expanding the Active Directory environment
- Adding centralized logging and monitoring
- Implementing SIEM and security monitoring tools
- Expanding vulnerability scanning and security testing workflows
- Implementing backup and recovery solutions
- Additional firewall hardening and network security improvements
- Expanding virtualization and lab infrastructure

---

## Author
Richard Roman Arzate
