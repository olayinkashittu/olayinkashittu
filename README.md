# IT Support & System Administration Portfolio

![GitHub last commit](https://img.shields.io/github/last-commit/olayinkashittu/it-support-portfolio)
![GitHub repo size](https://img.shields.io/github/last-commit/olayinkashittu/it-support-portfolio)
![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)

## 👨‍💻 Overview
Dedicated IT Support Administrator and Network Support professional with experience supporting enterprise IT infrastructure, users, and network environments. Skilled in Cisco networking, LAN/WAN support, TCP/IP, routing and switching, Windows Server administration, Active Directory, Microsoft 365, VPN connectivity, DHCP, DNS, and IT service management. Strong troubleshooting and customer support abilities with a commitment to maintaining highly available and secure IT systems.

# Hi, I'm @olayinkashittu
I am an IT Support Administrator with hands-on experience in managing IT systems, supporting network infrastructure, and troubleshooting hardware.
Resolving incidents efficiently, and providing high-quality technical support to end users to ensure minimal downtime and improved productivity.

- Professional Summary
I have practical experience working with Windows and Linux operating systems, configuring and maintaining network environments (TCP/IP, LAN/WAN), and managing user access and permissions through directory services.
I am proficient in IT service desk operations using tools such as Jira, where I handle incident tracking, service requests, and workflow management to ensure efficient resolution of technical issues.
My goal is to contribute to IT teams by delivering reliable technical support, improving system performance, and ensuring smooth IT operations.

## Skills
- Cisco IOS
- Routing & Switching
- LAN/WAN
- IPv4
- IPv6
- VLANs
- STP
- EtherChannel
- VPN
- DHCP
- DNS
- NAT
- TCP/IP
- Wireless Networking
- Operating Systems
- Windows 10/11
- Windows Server 2016/2019/2022
- Linux
- Microsoft Technologies
- Active Directory
- Group Policy
- Microsoft 365
- Entra ID
- Monitoring & Tools
- Cisco Packet Tracer
- Wireshark
- Remote Desktop
- TeamViewer
- PowerShell
- Azure
- Hardware & Software Support
  
TCP/IP configuration and troubleshooting
LAN/WAN fundamentals
Basic routing and switching concepts
Network diagnostics and connectivity support
- IT Support & Tools
Helpdesk & ticketing systems Jira Service Management
Incident and request management
Remote user support
Troubleshooting hardware and software issues
- Directory & Access Management
User account creation and management
Password resets and permission management

Projects & Practical Work

# Windows Server 2022 Active Directory Lab

![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-blue)
![Active Directory](https://img.shields.io/badge/Active%20Directory-AD%20DS-green)
![PowerShell](https://img.shields.io/badge/PowerShell-Administration-blue)
![VirtualBox](https://img.shields.io/badge/VirtualBox-Virtualization-orange)

## Project Overview

This project demonstrates the deployment and administration of a Windows Server 2022 Active Directory environment using Oracle VirtualBox.

The lab simulates a small enterprise IT infrastructure and provides hands-on experience in Windows Server administration, Active Directory Domain Services (AD DS), DNS, organizational units, user and group management, networking, PowerShell administration, and system verification.

## Lab Objectives

- Deploy Windows Server 2022 in a virtualized environment
- Configure a Domain Controller
- Install and configure Active Directory Domain Services
- Create the `lab.local` Active Directory domain
- Configure Organizational Units (OUs)
- Create and manage users and security groups
- Configure DNS services
- Use PowerShell for administrative tasks
- Test and verify Active Directory functionality
- Document the complete implementation process

## Lab Environment

| Component | Configuration |
|---|---|
| Operating System | Windows Server 2022 |
| Server Name | DC01 |
| Domain | lab.local |
| Server Role | Domain Controller |
| Virtualization | Oracle VirtualBox |
| IPv4 Address | 10.0.2.15 |
| Active Directory | AD DS |
| DNS | Windows DNS |
| Administrative Tool | PowerShell |

## Lab Architecture

```text
                    Internet
                       |
                   VirtualBox
                       |
                      DC01
              Windows Server 2022
                       |
                   10.0.2.15
                       |
                   lab.local
                       |
              +--------+--------+
              |                 |
             IT              IT-Admins
              |
             jdoe

``
lab.local
│
└── IT
    ├── jdoe
    └── IT-Admins
