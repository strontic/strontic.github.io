---
title: gpscript.dll | Script Client Side Extension
excerpt: What is gpscript.dll?
---

# gpscript.dll 

* File Path: `C:\Windows\SysWOW64\gpscript.dll`
* Description: Script Client Side Extension

## Hashes

Type | Hash
-- | --
MD5 | `3B0D76BC825E6BBF6EB8CEDB5DADE72A`
SHA1 | `24682108DC8A33CF32257EAAFC858D72A9D9A6EA`
SHA256 | `3533AC6FBF72208FB952AD01D56496A8F5A7F7D695E84DEBF266D93CDDF702B2`
SHA384 | `49C2BA6996CE7F408286465EE3969F05A9F549F583369703DECDD6E7081DAF6BC95E4F5356C2D89F3790F1237FDF3903`
SHA512 | `AE5017EE76BC4C334AD63BB83F28D199B2CF2256BD7BDB198DF971364045F2DA189635E09F686F96FC72C379B601B59E7D94185E584525A36179C3DB7B870267`
SSDEEP | `768:HjylU+7YM/lYep+F9cU6B81HLAt8Jmvtt8GCbwoei9DFQymL:W++7f/KepiJHUt8Avtt8Eoei9DFQ/L`
IMP | `1CDE47DB3A067DC1BB5599A41FC997EB`
PESHA1 | `7659418DEFFAD97B068608DE78B87E22CF19A430`
PE256 | `880C280B66B0C8255C6CA0F786C5628BCE9F72621635AA4B23593F4B28AC4DDF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ProcessScriptsGroupPolicyEx` | 3 | Exported Function
`ScrRegGPOListToWbem` | 4 | Exported Function
`GenerateScriptsGroupPolicy` | 1 | Exported Function
`ProcessScriptsGroupPolicy` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gpscript.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3533ac6fbf72208fb952ad01d56496a8f5a7f7d695e84debf266d93cddf702b2/detection/


## Possible Misuse

*The following table contains possible examples of `gpscript.dll` being misused. While `gpscript.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `Name: Gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Command: Gpscript /startup` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\System32\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Path: C:\Windows\SysWOW64\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- IOC: Execution of Gpscript.exe after logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `- Link: https://oddvar.moe/2018/04/27/gpscript-exe-another-lolbin-to-the-list/` | 



MIT License. Copyright (c) 2020 Strontic.


