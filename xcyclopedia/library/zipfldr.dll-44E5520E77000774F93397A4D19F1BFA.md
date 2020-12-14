---
title: zipfldr.dll | Compressed (zipped) Folders
excerpt: What is zipfldr.dll?
---

# zipfldr.dll 

* File Path: `C:\Windows\system32\zipfldr.dll`
* Description: Compressed (zipped) Folders

## Hashes

Type | Hash
-- | --
MD5 | `44E5520E77000774F93397A4D19F1BFA`
SHA1 | `9880C39735CD6B569B0F8EFB7A7F2BB2F06588E8`
SHA256 | `C771833CAB450839F5ACADCBDBC42A6F1AFA118013D87C6F2ADC3C412512BD0A`
SHA384 | `67CE696478FF9E16D95A8CF2938370F241CC4FC550BAF0D2CF737C3648FA4152C0F6826C3518E8BC09D7D0ED94013A2E`
SHA512 | `CB3A27A359D3E7567C732DFEDA6EEA7AD12BAA9207A8C1EB89E92D46DBF2F1BEDF843C66C282EF9D7DBC798E1A4EFEDB84E9EF66AFC28955025B559316D06AFF`
SSDEEP | `6144:076akJloyaeKHFmlPa3EJCAlaGe4vk9g8LTM:+kl4eKHFmlPNJCYaGehTM`
IMP | `593CA3031D83A0529943A339EBC6CF02`
PESHA1 | `035DF4E1FD30FBFD1FCDBD050ADDEC8290D40291`
PE256 | `5C582DF665505AB44F5ECFD9CD033B080A184B93F4A9DCE3936AB1DD93484C9E`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`RouteTheCall` | 1 | Exported Function
`DllGetClassObject` | 3 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ZIPFLDR.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/c771833cab450839f5acadcbdbc42a6f1afa118013d87c6f2adc3c412512bd0a/detection/


## Possible Misuse

*The following table contains possible examples of `zipfldr.dll` being misused. While `zipfldr.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

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


