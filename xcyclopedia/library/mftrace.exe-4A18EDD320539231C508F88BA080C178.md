---
title: mftrace.exe | Media Foundation Tracing Application
excerpt: What is mftrace.exe?
---

# mftrace.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\mftrace.exe`
* Description: Media Foundation Tracing Application

## Hashes

Type | Hash
-- | --
MD5 | `4A18EDD320539231C508F88BA080C178`
SHA1 | `06C009634386B7154140558E31D908C1EF9B7523`
SHA256 | `4508DFEAFD3D70C7BC5DE59775A67936F993D55FAFDFE81647FDFE061984F7AA`
SHA384 | `316E183316B5BFFC7EE5184E4F8A7461D0F98663EB10F693D627C046DD0FB9A4EA5FE11AAE71B06DDFD45AF5A68E1324`
SHA512 | `24D6A3542AE56B41C066982F479F8BB05BA2152370FE6D1FE3B04E975E9CAA0861EF9FE45BEB98224F2FEECA7F1C251B42E26FFC72C7DF3F8085902707AD2683`
SSDEEP | `6144:KsWcdeYPCkXZ/6EKADl8Pg+TjRxpZJ5pZN4Zx:ZWeeaCkXZ/6Edl8Pg+nRxpZJ5pZNEx`
IMP | `4EE03BCF465A67C28598DDD7E66E309B`
PESHA1 | `81B15D4CD8D242110EA5B54EF9F6503E4CB550FC`
PE256 | `AA5C352A58ED5A3A78F3501E3741016ADF17B52D053CC24A194734F8FAE93C23`

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
* Machine Type: 452

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mftrace.exe](mftrace.exe-C4E8F0C917D4AD90670DB8684FF0AC41.md) | 63

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


