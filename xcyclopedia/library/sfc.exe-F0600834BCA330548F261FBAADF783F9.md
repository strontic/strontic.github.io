﻿---
title: sfc.exe | System Integrity Check and Repair
excerpt: What is sfc.exe?
---

# sfc.exe 

* File Path: `C:\Windows\system32\sfc.exe`
* Description: System Integrity Check and Repair

## Hashes

Type | Hash
-- | --
MD5 | `F0600834BCA330548F261FBAADF783F9`
SHA1 | `8D76F73ECBD6837424C1845FF3E3BFA09B16F79D`
SHA256 | `E7A57BE660B32AEBEC5C59786D9F56DE1DFB9E4BCE2B1AAEFEA94CAAC5C63E42`
SHA384 | `F0972D3556DC3B1B630799073C796EC76C6332458E757323E598ABAA908EC68FFBF055A48F9BF8D665ECA9B1288A6368`
SHA512 | `6F701FA28AF5D235A72337120510FC42CCAEE7DF654AC0D4E9DC14AC63DB6322C49A4D6CD2E63D74CE53FA34FDF735A08D15A0EBEE56DC4F9A9766493DA040E1`
SSDEEP | `1536:hO1eY5wNp9njw3I8QQ/Q/CZ2ujdQsGyhP:m35J/0j+GsP`
IMP | `B189E8379F15898C31342CC9D3ED02C7`
PESHA1 | `416355E7F3D1A292D9E0480B8D1DB60E5A51A6AE`
PE256 | `DBF3FE018639860EF7A8FD0C10887812308047CAF7B5C744D6F9AF9FB7D514DF`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) Windows (R) Resource Checker Version 6.0
Copyright (C) Microsoft Corporation. All rights reserved.

Scans the integrity of all protected system files and replaces incorrect versions with 
correct Microsoft versions.

SFC [/SCANNOW] [/VERIFYONLY] [/SCANFILE=<file>] [/VERIFYFILE=<file>]
    [/OFFWINDIR=<offline windows directory> /OFFBOOTDIR=<offline boot directory> [/OFFLOGFILE=<log file path>]]

/SCANNOW        Scans integrity of all protected system files and repairs files with
                problems when possible.
/VERIFYONLY     Scans integrity of all protected system files. No repair operation is
                performed.
/SCANFILE       Scans integrity of the referenced file, repairs file if problems are
                identified. Specify full path <file>
/VERIFYFILE     Verifies the integrity of the file with full path <file>.  No repair
                operation is performed.
/OFFBOOTDIR     For offline repair, specify the location of the offline boot directory
/OFFWINDIR      For offline repair, specify the location of the offline windows directory
/OFFLOGFILE     For offline repair, optionally enable logging by specifying a log file path

e.g.

        sfc /SCANNOW
        sfc /VERIFYFILE=c:\windows\system32\kernel32.dll
        sfc /SCANFILE=d:\windows\system32\kernel32.dll /OFFBOOTDIR=d:\ /OFFWINDIR=d:\windows
        sfc /SCANFILE=d:\windows\system32\kernel32.dll /OFFBOOTDIR=d:\ /OFFWINDIR=d:\windows /OFFLOGFILE=c:\log.txt
        sfc /VERIFYONLY

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sfc.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sfc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/e7a57be660b32aebec5c59786d9f56de1dfb9e4bce2b1aaefea94caac5c63e42/detection


## Possible Misuse

*The following table contains possible examples of `sfc.exe` being misused. While `sfc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s4 = "\\sfc.exe" fullword ascii /* score: '11.005' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## sfc

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Scans and verifies the integrity of all protected system files and replaces incorrect versions with correct versions. If this command discovers that a protected file has been overwritten, it retrieves the correct version of the file from the **systemroot\system32\dllcache** folder, and then replaces the incorrect file.

> [!IMPORTANT]
> You must be logged on as a member of the Administrators group to run this command.

### Syntax

```
sfc [/scannow] [/verifyonly] [/scanfile=<file>] [/verifyfile=<file>] [/offwindir=<offline windows directory> /offbootdir=<offline boot directory>]
```

#### Parameters

| Parameter | Description |
|--|--|
| /scannow | Scans the integrity of all protected system files and repairs files with problems when possible. |
| /verifyonly | Scans the integrity of all protected system files, without performing repairs. |
| /scanfile `<file>` | Scans the integrity of the specified file (full path and filename) and attempts to repair any problems if they're detected. |
| /verifyfile `<file>` | Verifies the integrity of the specified file (full path and filename), without performing repairs. |
| /offwindir `<offline windows directory>` | Specifies the location of the offline windows directory, for offline repair. |
| /offbootdir `<offline boot directory>` | Specifies the location of the offline boot directory for offline repair. |
| /? | Displays help at the command prompt. |

### Examples

To verify the *kernel32.dll file*, type:

```
sfc /verifyfile=c:\windows\system32\kernel32.dll
```

To set up the offline repair of the *kernel32.dll* file with an offline boot directory set to *D:\* and an offline windows directory set to *D:\windows*, type:

```
sfc /scanfile=D:\windows\system32\kernel32.dll /offbootdir=D:\ /offwindir=d:\windows
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


