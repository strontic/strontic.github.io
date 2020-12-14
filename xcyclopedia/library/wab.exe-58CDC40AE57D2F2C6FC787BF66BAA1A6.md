---
title: wab.exe | Windows Contacts
excerpt: What is wab.exe?
---

# wab.exe 

* File Path: `C:\Program Files (x86)\Windows Mail\wab.exe`
* Description: Windows Contacts

## Hashes

Type | Hash
-- | --
MD5 | `58CDC40AE57D2F2C6FC787BF66BAA1A6`
SHA1 | `18DDC9D22EEFC841D98BCF261B0065285399E8DC`
SHA256 | `079ED81718D31EF8303DF2350C72E452E6CE40CEF8E048EF46350C4DFD6A78D0`
SHA384 | `A6AFDC81F0380F02CC5E0C70E490AE46AB3E5C38DA7965D78926E2F9069DCCAF786F4DDA96ECC90D2DD3B47976BED863`
SHA512 | `3EC0530B8DFA46000879A2115450075F3AFBEB672D9F90172D98CF82418673B7FC5BD0682D439B17FD8DD820C24C783A0DEC7BD7DBA273EA37F07716AD9222B9`
SSDEEP | `12288:2Tx5KRZ18xtSP+szdcIugOO50MMEMOkP:TmxtSP+sJ+O5FWPP`
IMP | `0EF04699A47ECF41DF8E2B3DD1491D68`
PESHA1 | `83E9D70BAE5B510A9B573A2C5F2B0F1E78E3D901`
PE256 | `11167B546AE827A288820902BE2A9A2E597D4CBC01069786AA28436E8C003D41`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Program Files (x86)\Common Files\system\en-US\wab32res.dll.mui | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\imageres.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_261b62a767ca4e6d | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme2131664586 | Section
\Windows\Theme966197582 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Mail\wab.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WAB.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/079ed81718d31ef8303df2350c72e452e6ce40cef8e048ef46350c4dfd6a78d0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Windows Mail\wab.exe](wab.exe-1763CB1756D4DF101F71DBC360C875E1.md) | 97

## Possible Misuse

*The following table contains possible examples of `wab.exe` being misused. While `wab.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `Name: Wab.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `- Command: wab.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `- Path: C:\Program Files\Windows Mail\wab.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `- Path: C:\Program Files (x86)\Windows Mail\wab.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `- IOC: WAB.exe should normally never be used` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wab.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wab.yml) | `- Link: http://www.hexacorn.com/blog/2018/05/01/wab-exe-as-a-lolbin/` | 



MIT License. Copyright (c) 2020 Strontic.


