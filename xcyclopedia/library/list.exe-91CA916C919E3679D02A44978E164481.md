---
title: list.exe | Microsoft File Lister
excerpt: What is list.exe?
---

# list.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\list.exe`
* Description: Microsoft File Lister

## Hashes

Type | Hash
-- | --
MD5 | `91CA916C919E3679D02A44978E164481`
SHA1 | `D951034139E07B73418E4F2FF43C951F495ED8BF`
SHA256 | `A7DC325D7203A7E9BC1511BD71231821E17C865E96F3D4311165C4E2002A59D4`
SHA384 | `CC7515DD42F3E5747198547F62F4FC8CEA4C6575E08246706DC050504430EB74A20B5F1C58DB55325A2EE2E1536C888C`
SHA512 | `032E81262CF5D12C28F7C5E14656C9FFA180C99B74823B8F56A95D3386E87EB7872F172C8B3CC8547629C1FAF9D515DEB2662C6263D1A04968B2C33A37D0885B`
SSDEEP | `768:RUs7zXS5I4k1smdfQjAZotwx7pYT1iyLQWIzMvleUoWN+j1q:RUsCufdfQjAC+72L/gMvlesN+g`
IMP | `FDA135ACC15B98BE89058AE7680DEB3F`
PESHA1 | `E5C542CFFA88E3C3CF4F5996230D94A60F22DF0D`
PE256 | `2AC75E01D10627EDA4423E4939AF0B1657BA10931763ACF2BEC2AE098555B7B6`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: list.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 452

## File Scan

* VirusTotal Detections: Unknown



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## list

Displays a list of disks, of partitions in a disk, of volumes in a disk, or of virtual hard disks (VHDs).

### Syntax

```
list { disk | partition | volume | vdisk }
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| disk | Displays a list of disks and information about them, such as their size, amount of available free space, whether the disk is a basic or dynamic disk, and whether the disk uses the master boot record (MBR) or GUID partition table (GPT) partition style. |
| partition | Displays the partitions listed in the partition table of the current disk. |
| volume | Displays a list of basic and dynamic volumes on all disks. |
| vdisk | Displays a list of the VHDs that are attached and/or selected. This command lists detached VHDs if they are currently selected; however, the disk type is set to Unknown until the VHD is attached. The VHD marked with an asterisk (*) has focus. |

##### Remarks

- When listing partitions on a dynamic disk, the partitions might not correspond to the dynamic volumes on the disk. This discrepancy occurs because dynamic disks contain entries in the partition table for the system volume or boot volume (if present on the disk). They also contain a partition that occupies the remainder of the disk in order to reserve the space for use by dynamic volumes.

- The object marked with an asterisk (*) has focus.

- When listing disks, if a disk is missing, its disk number is prefixed with M. For example, the first missing disk is numbered *M0*.

#### Examples

```
list disk
list partition
list volume
list vdisk
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


