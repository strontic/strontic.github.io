---
title: bcdboot.exe | Bcdboot utility
---

# bcdboot.exe 

* File Path: `C:\WINDOWS\system32\bcdboot.exe`
* Description: Bcdboot utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1B79840301B3CC6D57EEB26CC2D05E5D`
SHA1 | `2DFAB8018299855E69D6D47567B849D8C7D12BFC`
SHA256 | `57D1F9D55B2162A831C9F7C681A1616EE7E8E5091D2BC4873550A62AFB0B24AD`
SHA384 | `2307F31FB099862340EF2CBAF2608C665F0081CC5EDEA64756C0CEBB9FF9CDD00F99791C912AB1E95C44967F22E2772F`
SHA512 | `FC333D5DA133E34BBB603C5EBFB7C012F75D8F8D22837B9D8B7B71405AF0B462F8F6B1EBAEDDE02419DABD6E5E5D48A78B04602F46AE7CB993E88709CC57339F`
SSDEEP | `3072:RwaCz1ddjwX62Jlwj9C9fTVDP6QfgNzCqP9TTPec6UPNznjEz9:KaCxddjwq2Ij9CNJ+QYNuqPBfJE`

## Runtime Data

### Usage (stdout):
```Batchfile

Bcdboot - Bcd boot file creation and repair tool.

The bcdboot.exe command-line tool is used to copy critical boot files to the
system partition and to create a new system BCD store.

bcdboot <source> [/l <locale>] [/s <volume-letter> [/f <firmware>]] [/v]
                 [/m [{OS Loader ID}]] [/addlast] [/p] [/c]

  source     Specifies the location of the windows system root.

  /l         Specifies an optional locale parameter to use when
             initializing the BCD store. The default is US English.

  /s         Specifies an optional volume letter parameter to designate
             the target system partition where boot environment files are
             copied.  The default is the system partition identified by
             the firmware.

  /v         Enables verbose mode.

  /m         If an OS loader GUID is provided, this option merges the
             given loader object with the system template to produce a
             bootable entry. Otherwise, only global objects are merged.

  /d         Specifies that the existing default windows boot entry
             should be preserved.

  /f         Used with the /s command, specifies the firmware type of the
             target system partition. Options for <firmware> are 'UEFI',
             'BIOS', or 'ALL'.

  /addlast   Specifies that the windows boot manager firmware entry
             should be added last. The default behavior is to add it
             first.

  /bcdclean  Clean the BCD Store. By default, simply removes any duplicate
             entries in the BCD. Can be followed by 'full'. In this case,
             each entry is scanned. If the corresponding device for that entry
             does not exist, the entry is deleted.

  /p         Specifies that the windows boot manager firmware entry
             position should be preserved. If entry does not exist,
             new entry will be added in the first position.

  /c         Specifies that any existing objects described by the template
             should not be migrated.

Examples: bcdboot c:\windows /l en-us
          bcdboot c:\windows /s h:
          bcdboot c:\windows /s h: /f UEFI
          bcdboot c:\windows /m {00000000-0000-0000-0000-000000000000}
          bcdboot c:\windows /d /addlast
          bcdboot c:\windows /p

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bcdboot.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## bcdboot

Enables you to quickly set up a system partition, or to repair the boot environment located on the system partition. The system partition is set up by copying a simple set of Boot Configuration Data (BCD) files to an existing empty partition.

### Syntax

```
bcdboot <source> [/l] [/s]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| source | Specifies the location of the Windows directory to use as the source for copying boot environment files. |
| /l | Specifies the locale. The default locale is US English. |
| /s | Specifies the volume letter of the system partition. The default is the system partition identified by the firmware. |

### Examples

For information about where to find BCDboot and examples of how to use this command, see the [BCDboot Command-Line Options](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-8.1-and-8/hh824874(v=win.10)) topic.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


