# 🖥️ Enterprise IT Support & Active Directory Lab

![Status](https://img.shields.io/badge/status-complete-success)
![Platform](https://img.shields.io/badge/platform-VirtualBox-blue)
![Server](https://img.shields.io/badge/server-Windows%202022-blue)
![Client](https://img.shields.io/badge/client-Windows%2010-blue)

> **Professional IT support laboratory demonstrating Active Directory administration, help desk operations, remote support, systematic troubleshooting, MS Office365 skills and hardware troubleshooting.**

**Portfolio Project by Piyush Arora**
[LinkedIn Profile](https://www.linkedin.com/in/piyush-arora07) | piyusharora480@gmail.com

---

## 📊 Quick Stats

| Component | Details |
|-----------|---------|
| **Domain Controller** | Windows Server 2022 |
| **Client Workstations** | Windows 10 Pro |
| **Domain** | companylab.local |
| **Documented Scenarios** | 11 real-world situations |

---

## 🎯 What This Lab Demonstrates

### Technical Skills
✅ **Active Directory** - User/group management, OUs, permissions  
✅ **Windows Server** - Installation, configuration, domain services  
✅ **Help Desk Operations** - Ticket workflows, user support  
✅ **Remote Support** - RDP configuration and troubleshooting  
✅ **Network Services** - DNS, DHCP, file sharing  
✅ **Print Services** - Network printer setup and management  
✅ **Group Policy** - Centralized configuration management  
✅ **PowerShell** - Automation and scripting  
✅ **Troubleshooting** - Systematic problem-solving approach  
✅ **MS Office365** - Office365 tools usage and configuration

---

## 🏗️ Lab Topology

**Network:** `10.0.2.0/24` (Isolated NAT Network)
**Domain:** `companylab.local`

```text
┌─────────────────────────┐          ┌─────────────────────────┐
│  DC01 (Server)          │          │  CLIENT01 (Workstation) │
│  Windows Server 2022    │<-------->│  Windows 10 Enterprise  │
│  IP: 10.0.2.10          │          │  IP: DHCP (10.0.2.x)    │
│  (DNS, DHCP, AD DS)     │          │  (Domain Joined)        │
└─────────────────────────┘          └─────────────────────────┘
```

**Organizational Structure:**
- **5 Departments:** IT, Finance, Sales, HR, Marketing
- **12 Users:** Distributed across departments
- **9 Security Groups:** Role-based access control
- **6 Shared Folders:** Department and company-wide shares

---

## 📚 Documentation

### 🔹 Phase 1: Infrastructure Setup
* **[Lab Environment Documentation](Setup/Lab-Environment.md)**
    * *Detailing the hypervisor configuration, network topology, and server promotion process.*

### 🔹 Phase 2: Active Directory Administration
* **[01. User Onboarding](Active-Directory/01-User-Creation.md)**
    * *Creating users, assigning departmental OUs, and security groups.*
* **[02. Security & Password Management](Active-Directory/02-Password-Reset.md)**
    * *Handling account lockouts and enforcing password complexity policies.*
* **[03. Group Management (RBAC)](Active-Directory/03-Group-Management.md)**
    * *Implementing Role-Based Access Control using Security Groups.*
* **[04. File Server & Shared Drives](Active-Directory/04-Shared-Folders.md)**
    * *Configuring SMB shares and mapping network drives (Z:) for departments.*
* **[05. Group Policy (GPO)](Active-Directory/05-Group-Policy.md)**
    * *Enforcing corporate compliance (Legal Banners) via Group Policy Objects.*
* **[06. Enterprise Printer Deployment](Active-Directory/06-Printer-Deployment.md)**
    * *Deploying shared print queues and publishing them to the Directory.*

### 🔹 Phase 3: Technical Troubleshooting (Tier 2 Support)
* **[01. Remote Support (RDP)](Troubleshooting/01-RDP-Remote-Support.md)**
    * *Configuring Remote Desktop Protocol for secure administration.*
* **[02. Drive Access Failure](Troubleshooting/02-Shared-Drive-Access-Issue.md)**
    * *Diagnosing missing network drives and permission errors.*
* **[03. Network Connectivity / DNS](Troubleshooting/03-Network-Problems.md)**
    * *Fixing "Internet works but Company Files don't" (DNS Resolution Failure).*
* **[04. Performance Tuning](Troubleshooting/04-Slow-Computer.md)**
    * *Identifying and terminating "Rogue Processes" causing High CPU usage.*
* **[05. Login & Authentication Errors](Troubleshooting/05-Login-Issues.md)**
    * *Resolving Domain Trust and Time Synchronization (NTP) drifts.*

---

## 🛠️ Resources & Skills Inventory
*Detailed documentation of my technical skillset beyond the lab.*

* **[Hardware Diagnosis Skills](Resources/Hardware-Skills.md)** (RAM, SSD, Peripherals)
* **[Microsoft 365 & Office Support](Resources/Office365-Support.md)** (Outlook, Teams, OneDrive)
* **[IT Support Cheat Sheet](Resources/Cheat-Sheet.md)** (My daily reference for CLI commands)

---

## 🛠️ Technologies Used

**Operating Systems:** Windows Server 2022, Windows 10 Pro  
**Virtualization:** VirtualBox 7.0  
**Directory Services:** Active Directory Domain Services  
**Network Services:** DNS, DHCP, File Services, Print Services  
**Remote Access:** Remote Desktop Protocol (RDP)  
**Documentation:** Markdown, Git/GitHub  

---
**Target Roles:** IT Support Analyst | Help Desk Technician | Desktop Support | Junior System Administrator
---

## 📞 Contact

Piyush Arora | Melbourne, VIC
📧 piyusharora480@gmail.com

**Last Updated:** January 2026

</div>
