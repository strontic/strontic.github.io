---
title: wbadmin.exe | Command Line Interface for Microsoft BLB Backup
excerpt: What is wbadmin.exe?
---

# wbadmin.exe 

* File Path: `C:\Windows\system32\wbadmin.exe`
* Description: Command Line Interface for Microsoft BLB Backup

## Hashes

Type | Hash
-- | --
MD5 | `14833578D461729CC21CE9AF311EEC1F`
SHA1 | `2EED621A1F8D6E99B91D2294C8F3EE7BB60D1573`
SHA256 | `382B033D559B33D801F77776F4D6ECB180703C14A3CE5B91277A5B589B2F8B18`
SHA384 | `9AF2F99ADFCA212458EFC51D321BCA5266048990F6505B69ECD7C3E30855DB23EA32949561352B3C9E90E6B0C599261E`
SHA512 | `DD1854742B76745F150E8C304A9A3DA715FE4C55D8505E1C49FA2C1979A403E79576D178450B43F014C805FBA08F51614127764FD05F2B9AD35C8BEC41F53E80`
SSDEEP | `6144:F2qRmqUH1IHdfS08hQ/Cv1Sx4I48OUFfa6/9xkluvAloZNsEI:UqUcdS651ZDZKEI`
IMP | `D72A8A096458529EDF54E67F5F212651`
PESHA1 | `E72EC04F6A3754D2439D66DB7F5B84CB927AE6C1`
PE256 | `5CDC83B7A105D1B7B5A0901869A0C166A143A31D9CC6F9106B6B093B36E480D1`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wbadmin.exe |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/382b033d559b33d801f77776f4d6ecb180703c14a3ce5b91277a5b589b2f8b18/detection


## Possible Misuse

*The following table contains possible examples of `wbadmin.exe` being misused. While `wbadmin.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- '*wbadmin delete catalog -quiet*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- wbadmin.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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


