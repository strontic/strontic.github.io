---
title: zipfldr.dll | Compressed (zipped) Folders
excerpt: What is zipfldr.dll?
---

# zipfldr.dll 

* File Path: `C:\Windows\SysWOW64\zipfldr.dll`
* Description: Compressed (zipped) Folders

## Hashes

Type | Hash
-- | --
MD5 | `8BBE1112F61143D7DA5C67282DEF0397`
SHA1 | `346AF576BC606D5F2032A920D1BF38834DA06897`
SHA256 | `6CC4B493B39999303124D8410BC3F209ADF4DE96181483A0D28AA806707F43C9`
SHA384 | `AA743B7D3BEA119443AA03976A5475B1A89CA014A7B64E943D83842BD84803DEFED8FD1828E9E5B707B7539E34C42DB8`
SHA512 | `A05B918824ED468847AB2190AB3D428932AB93F94E3B1FD4BD4A92797908F3CED79E4061D3BE16B17267AABCFA4292EC8C7F0659695927B23A9E7AA4D16CF006`
SSDEEP | `3072:sBlo1ACPFavPGExRMN60lMHqBQlcn45jNec414xDp3:sriEPGKKN6cMsy8CNen14xD`
IMP | `B58D42559C125D7FEF2B3A9235FE815E`
PESHA1 | `E3C2EE2EB35182E86AB80719F47DBF0464C7BA8E`
PE256 | `C9A0BCE050CB49759A4CD3D85CDB4B121083716B1F97892228F19F74682B8968`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 2 (0x2) | Exported Function | 0x71214500 | 0x00014500
`DllGetClassObject` | 3 (0x3) | Exported Function | 0x7120a780 | 0x0000a780
`RouteTheCall` | 1 (0x1) | Exported Function | 0x71211990 | 0x00011990


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ZIPFLDR.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6cc4b493b39999303124d8410bc3f209adf4de96181483a0d28aa806707f43c9/detection/


## Possible Misuse

*The following table contains possible examples of `zipfldr.dll` being misused. While `zipfldr.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '*\rundll32.exe* zipfldr.dll,*RouteTheCall *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '* zipfldr.dll,*RouteTheCall *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Zipfldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Zipfldr.yml) | `Name: Zipfldr.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Zipfldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Zipfldr.yml) | `- Command: rundll32.exe zipfldr.dll,RouteTheCall calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Zipfldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Zipfldr.yml) | `- Command: rundll32.exe zipfldr.dll,RouteTheCall file://^C^:^/^W^i^n^d^o^w^s^/^s^y^s^t^e^m^3^2^/^c^a^l^c^.^e^x^e` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Zipfldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Zipfldr.yml) | `- Path: c:\windows\system32\zipfldr.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Zipfldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Zipfldr.yml) | `- Path: c:\windows\syswow64\zipfldr.dll` | 



MIT License. Copyright (c) 2020 Strontic.


