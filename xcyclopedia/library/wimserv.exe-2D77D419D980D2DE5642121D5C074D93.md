---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\Windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `2D77D419D980D2DE5642121D5C074D93`
SHA1 | `3B0BE4A5CC4D91B1F6D0AFEC7D53B8A28DEA5F70`
SHA256 | `8BE46FACF743B74F23E69FEB09794C1ABB689C9EC7667F7ED83DBEE8F88E582D`
SHA384 | `25BD9E3237E101FB6C5C2651493ACE3F18D13B82EA3BBF030B036CEE7C815CEBE52E682E2DE65AAE766D5F30D42124F8`
SHA512 | `C733770DD4E42F53B5F3BAAF517F826DF2D9A2D8D50E7C916BCEB3CE297C99E6B9C14B730D10C57F5859CBFFE1DCA220A25DDC1441BD4CA545A0588EF81E7EF5`
SSDEEP | `12288:FcTWNHCfCIVHMJTJrw2TZqCfO2zSj0n4a0P:+ICfCIhnjCfptn4a0P`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\wimserv.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1039 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1039
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\wimserv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


