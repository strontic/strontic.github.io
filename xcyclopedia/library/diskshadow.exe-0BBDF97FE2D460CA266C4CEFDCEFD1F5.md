---
title: diskshadow.exe | DiskShadow
excerpt: What is diskshadow.exe?
---

# diskshadow.exe 

* File Path: `C:\Windows\SysWOW64\diskshadow.exe`
* Description: DiskShadow

## Hashes

Type | Hash
-- | --
MD5 | `0BBDF97FE2D460CA266C4CEFDCEFD1F5`
SHA1 | `FC174DF5B50899DFC9F655BE195B46AD368CC91D`
SHA256 | `8F952634C1CD9A06E286AF1D55D52F06A4B1C316568A11ECA1B5A9AFF3C043F9`
SHA384 | `E5FFDCE381F2F522F94A3924240455D4A4A325C560D3E8D02D4A0A6728CA54AA9147AA976FDAFA523996C8DE67027813`
SHA512 | `0C6779B520004F160FD2E2DF342FD94E30BE5B6F5795BA5044DFE29E263CE8A4F99CC8A6FB1569D741AEFD4B511416A531F316F943F6BAB067C64A5F309FCA6E`
SSDEEP | `6144:KZnKEomdxniCQboHYcH8gdmkxLV/9jbIcfotva78wtNsYs:KZKE1dxnlV8qhX9jbC148+2`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft DiskShadow version 1.0
Copyright (C) 2013 Microsoft Corporation
On computer:  default-pc,  6/4/2020 4:38:26 PM

DISKSHADOW.EXE  [/s <scriptfile> [param1] [param2] [param3] ...] [/l <logfile>]
                          - Runs script mode

DISKSHADOW.EXE  [/l <logfile>]
                          - Interactive mode

    /s <scriptfile> [param1] [param2] [param3] ... [paramX]
                          - Script mode. Include environment parameters in script using
                            %DISKSH_PARAM_1%, %DISKSH_PARAM_2%, %DISKSH_PARAM_3%, ..., %DISKSH_PARAM_X%
                            to reference [paramX] above.
    /l <logfile>          - Output log file

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: diskshadow.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `diskshadow.exe` being misused. While `diskshadow.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Name: Diskshadow.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Description: Diskshadow.exe is a tool that exposes the functionality offered by the volume shadow copy Service (VSS).` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Command: diskshadow.exe /s c:\test\diskshadow.txt` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Description: Execute commands using diskshadow.exe from a prepared diskshadow script.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Usecase: Use diskshadow to exfiltrate data from VSS such as NTDS.dit` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Command: diskshadow> exec calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Description: Execute commands using diskshadow.exe to spawn child process` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `Usecase: Use diskshadow to bypass defensive counter measures` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Path: C:\Windows\System32\diskshadow.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Path: C:\Windows\SysWOW64\diskshadow.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- IOC: Child process from diskshadow.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- IOC: Diskshadow reading input from file` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Diskshadow.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Diskshadow.yml) | `- Link: https://bohops.com/2018/03/26/diskshadow-the-return-of-vss-evasion-persistence-and-active-directory-database-extraction/` | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## Diskshadow

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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
| [set command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/set_2.md) | Sets the context, options, verbose mode, and metadata file for creating shadow copies. |
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



MIT License. Copyright (c) 2020 Strontic.


