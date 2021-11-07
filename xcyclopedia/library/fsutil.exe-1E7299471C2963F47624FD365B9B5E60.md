---
title: fsutil.exe | fsutil.exe
excerpt: What is fsutil.exe?
---

# fsutil.exe 

* File Path: `C:\Windows\SysWOW64\fsutil.exe`
* Description: fsutil.exe

## Hashes

Type | Hash
-- | --
MD5 | `1E7299471C2963F47624FD365B9B5E60`
SHA1 | `B5AB72EDD818FF7B82EB5239CAC9BC0AD45BA9BB`
SHA256 | `3B13A67DD25962BB50AB60ACA722B0AEC4810C9C23F2F8D6E3648AD6D694B194`
SHA384 | `7D947E0A25C14338E2BDA8B732483CB36C22F21ADC3664CA866141814549FFDA3B57481496B6B04A66ED349855EAB409`
SHA512 | `3E4B4F5D9F8AF054556AAA03C651360434D7DAA81E46CBE8053E6575807F540A76C1EABAA26C9D878466A9B4889EFBDFF2FBF9267AFACFCB70974C7360781D93`
SSDEEP | `3072:cysAQ3C2HZ2byEfGCUuyHzy6lMg87j6jUr+87CXbRMuhrG:feZeyEeCUu11fpx7QRMuB`
IMP | `3AFDA70FA7E12943E4F800C706B88A82`
PESHA1 | `457097C0BA7F287EEC687EDE16A4542EC1B1ED72`
PE256 | `FD0933087EE2983678595EEB0E65CF2AD35C54BC7D9B8AA5836C2BE4875CA508`

## Runtime Data

