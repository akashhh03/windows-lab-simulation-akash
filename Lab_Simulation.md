# Windows Lab Simulation

This project simulates the Windows lab using GitHub on macOS.

---

## ✅ Step 1: User Creation (Simulated)
- Created three users: Akash1, Akash2, Akash3
- PowerShell script used is in `user_creation.ps1`

## ✅ Step 2: Rename Computers
- Renamed `ProjectClient10` and `ProjectClient25` (simulated)

## ✅ Step 3: Folder & File Creation
- Simulated creating `C:\SHARE` on ProjectClient25
- Simulated file: `Akash1Test.txt`

## ✅ Step 4: Permissions Table

| User     | NTFS Permission | Share Permission |
|----------|------------------|------------------|
| Akash1   | Read             | Read             |
| Akash2   | Write            | Change           |
| Akash3   | Full Control     | Full Control     |

## ✅ Step 5: Permissions Check (Simulated)
Command that would be run:
```powershell
Get-SmbShareAccess -Name "SHARE"
