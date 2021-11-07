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
MD5 | `FD9F6453E62EA9A67EA20236445D161F`
SHA1 | `FACA29CEE37CE3BE9A6B50EF1BD96F3B084F0941`
SHA256 | `EC750391D52BBA76BB5BBB2FF6FD53EEF03B043BC48DA72BAC0B9C07CD0241BE`
SHA384 | `D849B034175B71BF75A2D1F40511C6C78BE63ECDCA71574BF4A665CCB532EC482B11CCD26EBCAB9AFAAA9058DAD95BEC`
SHA512 | `C57E31A9D145F6A81333D13D2403A7024124CDE068D29FC0E257D546DADAD1A95A28C78282BA367A0D403BE824E28AB6C03F565BE786125DF9D741F22C9E826B`
SSDEEP | `3072:dyp7iWvhH9ZC8eMKnvedRJAfxwsZ4gRTp:AvhH9ZCkKnuifTZHR`

## Runtime Data

### Usage (stdout):
```cmhg
-help is an invalid parameter.
---- Commands Supported ----

8dot3name       8dot3name management
behavior        Control file system behavior
dirty           Manage volume dirty bit
file            File specific commands
fsinfo          File system information
hardlink        Hardlink management
objectid        Object ID management
quota           Quota management
repair          Self healing management
reparsepoint    Reparse point management
resource        Transactional Resource Manager management
sparse          Sparse file control
tiering         Storage tiering property management
transaction     Transaction management
usn             USN management
volume          Volume management
wim             Transparent wim hosting management

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fsutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


