---
title: diskshadow.exe | DiskShadow
excerpt: What is diskshadow.exe?
---

# diskshadow.exe 

* File Path: `C:\windows\system32\diskshadow.exe`
* Description: DiskShadow

## Hashes

Type | Hash
-- | --
MD5 | `85D520607D0DA6577E94600F2BC78AC7`
SHA1 | `B5E401239E51EA20C583980A2034EEADAD1DDE3C`
SHA256 | `E10CE1898A2817ACD53EB35EB097E8B4043684CA768B45686E6AA6EBE2F674A8`
SHA384 | `F474AE3473C843761677A1F126166B59344C0D6B93AC813D991C1CE12CAC9CA7A408D451AC18BEDD200EE5DEE3BA329F`
SHA512 | `DCAE8310FEA7CF8407C14231270E67BCA5CCE7836A4C574FE48D4A4C6CF7F64562B442C0E4A50D056D7E56104AEC2F07F8596F79A133F0C7749284AE9C6CD7F3`
SSDEEP | `6144:554+IPTyvXipu2C4pOZjf6O9MMXtEdiFR2tWUtLz6QOx4X+H:554+11X8uR2cXiO`

## Signature

* Status: The file C:\windows\system32\diskshadow.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: diskshadow.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `diskshadow.exe` being misused. While `diskshadow.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_deletion.yml) | `- '\diskshadow.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_diskshadow.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_diskshadow.yml) | `title: Execution via Diskshadow.exe `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_diskshadow.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_diskshadow.yml) | `description: Detects using Diskshadow.exe to execute arbitrary code in text file`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_diskshadow.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_diskshadow.yml) | `- https://bohops.com/2018/03/26/diskshadow-the-return-of-vss-evasion-persistence-and-active-directory-database-extraction/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_diskshadow.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_diskshadow.yml) | `Image\|endswith: '\diskshadow.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_diskshadow.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_diskshadow.yml) | `- False postitve can be if administrators use diskshadow tool in their infrastructure as a main backup tool with scripts.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Name: Diskshadow.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Description: Diskshadow.exe is a tool that exposes the functionality offered by the volume shadow copy Service (VSS).`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Command: diskshadow.exe /s c:\test\diskshadow.txt`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Description: Execute commands using diskshadow.exe from a prepared diskshadow script.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Usecase: Use diskshadow to exfiltrate data from VSS such as NTDS.dit`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Command: diskshadow> exec calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Description: Execute commands using diskshadow.exe to spawn child process`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Usecase: Use diskshadow to bypass defensive counter measures`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Path: C:\Windows\System32\diskshadow.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Path: C:\Windows\SysWOW64\diskshadow.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- IOC: Child process from diskshadow.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- IOC: Diskshadow reading input from file`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Link: https://bohops.com/2018/03/26/diskshadow-the-return-of-vss-evasion-persistence-and-active-directory-database-extraction/`{:.highlight .language-yaml} | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## Diskshadow

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Diskshadow.exe is a tool that exposes the functionality offered by the volume shadow copy Service (VSS). By default, Diskshadow uses an interactive command interpreter similar to that of Diskraid or Diskpart. Diskshadow also includes a scriptable mode.

> [!NOTE]
> Membership in the local Administrators group, or equivalent, is the minimum required to run Diskshadow.

### Syntax

For interactive mode, type the following at the command prompt to start the Diskshadow command interpreter:

```
diskshadow
```

For script mode, type the following, where *script.txt* is a script file containing Diskshadow commands:

```
diskshadow -s script.txt
```

#### Parameters

You can run the following commands in the Diskshadow command interpreter or through a script file. At a minimum, only **add** and **create** are necessary to create a shadow copy. However, this forfeits the context and option settings, will be a copy backup, and creates a shadow copy with no backup execution script.

| Command | Description |
| --------- | ----------- |
| [set command](./set.md) | Sets the context, options, verbose mode, and metadata file for creating shadow copies. |
| [load metadata command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/load-metadata.md) | Loads a metadata .cab file prior to importing a transportable shadow copy or loads the writer metadata in the case of a restore. |
| [writer command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/writer.md) | verifies that a writer or component is included or excludes a writer or component from the backup or restore procedure. |
| [add command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/add.md) | Adds volumes to the set of volumes that are to be shadow copied, or adds aliases to the alias environment. |
| [create command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/create.md) | Starts the shadow copy creation process, using the current context and option settings. |
| [exec command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/exec.md) | Executes a file on the local computer. |
| [begin backup command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/begin-backup.md) | Starts a full backup session. |
| [end backup command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/end-backup.md) | Ends a full backup session and issues a **backupcomplete** event with the appropriate writer state, if needed. |
| [begin restore command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/begin-restore.md) | Starts a restore session and issues a **prerestore** event to involved writers. |
| [end restore command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/end-restore.md) | Ends a restore session and issues a **postrestore** event to involved writers. |
| [reset command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset.md) | Resets Diskshadow to the default state. |
| [list command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/list.md) | Lists writers, shadow copies, or currently registered shadow copy providers that are on the system. |
| [delete shadows command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/delete-shadows.md) | Deletes shadow copies. |
| [import command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/import.md) | Imports a transportable shadow copy from a loaded metadata file into the system. |
| [mask command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/mask.md) | Removes hardware shadow copies that were imported by using the **import** command. |
| [expose command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/expose.md) | Exposes a persistent shadow copy as a drive letter, share, or mount point. |
| [unexpose command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/unexpose.md) | Unexposes a shadow copy that was exposed by using the **expose** command. |
| [break command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/break_2.md) | Disassociates a shadow copy volume from VSS. |
| [revert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/revert.md) | Reverts a volume back to a specified shadow copy. |
| [exit command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/exit.md) | Exits the command interpreter or script. |

### Examples

This is a sample sequence of commands that will create a shadow copy for backup. It can be saved to file as script.dsh, and executed using `diskshadow /s script.dsh`.

Assume the following:

- You have an existing directory called c:\\diskshadowdata.

- Your system volume is C: and your data volume is D:.

- You have a backupscript.cmd file in c:\\diskshadowdata.

- Your backupscript.cmd file will perform the copy of shadow data p: and q: to your backup drive.

You can enter these commands manually or script them:

```
##Diskshadow script file
set context persistent nowriters
set metadata c:\diskshadowdata\example.cab
set verbose on
begin backup
add volume c: alias systemvolumeshadow
add volume d: alias datavolumeshadow

create

expose %systemvolumeshadow% p:
expose %datavolumeshadow% q:
exec c:\diskshadowdata\backupscript.cmd
end backup
##End of script
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


