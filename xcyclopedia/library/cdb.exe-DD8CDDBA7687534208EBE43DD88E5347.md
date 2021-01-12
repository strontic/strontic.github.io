---
title: cdb.exe | Symbolic Debugger for Windows
excerpt: What is cdb.exe?
---

# cdb.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\cdb.exe`
* Description: Symbolic Debugger for Windows

## Hashes

Type | Hash
-- | --
MD5 | `DD8CDDBA7687534208EBE43DD88E5347`
SHA1 | `82641BCC048F687D4CFBBB02DE6B22FA1958F814`
SHA256 | `1EB127E7F0983BA09FC6559FF72ADF11FFCF7116F94B5FDB18F5A728FE8545D7`
SHA384 | `2CE97CC562F367B2DFC6BCA5388E6079529379BCB7962DE9049A723E62D228A3D6F718080DBD8D800A0280A4D25387B1`
SHA512 | `2510B89CA7E78852C8CA66F4DACC438F629EF9561FD0EC5B3C0953F7B906CACB1695729998022CAFE4468CF88E5882F584BDA417360CBF8B280A5512ABF621BD`
SSDEEP | `3072:U2bOoZisWyRcOYZ4P31R4pVX7MImpATeKt7bFyZh6:Z62isWyRcOY23ozbFy2`
IMP | `C64EB6694DCC19EE7E65F4F6C8BFECF0`
PESHA1 | `8462DAB8C5B236570E94644F17197F1EA4F8C46B`
PE256 | `AE1CF1A6EF3DB69A1152B2C5935EA39539CA1A91CE9BFB36D7CB7CA8A2BA5750`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CDB.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a


## Possible Misuse

*The following table contains possible examples of `cdb.exe` being misused. While `cdb.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `description: Launch 64-bit shellcode from a debugger script file using cdb.exe.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `Image\|endswith: '\cdb.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `Name: Cdb.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Command: cdb.exe -cf x64_calc.wds -o notepad.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `Description: Launch 64-bit shellcode from the x64_calc.wds file using cdb.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\cdb.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe` | 



MIT License. Copyright (c) 2020 Strontic.


