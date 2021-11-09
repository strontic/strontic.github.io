---
title: diskpart.exe | DiskPart
excerpt: What is diskpart.exe?
---

# diskpart.exe 

* File Path: `C:\WINDOWS\system32\diskpart.exe`
* Description: DiskPart

## Hashes

Type | Hash
-- | --
MD5 | `7C68D522166784F81270297F6ADC26B9`
SHA1 | `CFDD720D3B4927DDDA025445BBBC736DE655F99F`
SHA256 | `E1AC914C4109A596C0DE80AF5F70FF8177F9E893DFF07EBC169685D4C1DB08DD`
SHA384 | `1733488EA7591E275B410195F18A79728774BD41D52EE24E05A7C5EAD7003B5F1DF06F59657644968309285BE935F113`
SHA512 | `E569E5E28FAE02685436E482A7999C8B233D46A86978FDBEE1E5466A7C0E5113C5F984835D939277ABF499AE5B83CBFACDEDC8ED8A263B5A1E32C06911EF08B3`
SSDEEP | `3072:yjXWl6xZSlyogMWDtba8AQh4szeaGgNwq8MBducDorVOI9VF5KF1NswE9vMjYuKC:yjXA6xZSlyogMWDtbaxQh4szeaGewq8g`
IMP | `118596C58B789852789B781D0AF467C7`
PESHA1 | `6EF546C5DBDA7FB3CF67DC23E9CDB1F954315949`
PE256 | `DC0D8A74131F7F2D169E5C2CCD0A0FEEB68782CD5D55AEFA8EB0D2EBBE710950`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft DiskPart version 10.0.22000.1

Copyright (C) Microsoft Corporation.
On computer: default-pc

DiskPart was unable to process the parameters.
Use 'diskpart /?' for more information.

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\diskpart.exe.mui | File
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\diskpart.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: diskpart.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/e1ac914c4109a596c0de80af5f70ff8177f9e893dff07ebc169685d4c1db08dd/detection


## Possible Misuse

*The following table contains possible examples of `diskpart.exe` being misused. While `diskpart.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- '\diskpart.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- Diskpart.exe usage to manage partitions on the local hard drive`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- diskpart.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## diskpart

>Applies to: Windows Server 2022, Windows 10, Windows 8.1, Windows 8, Windows 7, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012, and Windows Server 2008 R2, Windows Server 2008

The diskpart command interpreter helps you manage your computer's drives (disks, partitions, volumes, or virtual hard disks).

Before you can use **diskpart** commands, you must first list, and then select an object to give it focus. After an object has focus, any diskpart commands that you type will act on that object.

### List available objects

You can list the available objects and determine an object's number or drive letter by using:

- `list disk` - Displays all the disks on the computer.

- `list volume` - Displays all the volumes on the computer.

- `list partition` - Displays the partitions on the disk that has focus on the computer.

- `list vdisk` - Displays all the virtual disks on the computer.

After you run the **list** commands, an asterisk (*) appears next to the object with focus.

### Determine focus

When you select an object, the focus remains on that object until you select a different object. For example, if the focus is set on disk 0 and you select volume 8 on disk 2, the focus shifts from disk 0 to disk 2, volume 8.

Some commands automatically change the focus. For example, when you create a new partition, the focus automatically switches to the new partition.

You can only give focus to a partition on the selected disk. After a partition has focus, the related volume (if any) also has focus. After a volume has focus, the related disk and partition also have focus if the volume maps to a single specific partition. If this isn't the case, focus on the disk and partition is lost.

### Syntax

To start the diskpart command interpreter, at the command prompt type:

```
diskpart <parameter>
```

> [!IMPORTANT]
> You must be in your local **Administrators** group, or a group with similar permissions, to run diskpart.

#### Parameters

You can run the following commands from the Diskpart command interpreter:

