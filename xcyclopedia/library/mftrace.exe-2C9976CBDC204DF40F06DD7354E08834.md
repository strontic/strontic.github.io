---
title: mftrace.exe | Media Foundation Tracing Application
excerpt: What is mftrace.exe?
---

# mftrace.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\mftrace.exe`
* Description: Media Foundation Tracing Application

## Hashes

Type | Hash
-- | --
MD5 | `2C9976CBDC204DF40F06DD7354E08834`
SHA1 | `2B3485F16FE3CF00E0A428D28DA3A5511114AF02`
SHA256 | `89BF81932290CB2DD2B0B4E3E027902B9A17349AE4CB36A086BF5CA02945D233`
SHA384 | `CF860BA584A7BFF794F84DE765D6458B5A7C04C3816C931ACCF504625C6368DD918CEC5DFE8A31367F1ED6243528C9DE`
SHA512 | `08361333FCBE4DE77BD20B21748D3CE668BDF9E6B80EF8B062F3E551F8A9B84693A25AF2F583A8B551D214634CED5FBA5466B3868AE3A13F1B3AF6DF4A7B7F47`
SSDEEP | `6144:aSxybZCCpiw7M03f6hiLQKJsSaCqsmMNQ7xBO/C0nJP6EnAFmP6T:UMem+JC0nJP6E2K6T`
IMP | `4CAC2F45048FBC8CDC66187BD04306FC`
PESHA1 | `E8509948B4EFF08598680C70F030F96BA896AAD7`
PE256 | `7A4FCD595359C3DF8FC8AF0F7E306325C2BE6B6EF0C669E0DB2AE32217E353AE`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mftrace.exe
* Product Name: Media Foundation Tracing Application
* Company Name: Microsoft
* File Version: 1.1.0.1
* Product Version: 1.1.0.1
* Language: Language Neutral
* Legal Copyright: (c) Microsoft.  All rights reserved.
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a


## Possible Misuse

*The following table contains possible examples of `mftrace.exe` being misused. While `mftrace.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\mftrace.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Name: Mftrace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe cmd.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Description: Launch cmd.exe as a subprocess of Mftrace.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of cmd.exe as a subprocess of Mftrace.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe powershell.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of powershell.exe as a subprocess of Mftrace.exe.` | 



MIT License. Copyright (c) 2020 Strontic.


