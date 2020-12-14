---
title: sfc.exe | System Integrity Check and Repair
excerpt: What is sfc.exe?
---

# sfc.exe 

* File Path: `C:\Windows\SysWOW64\sfc.exe`
* Description: System Integrity Check and Repair

## Hashes

Type | Hash
-- | --
MD5 | `4D2662964EF299131D049EC1278BE08B`
SHA1 | `C89A23D318FADD7BEFC525EC8B396FBA42C0AD6B`
SHA256 | `167A282DE037BCD2192205EC555890F849C4BF305CD284A763060F3332C453C6`
SHA384 | `01291DD0A1C6CF4A1CEBC5215D0BE89839F94FD1400161D33C03DC03A057A462749023FF214658D1B5FD7FEF946975A0`
SHA512 | `844B73A4C9D55F227FD4CACDF6634DA3BDFB992DAA5AFC5F14E1E28CB8CA9A66A4013E3835EAC934009EB35AA96664FD8D5E2380E41969810F5BB3693B7E8C44`
SSDEEP | `768:DQ4px32PIRdrO8Zxt6MmHgft1g8GjL6EvUio4dU03CFA2PHGTBpPPopUT:VNdr5oMmHgV1lGHfox0gPHGlpP4U`
IMP | `0E481D15F5D349B3A5B413EA7E093AE3`
PESHA1 | `A300AEA0389D9C2AC2902BCBC25CC51B051A00E2`
PE256 | `0A64FE4CE5D824E282D92CC028C6EAD3F76F7A8CC54E5AFB39C2109AF9868A64`

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

### Child Processes:
explorer.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\sfc.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sfc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/167a282de037bcd2192205ec555890f849c4bf305cd284a763060f3332c453c6/detection


## Possible Misuse

*The following table contains possible examples of `sfc.exe` being misused. While `sfc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s4 = "\\sfc.exe" fullword ascii /* score: '11.005' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## sfc

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


