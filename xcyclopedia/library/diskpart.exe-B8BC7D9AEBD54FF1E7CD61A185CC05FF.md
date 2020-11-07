---
title: diskpart.exe | DiskPart
excerpt: What is diskpart.exe?
---

# diskpart.exe 

* File Path: `C:\Windows\system32\diskpart.exe`
* Description: DiskPart

## Hashes

Type | Hash
-- | --
MD5 | `B8BC7D9AEBD54FF1E7CD61A185CC05FF`
SHA1 | `7654183139B9DB5505A74B58E7F0DEC6F17FCE8B`
SHA256 | `B9AA0F0F7C8924BD38734B8DE08D435FB2E73EEB16B89D4EA5BFE6F2AC06B54E`
SHA384 | `7D49A0F80E9A7CEFC465B24A59C1A38EB494B7CEDA2A2778DA72082609F58BF87C5EE2E1E8EF19F136E1AF78B2F28D64`
SHA512 | `28118CBC70489D2E1813BCE1BF7FC1FAEEDCC4CD46F9C1E1E2142A3DE6A4488760ABDD6097B8AC484A6A559F7F81AECD953392124562011C1EEC227BA9D6CFEF`
SSDEEP | `3072:BW48cN69DcPeNUEUXG2O87UATXX7CrtFtt5WTLfV5FfxEwV:H8cN69I2uESGibXChd56Ltrm`
IMP | `F82C2F5655093594CEAD2DBD23248DE9`
PESHA1 | `963E524794EB9BEEAC6D36D93F47971E64BD74BC`
PE256 | `259DBE480B1352E380B2E2826F472D43958200B194F8AD7CFD8F900AE5841AFB`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft DiskPart version 10.0.19041.610

Copyright (C) Microsoft Corporation.
On computer: 4BBCEEA8-6A14-4

Microsoft DiskPart syntax:
	diskpart [/s <script>] [/?]

	/s <script> - Use a DiskPart script.
	/?          - Show this help screen.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\diskpart.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: diskpart.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/b9aa0f0f7c8924bd38734b8de08d435fb2e73eeb16b89d4ea5bfe6f2ac06b54e/detection


## Possible Misuse

*The following table contains possible examples of `diskpart.exe` being misused. While `diskpart.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- '*\diskpart.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- Diskpart.exe usage to manage partitions on the local hard drive` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- diskpart.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## diskpart

> Applies to: Windows 10, Windows 8.1, Windows 8, Windows 7, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012, and Windows Server 2008 R2, Windows Server 2008

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
| [import](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/import.md) | Imports a foreign disk group into the disk group of the local computer. |
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



MIT License. Copyright (c) 2020 Strontic.


