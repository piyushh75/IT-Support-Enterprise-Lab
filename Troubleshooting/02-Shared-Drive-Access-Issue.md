# 📂 Shared Drive Access Issue

## 1. Ticket Overview
**Ticket ID:** TRB-002
**Issue:** User reported "Missing Z: Drive" and inability to access departmental files.
**Root Cause:** The drive map policy had not applied to the user's session.

## 2. Troubleshooting Steps
* **Verification:** Checked `This PC` and confirmed Z: Drive was missing.
* **Connectivity Check:** Pinged file server (`ping dc01`) -> Successful.
* **Manual Map:** Used command `net use Z: \\DC01\CompanyData` to force connection.
* **Permissions:** Verified user `sjones` had Read/Write access to the share.

## 3. Resolution
Mapped the drive persistently and verified file visibility.

![Shared Drive Proof](../Active-Directory/screenshots/mapped-drive-proof.png)
