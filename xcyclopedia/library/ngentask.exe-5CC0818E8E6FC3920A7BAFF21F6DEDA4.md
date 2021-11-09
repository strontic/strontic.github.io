---
title: ngentask.exe | Microsoft .NET Framework optimization service
excerpt: What is ngentask.exe?
---

# ngentask.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe`
* Description: Microsoft .NET Framework optimization service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `5CC0818E8E6FC3920A7BAFF21F6DEDA4`
SHA1 | `B12ADC6C8B7D71AE95B9890F38F23211CDC3950E`
SHA256 | `150BF8A1FF5E05FE0D3E8190D4F3A96E279EAA25B3E40620FEBEE0F623B71E05`
SHA384 | `5ED9EEF74BE842B94FF53821445B7E2BFA2658E3C2283AA8F5620F520FF245458DBB3BC05963FC24FE0F0DA1C3A6C8F1`
SHA512 | `C9098E6241A6CA6515D8100F49DD7747794D2CDFA7E8049CA3C9337433D6DD5EE24B411F400C53CD2B14424D0ED702A23ADCECF7603C027316A30DB3352B539D`
SSDEEP | `1536:X9eXaGuBPGsm5x4v2zUFl7ppN8InFurR+O1S0:N7GuhhmXngXFf8IF5OQ0`
PESHA1 | `61B21AC2FABBCDB600D36B185F902465EF29A898`
PE256 | `D48FECC645EE76720673F08845838ACC9917BBEA695B4DA51D908255A390992A`

## Runtime Data

### Usage (stdout):
```cmhg
NGen Task starting, command line: "C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe" --help
Unrecognized command line option --help

```

### Usage (stderr):
```cmhg
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe [options...]
 This tool reads from the usage log data produced by the runtime, and triggers NGen to occur.
   /RuntimeWide - Parse the fusion stream of the usage logs instead of the App stream. Task runs in machine-wide mode.
   /Critical - Runs as a critical idle task.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe |
C:\WINDOWS\System32\KERNEL32.dll |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\MSCOREE.DLL |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NGenTask.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4341.0 built by: NET48REL1LAST_C
* Product Version: 4.8.4341.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/150bf8a1ff5e05fe0d3e8190d4f3a96e279eaa25b3e40620febee0f623b71e05/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe](ngentask.exe-3142937610966B092CA8886C76A3B113.md) | 80
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ngentask.exe](ngentask.exe-E983CDC58F22C7641CFAB9A21A3171DD.md) | 55

## Possible Misuse

*The following table contains possible examples of `ngentask.exe` being misused. While `ngentask.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\ngentask.exe'  # c:\Windows\Microsoft.NET\Framework(64)\ngentask.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


