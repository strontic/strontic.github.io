
# convert.exe 

* File Path: `C:\Windows\system32\convert.exe`
* Description: File System Conversion Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B7F09576EA6958004C704E5F4AD13D35`
SHA1 | `FC21F5E51611B8A19F0B5A6E2D8155FFD4C9A400`
SHA256 | `E02C54FDA923DC10375E569D6C5C45D95AF8ED5E6613B073A77DAE2BA0B20AE9`
SHA384 | `BE55FE701A1C59CD496CD71259B068A53368C3F72DE69AAA3506F1F2872D0D287D8D9EF16B4476731F516DBCF34ECF05`
SHA512 | `BF21D3B3AE13A3E21C275054930E20F27D9877A612EAE494232FB0830559699DCEA4DBF9AFBF2538146C260FD47A726D3BB905E84E02ED9F7D31B01573FDA33C`
SSDEEP | `384:eEN9ZWz+IhDbQ7ZUnGtg9yV1Y2yoRk+vKclmPaNcWzqW:PZWz+I9Q1/tUyVeoeOmPa3`

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
* File Version: 10.0.14393.2969 (rs1_release.190503-1820)
* Product Version: 10.0.14393.2969
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


