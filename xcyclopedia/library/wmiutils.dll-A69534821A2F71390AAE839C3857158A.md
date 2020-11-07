---
title: wmiutils.dll | WMI
excerpt: What is wmiutils.dll?
---

# wmiutils.dll 

* File Path: `C:\Windows\system32\wbem\wmiutils.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `A69534821A2F71390AAE839C3857158A`
SHA1 | `06C0EF6A6E0F404EFED0D3819AC1B3E37C07378E`
SHA256 | `F74152C7CD7E806D7911BD142672DE48D9306D125764307533ECCBE0D25DA3A3`
SHA384 | `DDBE2E3A1CE99B086CB07112315142B0646F5164D558F309F54520E7BE8ED58A44FF96C5B6A6713104D12C0ACB005BEC`
SHA512 | `1C1B5D7C431C4E23B72F0A5F391570DD0FE42598FD295CA12BAB42ED9B51AAA9CD2FD1C6BFF3D10B3C5B7B9843BFF8ADDB4B54D5C8F47497B42D8C7C9011886E`
SSDEEP | `3072:YlFzdVHgN21i0hUjDN0M1mEOAN9Rygdh4oBpMZ2:qvHgl0hUjx0Rg74oBk`
IMP | `0D31E6D27B954AD879CB4DF742982F1A`
PESHA1 | `1AFF40B476E9B0DAC9520B5FFC16399C7984C81A`
PE256 | `FBAF42A06041C98A2CD80BEBE147DD7D9C4454E5653FE71DBB88F0281F5F307B`

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

* Original Filename: wmiutils.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/f74152c7cd7e806d7911bd142672de48d9306d125764307533eccbe0d25da3a3/detection/


## Possible Misuse

*The following table contains possible examples of `wmiutils.dll` being misused. While `wmiutils.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wmiutils.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wmiutils.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


