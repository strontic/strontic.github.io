---
title: mscorsvw.exe | .NET Runtime Optimization Service
excerpt: What is mscorsvw.exe?
---

# mscorsvw.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\mscorsvw.exe`
* Description: .NET Runtime Optimization Service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `C17EBBA87A1484B3A72BE5F241045B70`
SHA1 | `B0B4928730610938ECD6777CD639A189D2357FE3`
SHA256 | `286CDA2760E25CA64356F82A7420DA8F4B8A3EDCB2B7BFBB75D74B0571995CA7`
SHA384 | `E4E8E4EC316511AB74297A0FDEBAE20E2DA3DA2C7D4693A8C8564F2BC25A885FF007C31F37E2A5C3D531E501FAA1B8F2`
SHA512 | `D1B83B243B310621E0F1A3A9EC4568000747A2FE450F439EC9C26A693E2754B214AF4D877DF149071CC8BC0145B6CCEE1338904413F4C448D5FF306B54FC4918`
SSDEEP | `3072:HAipiUHyesEM+R9A0lBan8iEFGg7s+pT7C:p9tB97an8J7sWT7C`
IMP | `B7B46D14320453EEF45740445AF31BF1`
PESHA1 | `E16607881CAD128AC3F6D59788F9A1F18A3581EC`
PE256 | `2A97E4EDA6A021D3C24D85D88792262025BD2D55DCE7550DE18E1CAAE3F3F20A`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\mscorsvw.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mscorsvw.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4341.0 built by: NET48REL1LAST_C
* Product Version: 4.8.4341.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/286cda2760e25ca64356f82a7420da8f4b8a3edcb2b7bfbb75d74b0571995ca7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\mscorsvw.exe](mscorsvw.exe-D7365B80E8951DDC95F3A8E3AC01D37D.md) | 86

## Possible Misuse

*The following table contains possible examples of `mscorsvw.exe` being misused. While `mscorsvw.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\mscorsvw.exe'  # c:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscorsw.exe for instance`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


