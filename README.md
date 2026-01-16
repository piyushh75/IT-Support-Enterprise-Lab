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

## 🎯 Technical Skills Demonstrated-

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



---

## 📚 Documentation: Active Directory & Infrastructure
*Core infrastructure management and Tier-2 troubleshooting.*

### 🏗️ Lab Topology

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

## 🛒 Documentation: Retail POS Systems Deployment
*A standalone deployment project focusing on Application Support and Database connectivity.*

* **01. Application Architecture**
  Deployed **uniCenta oPOS** using a specialized Client-Server model with **MySQL 8.0** to simulate a commercial branch environment.

* **02. Runtime Environment Hardening**
  Wrote custom batch scripts to force **Java 8 (JRE 1.8)** usage, resolving critical application crashes caused by conflicts with system-wide Java 22.

* **03. Peripheral Emulation & Hardware**
  Configured **Virtual COM Ports** to simulate legacy hardware (Cash Drawers/Receipt Printers) and programmed Barcode Scanners for automated carriage returns.

* **04. SQL Data Analytics**
  Connected **DBeaver** to the backend database to run raw SQL queries for Sales Revenue, Tax Reports, and Inventory levels.

> **[📄 View the Full POS Setup Guide & Evidence Here](./Retail-POS-Deployment/POS-Setup-Guide.md)**

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

## 📞 Contact

Piyush Arora | Melbourne, VIC
📧 piyusharora480@gmail.com

**Last Updated:** January 2026

</div>
# 🖥️ IT Support, Active Directory & POS Deployment Lab

![Status](https://img.shields.io/badge/status-complete-success)
![Platform](https://img.shields.io/badge/platform-VirtualBox-blue)
![Server](https://img.shields.io/badge/server-Windows%202022-blue)
![Client](https://img.shields.io/badge/client-Windows%2010-blue)

**Professional IT portfolio demonstrating end-to-end infrastructure management: Windows Server administration & Retail Point-of-Sale (POS) system deployment.**

**Portfolio Project by Piyush Arora**
LinkedIn Profile | piyusharora480@gmail.com

## 📊 Quick Stats
| Component | Details |
| :--- | :--- |
| **Domain Controller** | Windows Server 2022 (AD DS, DNS, DHCP) |
| **Client Infrastructure** | Windows 10 Enterprise (Corporate Workstations) |
| **Retail Infrastructure** | Dedicated POS Terminals (Java/SQL Environment) |
| **Database Backend** | MySQL 8.0 Server (High-Availability Setup) |
| **POS Software** | uniCenta oPOS v5 (Commercial Retail Software) |
| **Documented Scenarios** | 15+ real-world technical implementations |

## 🎯 Technical Skills Demonstrated
### 🏢 Enterprise Infrastructure (Back-End)
✅ **Active Directory** - User/group management, OUs, RBAC security models
✅ **Windows Server** - Domain promotion, DNS/DHCP scope management
✅ **Group Policy (GPO)** - Centralized configuration and security hardening
✅ **Remote Support** - RDP configuration and secure remote administration

### 🛒 Retail Systems (Front-End)
✅ **POS Deployment** - Installation of uniCenta oPOS in a Client-Server architecture
✅ **Database Admin** - MySQL 8.0 connectivity, schema management, and SQL analytics
✅ **Hardware Config** - Peripheral setup (Receipt Printers, Barcode Scanners)
✅ **Application Support** - Troubleshooting Java Runtime (JRE) path conflicts

---

## 📚 Documentation: Active Directory & Infrastructure
*Core infrastructure management and Tier-2 troubleshooting.*

### 🏗️ Lab Topology
**Network:** 10.0.2.0/24 (Isolated NAT) | **Domain:** companylab.local

```text
┌─────────────────────────┐          ┌─────────────────────────┐
│  DC01 (Server)          │          │  CLIENT01 (Workstation) │
│  Windows Server 2022    │<-------->│  Windows 10 Enterprise  │
│  IP: 10.0.2.10          │          │  IP: DHCP (10.0.2.x)    │
│  (DNS, DHCP, AD DS)     │          │  (Domain Joined)        │
└─────────────────────────┘          └─────────────────────────┘
```
### 🔹 Phase 1: Infrastructure Setup
* **Lab Environment:** Hypervisor configuration (VirtualBox), network topology design, and Server 2022 promotion.

### 🔹 Phase 2: Active Directory Administration
* **01. User Onboarding:** Creating users, assigning departmental OUs, and security groups.
* **02. Security & Password Management:** Handling account lockouts and enforcing complexity policies.
* **03. Group Management (RBAC):** Implementing Role-Based Access Control using Security Groups.
* **04. File Server & Shared Drives:** Configuring SMB shares and mapping network drives (Z:) via scripts.
* **05. Group Policy (GPO):** Enforcing corporate compliance (Legal Banners) and wallpaper policies.
* **06. Enterprise Printer Deployment:** Deploying shared print queues and publishing them to the Directory.

### 🔹 Phase 3: Technical Troubleshooting (Tier 2 Support)
* **01. Remote Support (RDP):** Configuring Secure RDP for remote administration.
* **02. Drive Access Failure:** Diagnosing permission errors (NTFS vs Share permissions).
* **03. Network Connectivity / DNS:** Fixing "Internet works but Company Files don't" (DNS Resolution).
* **04. Performance Tuning:** Identifying and terminating "Rogue Processes" causing High CPU.
* **05. Login & Authentication Errors:** Resolving Domain Trust issues and NTP Time drifts.

---

## 🛒 Documentation: Retail POS Systems Deployment
*A standalone deployment project focusing on Application Support and Database connectivity.*

* **01. Application Architecture**
  Deployed **uniCenta oPOS** using a specialized Client-Server model with **MySQL 8.0** to simulate a commercial branch environment.

* **02. Runtime Environment Hardening**
  Wrote custom batch scripts to force **Java 8 (JRE 1.8)** usage, resolving critical application crashes caused by conflicts with system-wide Java 22.

* **03. Peripheral Emulation & Hardware**
  Configured **Virtual COM Ports** to simulate legacy hardware (Cash Drawers/Receipt Printers) and programmed Barcode Scanners for automated carriage returns.

* **04. SQL Data Analytics**
  Connected **DBeaver** to the backend database to run raw SQL queries for Sales Revenue, Tax Reports, and Inventory levels.

> **[📄 View the Full POS Setup Guide & Evidence Here](./Retail-POS-Deployment/POS-Setup-Guide.md)**

---

## 🛠️ Technologies Used
* **Operating Systems:** Windows Server 2022, Windows 10 Pro
* **Retail Tech:** uniCenta oPOS, MySQL 8.0 Community Edition
* **Virtualization:** VirtualBox 7.0
* **Directory Services:** Active Directory Domain Services
* **Scripting:** PowerShell, Batch (.bat), SQL
* **Tools:** DBeaver (Database Management), Sysinternals

## 📞 Contact
**Piyush Arora** | Melbourne, VIC
📧 piyusharora480@gmail.com
