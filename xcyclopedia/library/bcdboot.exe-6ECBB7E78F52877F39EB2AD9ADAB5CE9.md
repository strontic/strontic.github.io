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
MD5 | `6ECBB7E78F52877F39EB2AD9ADAB5CE9`
SHA1 | `4D04271BD419CEF7D219C702A779BB85BC01334E`
SHA256 | `D8F1C8A9D019A9430366322D78D76D5647E30664E2D96B3A5FB87738D603D19B`
SHA384 | `5AE5A7B48C8587ECDEE726DB3FE5F56A51E0447EB4CBDD7755D54FDD823A59F246BF8B70E75AA67E0615AF63351BBDA4`
SHA512 | `D247606D7CAD16C7DC5927F8AEA64CD3C2E80DBE80183685F7721F105D447816CF1DDEF126A9C13BE5305E3E028D09A76AB78E4CD209B619BAF5488524B18988`
SSDEEP | `3072:/82iEYVE+5UdD2To8pN8mNlxYPcKrg2aP6nONeeR++2LKn2ONUml:biZVNUdDa7N8yjKrg5PeKWjKUm`
IMP | `F4BBB8FABFB86F652548E2B91DF66B99`
PESHA1 | `6BE8794E215504DDB4C25E4A9DC1018A3D13C0D7`
PE256 | `8355A29037F7B3C17DD61B8B08BD0390249A64A01FD19C6315458A96790D986E`

## Runtime Data

### Usage (stdout):
```cmhg

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
          bcdboot c:\windows /m {d58d10c6-df53-11dc-878f-00064f4f4e08}
          bcdboot c:\windows /d /addlast
          bcdboot c:\windows /p

```

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/d8f1c8a9d019a9430366322d78d76d5647e30664e2d96b3a5fb87738d603d19b/detection/



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


