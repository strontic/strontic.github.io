---
title: oleview.exe | OLE/COM Object Viewer
excerpt: What is oleview.exe?
---

# oleview.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\oleview.exe`
* Description: OLE/COM Object Viewer

## Screenshot

![oleview.exe](screenshots/oleview.exe-29E1A12E2FC60FBA5FB91D4063108403-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `29E1A12E2FC60FBA5FB91D4063108403`
SHA1 | `5EDC3DE0ADE3770460981EA9330159272EB7B66B`
SHA256 | `2AD8F23459416A2C1EFA5E333C5FE90D26A3F67A37CE9986CC7A9384B8888BA5`
SHA384 | `83F11A9722A422CD45D891BAD462D62E022A0475E44C88464D7A7D777E731A11E664E5764FF0D0EB9E613EA321724E3B`
SHA512 | `BB0ABD5A2A42E5E18882CD6F9AE5E9DEFA6F54548136F0483036554992565D9989A6B6A20E256AAA59FFF67F699BE87FF812EC541FE376045A10ADC094C8BE8D`
SSDEEP | `3072:mF6DZ33CnS4/QMfz06qeAvd0D1vPD/Hb7f548Km9jDWa+1gQPQ9S8:mF6DmS4/zr0uaUFPDPXfv9jDcbPwp`
IMP | `4048276EA1E1519152D9F28F2E9E23FC`
PESHA1 | `4236ECDD86426F88892699090DDC505327A87BE4`
PE256 | `93C489F6AE064E4BFB025794D063A32765458055971EE54DAE1D775879C4C702`

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
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\RotHintTable | Section
\Sessions\1\BaseNamedObjects\24b4HWNDInterface:5006f8 | Section
\Sessions\1\Windows\Theme1383959086 | Section
\Windows\Theme2042523233 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\oleview.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MFC42u.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21\COMCTL32.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/2ad8f23459416a2c1efa5e333c5fe90d26a3f67a37ce9986cc7a9384b8888ba5/detection


## Possible Misuse

*The following table contains possible examples of `oleview.exe` being misused. While `oleview.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\OleView.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


