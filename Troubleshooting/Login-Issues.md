# 🕒 Login Failure (Time Synchronization)

## 1. Ticket Overview
**Ticket ID:** TRB-004
**Issue:** User unable to log in. Error: "The security database on the server does not have a computer account for this workstation trust relationship."
**Root Cause:** Kerberos authentication failed because the Client's system clock drifted more than 5 minutes from the Domain Controller.

## 2. Troubleshooting
* **Check:** Compared time on Client vs. Server.
    * Server: `10:00 AM`
    * Client: `10:15 AM` (Drift > 5 mins breaks Kerberos).
* **Fix:** Forced time synchronization with the Domain Controller (NTP Source).

## 3. Resolution Command
Opened Command Prompt as Administrator and ran:
```cmd
w32tm /resync
Result: "The command completed successfully."

Outcome: User login succeeded immediately after time correction.
