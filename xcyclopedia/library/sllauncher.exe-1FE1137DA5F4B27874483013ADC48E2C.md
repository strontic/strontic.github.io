---
title: sllauncher.exe | Microsoft Silverlight Out-of-Browser Launcher
excerpt: What is sllauncher.exe?
---

# sllauncher.exe 

* File Path: `C:\Program Files\Microsoft Silverlight\sllauncher.exe`
* Description: Microsoft Silverlight Out-of-Browser Launcher

## Screenshot

![sllauncher.exe](screenshots/sllauncher.exe-0DC901F89BE6746BB33377F182931D77-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `1FE1137DA5F4B27874483013ADC48E2C`
SHA1 | `E48B9D3EB2A30F1138129F421471ED6012F1FDBF`
SHA256 | `AE4F4CB0DAAB04CB4C7DD2D6182EA38DEE8B9CD3E0D7883C944E6CD7630A2F98`
SHA384 | `2F2890F15A6E8F5419867978E05F06C1758BC0182A779B01168598C8CE4C6129B5A7F85B07D44BED7B9271BD3B7C9552`
SHA512 | `2810D6B71EF623CC925C05C20B85C80B6AB0F4279D1340D2A5C95AFFFAFE2EC2C3F95A18CD12655ED2E6050C44E666B4A1277673F4975130D9A1F88195A7C28C`
SSDEEP | `12288:V2c62MvEAxOC87yLbjOO4NbmeBlVcjrIM:C2nP7yl4NqeBlVcjrIM`
IMP | `1BE4179BFB268C55E8CD8A5E9C78F326`
PESHA1 | `09CF3A6CB2C0816F660863EBECADE41E15EC7451`
PE256 | `8A1F09E6A4A169B7A41276FC66A1CAB65D77D8CC099379B7D8A3843C18EE96C7`

## Runtime Data

### Window Title:
Error

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.19041.488_none_4238de57f6b64d28 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Microsoft Silverlight\sllauncher.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sllauncher.exe
* Product Name: Microsoft Silverlight
* Company Name: Microsoft Corporation
* File Version: 5.1.50918.0
* Product Version: 5.1.50918.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/ae4f4cb0daab04cb4c7dd2d6182ea38dee8b9cd3e0d7883c944e6cd7630a2f98/detection/


## Possible Misuse

*The following table contains possible examples of `sllauncher.exe` being misused. While `sllauncher.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_emissarypanda_sep19.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_emissarypanda_sep19.yml) | `title: Emissary Panda Malware SLLauncher` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_emissarypanda_sep19.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_emissarypanda_sep19.yml) | `ParentImage: '*\sllauncher.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


