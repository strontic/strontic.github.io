﻿---
title: sfc.exe | System Integrity Check and Repair
excerpt: What is sfc.exe?
---

# sfc.exe 

* File Path: `C:\Windows\SysWOW64\sfc.exe`
* Description: System Integrity Check and Repair

## Hashes

Type | Hash
-- | --
MD5 | `4A5EAB448C2CCC0FE104F3D2EAFA31E8`
SHA1 | `6C8C046CF68396AF97D56870D576BD3E17EC5DFE`
SHA256 | `9947DAF25487C97017038EFC3E19F6B8D7F3208BBAC05BD9C7DE2CD0A37C48C4`
SHA384 | `81AFA8298A5ED212510C109B2AB1C49B7734CA4A80061DE999B65DE5C2106E1A50A07368B2DF440D0C425D8F82683487`
SHA512 | `11F64F6B78595041EC4A4E5786B0F043F769D20A1BBED62CD90813A773BF6045E61DBFDDBB89503CACE1C0198CD9826A43AED8A8A3679FEDED6CCA677245CE4F`
SSDEEP | `768:4+r4pn+uvQ+4mAwOZIVDxK9E91dhU8lOjw4NUGEBk6a:4+uv/awrIGznbCUGEBk6a`
IMP | `CAC2B6353149BCC7390792522C3321BD`
PESHA1 | `5789893F1A1E2C5C20C4DFC964D0FAF99646BD09`
PE256 | `6D2A22F45E5DE9AA8CC2A2D5F08936061094E6487FB2D02675BAF85C8C77709C`

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

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sfc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/9947daf25487c97017038efc3e19f6b8d7f3208bbac05bd9c7de2cd0a37c48c4/detection/


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


