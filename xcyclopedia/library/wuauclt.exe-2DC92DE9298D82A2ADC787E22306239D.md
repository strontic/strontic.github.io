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
MD5 | `2DC92DE9298D82A2ADC787E22306239D`
SHA1 | `C5317A49B291F1CE71136A432B71685D70FD4FAF`
SHA256 | `6858C6B1F3C45F9788C9988EF6319483D9C7AEBBC5B59DAF71C2F4208997B59A`
SHA384 | `C824993933678802459A4CF22DBCC8217B1302763241208E2BF4673D0ED8CE637C144D0C1FA5CF366391DEC03BA265F6`
SHA512 | `2B05E204D49F876F135E910C85B9BD7769EE0F3CED6D4D6EEBB0FC882FDE8C1F582C408E081F55B0F5EF1647D85C52F78D03504C2B44EC928ACA2EC5A0E8B959`
SSDEEP | `768:ao+yE/Mvy1sxCf1eQAqTE0OVJzOH/K4FVQcqj5fCuKAEXOaEnw1BulMWZqy4Z951:LE/Skra/Cle7lM7jYCfRdglPc`
IMP | `51E0B3CA4E9BE50477C08867FFEF206F`
PESHA1 | `B2E4010138A9FB40A83C6B3D72983E9609D3BC37`
PE256 | `3614B8E342466C44D4AF84AA1ABCCB9579170D51253010CB000EFA108B948AE2`

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
* File Version: 10.0.17763.1457 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1457
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/6858c6b1f3c45f9788c9988ef6319483d9c7aebbc5b59daf71c2f4208997b59a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-A9C97125C0114959C493706B43C3DC8C.md) | 93

## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `Name: wuauclt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Command: wuauclt.exe /UpdateDeploymentProvider <Full_Path_To_DLL> /RunHandlerComServer` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Path: C:\Windows\System32\wuauclt.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- IOC: wuauclt run with a parameter of a DLL path` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Link: https://dtm.uk/wuauclt/` | 
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


