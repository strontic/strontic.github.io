---
title: rdrleakdiag.exe | Microsoft Windows Resource Leak Diagnostic
excerpt: What is rdrleakdiag.exe?
---

# rdrleakdiag.exe 

* File Path: `C:\Windows\system32\rdrleakdiag.exe`
* Description: Microsoft Windows Resource Leak Diagnostic

## Hashes

Type | Hash
-- | --
MD5 | `C04F4FB2C7B44E19E85908459D3F0085`
SHA1 | `5352E3C56E4AB1C017CC4571423B3EC9C2629B39`
SHA256 | `D66E1EE7970598A5F34FD4B468B5B7705219E80A8A2784E7B18564831FCA797C`
SHA384 | `35BFF04CEFC1F1A07B78EA3C829935F5FC81A4FDEE92B8C3BDE84E80A07F52D37F2F27E286EC59724D7DBEA5706E29E5`
SHA512 | `81298F03B5D8EF919A4BE90C978A89B19F0945669BE682BF6FEFD35FCC4A7B121AB9F44BB55F81CCD69E079C5F6B67E441915BE58D1C5B0ED60697729AF9526F`
SSDEEP | `768:e9c+P7qBxdbY2rZuv/lOmhqabv28XZACDJMwxKiHHd3nyBQgpHBe/pIP6kFNco2j:GIdVuv/lOmLRdvHpt5A6kFNx5W`
IMP | `5D87ACDE58B6E042FB38FE42B86E9C25`
PESHA1 | `78D441F82CBF5B4BD50AA8E4DFD1261805AFD539`
PE256 | `4D03657D4914B50993DAB38B70720E77F7E6A1CF1C8298070D041498E3B4DC9B`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\rdrleakdiag.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdrLeakDiag.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/d66e1ee7970598a5f34fd4b468b5b7705219e80a8a2784e7b18564831fca797c/detection


## Possible Misuse

*The following table contains possible examples of `rdrleakdiag.exe` being misused. While `rdrleakdiag.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `title: Process Dump via RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `description: Detects a process memory dump performed by RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_process_dump_rdrleakdiag.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_process_dump_rdrleakdiag.yml) | `OriginalFileName: RdrLeakDiag.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


