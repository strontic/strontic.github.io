---
title: diskperf.exe | Disk Performance Configuration Utility
excerpt: What is diskperf.exe?
---

# diskperf.exe 

* File Path: `C:\Windows\system32\diskperf.exe`
* Description: Disk Performance Configuration Utility

## Hashes

Type | Hash
-- | --
MD5 | `5038A44C5A7351D77A285877EB7CC95A`
SHA1 | `F61F23883F3BDDB6E01CAE6967D4EB37F58922BF`
SHA256 | `29BC6751B20EAFAA4E2748370B5358F0C7AE679627DF2E01808615D96AA89A32`
SHA384 | `3BA74BE13DA42513AA162C44DBFB9D8220D3AA117EF19FDC8172F2ACCD14D4C729EA8EDC0F56693818F16276AF88C44B`
SHA512 | `D72AD7485EBB479497A164E9185D81438F8345F58E19C3C8ABF9B9806B425944FB27360B5B79D355EC0C2D7761A2321A4A98AC5C9DB62B54DA6CE69D8A762A28`
SSDEEP | `384:t1Y8+hriGBKOuP5X5ol44lDHtiPSmLkyT8QwgrZiOMoAt1GgrOweQZsadWDJW:tAhrtQol44lDASG8uiOMotwzZsa+`
IMP | `8C30315F0059261E5778F328A7850B04`
PESHA1 | `13F50EBE3AD24FE895F2B8CA7A5836713D084B23`
PE256 | `523BD8D0FA084E3C44F7DAE129D009D1982C79D93C672E227BC3ABEE2086DF4F`

## Runtime Data

### Usage (stdout):
```cmhg


DISKPERF=====================

Starts and stops system disk performance counters.

Used without the command switches, DISKPERF reports what disk
performance counters are enabled on the specified Windows 2000 computer.

Disk performance counters can be specified to report the
performance of the individual physical drives, or the individual
logical drives or storage volumes. Note that these two sets of
performance counters are measured independently. The user
has the option of enabling and disabling them independently
using the command line switches.
NOTE: This command can only be used to control remote
Windows 2000 systems. In newer systems, these performance counters
are automatically enabled.

DISKPERF [-Y[D|V] | -N[D|V]] [\\computername]

  -Y  Sets the system to start all disk performance counters
      when the system is restarted.

  -YD Enables the disk performance counters for physical drives.
      when the system is restarted.
  -YV Enables the disk performance counters for logical drives
      or storage volumes when the system is restarted.
  -N  Sets the system to disable all disk performance counters
      when the system is restarted.

  -ND Disables the disk performance counters for physical drives.
  -NV Disables the disk performance counters for logical drives.
  \\computername        Is the name of the computer you want to
                        see or set disk performance counter use.
                        The computer must be a Windows 2000 system.
  NOTE: Disk performance counters are permanently enabled on
        systems beyond Windows 2000.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\diskperf.exe |
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

* Original Filename: DISKPERF.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/29bc6751b20eafaa4e2748370b5358f0c7ae679627df2e01808615d96aa89a32/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\diskperf.exe](diskperf.exe-7FACE5A6C4FA7913A7051BB8C8F9E7ED.md) | 82


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## diskperf

The **diskperf** command remotely enables or disables physical or logical disk performance counters on computers running Windows.

### Syntax

```
diskperf [-y[d|v] | -n[d|v]] [\\computername]
```

### Options

| Option | Description |
| ------ | ----------- |
| -y | Starts all disk performance counters when the computer restarts. |
| -yd | Enables disk performance counters for physical drives when the computer restarts. |
| -yv | Enables disk performance counters for logical drives or storage volumes when the computer restarts. |
| -n | Disables all disk performance counters when the computer restarts. |
| -nd | Disable disk performance counters for physical drives when the computer restarts. |
| -nv | Disable disk performance counters for logical drives or storage volumes when the computer restarts. |
| `\\<computername>` | Specifies the name of the computer where you want to enable or disable disk performance counters. |
| -? | Displays context sensitive help. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


