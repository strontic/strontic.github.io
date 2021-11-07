---
title: oleview.exe | OLE/COM Object Viewer
excerpt: What is oleview.exe?
---

# oleview.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\oleview.exe`
* Description: OLE/COM Object Viewer

## Screenshot

![oleview.exe](screenshots/oleview.exe-29E1A12E2FC60FBA5FB91D4063108403-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `A5BBC4727B92D18A472C8DFB566CAB1E`
SHA1 | `12E3095AF25E991FA1E5B981AE38A4817F0521F8`
SHA256 | `FCD9002C8CB103B8E28A399075068B7713A3696350C0C2AAF8DD7642711A1481`
SHA384 | `759B4FFE9EA550EBC9F0B5B9FC96A1A2AF9D2CA33BAF2EEF9219FF41FE0592C95151E0BCEDAE98B9D1F39BC25DDBB427`
SHA512 | `3F3B2C60B929A0FC1C19BB3E9A57D6D378F4B01FA24C5BBD74B2175EF433EB48CA17041FE5088CD5352DB185CCC1017C1924C5E6FD2B8E6C77BAE50E92B66863`
SSDEEP | `3072:NyoSSX7XA5RwkP10/Cg+ufLLobyT9S9jDeQPQ9S0bGA:EaXjA5yBF+ma9jDNPwTG`
IMP | `7F02DF18D2B4D893FC5BFAF1D6EB2AB6`
PESHA1 | `DAD88D52033321971FCBD8FA42FCABBC7EA63E2E`
PE256 | `21C6C3591D1711D48BDDCD3B416BEDBB8696668B496D02740C35870929220655`

## Runtime Data

### Window Title:
OLE/COM Object Viewer

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\aclui.dll.mui | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\System32\en-US\MFC42u.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\RotHintTable | Section
\Sessions\1\BaseNamedObjects\1b80HWNDInterface:a90726 | Section
\Sessions\1\Windows\Theme1383959086 | Section
\Windows\Theme2042523233 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\oleview.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: OLEVIEW.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/fcd9002c8cb103b8e28a399075068b7713a3696350c0c2aaf8dd7642711a1481/detection


## Possible Misuse

*The following table contains possible examples of `oleview.exe` being misused. While `oleview.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image\|endswith: '\OleView.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


