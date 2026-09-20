# Proxmox Infrastructure & Security Homelab

A hands-on home lab built on Proxmox to develop practical skills across infrastructure, cloud fundamentals, Windows/Linux administration, networking, monitoring, automation, and cyber security.

The lab is designed to simulate a small business environment where I can build, troubleshoot, monitor, and secure systems rather than only follow guided labs.

## Lab Environment

- Proxmox VE hypervisor
- WAZUH01: Ubuntu Server running Wazuh Manager, Indexer, and Dashboard
- CLIENT01: Windows 11 endpoint
- DNS01: DNS services
- MON01: Monitoring services
- Additional Windows/Linux systems added as the environment develops

## Skills Practised

### Infrastructure & Systems Administration
- Virtual machine and container deployment
- Linux and Windows administration
- Virtual networking
- DNS configuration
- Storage and resource management
- VM troubleshooting
- Performance and capacity management

### Security & SOC
- SIEM deployment and administration with Wazuh
- Endpoint monitoring
- Windows Security log collection
- Authentication monitoring
- Threat hunting
- Alert investigation
- Vulnerability monitoring
- File integrity monitoring
- Incident troubleshooting

### Cloud & DevOps Foundations
- Infrastructure documentation
- Git and GitHub version control
- Configuration management concepts
- Automation workflows
- Monitoring and observability
- CI/CD and infrastructure-as-code planned for future development

## Current Projects

- Deployed an all-in-one Wazuh SIEM server on Ubuntu
- Enrolled Windows endpoints into Wazuh
- Collected and analysed Windows Security events
- Generated controlled failed-logon activity and validated detection in Wazuh
- Investigated storage exhaustion affecting Wazuh services
- Diagnosed Proxmox OOM events terminating a virtual machine
- Rebalanced VM and container memory allocation to improve stability
- Built Windows 11 virtual endpoints using Proxmox, VirtIO, TPM, and UEFI
- Configured supporting DNS and monitoring services

## Planned Development

- Active Directory domain lab
- Sysmon telemetry
- File Integrity Monitoring
- Microsoft Defender event analysis
- Custom Wazuh detection rules
- Incident investigation write-ups
- Firewall and network segmentation
- Infrastructure automation
- GitHub Actions
- Terraform
- Ansible
- Azure/AWS integration
- Centralised logging and monitoring

## Repository Structure

- `architecture/`: lab diagrams and topology
- `proxmox/`: virtualisation and infrastructure
- `wazuh/`: SIEM configuration and monitoring
- `windows/`: Windows endpoint configuration
- `detections/`: security detections and investigations
- `troubleshooting/`: technical incidents and fixes
- `screenshots/`: sanitised evidence from the lab

## Purpose

The aim of this lab is to build practical experience that supports roles across:

- SOC / Cyber Security
- Cloud Engineering
- Infrastructure
- Systems Administration
- DevOps
- Technical Support