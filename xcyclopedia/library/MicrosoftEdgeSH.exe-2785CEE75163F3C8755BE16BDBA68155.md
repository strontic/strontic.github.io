---
title: MicrosoftEdgeSH.exe | Microsoft Edge Web Platform
excerpt: What is MicrosoftEdgeSH.exe?
---

# MicrosoftEdgeSH.exe 

* File Path: `C:\Windows\system32\MicrosoftEdgeSH.exe`
* Description: Microsoft Edge Web Platform

## Hashes

Type | Hash
-- | --
MD5 | `2785CEE75163F3C8755BE16BDBA68155`
SHA1 | `CE41DC5BBDDE4F779C2CCFFB119FEFAFDFCAF01D`
SHA256 | `D7A4F824B02C13DAACA06815F1D579612B24D6B0FC4138317FC23D2AA7E24025`
SHA384 | `D8780F65B5672BC4CC496C40F03CC5B8A3A4AACF8BAE509CFDF1E79AB6F4E441B81B47BA1C986899AE6B9D85A3A9A7DA`
SHA512 | `85C126DC5C38E9354035E32FADDBBA11778FBE8EC47B6F7A108BAD35D7762A0B01C4B17CB1184F8C449F8E1138D1A97D6C7EC75030E6DF1B707F428D81741CB2`
SSDEEP | `768:FZymeD5NFlGX3MAtrpgBD+YGiYH3j5cTnYSu9aeqb1+ync+:FZm5NFlGX3ZtrpgClNtSuHq5+ync+`
IMP | `A34FE6D82B7B3A5185FB8B7B2D288801`
PESHA1 | `A16BE3B8BFDA60477E3757896886848995F04890`
PE256 | `7E34D92FF0D975A33563B5F3E0D5AD4EB57866E5DBF73C8A94D98EEF6A5FF1FF`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\system32\edgeIso.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\system32\iertutil.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MicrosoftEdgeSH.exe |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\SYSTEM32\profext.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\system32\USERENV.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WINTRUST.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeSH.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/d7a4f824b02c13daaca06815f1d579612b24d6b0fc4138317fc23d2aa7e24025/detection/


## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeSH.exe` being misused. While `MicrosoftEdgeSH.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- "MicrosoftEdgeSH.exe"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


