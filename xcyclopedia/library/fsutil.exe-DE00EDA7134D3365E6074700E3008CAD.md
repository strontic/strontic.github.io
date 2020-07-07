---
title: fsutil.exe | fsutil.exe
---

# fsutil.exe 

* File Path: `C:\Windows\system32\fsutil.exe`
* Description: fsutil.exe
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DE00EDA7134D3365E6074700E3008CAD`
SHA1 | `B1E5B19E3828886FD4A3A8F827A41232514ED71B`
SHA256 | `8767BC230A6928DF40B66A1D127C7DBAEDF70BD18D5C20C094FFC7F23902A7CF`
SHA384 | `537B8646163E1090A1405B9C9ACD7DFDEFD0467C49DFBDD1E53024EC55244F37E39C62C03685FDE7E1398FAB9F697C68`
SHA512 | `1EDFE25FD2067AC3D3E15A4BF3FD1A621B0EDADEBB2530F35667F6800995827EEEFDAFE42CE64BE72814F7F04973BFE02AD4E1A2297A7A3CF5D87289A48077D8`
SSDEEP | `6144:O4AA5pY72zEUIK0wSA4SjabSrlbEbTNOjM:lAwbJv0wLvjabZ/so`

## Runtime Data

### Usage (stdout):
```Batchfile
-help is an invalid parameter.
---- Commands Supported ----

8dot3name         8dot3name management
behavior          Control file system behavior
dax               Dax volume management
dirty             Manage volume dirty bit
file              File specific commands
fsInfo            File system information
hardlink          Hardlink management
objectID          Object ID management
quota             Quota management
repair            Self healing management
reparsePoint      Reparse point management
storageReserve    Storage Reserve management
resource          Transactional Resource Manager management
sparse            Sparse file control
tiering           Storage tiering property management
transaction       Transaction management
usn               USN management
volume            Volume management
wim               Transparent wim hosting management

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fsutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `fsutil.exe` being misused. While `fsutil.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `title: Fsutil Suspicious Invocation` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `description: Detects suspicious parameters of fsutil (deleting USN journal, configuring it with small size..). Might be used by ransomwares during the attack (seen by NotPetya and others)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `    - https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/fsutil-usn` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `        Image\|endswith: '\fsutil.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_fsutil_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_fsutil_usage.yml) | `        OriginalFileName: 'fsutil.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: Indicator Removal using FSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #1: Indicator Removal using FSUtil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1551.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1551/T1551.md) | - [Atomic Test #1 - Indicator Removal using FSUtil](#atomic-test-1---indicator-removal-using-fsutil) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1551.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1551/T1551.md) | ## Atomic Test #1 - Indicator Removal using FSUtil | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1551.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1551/T1551.md) | will be displayed. More information about fsutil can be found at https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/fsutil-usn | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1551.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1551/T1551.md) | fsutil usn deletejournal /D C: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1551.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1551/T1551.md) | fsutil usn createjournal m=1000 a=100 c: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## fsutil

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows 10, Windows Server 2012 R2, Windows 8.1, Windows Server 2012, Windows 8, Windows Server 2008 R2, Windows 7

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



MIT License. Copyright (c) 2020 Strontic.


