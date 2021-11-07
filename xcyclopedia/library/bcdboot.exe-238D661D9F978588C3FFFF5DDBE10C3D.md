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
MD5 | `238D661D9F978588C3FFFF5DDBE10C3D`
SHA1 | `7860ED7AE4E758ACBBB803E6AFF0A6CCF3C02BDC`
SHA256 | `340B7DF12C0AFC58708A5ADBA76E702613DEE6C8C30399920EFE72146E7E44D7`
SHA384 | `8BCE1EE69715A3A52FC2A404D75C7C94FA60849383116751040417A518F1B09FCB6EB13196167590A640F6676993FC8C`
SHA512 | `2D64267B4BA4D91DDF555EBF6B07A5F5F3A11FD327146D6A17D8168D6F73CFDF41587C40BC6C3CE9505F8A72CDD335B8B15D321AF7D59C055EE8A406A8E5FB4E`
SSDEEP | `3072:l5yO4LP6gg/uYuMeyoRJLc15QIvoKHcfAn8L2eoH0vuHimNdE:l5yO+6luYfGLWoKHIAn8wuYN`
IMP | `9FCFE0EF5D3B0F8A151D4BB5844796D6`
PESHA1 | `F0D4B1187B6819E0A2B0F4CFC4CAB02D069555A6`
PE256 | `7A2058EDF946DA994742A176F8B0BE63CFD9B0B4D6B0B3F0FFEF411C06F76E9C`

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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
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

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/340b7df12c0afc58708a5adba76e702613dee6c8c30399920efe72146e7e44d7/detection



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


