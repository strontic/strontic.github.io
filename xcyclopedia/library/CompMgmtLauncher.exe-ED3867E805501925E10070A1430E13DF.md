---
title: CompMgmtLauncher.exe | Computer Management Snapin Launcher
excerpt: What is CompMgmtLauncher.exe?
---

# CompMgmtLauncher.exe 

* File Path: `C:\Windows\system32\CompMgmtLauncher.exe`
* Description: Computer Management Snapin Launcher

## Hashes

Type | Hash
-- | --
MD5 | `ED3867E805501925E10070A1430E13DF`
SHA1 | `58743A6E4BE8076B5D84DDC484B6093FB0123049`
SHA256 | `E95853AA8C13062CDF99342D307B13BBE62D61FC653EE0FE7E6EAD4CCD4A46A2`
SHA384 | `E790A90FC55A01ABB1C4EC94713FE0F2EDEAE3238ECA97A612CDE11D045F73B9509238693720F04F4AB90C8EC3AB6A10`
SHA512 | `E4784B15C3B374F4BD422A5BD948C39A7D95D8A0D6A908B50AEF65E7F19C433892A3F69B4DA896209354698590D2125D0EF55EA98193C0A62FF78B0B965D9BC1`
SSDEEP | `1536:F3V5MYdZ1e5zb6j6g8gZ7fRMv3ilVOFGxVz9lOo+vi6Uf:FlbL1epuj6AZ7fRMvusFGxVz9co+Q`
IMP | `5C07F48325D782CDDABE04AA4F7F5B0B`
PESHA1 | `2DBE31B9C629B3FD472312C2EEBF49135240CFD7`
PE256 | `C5D0ED5331B06373B4CF46D08E9252A6CB3B54B6703BCB8B7812BEA66FC58BEE`

## Runtime Data

### Child Processes:
ServerManager.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CompMgmtLauncher.exe |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\system32\PROPSYS.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/e95853aa8c13062cdf99342d307b13bbe62d61fc653ee0fe7e6ead4ccd4a46a2/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-28317A51B8F874BCF5220872269FEC2C.md) | 32
[C:\WINDOWS\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-E0861FA9E0A4B441C6A11405D12D0C30.md) | 38
[C:\windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-EF0DB115967BFB1996403434AA3C9D7E.md) | 33
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-FF9690925244473ECC4C2E5B535B8599.md) | 38
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-984C9F7202A43577C2A3D52A1300FFE7.md) | 41
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CA3A931A56D4B2429A39871131964101.md) | 32
[C:\windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CF83A07EECB55210ADAA65EF8B4C75D8.md) | 33

## Possible Misuse

*The following table contains possible examples of `CompMgmtLauncher.exe` being misused. While `CompMgmtLauncher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_uac_bypass.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_uac_bypass.yml) | `- '\CompMgmtLauncher.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


