---
title: VSSVC.exe | Microsoft Volume Shadow Copy Service
excerpt: What is VSSVC.exe?
---

# VSSVC.exe 

* File Path: `C:\Windows\system32\VSSVC.exe`
* Description: Microsoft Volume Shadow Copy Service

## Hashes

Type | Hash
-- | --
MD5 | `2A6BB06A14D810601F8CA02A98A3E16F`
SHA1 | `D2720CDBF4A96A21266FBEEC4D79182D983D979B`
SHA256 | `0BA31F101507CD279108F7845AA7EF38B7ADC2E595921F6A1C09954A2315409D`
SHA384 | `0345C6CCCDA1C5C90B4417EC8BCF2B1067811454F1EF4C820D4E0A6B4AE56AEAF959CE6C0896716DAB45451B03AC7785`
SHA512 | `E541523ABF25744A5A2AB6D9B827AE69A88A1942E1203D7221F118377E99FC67BD48A6775B0244926693B0ACBE8FD207085EF7AF36D743CC5893BC2288B82253`
SSDEEP | `24576:h4A9Q+MAmdFWAfPf0irTqAs8ndjGUbXCZvyg3cvVQv0b/:hAAmfXfVrxs8dSYCZvygMNQ8b/`
IMP | `DBAF0083B9DB3B427241890602C826A3`
PESHA1 | `BD5CE9B6276D857BCF92BE0D622E66E1F1BEF5FC`
PE256 | `489066B79878A674078F317AB243630BFACD290011323BA9578643AE58F1BEFC`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\VSSVC.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSVC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/0ba31f101507cd279108f7845aa7ef38b7adc2e595921f6a1c09954a2315409d/detection


## Possible Misuse

*The following table contains possible examples of `VSSVC.exe` being misused. While `VSSVC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\vssvc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


