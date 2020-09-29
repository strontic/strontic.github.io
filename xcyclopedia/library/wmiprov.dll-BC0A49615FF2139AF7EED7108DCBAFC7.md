---
title: wmiprov.dll | WMI
excerpt: What is wmiprov.dll?
---

# wmiprov.dll 

* File Path: `C:\Windows\system32\wbem\wmiprov.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `BC0A49615FF2139AF7EED7108DCBAFC7`
SHA1 | `FA5E1309C7FF60615768CEB82A1AC39DB0159C11`
SHA256 | `1D5B7F54EC06DF0B97F9171C6C34D79979C2CF9F7A99910FDB71DF50BE531459`
SHA384 | `5C011BAF00BE57CAD545A6829CEBE29C6BD273859869B8D8EEDFE6575D3C57DCD668C92227B1E935608B71D8E683F4DF`
SHA512 | `054AE52E36A1E61892A97A9A7729BD72611E86B89D701C15C3BC25E92D09CA88D769E433424A070ED41212C63CA887A88AA36BC39B0FD20C53C038CAA129E5D1`
SSDEEP | `6144:vZ5y7H1gbC7kGiz6L9hYxg02j+MrOx1+oJzkSp:vZ5yme7kGoQhNMM63qo`
IMP | `2F12F25BABC8F20052A8070481FF267B`
PESHA1 | `EFC5913C329E7E84C42B651094E1F959174F614E`
PE256 | `9011BD38451EEE55DF005FFA0200B77068C52221DF60C09B31369B8F59851E36`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x0000000180008e90 | 0x00008e90
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x0000000180002870 | 0x00002870
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x0000000180011200 | 0x00011200
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x0000000180011400 | 0x00011400


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mofd.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/1d5b7f54ec06df0b97f9171c6c34d79979c2cf9f7a99910fdb71df50be531459/detection/


## Possible Misuse

*The following table contains possible examples of `wmiprov.dll` being misused. While `wmiprov.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wmiprov.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


