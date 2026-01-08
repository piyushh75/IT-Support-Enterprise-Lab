# ⚡ IT Support & Command Line Cheat Sheet

## 🌐 Network Troubleshooting
| Command | Purpose | Example Use Case |
| :--- | :--- | :--- |
| **`ping <address>`** | Tests connectivity to a server/website. | `ping 10.0.2.10` (Check if Server is online). |
| **`ipconfig /all`** | Shows detailed IP, DNS, and MAC info. | Checking if the PC has the correct DNS server IP. |
| **`ipconfig /flushdns`** | Clears the DNS cache. | Fixing "Site not found" errors after a DNS change. |
| **`nslookup <domain>`** | Tests Name Resolution (DNS). | `nslookup companylab.local` (Does the name match the IP?). |
| **`tracert <address>`** | Traces the path packets take. | Seeing where a connection is getting stuck. |

## 🔑 Active Directory & System Administration
| Command | Purpose | Example Use Case |
| :--- | :--- | :--- |
| **`gpupdate /force`** | Forces Group Policies to update. | Applying a new "Legal Notice" or Wallpaper policy immediately. |
| **`dsa.msc`** | Opens AD Users & Computers. | Quickly opening the console to reset a password. |
| **`net use Z: \\server\share`**| Maps a network drive manually. | Troubleshooting missing shared drives for a user. |
| **`whoami`** | Shows current user & domain. | Verifying if you are logged in as Admin or a Standard User. |
| **`hostname`** | Displays the computer name. | Confirming which machine you are working on. |

## 🛠️ Remote Access & Management
| Command | Purpose | Example Use Case |
| :--- | :--- | :--- |
| **`mstsc`** | Opens Remote Desktop (RDP). | Remoting into a user's PC to provide support. |
| **`compmgmt.msc`** | Opens Computer Management. | Checking Event Logs or managing local disks. |
| **`taskmgr`** | Opens Task Manager. | Killing a frozen app or "High CPU" process. |
| **`control`** | Opens the classic Control Panel. | Accessing older settings like "Devices and Printers". |
