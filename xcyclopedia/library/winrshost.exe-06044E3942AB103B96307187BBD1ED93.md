---
title: winrshost.exe | Host Process for WinRM's Remote Shell plugin
excerpt: What is winrshost.exe?
---

# winrshost.exe 

* File Path: `C:\Windows\SysWOW64\winrshost.exe`
* Description: Host Process for WinRM's Remote Shell plugin

## Hashes

Type | Hash
-- | --
MD5 | `06044E3942AB103B96307187BBD1ED93`
SHA1 | `459432B5421F14A0EDFC1586C1AB416A6F625BF6`
SHA256 | `9572884598BDB3C1A4B7D2E0E1B6945ED62F4172221E468EF53AA5A25E809691`
SHA384 | `B6C277416C47D1E94EE97E5237A6F8591A5509CA378BF2ECAE96DC8C62CE57D91C892E9F7A2C4A3055D330F39E1169D7`
SHA512 | `8F087E5B3D6EB827784350C41687FAB96EA9B971B28FC902765697A5F7E60D02155C2A7393AAD28DE6F59D52E01C41602D15419F9DB49EBCD278D0E29299FD9C`
SSDEEP | `384:gAQKb0LRGc5stCMg2uVYmfmknTTW3ap/Gh1WsnEW:ZTb0Yc5soMg2kHaKp/GhP`
IMP | `84E8D0734E85FF07FA62BE51BF7504A9`
PESHA1 | `816C692BA83D9EE210022512A47CBB65E612C18F`
PE256 | `4AF30F1E5BBA5321F0FC307CB17C215EED2561F44627F651BDF406D17B3F50CD`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\RPC Control\DSECD40 | Section
\Sessions\2\Windows\Theme2131664586 | Section
\Windows\Theme966197582 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\winrshost.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winrshost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/9572884598bdb3c1a4b7d2e0e1b6945ed62f4172221e468ef53aa5a25e809691/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\winrshost.exe](winrshost.exe-6052104B17F7344A9655A3EE30365D1A.md) | 43

## Possible Misuse

*The following table contains possible examples of `winrshost.exe` being misused. While `winrshost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\winrshost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


