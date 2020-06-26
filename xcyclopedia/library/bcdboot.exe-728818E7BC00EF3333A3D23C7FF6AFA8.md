---
title: bcdboot.exe | Bcdboot utility
---

# bcdboot.exe 

* File Path: `C:\Windows\system32\bcdboot.exe`
* Description: Bcdboot utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `728818E7BC00EF3333A3D23C7FF6AFA8`
SHA1 | `42A50C87008B7EECA9918F47471C74AA2B065D5F`
SHA256 | `6FCE4D0E7A0C3A0D051EFB61CA5AD1E30AF75BCCA01DCD42CD3F49A105F34FFE`
SHA384 | `062187D0487EE03AE1CF82D50C2966FCAE78D3C291943050639DBA3ED36E4DDAB91E06754F059A280D67017D4EB9DB0E`
SHA512 | `24A61D11977F8FCE680F6F2DA80FE354FE8CBB5303E0F01AA162F900B7FA114E6743552D97EA05B6A25873CD2EA375E85A9DF46D3C2B47EC6BB886C4DA276421`
SSDEEP | `3072:BohQoV9ohKGp0qe9kzMVjS5EVk/R6iPeW+cUfbdQ:BohQoVGhKE0qt49Sak/0Dd`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bcdboot.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


