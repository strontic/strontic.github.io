﻿---
title: CompMgmtLauncher.exe | Computer Management Snapin Launcher
excerpt: What is CompMgmtLauncher.exe?
---

# CompMgmtLauncher.exe 

* File Path: `C:\Windows\system32\CompMgmtLauncher.exe`
* Description: Computer Management Snapin Launcher

## Hashes

Type | Hash
-- | --
MD5 | `FF9690925244473ECC4C2E5B535B8599`
SHA1 | `14B1887A1979904AE2AEFB582BCBDBB33DF66A5A`
SHA256 | `764AD199D40BFD87C0906470A816422ECDAA7CAFF7DF97592922B068FA9C5F40`
SHA384 | `91B06E9726F88D28645FA864D692B72D7E02D585925B97D56ADBA97085846A7C7A26C5AA7C508FE5A36C027FD43E16F2`
SHA512 | `096DEF64516A9268E388EB06CEAA34E0772D9AD041A5368F5F68036DBA3DC5F756E226A00BD6A8B5710B9A075ADD2849E180E68603430873685330A95D7802A1`
SSDEEP | `1536:PHsdhnqKTs6GHQm7cMvn3MuD4ptcD2e9lOo+vi6Uf:PMnnq25Gwm7cMv3p4ptcCe9co+Q`
IMP | `5C07F48325D782CDDABE04AA4F7F5B0B`
PESHA1 | `B3ABD82ABA30E9678C03893E75B2AA432BB1C420`
PE256 | `A4AF3E4F731BF33178E2B415552770CE9BD16F6EDBB48F14E30262A22DD2EAA1`

## Runtime Data

### Child Processes:
mmc.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CompMgmtLauncher.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompMgmtLauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/764ad199d40bfd87c0906470a816422ecdaa7caff7df97592922b068fa9c5f40/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-28317A51B8F874BCF5220872269FEC2C.md) | 33
[C:\WINDOWS\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-BEC3F5CE1CACCF010912D35A2AD53039.md) | 32
[C:\WINDOWS\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-E0861FA9E0A4B441C6A11405D12D0C30.md) | 43
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-ED3867E805501925E10070A1430E13DF.md) | 38
[C:\windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-EF0DB115967BFB1996403434AA3C9D7E.md) | 35
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-984C9F7202A43577C2A3D52A1300FFE7.md) | 33
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CA3A931A56D4B2429A39871131964101.md) | 36
[C:\windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CF83A07EECB55210ADAA65EF8B4C75D8.md) | 35

## Possible Misuse

*The following table contains possible examples of `CompMgmtLauncher.exe` being misused. While `CompMgmtLauncher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_uac_bypass.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_uac_bypass.yml) | `- '\CompMgmtLauncher.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


