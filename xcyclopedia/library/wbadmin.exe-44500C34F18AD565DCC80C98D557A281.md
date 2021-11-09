---
title: wbadmin.exe | Command Line Interface for Microsoft BLB Backup
excerpt: What is wbadmin.exe?
---

# wbadmin.exe 

* File Path: `C:\WINDOWS\system32\wbadmin.exe`
* Description: Command Line Interface for Microsoft BLB Backup

## Hashes

Type | Hash
-- | --
MD5 | `44500C34F18AD565DCC80C98D557A281`
SHA1 | `C2F5963F4767EFF9F4CB870345CF9BC0D9303FE9`
SHA256 | `BE37E10BFAEDC167665AE8C448805AB1DEF5E299C6ACD274113248F8414B0696`
SHA384 | `1511E89D65A7A5B899412859B972CDD31089D007EFA868B8F6D2FE224DB9713503A81585B71AE3AD861646CC229C324C`
SHA512 | `B2666E9B0165CDDB566C9EABB4E8E8DF1E75B262E3BCFE009F5F9B8E778768F3D1CA6EE9A79EB98EFB87534D54243F220C6B2B75D4CC4949ECA9DF8BFC4442CA`
SSDEEP | `6144:bIifM+RjQFUFzyOzrxw2GSDcfWj+tKksv5eGqgb3HBP:b9k+RjQmFzyOz/uwX3BP`
IMP | `6858CD4B0763C9E4C7420DB6DC922801`
PESHA1 | `67029472D163AE7073B475F4D47F9CDAF42023EB`
PE256 | `D3755C8C3ECD43E73B7A353A899ED655636A3653575BD4A8C974F1941B79B1A5`

## Runtime Data

### Usage (stdout):
```cmhg
wbadmin 1.0 - Backup command-line tool
(C) Copyright Microsoft Corporation. All rights reserved.

---- Commands Supported ----

ENABLE BACKUP             -- Creates or modifies a daily backup schedule.
DISABLE BACKUP            -- Disables the scheduled backups.
START BACKUP              -- Runs a one-time backup.
STOP JOB                  -- Stops the currently running backup or recovery 
                              operation.
GET VERSIONS              -- Lists details of backups that can be recovered 
                              from a specified location.
GET ITEMS                 -- Lists items contained in a backup.
GET STATUS                -- Reports the status of the currently running 
                              operation.
DELETE BACKUP             -- Deletes one or more backups.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\wbadmin.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WBADMIN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/be37e10bfaedc167665ae8c448805ab1def5e299c6acd274113248f8414b0696/detection


## Possible Misuse

*The following table contains possible examples of `wbadmin.exe` being misused. While `wbadmin.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- 'wbadmin'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- wbadmin.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_deletion.yml) | `- '\wbadmin.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Windows - wbadmin Delete Windows Backup Catalog [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #7: Windows - wbadmin Delete systemstatebackup [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Windows - wbadmin Delete Windows Backup Catalog [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #7: Windows - wbadmin Delete systemstatebackup [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | * <code>wbadmin.exe</code> can be used to delete the Windows Backup Catalog - <code>wbadmin.exe delete catalog -quiet</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | - [Atomic Test #3 - Windows - wbadmin Delete Windows Backup Catalog](#atomic-test-3---windows---wbadmin-delete-windows-backup-catalog) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | - [Atomic Test #7 - Windows - wbadmin Delete systemstatebackup](#atomic-test-7---windows---wbadmin-delete-systemstatebackup) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | ## Atomic Test #3 - Windows - wbadmin Delete Windows Backup Catalog | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | wbadmin delete catalog -quiet | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | ## Atomic Test #7 - Windows - wbadmin Delete systemstatebackup | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | Deletes the Windows systemstatebackup using wbadmin.exe. This technique is used by numerous ransomware families. This may only be successful on server platforms that have Windows Backup enabled. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | wbadmin delete systemstatebackup -keepVersions:0 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## wbadmin

Enables you to back up and restore your operating system, volumes, files, folders, and applications from a command prompt.

To configure a regularly scheduled backup using this command, you must be a member of the **Administrators** group. To perform all other tasks with this command, you must be a member of the **Backup Operators** group or the **Administrators** group, or you must have been delegated the appropriate permissions.

You must run **wbadmin** from an elevated command prompt, by right-clicking **Command Prompt**, and then selecting **Run as administrator**.

### Parameters

| Parameter | Description |
|--|--|
| [wbadmin delete catalog](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-delete-catalog.md) | Deletes the backup catalog on the local computer. Use this command only if the backup catalog on this computer is corrupted and you have no backups stored at another location that you can use to restore the catalog. |
| [wbadmin delete systemstatebackup](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-delete-systemstatebackup.md) | Deletes one or more system state backups. |
| [wbadmin disable backup](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-disable-backup.md) | Disables your daily backups. |
| [wbadmin enable backup](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-enable-backup.md) | Configures and enables a regularly scheduled backup. |
| [wbadmin get disks](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-get-disks.md) | Lists disks that are currently online. |
| [wbadmin get items](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-get-items.md) | Lists the items included in a backup. |
| [wbadmin get status](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-get-status.md) | Shows the status of the currently running backup or recovery operation. |
| [wbadmin get versions](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-get-versions.md) | Lists details of backups recoverable from the local computer or, if another location is specified, from another computer. |
| [wbadmin restore catalog](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-restore-catalog.md) | Recovers a backup catalog from a specified storage location in the case where the backup catalog on the local computer has been corrupted. |
| [wbadmin start backup](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-start-backup.md) | Runs a one-time backup. If used with no parameters, uses the settings from the daily backup schedule. |
| [wbadmin start recovery](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-start-recovery.md) | Runs a recovery of the volumes, applications, files, or folders specified. |
| [wbadmin start sysrecovery](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-start-sysrecovery.md) | Runs a recovery of the full system (at least all the volumes that contain the operating system's state). This command  is only available if you are using the Windows Recovery Environment. |
| [wbadmin start systemstatebackup](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-start-systemstatebackup.md) | Runs a system state backup. |
| [wbadmin start systemstaterecovery](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-start-systemstaterecovery.md) | Runs a system state recovery. |
| [wbadmin stop job](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wbadmin-stop-job.md) | Stops the currently running backup or recovery operation. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Windows Server Backup Cmdlets in Windows PowerShell](/powershell/module/windowsserverbackup)

- [Windows Recovery Environment (WinRE)](/windows-hardware/manufacture/desktop/windows-recovery-environment--windows-re--technical-reference)

---



MIT License. Copyright (c) 2020-2021 Strontic.


