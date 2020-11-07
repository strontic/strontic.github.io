---
title: wbemcons.dll | WMI Standard Event Consumers
excerpt: What is wbemcons.dll?
---

# wbemcons.dll 

* File Path: `C:\Windows\system32\wbem\wbemcons.dll`
* Description: WMI Standard Event Consumers

## Hashes

Type | Hash
-- | --
MD5 | `165004875959CA2C2E72F4A81B1353EE`
SHA1 | `E6BAC753201C380A36D17E3FA4BBB90133D20AD9`
SHA256 | `D5E85E09723063F643F1057B6B07A5899B2DF1EB84BEC94C39F383CB43B6E6A5`
SHA384 | `A3F4D28D7B3AA3537325BFF40BEA18B8087723DF0B4DC908BB0535F39DDF0B9A3B0FCDF4A24F7DA1CD99767FF4F96731`
SHA512 | `AEF5CC1D2240008E886165763F1762F9A2900B821811AEF38B3EAB8865CD48CD6E82CA34F03B67C2DCBC7B008E61CC7B810EE1BF23EF665188ADE37C2DFC6135`
SSDEEP | `1536:G7gpGXlvDjsnv1Lr6zQmC4SDDcb6lO/UOmLJjX6ESc+nAQXzT+:CX52CQvLDgelO/UDLdX6ESc+nAAG`
IMP | `A93C79EE513630A9200EC00B28CCC2DC`
PESHA1 | `A03D36935DA8110BFB0616EAF05841E511C32190`
PE256 | `65E627626F1F6B5E58364E28901FD325A9513C99891BE9931DB3CFEA0D8A501D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WbemCons
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/d5e85e09723063f643f1057b6b07a5899b2df1eb84bec94c39f383cb43b6e6a5/detection/


## Possible Misuse

*The following table contains possible examples of `wbemcons.dll` being misused. While `wbemcons.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_persistence_commandline_event_consumer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_persistence_commandline_event_consumer.yml) | `ImageLoaded\|endswith: '\wbemcons.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


