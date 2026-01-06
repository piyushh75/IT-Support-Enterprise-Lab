# 🖥️ Enterprise IT Support & Active Directory Lab

![Status](https://img.shields.io/badge/status-complete-success)
![Platform](https://img.shields.io/badge/platform-VirtualBox-blue)
![Server](https://img.shields.io/badge/server-Windows%202022-blue)
![Client](https://img.shields.io/badge/client-Windows%2010-blue)

> **Professional IT support laboratory demonstrating Active Directory administration, help desk operations, remote support, and systematic troubleshooting.**

**Portfolio Project by [Piyush Arora]** | [LinkedIn](www.linkedin.com/in/piyush-arora07) | [Email](piyusharora480@gmail.com)

---

## 📊 Quick Stats

| Component | Details |
|-----------|---------|
| **Domain Controller** | Windows Server 2022 |
| **Client Workstations** | 2x Windows 10 Pro |
| **Domain** | companylab.local |
| **Users** | 12 across 5 departments |
| **Documented Scenarios** | 12 real-world situations |
| **PowerShell Scripts** | 3 automation tools |

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

### Professional Skills
✅ Technical documentation  
✅ Customer service communication  
✅ Root cause analysis  
✅ Time management  
✅ Self-directed learning  

---

## 🏗️ Lab Infrastructure
```
Domain: companylab.local
Network: 10.0.2.0/24 (NAT Network)

┌─────────────────────────────────────┐
│  DC01 - Domain Controller           │
│  • Windows Server 2022              │
│  • Active Directory, DNS, DHCP      │
│  • File & Print Server              │
│  • IP: 10.0.2.10                    │
│  • 4GB RAM | 2 CPU                  │
└─────────────────────────────────────┘
           │
    ───────┴────────
    │              │
┌─────────┐  ┌─────────┐
│ CLIENT01│  │ CLIENT02│
│ Finance │  │ Sales   │
│ Win10Pro│  │ Win10Pro│
│.20      │  │.21      │
└─────────┘  └─────────┘
```

**Organizational Structure:**
- **5 Departments:** IT, Finance, Sales, HR, Marketing
- **12 Users:** Distributed across departments
- **9 Security Groups:** Role-based access control
- **6 Shared Folders:** Department and company-wide shares

---

## 📚 Documentation

### [Setup Guide](Setup/Lab-Environment.md)
Complete walkthrough of building the lab from scratch

### Active Directory Tasks
1. **[User Account Creation](Active-Directory/01-User-Creation.md)** - New employee onboarding
2. **[Password Reset & Unlock](Active-Directory/02-Password-Reset.md)** - Account recovery procedures
3. **[Group Management](Active-Directory/03-Group-Management.md)** - Security group administration
4. **[Shared Folder Permissions](Active-Directory/04-Shared-Folders.md)** - NTFS & Share permissions
5. **[Group Policy Configuration](Active-Directory/05-Group-Policy.md)** - Drive mapping automation

### Troubleshooting Scenarios
1. **[Shared Drive Access Issues](Troubleshooting/01-Shared-Drive-Access.md)** - Cached credentials
2. **[Account Lockout](Troubleshooting/02-Account-Lockout.md)** - Investigation & resolution
3. **[Slow Computer Performance](Troubleshooting/03-Slow-Computer.md)** - System optimization
4. **[Login Failures](Troubleshooting/04-Login-Issues.md)** - Authentication troubleshooting
5. **[Network Connectivity](Troubleshooting/05-Network-Problems.md)** - TCP/IP diagnostics
6. **[Network Printer Setup](Troubleshooting/06-Printer-Setup.md)** - Print services configuration
7. **[Remote Desktop Support](Troubleshooting/07-RDP-Remote-Support.md)** - RDP troubleshooting

### [PowerShell Scripts](Scripts/)
- **Create-Users.ps1** - Bulk user provisioning
- **Reset-Password.ps1** - Automated password reset
- **Get-UserInfo.ps1** - User account auditing

---

## 🛠️ Technologies Used

**Operating Systems:** Windows Server 2022, Windows 10 Pro  
**Virtualization:** VirtualBox 7.0  
**Directory Services:** Active Directory Domain Services  
**Network Services:** DNS, DHCP, File Services, Print Services  
**Remote Access:** Remote Desktop Protocol (RDP)  
**Scripting:** PowerShell 5.1  
**Documentation:** Markdown, Git/GitHub  

---

## 🚀 Key Accomplishments

✅ Built enterprise AD environment from scratch  
✅ Configured domain services (DNS, DHCP, File/Print)  
✅ Implemented role-based access control  
✅ Documented 12 real-world IT support scenarios  
✅ Created automation scripts for common tasks  
✅ Established remote support infrastructure  
✅ Demonstrated systematic troubleshooting methodology  

---

## 💼 Why This Project

This lab was built to:
- **Demonstrate practical skills** for IT Support/Help Desk roles
- **Showcase technical knowledge** beyond theoretical learning
- **Provide interview talking points** with real examples
- **Prove ability to learn independently** and document professionally

**Target Roles:** IT Support Analyst | Help Desk Technician | Desktop Support | Junior System Administrator

---

## 📞 Contact

**[Your Name]**  
📧 your.email@example.com  
💼 [LinkedIn Profile](https://linkedin.com/in/yourprofile)  
📍 Melbourne, Victoria, Australia  

**Status:** Actively seeking IT Support opportunities in Melbourne or remote

---

## 📝 License

This project is for educational and portfolio purposes.

---

<div align="center">

### ⭐ If this helped you, consider giving it a star!

**Last Updated:** December 2024

</div>
