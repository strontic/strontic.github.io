---
title: rdrleakdiag.exe | Microsoft Windows Resource Leak Diagnostic
excerpt: What is rdrleakdiag.exe?
---

# rdrleakdiag.exe 

* File Path: `C:\Windows\SysWOW64\rdrleakdiag.exe`
* Description: Microsoft Windows Resource Leak Diagnostic

## Hashes

Type | Hash
-- | --
MD5 | `A44B52E1F19718E6C5CC4A3DF406E2A3`
SHA1 | `EC8F78868D0BEF3780D0BE82B2975539B9844449`
SHA256 | `20ADE22FA45A4BF6C0EF5C17B21E9661DB6AAC6968AED663349B27C4F3021961`
SHA384 | `9DDC87B3F0B2825DCC5E24AB372B4DD77438C3E1CD877A8731AEFA81AECF33F8C204572C8D2793C6C9366B88156EE4A9`
SHA512 | `E32E5A5EB98E4D282C32DB9EA878FF87111390D2733268C468209C448D7F9F2C03983DB5AEF733F5251EEBBD8A8C392B9B527741477EDEE3A92B1F74266BD954`
SSDEEP | `768:7heXra9e4GeB8yM/2Iy6/Nco2NVhIz6A:Q7aiemyKe6/Noh`
IMP | `26A323EA27CD8D60E52073979B67F593`
PESHA1 | `75A7845D3068912236A74D51F67337261903C02C`
PE256 | `74AE6D2897BBC00FA35CE7C450091492F980F56A41D29CCC883F883ACB063219`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\rdrleakdiag.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdrLeakDiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/20ade22fa45a4bf6c0ef5c17b21e9661db6aac6968aed663349b27c4f3021961/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\rdrleakdiag.exe](rdrleakdiag.exe-E2085A5CDC42A0F04BE67A4C00BAE7E8.md) | 40

## Possible Misuse

*The following table contains possible examples of `rdrleakdiag.exe` being misused. While `rdrleakdiag.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `title: Process Dump via RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `description: Detects a process memory dump performed by RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `OriginalFileName: RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


