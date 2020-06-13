
# convert.exe 

* File Path: `C:\Windows\SysWOW64\convert.exe`
* Description: File System Conversion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `403796E5FE1A26EA37D69B8D4D8BC1BA`
SHA1 | `CFF2A6ABC5B899391B34618D2FC1C88192595030`
SHA256 | `E0A1B8B41A7499048FC515A90865D115B3E7E3CD9356FFD702880935CD2AB2AA`
SHA384 | `92BBC415412F5212800CCA099CB719E11BEF8B8C7B43FE8031A68B83281CD6D1E432258503DB046D1DC471FD8F2E1803`
SHA512 | `6EC004ABDF8FB4054AF0479DB64CA06C602751D861BA5FEA3719F03864BC0A63980BAD0766540F57A0C0BEEE005130505DF5B6EF664C38D00076623EE3B480B0`
SSDEEP | `384:pp4z/zKn/Fuagz8Xf2Idvm/e45PNwWBqWT:ppU/zK/mzpA7OP5`

## Runtime Data

### Usage (stdout):
```Batchfile
Converts a FAT volume to NTFS.

CONVERT volume /FS:NTFS [/V] [/CvtArea:filename] [/NoSecurity] [/X]


  volume      Specifies the drive letter (followed by a colon),
              mount point, or volume name.
  /FS:NTFS    Specifies that the volume will be converted to NTFS.
  /V          Specifies that Convert will be run in verbose mode.
  /CvtArea:filename
              Specifies a contiguous file in the root directory
              that will be the place holder for NTFS system files.
  /NoSecurity Specifies that the security settings on the converted
              files and directories allow access by all users.
  /X          Forces the volume to dismount first if necessary.
              All open handles to the volume will not be valid.

```

### Usage (stderr):
```Batchfile
Invalid drive specification.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONVERT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.2457 (rs1_release_inmarket.180822-1743)
* Product Version: 10.0.14393.2457
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# convert

Converts a disk from one disk type to another.

## Syntax

```
convert basic
convert dynamic
convert gpt
convert mbr
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| [convert basic command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-basic.md) | Converts an empty dynamic disk into a basic disk. |
| [convert dynamic command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-dynamic.md) | Converts a basic disk into a dynamic disk. |
| [convert gpt command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-gpt.md) | Converts an empty basic disk with the master boot record (MBR) partition style into a basic disk with the GUID partition table (GPT) partition style. |
| [convert mbr command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-mbr.md) | Converts an empty basic disk with the GUID Partition Table (GPT) partition style into a basic disk with the master boot record (MBR) partition style. |

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


