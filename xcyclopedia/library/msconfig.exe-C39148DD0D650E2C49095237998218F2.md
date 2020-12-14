---
title: msconfig.exe | System Configuration Utility
excerpt: What is msconfig.exe?
---

# msconfig.exe 

* File Path: `C:\Windows\system32\msconfig.exe`
* Description: System Configuration Utility

## Screenshot

![msconfig.exe](screenshots/msconfig.exe-FA81544250A477790C003D6D88256078-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `C39148DD0D650E2C49095237998218F2`
SHA1 | `950228195DC712E9E94F176518E4182F0F2911AF`
SHA256 | `D651FD59887B01833F6434C3E7540CA0E3768E070DC986439355E981E92A110E`
SHA384 | `DA12254A44BC702EB98C77CF2AD63C9E3E542274771BB926E2A21B6EE65F6CD5D01232779FF3612EE9FBF673351672DD`
SHA512 | `6195341CD8115984AEDD4DFB853DA1BF1738DCD2E44CFF382F8135727AABB97BD4F7F0F2D3A88455956E1CA33E3D5F5A165670A03EDD21A39692C8E70FEFEA7B`
SSDEEP | `3072:LBxoaLVCKd0quj5hOl5MGIIC09CS0IIb6V+rpTfUd0/HlGJRA1f:/oow8xuj5hOkp0U6VELUdSGJRW`
IMP | `48D24FD6767DEDAF3D3F9B0CAA18321E`
PESHA1 | `552F375AADBE1EF84AA2D31AF1E01F22AD1A6587`
PE256 | `9BA3F4822B31B5D60C99781EC34BA18270ED51235CDEAA31A0A868756D65E971`

## Runtime Data

### Window Title:
System Configuration

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(R-D)   C:\Windows\System32\en-US\MFC42u.dll.mui | File
(R-D)   C:\Windows\System32\en-US\msconfig.exe.mui | File
(R-D)   C:\Windows\WinSxS\amd64_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.19041.1_en-us_cb612d02732b0fd9\comctl32.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.19041.1_en-us_cb612d02732b0fd9 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme1175649999 | Section
\Windows\Theme601709542 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\msconfig.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msconfig.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/d651fd59887b01833f6434c3e7540ca0e3768e070dc986439355e981e92a110e/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\msconfig.exe](msconfig.exe-9115A4002D040BF7F16AC1E29F353FB9.md) | 41
[C:\Windows\system32\msconfig.exe](msconfig.exe-EA390568A41C03B6327AAE1873664B45.md) | 41
[C:\WINDOWS\system32\msconfig.exe](msconfig.exe-EC284B6D1AFBBA44211F4F0C3EA44838.md) | 44
[C:\Windows\system32\msconfig.exe](msconfig.exe-FA81544250A477790C003D6D88256078.md) | 41

## Possible Misuse

*The following table contains possible examples of `msconfig.exe` being misused. While `msconfig.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Name: Msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Description: MSConfig is a troubleshooting tool which is used to temporarily disable or re-enable software, device drivers or Windows services that run during startup process to help the user determine the cause of a problem with Windows` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- Command: Msconfig.exe -5` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Usecase: Code execution using Msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- Path: C:\Windows\System32\msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `- IOC: msconfig.exe executing` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`msconfig.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


