# Script-For-CVE-2024-20666
Automate updating the WinRE partition (without having to resize it first) and patch the CVE-2024-20666 BitLocker vulnerability.
[Microsoft Link (Script found here)](https://support.microsoft.com/en-us/topic/kb5034957-updating-the-winre-partition-on-deployed-devices-to-address-security-vulnerabilities-in-cve-2024-20666-0190331b-1ca3-42d8-8a55-7fc406910c10)

## Works for
- Windows Server 2022 (Server Core installation) ([KB5034439](https://support.microsoft.com/help/5034439): Windows Recovery Environment update for Azure Stack HCI, version 22H2 and Windows Server 2022: Jan 9, 2024)
- Windows Server 2022 ([KB5034439](https://support.microsoft.com/help/5034439): Windows Recovery Environment update for Azure Stack HCI, version 22H2 and Windows Server 2022: January 9, 2024)
- Windows Server 2022, 23H2 Edition (Server Core installation) ([KB5034439](https://support.microsoft.com/help/5034439): Windows Recovery Environment update for Azure Stack HCI, version 22H2 and Windows Server 2022: January 9, 2024)
- Windows 11 version 21H2 for x64-based Systems ([KB5034440](https://support.microsoft.com/help/5034440): Windows Recovery Environment update for Windows 11, version 21H2: January 9, 2024)
- Windows 10 Version 22H2 for x64-based Systems ([KB5034441](https://support.microsoft.com/help/5034441): Windows Recovery Environment update for Windows 10, version 21H2 and 22H2: January 9, 2024)
- Windows 10 Version 22H2 for 32-bit Systems ([KB5034441](https://support.microsoft.com/help/5034441): Windows Recovery Environment update for Windows 10, version 21H2 and 22H2: January 9, 2024)
- Windows 10 Version 21H2 for x64-based Systems ([KB5034441](https://support.microsoft.com/help/5034441): Windows Recovery Environment update for Windows 10, version 21H2 and 22H2: January 9, 2024)
- Windows 10 Version 21H2 for 32-bit Systems ([KB5034441](https://support.microsoft.com/help/5034441): Windows Recovery Environment update for Windows 10, version 21H2 and 22H2: January 9, 2024)

## To run - copy and paste the code on Powershell (Administrator).
This script is for Windows 10, version 2004 and later versions, including Windows 11. We recommend that you use this version of the script, because it is more robust but uses features available only on Windows 10, version 2004 and later versions.
```ps
irm https://raw.githubusercontent.com/nnotwen/Script-For-CVE-2024-20666/main/PatchWinREScript_2004plus.ps1 | iex
```
This script is for Windows 10, version 1909 and earlier versions, but executes on all versions of Windows 10 and Windows 11.
```ps
irm https://raw.githubusercontent.com/nnotwen/Script-For-CVE-2024-20666/main/PatchWinREScript_General.ps1 | iex
```

