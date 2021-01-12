---
title: wuauclt.exe | Windows Update
excerpt: What is wuauclt.exe?
---

# wuauclt.exe 

* File Path: `C:\Windows\system32\wuauclt.exe`
* Description: Windows Update

## Hashes

Type | Hash
-- | --
MD5 | `A9C97125C0114959C493706B43C3DC8C`
SHA1 | `9F02F926440E40F49A342EC4535F65BF422555ED`
SHA256 | `CC855323B6AB7259C92BD1310211DD95174E43BE2F46C828E38F0060DD2E4488`
SHA384 | `781CDC21628D2D9122352374AD52BEF0535D3EA22EA59E37490A9E3DA60C39A0DA2F71163261FD3E76FA389766AF8DF9`
SHA512 | `DA7A8004A3D5F643288CC19C0F8A14D4307E697FFA0D4034A392D75791714484D7EDA06B7165117B6E18DF6024CAF4CC0320B2774D744666148CFF2E94C51F6F`
SSDEEP | `768:ah2S//Mvy1sxCf1eQAqTE0OVJzOH/K4FVQcqj5fCuKAEXOaEnw1BulMWZqy4Z95h:6//Skra/ylerKD7gYlBRdV9pP`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wuauclt.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wuauclt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-2DC92DE9298D82A2ADC787E22306239D.md) | 93

## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `description: Detects code execution via the Windows Update client (wuauclt)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `- https://dtm.uk/wuauclt/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `- '\wuauclt.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `Name: wuauclt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Command: wuauclt.exe /UpdateDeploymentProvider <Full_Path_To_DLL> /RunHandlerComServer` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Path: C:\Windows\System32\wuauclt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- IOC: wuauclt run with a parameter of a DLL path` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Link: https://dtm.uk/wuauclt/` | 
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


