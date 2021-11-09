---
title: rdpclip.exe | RDP Clipboard Monitor
excerpt: What is rdpclip.exe?
---

# rdpclip.exe 

* File Path: `C:\WINDOWS\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor

## Hashes

Type | Hash
-- | --
MD5 | `94F0594C63731B3A6EEAB348C6B84D47`
SHA1 | `693EF6AE1844C60ADF8DA6F60EAC882DA71E7598`
SHA256 | `AFC25936F02CEEF4DF988E7EC4AB497B6E8119A5306A3045DBB9E93A4441EF9F`
SHA384 | `4C8D155AE4893FA406DC295DE507CDBE0D7D92A83417CF5EC830ACA9057C45997E1046497D8287AEF0B5D09F518E8942`
SHA512 | `C9D9A4B2038A49C3C7C9332A9D7ADFE05709C2597F2E2EB0791D02EFA343C7446D73AA4D290C4C5C3031E8BD6C3BA9B1F83C81A94A00013561F4D962A9064465`
SSDEEP | `12288:O1GmdICEUHaHtNE4CE7NO4JlTI6RPyWXXQ+if9PoqurPp4Q+AY3sH2XU0O6PnPqa:QIrbHtNiE7NO4vTPRPjXXvilPjQtY3s0`
IMP | `75C3586D6FDD16FB1D070F924F106202`
PESHA1 | `0967FFFB10F0417CA0485437EE2D0B08FC5E4DB9`
PE256 | `29052BE08D89F15559621F9408176719B29C377499DA3AA496B9B7435AB61594`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\SYSTEM32\cfgmgr32.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\System32\CRYPT32.dll |
C:\WINDOWS\system32\CRYPTBASE.DLL |
C:\WINDOWS\system32\DEVOBJ.dll |
C:\WINDOWS\system32\dwmapi.dll |
C:\WINDOWS\System32\GDI32.dll |
C:\WINDOWS\System32\gdi32full.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\MPR.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ole32.dll |
C:\WINDOWS\system32\rdpclip.exe |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\shcore.dll |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\System32\win32u.dll |
C:\WINDOWS\SYSTEM32\windows.storage.dll |
C:\WINDOWS\system32\WINSPOOL.DRV |
C:\WINDOWS\system32\WINSTA.dll |
C:\WINDOWS\SYSTEM32\wintypes.dll |
C:\WINDOWS\system32\WTSAPI32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rdpclip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/afc25936f02ceef4df988e7ec4ab497b6e8119a5306a3045dbb9e93a4441ef9f/detection


## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `Image\|endswith: '\rdpclip.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


