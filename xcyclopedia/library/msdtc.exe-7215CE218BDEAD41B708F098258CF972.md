---
title: msdtc.exe | Microsoft Distributed Transaction Coordinator Service
excerpt: What is msdtc.exe?
---

# msdtc.exe 

* File Path: `C:\Windows\system32\msdtc.exe`
* Description: Microsoft Distributed Transaction Coordinator Service

## Hashes

Type | Hash
-- | --
MD5 | `7215CE218BDEAD41B708F098258CF972`
SHA1 | `A002BC39095E7F9A3C3281505A42876F480FB95F`
SHA256 | `1EAB4B9691E9EFA1DA02BDCB84035F65EDA4B525E5AEE925A6E1E4107F8E4F31`
SHA384 | `DCD1B3A7FA630620C1567F4249B6DA7650A1907F0D593445AB643CADF5B438057BCE08F5A7401F1C20A2DD5D55A31CED`
SHA512 | `58D10D21AB916A4E1D21DBFD65856ED95D484622989B2CB6A95C0D6EA49757B18C97AE06DC3B9F32AA88A0D534E0121F04ECA9F0597A952E057FFC69B93426D3`
SSDEEP | `1536:wpfx6C1a800NG/qtbC15ZkuH1A0a4qDLZAQcEzok3E8vroH3S7NtiXE/Lp:u1aLyMBkNv7fcmEAkyXiqp`
IMP | `D76D41E51FC79BF5C56F90FE6A798765`
PESHA1 | `283A9A4B8AA73DB517D2ED2C021263AB3DAE18EA`
PE256 | `7BC6646161700CC43F520B7684EEB40C0E94E2D0806B12616214DE3AABA0AD00`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\msdtc.exe |
C:\Windows\system32\MSDTCLOG.dll |
C:\Windows\system32\MSDTCPRX.dll |
C:\Windows\system32\MSDTCTM.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSDTC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10941.16384 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/1eab4b9691e9efa1da02bdcb84035f65eda4b525e5aee925a6e1e4107f8e4f31/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msdtc.exe](msdtc.exe-2EF846AC66E181BE820B513DBC15B5D2.md) | 66
[C:\Windows\system32\msdtc.exe](msdtc.exe-308F08347923DEEDE7BC03EC7D485841.md) | 68
[C:\windows\system32\msdtc.exe](msdtc.exe-915747E010A9414B069173284A9B93F4.md) | 66
[C:\WINDOWS\system32\msdtc.exe](msdtc.exe-DC59FE37CFF118B6DAC426FE9923B32C.md) | 75

## Possible Misuse

*The following table contains possible examples of `msdtc.exe` being misused. While `msdtc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_lazarus_session_highjack.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_lazarus_session_highjack.yml) | `- '*\msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


