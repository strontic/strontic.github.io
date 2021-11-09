---
title: FXSSVC.exe | Fax Service
excerpt: What is FXSSVC.exe?
---

# FXSSVC.exe 

* File Path: `C:\WINDOWS\system32\FXSSVC.exe`
* Description: Fax Service

## Hashes

Type | Hash
-- | --
MD5 | `71DBF2B3C25F6CC492490FDA2D6E0ABB`
SHA1 | `2210CE0D517FC746A85965C4C2BC06F160413473`
SHA256 | `D3DD5446664DC47A3CD0F97A0DCD85A3B7164A48CD9A71644302EE483F6A34DE`
SHA384 | `DEB155003120E751C44F1A5C82EFE661ACF0C8C59FDD03E86E55CBE0B57CF52587AF93AF6928413FE19B38883EFD672D`
SHA512 | `3E93EFC11A0E69E51C94D6DB6A84AEE8F9D93535D2033B01C69A63D087DC088B41143D47042651DF9563A3805BD331306687655DA80F2E41B2DF9643B224091D`
SSDEEP | `12288:mqhmhDZsmP0yo21a0WqrVqHraM/2dVKlVzMXVxcgAn:mjsmP0yHaqrVqHra44KDzMsrn`
IMP | `C36DD14BEDCA4B48168C22CF81A7DA66`
PESHA1 | `3A142428B576F0FE4C4D8F564D755F5B88EB933B`
PE256 | `0EC8D2581DE7E74A1288485B543138FBE73D4B6D5EDEA2E9A2FC50DA089C44E0`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\FXSSVC.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FXSSVC.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/d3dd5446664dc47a3cd0f97a0dcd85a3b7164a48cd9a71644302ee483f6a34de/detection


## Possible Misuse

*The following table contains possible examples of `FXSSVC.exe` being misused. While `FXSSVC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_fax_dll.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_fax_dll.yml) | `- fxssvc.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc config Fax binPath= "C:\WINDOWS\system32\fxssvc.exe" >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