| Command | Description |
| ------- | ----------- |
| [active](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/active.md) | Marks the disk's partition with focus, as active. |
| [add](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/add.md) | Mirrors the simple volume with focus to the specified disk. |
| [assign](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/assign.md) | Assigns a drive letter or mount point to the volume with focus. |
| [attach vdisk](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/attach-vdisk.md) | Attaches (sometimes called mounts or surfaces) a virtual hard disk (VHD) so that it appears on the host computer as a local hard disk drive. |
| [attributes](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/attributes.md) | Displays, sets, or clears the attributes of a disk or volume. |
| [automount](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/automount.md) | Enables or disables the automount feature. |
| [break](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/break.md) | Breaks the mirrored volume with focus into two simple volumes. |
| [clean](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/clean.md) | Removes any and all partition or volume formatting from the disk with focus. |
| [compact vdisk](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/compact-vdisk.md) | Reduces the physical size of a dynamically expanding virtual hard disk (VHD) file. |
| [convert](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md) | Converts file allocation table (FAT) and FAT32 volumes to the NTFS file system, leaving existing files and directories intact. |
| [create](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/create.md) | Creates a partition on a disk, a volume on one or more disks, or a virtual hard disk (VHD). |
| [delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/delete.md) | Deletes a partition or a volume. |
| [detach vdisk](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/detach-vdisk.md) | Stops the selected virtual hard disk (VHD) from appearing as a local hard disk drive on the host computer. |
| [detail](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/detail.md) | Displays information about the selected disk, partition, volume, or virtual hard disk (VHD). |
| [exit](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/exit.md) | Exits the diskpart command interpreter. |
| [expand vdisk](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/expand-vdisk.md) | Expands a virtual hard disk (VHD) to the size that you specify. |
| [extend](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/extend.md) | Extends the volume or partition with focus, along with its file system, into free (unallocated) space on a disk. |
| [filesystems](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/filesystems.md) | Displays information about the current file system of the volume with focus and lists the file systems that are supported for formatting the volume. |
| [format](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/format.md) | Formats a disk to accept Windows files. |
| [gpt](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/gpt.md) | Assigns the gpt attribute(s) to the partition with focus on basic GUID partition table (gpt) disks. |
| [help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/help.md) | Displays a list of the available commands or detailed help information on a specified command. |
| [import](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/import_1.md) | Imports a foreign disk group into the disk group of the local computer. |
| [inactive](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/inactive.md) | Marks the system partition or boot partition with focus as inactive on basic master boot record (MBR) disks. |
| [list](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/list.md) | Displays a list of disks, of partitions in a disk, of volumes in a disk, or of virtual hard disks (VHDs). |
| [merge vdisk](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/merge-vdisk.md) | Merges a differencing virtual hard disk (VHD) with its corresponding parent VHD. |
| [offline](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/offline.md) | Takes an online disk or volume to the offline state. |
| [online](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/online.md) | Takes an offline disk or volume to the online state. |
| [recover](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/recover.md) | Refreshes the state of all disks in a disk group, attempt to recover disks in an invalid disk group, and resynchronizes mirrored volumes and RAID-5 volumes that have stale data. |
| [rem](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/rem.md) | Provides a way to add comments to a script. |
| [remove](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remove.md) | Removes a drive letter or mount point from a volume. |
| [repair](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/repair.md) | Repairs the RAID-5 volume with focus by replacing the failed disk region with the specified dynamic disk. |
| [rescan](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/rescan.md) | Locates new disks that may have been added to the computer. |
| [retain](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/retain.md) | Prepares an existing dynamic simple volume to be used as a boot or system volume. |
| [san](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/san.md) | Displays or sets the storage area network (san) policy for the operating system. |
| [select](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/select.md) | Shifts the focus to a disk, partition, volume, or virtual hard disk (VHD). |
| [set id](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/set-id.md) | Changes the partition type field for the partition with focus. |
| [shrink](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/shrink.md) | Reduces the size of the selected volume by the amount you specify. |
| [uniqueid](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/uniqueid.md) | Displays or sets the GUID partition table (GPT) identifier or master boot record (MBR) signature for the disk with focus. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Disk management overview](../../storage/disk-management/overview-of-disk-management.md)

- [Storage Cmdlets in Windows PowerShell](/powershell/module/storage/)

---



MIT License. Copyright (c) 2020-2021 Strontic.


