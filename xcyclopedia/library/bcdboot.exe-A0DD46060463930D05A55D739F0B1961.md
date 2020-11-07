---
title: bcdboot.exe | Bcdboot utility
excerpt: What is bcdboot.exe?
---

# bcdboot.exe 

* File Path: `C:\Windows\system32\bcdboot.exe`
* Description: Bcdboot utility

## Hashes

Type | Hash
-- | --
MD5 | `A0DD46060463930D05A55D739F0B1961`
SHA1 | `B71F09BBB4004620FFDBF225AAE6F399CFE6CD92`
SHA256 | `04A7284AD746597DDA60589B07CF133C3A1CADF556E555AFF4967CF5EC76A097`
SHA384 | `6D8A50CB2024C08BA3D64295C575689E66DC90B98AA4D666342E4CB16FD8DB27C3994AF9AD7AFF9D968B87600CA947BF`
SHA512 | `9D2A41EF7889A486D5B79DA1F36C0C67AE56DE3A278F0F1CABA4F2144A8B6D0EE6E4696EF366D2D9607EC67CD3F9124D0F3F60ED7D023FACA89D3ECFB0D68590`
SSDEEP | `3072:iBAqaCxGjFhQ5ny02WDNHGR5aK2QAP9wqb83OD+eOT3Rz4DUVQkx:iCqagV5nyNW+aK2vP9d83ODSUUV3`
IMP | `AF86C47D5C1FD207A4F0077D8879A7AB`
PESHA1 | `5E4BE138CFDB20F9F06534089C40449F270B5182`
PE256 | `D0BDFD724A6E14FE6BB5ACB490B2C28E58E5762089DD8A2CD5EF04CE111396FF`

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
C:\Windows\system32\bcdboot.exe |
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

* Original Filename: bcdboot.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/04a7284ad746597dda60589b07cf133c3a1cadf556e555aff4967cf5ec76a097/detection



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



MIT License. Copyright (c) 2020 Strontic.


