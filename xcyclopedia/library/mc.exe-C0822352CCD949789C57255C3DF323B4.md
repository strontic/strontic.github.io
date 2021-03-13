---
title: mc.exe | Windows Message Compiler
excerpt: What is mc.exe?
---

# mc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\mc.exe`
* Description: Windows Message Compiler

## Hashes

Type | Hash
-- | --
MD5 | `C0822352CCD949789C57255C3DF323B4`
SHA1 | `E3E983EF3273E5B1E633BAAF1E2DABC9D4B90CC9`
SHA256 | `1A0793BFB8F0F8E14592591CE61369432AEDE5731564550246B33FB9821B4025`
SHA384 | `A88DB46E8AC158407BE8CD5B29873C56646120E012499FF912FF198FC8539AA30EF0E692E9E169CBF4A213D4CD2E7749`
SHA512 | `3884424B9A80C382192F6FC40D938D4AE36541CFDA3E0AAAC2B22DE144298E98E03CFD3760A5EBBD1C22AB69D7720E04AFC54E3D39709332F89D16D868133191`
SSDEEP | `6144:yBS3aH99xN1pdIa3Gisek01OkKSjXYBSRp1QcGdQmdzWLk/wPqaL2JjsAbjsi3yQ:yQqd9Fph3U521O+mEk/zjsAljvFUY1`
IMP | `3D8DA6D9101AE2AEA81154824B6E3760`
PESHA1 | `7EA95587B2F9121D20AC3BB33CC6C03879EBD3E6`
PE256 | `ECEA5A87A6B9A7FE510DDEB1C02973D084E9ECD042DD03D5B5774328A8D8D0FE`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: Unknown


## Possible Misuse

*The following table contains possible examples of `mc.exe` being misused. While `mc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\Mc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


