---
title: list.exe | Microsoft File Lister
excerpt: What is list.exe?
---

# list.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\list.exe`
* Description: Microsoft File Lister

## Hashes

Type | Hash
-- | --
MD5 | `02FABE339B0F5DBCC7E5C88243B46B7C`
SHA1 | `57571BB40351D3791E284730739F0C29DAF4DA45`
SHA256 | `AC1A48B17543A37655B1BEFDE747BFDD99360A86F41E6E84C1F828C5DB6BBF2D`
SHA384 | `796D6D25151698A8C42CAEBF3C3C95220025DDD86EE044FF046A3FC3443FD37F203392E8B67E8A420636509B65510EF7`
SHA512 | `087E102AF816D521AA9765A925857F05D9494C2266E0FD0FD21660290444432DF4D6F6062DF5C1EDCDD89A9757762711FE2A063AEE700CE98DB4398642E214F6`
SSDEEP | `1536:Xn5EUQTUKXs8LnPhia1W9G8bh4A9ip4W9OXxsXQ58OPT8sFo:Xn5QwQ6bh4A9q4jCyZFo`
IMP | `D176963A2A09326A75676A6B302B30D3`
PESHA1 | `5E38434B0AA6D630EB2F83B62E4251A4EB40348A`
PE256 | `4670E1AD7DF3C2352BC730F0951DDD9C4F0722C950FE36AB39A8F5352ACC79B5`

## Runtime Data

### Usage (stdout):
```cmhg
list [-s:string] [-g:line#] filename, ...

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\list.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: list.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/ac1a48b17543a37655b1befde747bfdd99360a86f41e6e84c1f828c5db6bbf2d/detection



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



MIT License. Copyright (c) 2020 Strontic.


