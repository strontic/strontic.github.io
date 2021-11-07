---
title: rdpclip.exe | RDP Clipboard Monitor
excerpt: What is rdpclip.exe?
---

# rdpclip.exe 

* File Path: `C:\Windows\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor

## Hashes

Type | Hash
-- | --
MD5 | `A52402D6BD4E20A519A2EEEC53332752`
SHA1 | `129F2B6409395EF877B9CA39DD819A2703946A73`
SHA256 | `9D5BE181D9309DEA98039D2CE619AFE745FC8A9A1B1C05CF860B3620B5203308`
SHA384 | `65F13B5ED3D57E4C02CEA226374DF127336F90F3E7AEC6944D49C16640DA780DCD6DF675072F6EB134E82AB3CC740327`
SHA512 | `632DDA67066CFF2B940F27E3F409E164684994A02BDA57D74E958C462B9A0963E922BE4A487C06126CECC9EF34D34913EF8315524BF8422F83C0C135B8AF924E`
SSDEEP | `12288:jrfeYamPVO2t51YqbAOKRJi03fhtV4Y398wXQJnHXQmArTo+7TsRXUK8mEvh13ps:veYamtO2b1YqbATRJi0vUyUwTFnR6qW`
IMP | `810E64B8DF587DC8C95D4C20115A7F58`
PESHA1 | `A6C74654558C87A1B26811EEEE802D4B4A9E88AE`
PE256 | `918AB5D6AE0895DA001DA77D9872FF2B69247478C54E534D977C491B4909BA6C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLE32.dll |
C:\Windows\system32\rdpclip.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9d5be181d9309dea98039d2ce619afe745fc8a9a1b1c05cf860b3620b5203308/detection


## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `Image\|endswith: '\rdpclip.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


