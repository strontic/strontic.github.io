---
title: devmgr.dll | Device Manager MMC Snapin
excerpt: What is devmgr.dll?
---

# devmgr.dll 

* File Path: `C:\Windows\SysWOW64\devmgr.dll`
* Description: Device Manager MMC Snapin

## Hashes

Type | Hash
-- | --
MD5 | `A34BB067C51E2333AEC0C66FBC1FD1CF`
SHA1 | `17FD4EF7B5C77EF05319F8E19659B6D8933403EC`
SHA256 | `2A3706F4A1E7CD34BED48970374AC367FB83300BF8D2A94DC28FA522721A1FCC`
SHA384 | `CED46E41ECA054D05CEF04B9FBD130C92F2BA8005B9A09F622B321A5D8F8C586826BA5F5111284EFC1B1F625513589E2`
SHA512 | `994F364FB94414E7937A1809CC381B35A8A46CA068820113816B6CE6771C187EA2A22355FEF10BCF5034F2E71073F5F8EB6D902896515AC70C65CE2CD3677261`
SSDEEP | `12288:itlPO+oq3wpZZR3kpMx5ZibZvOXTrov8EZvOXTro+HN14L6L:ivO+rarRUpMUo7K6L`
IMP | `CE91CDCFF9BDDFA706C2B85928DCB9FF`
PESHA1 | `A123212FCA4B9F53E4F54A86CFA67A3CE4FD94FB`
PE256 | `1480FFAAE904C8F1A04C8CFECD0D7B5C37D7551C68C159A4CB10DD4A9C4B203C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DeviceAdvancedPropertiesA` | 17 | Exported Function
`DllGetClassObject` | 16 | Exported Function
`DllCanUnloadNow` | 15 | Exported Function
`DevicePropertiesW` | 8 | Exported Function
`DevicePropertiesExW` | 22 | Exported Function
`DevicePropertiesExA` | 21 | Exported Function
`DevicePropertiesA` | 7 | Exported Function
`DeviceProperties_RunDLLW` | 6 | Exported Function
`DeviceProperties_RunDLLA` | 5 | Exported Function
`DeviceProblenWizard_RunDLLW` | 24 | Exported Function
`DllRegisterServer` | 26 | Exported Function
`DeviceProblenWizard_RunDLLA` | 23 | Exported Function
`DeviceProblemWizardA` | 13 | Exported Function
`DeviceProblemTextW` | 12 | Exported Function
`DeviceProblemTextA` | 11 | Exported Function
`DeviceManager_ExecuteW` | 10 | Exported Function
`DeviceManager_ExecuteA` | 9 | Exported Function
`DeviceCreateHardwarePageEx` | 20 | Exported Function
`DeviceCreateHardwarePageCustom` | 25 | Exported Function
`DeviceCreateHardwarePage` | 19 | Exported Function
`DeviceAdvancedPropertiesW` | 18 | Exported Function
`DeviceProblemWizardW` | 14 | Exported Function
`DllUnregisterServer` | 27 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: devmgr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/2a3706f4a1e7cd34bed48970374ac367fb83300bf8d2a94dc28fa522721a1fcc/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\devmgr.dll](devmgr.dll-8EDD1D104C170B92EBE55A5E17E21B10.md) | 60

## Possible Misuse

*The following table contains possible examples of `devmgr.dll` being misused. While `devmgr.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_wocao.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_wocao.yml) | `- '\c$\windows\system32\devmgr.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


