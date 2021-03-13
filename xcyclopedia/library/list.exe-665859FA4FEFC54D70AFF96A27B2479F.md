---
title: list.exe | Microsoft File Lister
excerpt: What is list.exe?
---

# list.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\list.exe`
* Description: Microsoft File Lister

## Hashes

Type | Hash
-- | --
MD5 | `665859FA4FEFC54D70AFF96A27B2479F`
SHA1 | `2E9288755A0437A0262E8E19A8546777AC7A97FD`
SHA256 | `DFA26FB6AC35987EF743EF64A3BC849E7DCC1C6F5B954368F6A3B03A928424AC`
SHA384 | `42A47A020E6EBD5B9BE2D4644ACD27FA65FD153687B8DFF44DBD281CA69B91806FA9084CEF820FE611E25732A09916A8`
SHA512 | `398D114251F117930DDA8720F0E5FCB75AF4B3CB4E8C77EA463C81573A547F36AF1DB1725EBD8A8CF6CB0E7C196A5FE054C512651B886CEA9D8C6E1B1F392E3F`
SSDEEP | `1536:9UcXs6RbVBxpdD52v5iI99sKlBWRWE279iNugNiAeDpLh:NXxxpdD5E56UByp2TgNiHpl`
IMP | `AA9DED3E543513E55C99238C77B036BD`
PESHA1 | `BFE4063FD38D93BF2BB256E3A07D99871C0031C4`
PE256 | `7D8CC6F2C7216735D671498C597D352F5044399EBC6A38AC8DF9DA7ED89DA793`

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
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\list.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

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


