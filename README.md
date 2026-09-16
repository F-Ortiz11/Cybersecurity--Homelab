# Cybersecurity-Homelab

## Current Architecture

| System | Role | IP Address |
|---|---|---|
| QE-DC01 | Windows Server / Domain Controller / DNS | 192.168.154.10 |
| QE-WIN11-01 | Windows 11 Domain Workstation | 192.168.154.20 |
| VMware NAT Gateway | Internet Gateway | 192.168.154.2 |

## Active Directory

Domain:

`quantumedge.local`

Current services:

- Active Directory Domain Services
- DNS
- Centralized user authentication
- Domain-joined Windows workstation

## Lab Objectives

- Deploy and administer Active Directory
- Use appropriate ISOs (Virtual Disk) for OS installation 
- Configure DNS and TCP/IP networking
- Manage users, groups, and permissions
- Implement Group Policy
- Deploy pfSense firewalling and segmentation
- Implement centralized logging with Wazuh
- Perform controlled security testing
- Automate administrative and security tasks with Python

## Current Progress

- [x] Windows Server VM deployed
- [x] VMware Tools installed
- [x] Static IP configured
- [x] Active Directory Domain Services installed
- [x] DNS Server installed
- [x] New AD forest created
- [x] Domain Controller deployed
- [x] Windows 11 client deployed
- [x] Windows 11 client joined to domain
- [ ] Create users and security groups
- [ ] Configure Organizational Units
- [ ] Configure Group Policy
- [ ] Deploy pfSense
- [ ] Deploy Wazuh
- [ ] Add Ubuntu
- [ ] Add Kali Linux
