---
title: cdb.exe | Symbolic Debugger for Windows
excerpt: What is cdb.exe?
---

# cdb.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\cdb.exe`
* Description: Symbolic Debugger for Windows

## Hashes

Type | Hash
-- | --
MD5 | `5017F8EFBE98513AEB75EAC57C1EA351`
SHA1 | `78E71D72E6DDE526B5BAA6C848559C2BADF7F471`
SHA256 | `264BBA62780E62AF8A1245FD2345AAE5CFBFFEDDDA68E84F5561E3192473A821`
SHA384 | `FC4762846469ACD0E9EA430B364083E16965845777D461A338FC01FEA4FA5365132477A12FBC1D209E4BAB3F2C7159A6`
SHA512 | `129A8B2C9F042D9195B2217F11015047448183AA1612DE911DFFD9EE4831A44C7300BCFEAD8EB72B13CEBDAD4AAC01A41DDB3F87982FD7B28A0B63D10B577A71`
SSDEEP | `3072:Cmmyc+k5FnbMomoWATuaT0zByCZSUj/VPp59RdJg:lcQ9ZSgp59rJg`
IMP | `01717BB155F546CAE097D15EB7D5763C`
PESHA1 | `9087739A71D8BC6E8635BCA5DAAEAE3E258C5079`
PE256 | `B60FE185A81F01D1AD26E190B7BE7074132D64F1E2A17E756F3C9C36818DEAE6`

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
* Machine Type: 452

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\kd.exe](kd.exe-F6B9E69A6C0563D9338B4B73EBAAC34C.md) | 41
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\ntkd.exe](ntkd.exe-F468EEBF04739821C2B5C322754FA720.md) | 43
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\ntsd.exe](ntsd.exe-629EA12D527237B9CD945AC44C2DE80D.md) | 43
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe](cdb.exe-6E953EFEB12896AC0EC17D198902FAE1.md) | 44
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kd.exe](kd.exe-E61F51C4CF00EFABF19CC6E80A128846.md) | 33
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\ntkd.exe](ntkd.exe-BCABCBB87A2D6CF497D3FBF60BDD2543.md) | 44
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\ntsd.exe](ntsd.exe-329FBD3549A7D0FB1BF3A250ED8BDFB7.md) | 38

## Possible Misuse

*The following table contains possible examples of `cdb.exe` being misused. While `cdb.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `description: Launch 64-bit shellcode from a debugger script file using cdb.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `Image\|endswith: '\cdb.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `Name: Cdb.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Command: cdb.exe -cf x64_calc.wds -o notepad.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `Description: Launch 64-bit shellcode from the x64_calc.wds file using cdb.exe.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\cdb.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


