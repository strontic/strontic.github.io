---
title: gpscript.dll | Script Client Side Extension
excerpt: What is gpscript.dll?
---

# gpscript.dll 

* File Path: `C:\Windows\system32\gpscript.dll`
* Description: Script Client Side Extension

## Hashes

Type | Hash
-- | --
MD5 | `54F5651FD7043941AFE97639CDDD1A4C`
SHA1 | `1D23E7C26520CBD669082655E009C9157839B06C`
SHA256 | `65B8BA701610771C3AFC0D98FBACCC3B0C71518446A504A8C541D02C8E17EC27`
SHA384 | `8FB5964F4EBA41BF7923824BB4D06346E0EC74FA15EA2B81B72274FEC346D4C157E04F228BDC9E198F847B4F960C062E`
SHA512 | `86EF13686672972A90F0841DD049ECE91005331A1A32C81A94CA343933FBD6E73B106542984A60A81A25D03334108D3C2301F29B08A6FC8261EB9BD2B0EC76B5`
SSDEEP | `1536:yFuLLeXsHO0tdgy5wwq8RFd+egk79KUAz:l+XMO0tygwwqO+egk79VW`
IMP | `6FB6CAF2F9DA217DF686DB4E5C158D20`
PESHA1 | `76F6E9C4FE72D638B6BC8F4DECB8137EA4643A28`
PE256 | `8049D5CAE7F4B219FEAE0CF9A71F2AAA0629E19C58D64F5A625A2770C4E6F096`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`GenerateScriptsGroupPolicy` | 1 | Exported Function
`ProcessScriptsGroupPolicy` | 2 | Exported Function
`ProcessScriptsGroupPolicyEx` | 3 | Exported Function
`ScrRegGPOListToWbem` | 4 | Exported Function


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/65b8ba701610771c3afc0d98fbaccc3b0c71518446a504a8c541d02c8e17ec27/detection/


## Possible Misuse

*The following table contains possible examples of `gpscript.dll` being misused. While `gpscript.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


