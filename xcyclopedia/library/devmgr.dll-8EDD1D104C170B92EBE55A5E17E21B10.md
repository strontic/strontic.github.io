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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DeviceAdvancedPropertiesA` | 17 (0x11) | Exported Function | 0x0000000180032100 | 0x00032100
`DllGetClassObject` | 16 (0x10) | Exported Function | 0x0000000180004b20 | 0x00004b20
`DllCanUnloadNow` | 15 (0xf) | Exported Function | 0x0000000180006720 | 0x00006720
`DevicePropertiesW` | 8 (0x8) | Exported Function | 0x00000001800329c0 | 0x000329c0
`DevicePropertiesExW` | 22 (0x16) | Exported Function | 0x0000000180032900 | 0x00032900
`DevicePropertiesExA` | 21 (0x15) | Exported Function | 0x0000000180032810 | 0x00032810
`DevicePropertiesA` | 7 (0x7) | Exported Function | 0x0000000180032730 | 0x00032730
`DeviceProperties_RunDLLW` | 6 (0x6) | Exported Function | 0x0000000180032b40 | 0x00032b40
`DeviceProperties_RunDLLA` | 5 (0x5) | Exported Function | 0x0000000180032a90 | 0x00032a90
`DeviceProblenWizard_RunDLLW` | 24 (0x18) | Exported Function | 0x0000000180032690 | 0x00032690
`DllRegisterServer` | 26 (0x1a) | Exported Function | 0x000000018000c160 | 0x0000c160
`DeviceProblenWizard_RunDLLA` | 23 (0x17) | Exported Function | 0x00000001800325e0 | 0x000325e0
`DeviceProblemWizardA` | 13 (0xd) | Exported Function | 0x0000000180032460 | 0x00032460
`DeviceProblemTextW` | 12 (0xc) | Exported Function | 0x0000000180032440 | 0x00032440
`DeviceProblemTextA` | 11 (0xb) | Exported Function | 0x0000000180032300 | 0x00032300
`DeviceManager_ExecuteW` | 10 (0xa) | Exported Function | 0x0000000180032270 | 0x00032270
`DeviceManager_ExecuteA` | 9 (0x9) | Exported Function | 0x0000000180032270 | 0x00032270
`DeviceCreateHardwarePageEx` | 20 (0x14) | Exported Function | 0x0000000180039ee0 | 0x00039ee0
`DeviceCreateHardwarePageCustom` | 25 (0x19) | Exported Function | 0x0000000180039dd0 | 0x00039dd0
`DeviceCreateHardwarePage` | 19 (0x13) | Exported Function | 0x0000000180039db0 | 0x00039db0
`DeviceAdvancedPropertiesW` | 18 (0x12) | Exported Function | 0x00000001800321c0 | 0x000321c0
`DeviceProblemWizardW` | 14 (0xe) | Exported Function | 0x0000000180032530 | 0x00032530
`DllUnregisterServer` | 27 (0x1b) | Exported Function | 0x000000018000c170 | 0x0000c170


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


