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
MD5 | `9F43FA8FA2B91083214526A71E255913`
SHA1 | `813C66FF0AD879805BAED34566316477EE060D29`
SHA256 | `90314B939CA7D68F964D7345B0351A0C40F1D40C96645DFBF81EC146DCC80C15`
SHA384 | `C9CED6ADEBC1E97281189BF58666D5F600459CEDEFA0C59278AA071BF2DC5B7CBD74F1D58E80226727464D4234655FA3`
SHA512 | `1F9CD05F04644D3860CA27C971DE3E83493C7195793E8A4B86B33D4475A37C21718D110CFF24442AEB209E0436B2079CD827ED60E98E5838BC218BFD82C3F4FA`
SSDEEP | `6144:d3+IcCc82Hrr4ZQTPUm0NVsk0S/upAGr7e1wytGI:wIGHzT4bkVCHtGI`

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

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WBADMIN.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wbadmin.exe` being misused. While `wbadmin.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- '*wbadmin delete catalog -quiet*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- wbadmin.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | * <code>wbadmin.exe</code> can be used to delete the Windows Backup Catalog - <code>wbadmin.exe delete catalog -quiet</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | wbadmin.exe delete catalog -quiet | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

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



MIT License. Copyright (c) 2020 Strontic.


