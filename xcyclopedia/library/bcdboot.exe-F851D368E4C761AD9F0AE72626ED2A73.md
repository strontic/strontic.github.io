---
title: bcdboot.exe | Bcdboot utility
excerpt: What is bcdboot.exe?
---

# bcdboot.exe 

* File Path: `C:\WINDOWS\system32\bcdboot.exe`
* Description: Bcdboot utility

## Hashes

Type | Hash
-- | --
MD5 | `F851D368E4C761AD9F0AE72626ED2A73`
SHA1 | `789D0F5A23645C12C91C9F05D65FFFD034559ED5`
SHA256 | `CF3C4B42C8924F23A70C3E94E2D6189CE2DA95674AFF5D29E3FFDC8AB0C1255A`
SHA384 | `A1C5FAEAFD7F88B1C87F56FBD836D4E275A48582C06045EA6AC296AF52F370C12F86CC4BB9518AE70888EDD83E324264`
SHA512 | `E59A6D501994526B18325C2B4B5B92348336287FD3BAB0B31375C9F23C58C2D8CC8849B0869A8CE92C826B41BF90994B2123DA9C08AB1BF9826C27443B83837E`
SSDEEP | `6144:WRTY9wUJAlvhuFmnlzvbPkfUASQBhkfpFsj:WRqwnlvhuizyBEpOj`
IMP | `DC826693E0D61B026C09EC76503F04A6`
PESHA1 | `4602AB29D51BDAEA72992F5783BEFA3BFE9A46EA`
PE256 | `AE07B70AAFC390CE60D092F82795506013F3CE6A4FD9E00E5DABADD7E9A3413C`

## Runtime Data

### Usage (stdout):
```cmhg

Bcdboot - Bcd boot file creation and repair tool.

The bcdboot.exe command-line tool is used to copy critical boot files to the
system partition and to create a new system BCD store.

bcdboot <source> [/l <locale>] [/s <volume-letter> [/f <firmware>]] [/v]
                 [/vbcd] [/m [{OS Loader ID}]] [/addlast] [/p] [/c]

  source     Specifies the location of the windows system root.

  /l         Specifies an optional locale parameter to use when
             initializing the BCD store. The default is US English.

  /s         Specifies an optional volume letter parameter to designate
             the target system partition where boot environment files are
             copied.  The default is the system partition identified by
             the firmware.

  /v         Enables verbose mode.

  /vbcd      Enables BCD logging.

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
          bcdboot c:\windows /m {d58d10c6-df53-11dc-878f-00064f4f4e08}
          bcdboot c:\windows /d /addlast
          bcdboot c:\windows /p

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\bcdboot.exe |
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

* Original Filename: bcdboot.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/cf3c4b42c8924f23a70c3e94e2d6189ce2da95674aff5d29e3ffdc8ab0c1255a/detection



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

For information about where to find BCDboot and examples of how to use this command, see the [BCDboot Command-Line Options](/previous-versions/windows/it-pro/windows-8.1-and-8/hh824874(v=win.10)) topic.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