### Usage (stdout):
```cmhg
--help is an invalid parameter.
---- Commands Supported ----

8dot3name       8dot3name management
behavior        Control file system behavior
dax             Dax volume management
dirty           Manage volume dirty bit
file            File specific commands
fsInfo          File system information
hardlink        Hardlink management
objectID        Object ID management
quota           Quota management
repair          Self healing management
reparsePoint    Reparse point management
resource        Transactional Resource Manager management
sparse          Sparse file control
tiering         Storage tiering property management
transaction     Transaction management
usn             USN management
volume          Volume management
wim             Transparent wim hosting management

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\fsutil.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fsutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.652 (WinBuild.160101.0800)
* Product Version: 10.0.17763.652
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3b13a67dd25962bb50ab60aca722b0aec4810c9c23f2f8d6e3648ad6d694b194/detection/


## Possible Misuse

*The following table contains possible examples of `fsutil.exe` being misused. While `fsutil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `title: Fsutil Suspicious Invocation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `description: Detects suspicious parameters of fsutil (deleting USN journal, configuring it with small size, etc). Might be used by ransomwares during the attack (seen by NotPetya and others).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/fsutil-usn`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `Image\|endswith: '\fsutil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `OriginalFileName: 'fsutil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \fsutil.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Indicator Removal using FSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Indicator Removal using FSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070/T1070.md) | - [Atomic Test #1 - Indicator Removal using FSUtil](#atomic-test-1---indicator-removal-using-fsutil) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070/T1070.md) | ## Atomic Test #1 - Indicator Removal using FSUtil | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070/T1070.md) | will be displayed. More information about fsutil can be found at https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/fsutil-usn | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070/T1070.md) | fsutil usn deletejournal /D C: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070/T1070.md) | fsutil usn createjournal m=1000 a=100 c: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_badrabbit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_badrabbit.yar) | $s4 = "fsutil usn deletejournal /D %c:" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nopetya_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nopetya_jun17.yar) | $x5 = "fsutil usn deletejournal /D %c:" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## fsutil

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows 10, Windows Server 2012 R2, Windows 8.1, Windows Server 2012, Windows 8, Windows Server 2008 R2, Windows 7

Performs tasks that are related to file allocation table (FAT) and NTFS file systems, such as managing reparse points, managing sparse files, or dismounting a volume. If it's used without parameters, **fsutil** displays a list of supported subcommands.

> [!NOTE]
> You must be logged on as an administrator or a member of the Administrators group to use **fsutil**. This command is quite powerful and should be used only by advanced users who have a thorough knowledge of WindowsÂ operating systems.
>
>You must enable Windows Subsystem for Linux before you can run **fsutil**. Run the following command as Administrator in PowerShell to enable this optional feature:
>
> `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`
>
> You'll be prompted to restart your computer once it's installed. After your computer restarts, you'll be able to run **Fsutil** as an administrator.

#### Parameters

| Subcommand | Description |
| ---------- | ----------- |
| [fsutil 8dot3name](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-8dot3name.md) | Queries or changes the settings for short name behavior on the system, for example, generates 8.3 character-length file names. Removes short names for all files within a directory. Scans a directory and identifies registry keys that might be impacted if short names were stripped from the files in the directory. |
| [fsutil dirty](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-dirty.md) | Queries whether the volume's dirty bit is set or sets a volume's dirty bit. When a volume's dirty bit is set, **autochk** automatically checks the volume for errors the next time the computer is restarted. |
| [fsutil file](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-file.md) | Finds a file by user name (if Disk Quotas are enabled), queries allocated ranges for a file, sets a file's short name, sets a file's valid data length, sets zero data for a file, creates a new file of a specified size, finds a file ID if given the name, or finds a file link name for a specified file ID. |
| [fsutil fsinfo](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-fsinfo.md) | Lists all drives and queries the drive type, volume information, NTFS-specific volume information, or file system statistics. |
| [fsutil hardlink](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-hardlink.md) | Lists hard links for a file, or creates a hard link (a directory entry for a file). Every file can be considered to have at least one hard link. On NTFS volumes, each file can have multiple hard links, so a single file can appear in many directories (or even in the same directory, with different names). Because all of the links reference the same file, programs can open any of the links and modify the file. A file is deleted from the file system only after all links to it are deleted. After you create a hard link, programs can use it like any other file name. |
| [fsutil objectid](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-objectid.md) | Manages object identifiers, which are used by the Windows operating system to track objects such as files and directories. |
| [fsutil quota](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-quota.md) | Manages disk quotas on NTFS volumes to provide more precise control of network-based storage. Disk quotas are implemented on a per-volume basis and enable both hard- and soft-storage limits to be implemented on a per-user basis. |
| [fsutil repair](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-repair.md) | Queries or sets the self-healing state of the volume. Self-healing NTFS attempts to correct corruptions of the NTFS file system online without requiring **Chkdsk.exe** to be run. Includes initiating on-disk verification and waiting for repair completion. |
| [fsutil reparsepoint](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-reparsepoint.md) | Queries or deletes reparse points (NTFS file system objects that have a definable attribute containing user-controlled data). Reparse points are used to extend functionality in the input/output (I/O) subsystem. They are used for directory junction points and volume mount points. They are also used by file system filter drivers to mark certain files as special to that driver. |
| [fsutil resource](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-resource.md) | Creates a Secondary Transactional Resource Manager, starts or stops a Transactional Resource Manager, displays information about a Transactional Resource Manager  or modifies its behavior. |
| [fsutil sparse](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-sparse.md) | Manages sparse files. A sparse file is a file with one or more regions of unallocated data in it. A program will see these unallocated regions as containing bytes with the value zero, but no disk space is used to represent these zeros. All meaningful or nonzero data is allocated, whereas all non-meaningful data (large strings of data composed of zeros) is not allocated. When a sparse file is read, allocated data is returned as stored and unallocated data is returned as zeros (by default in accordance with the C2 security requirement specification). Sparse file support allows data to be deallocated from anywhere in the file. |
| [fsutil tiering](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-tiering.md) | Enables management of storage tier functions, such as setting and disabling flags and listing of tiers. |
| [fsutil transaction](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-transaction.md)   | Commits a specified transaction, rolls back a specified transaction, or displays info about the transaction. |
| [fsutil usn](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-usn.md) | Manages the update sequence number (USN) change journal, which provides a persistent log of all changes made to files on the volume. |
| [fsutil volume](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-volume.md) | Manages a volume. Dismounts a volume, queries to see how much free space is available on a disk, or finds a file that is using a specified cluster. |
| [fsutil wim](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-wim.md) | Provides functions to discover and manage WIM-backed files. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


