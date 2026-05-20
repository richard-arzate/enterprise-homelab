# Firewall Rules

This section documents the UniFi firewall policies and zone-based network segmentation implemented within the homelab environment.

Firewall rules were configured to:
- Restrict unnecessary inter-VLAN communication
- Isolate guest and IoT networks
- Protect management systems
- Control access between trusted and lab networks
- Validate segmentation and east-west traffic restrictions

## Security Objectives
- Reduce attack surface
- Implement least-privilege access controls
- Isolate untrusted devices
- Improve network visibility and control

## Technologies Used
- UniFi Zone-Based Firewall Policies
- VLAN Segmentation
- Inter-VLAN Access Control
