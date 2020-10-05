---
title: devmgr.dll | Device Manager MMC Snapin
excerpt: What is devmgr.dll?
---

# devmgr.dll 

* File Path: `C:\Windows\system32\devmgr.dll`
* Description: Device Manager MMC Snapin

## Hashes

Type | Hash
-- | --
MD5 | `8EDD1D104C170B92EBE55A5E17E21B10`
SHA1 | `EA79A0CF531E787F81B85C6F3C12AA39D00DB3CA`
SHA256 | `9666061D1A8FB5A4EA7083CFBAC63EAD521E3A3A9BE9DF1809D4D05CB863DC9C`
SHA384 | `28C4C7E4860585127F92D13745F316B20AD6BA2753630F20E5A16AEEFF8C8F46575E752BD59A67195B0F3E72DE7C37B2`
SHA512 | `35A8FDB81CFD22D06C45F3DFB5122EA55B509724A468D505139766B7C0343832C47C4A6D7FF222E57C866112E69FDE1297307FB09C3EA602CD134549898E0CEF`
SSDEEP | `12288:xRgKJvUWezmqL79v3X7ZibZvOXTrov8EZvOXTro+HN14:xRaWami/Ao7`
IMP | `0C11E6B37F5994B81F00FF397554FFC3`
PESHA1 | `092D180AE00F19EC04E7BF68B533EB26323661CF`
PE256 | `95EFA10A4E9DE2EB60EE8E8D8D141247D67607079DEF61F1E1F690C6BD05A445`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DevicePropertiesA` | 7 | Exported Function
`DevicePropertiesExA` | 21 | Exported Function
`DeviceProperties_RunDLLW` | 6 | Exported Function
`DeviceProblenWizard_RunDLLW` | 24 | Exported Function
`DeviceProperties_RunDLLA` | 5 | Exported Function
`DevicePropertiesExW` | 22 | Exported Function
`DllRegisterServer` | 26 | Exported Function
`DllUnregisterServer` | 27 | Exported Function
`DllGetClassObject` | 16 | Exported Function
`DevicePropertiesW` | 8 | Exported Function
`DllCanUnloadNow` | 15 | Exported Function
`DeviceProblenWizard_RunDLLA` | 23 | Exported Function
`DeviceCreateHardwarePageCustom` | 25 | Exported Function
`DeviceCreateHardwarePageEx` | 20 | Exported Function
`DeviceCreateHardwarePage` | 19 | Exported Function
`DeviceAdvancedPropertiesA` | 17 | Exported Function
`DeviceAdvancedPropertiesW` | 18 | Exported Function
`DeviceManager_ExecuteA` | 9 | Exported Function
`DeviceProblemWizardA` | 13 | Exported Function
`DeviceProblemWizardW` | 14 | Exported Function
`DeviceProblemTextW` | 12 | Exported Function
`DeviceManager_ExecuteW` | 10 | Exported Function
`DeviceProblemTextA` | 11 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: devmgr.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/9666061d1a8fb5a4ea7083cfbac63ead521e3a3a9be9df1809d4d05cb863dc9c/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\devmgr.dll](devmgr.dll-A34BB067C51E2333AEC0C66FBC1FD1CF.md) | 60

## Possible Misuse

*The following table contains possible examples of `devmgr.dll` being misused. While `devmgr.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_wocao.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_wocao.yml) | `- '\c$\windows\system32\devmgr.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


