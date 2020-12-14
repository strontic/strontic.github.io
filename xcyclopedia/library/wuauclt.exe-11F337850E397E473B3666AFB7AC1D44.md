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
MD5 | `11F337850E397E473B3666AFB7AC1D44`
SHA1 | `C2CDB95CB70A1C9D6908A286A61B3A3E01A6C7DE`
SHA256 | `3BF0C76DD0B3FA97C14E765E5B0C02EB4FC6BCD539EA382B8A70E994749A5DD7`
SHA384 | `B6C879EC0F11542CD47DA8D386EF9AC6DD60AA863370E1095F7741898E049D0C7F925F0F8A145F3654A4569F8EFAB23D`
SHA512 | `6703CD49A5090E176F178F1A8B6FDFBAAD8D644DA4BD577C0B6EE4718A31F54A2C2747B38F303316478EB828924384ACFD602D243F285775BAFCF5752D3C719A`
SSDEEP | `1536:OK0TzC8tY6HAqCsd56ncymh7TpkwsZYZ6PD3:OKE+8tY6H/FPRkLYZ67`

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
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-42B8C692B9A93F2224CA4BA56B99FC37.md) | 66
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-95E303BF80AECA5A296E519C61F42427.md) | 88
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-E97B13E82F4E1ED5918A6C0466E19748.md) | 88

## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `Name: wuauclt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Command: wuauclt.exe /UpdateDeploymentProvider <Full_Path_To_DLL> /RunHandlerComServer` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Path: C:\Windows\System32\wuauclt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- IOC: wuauclt run with a parameter of a DLL path` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Link: https://dtm.uk/wuauclt/` | 
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


