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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DeviceAdvancedPropertiesA` | 17 (0x11) | Exported Function | 0x5fcb6c70 | 0x00036c70
`DllGetClassObject` | 16 (0x10) | Exported Function | 0x5fc8ec00 | 0x0000ec00
`DllCanUnloadNow` | 15 (0xf) | Exported Function | 0x5fc90bb0 | 0x00010bb0
`DevicePropertiesW` | 8 (0x8) | Exported Function | 0x5fcb7300 | 0x00037300
`DevicePropertiesExW` | 22 (0x16) | Exported Function | 0x5fcb7280 | 0x00037280
`DevicePropertiesExA` | 21 (0x15) | Exported Function | 0x5fcb71d0 | 0x000371d0
`DevicePropertiesA` | 7 (0x7) | Exported Function | 0x5fcb7120 | 0x00037120
`DeviceProperties_RunDLLW` | 6 (0x6) | Exported Function | 0x5fcb7420 | 0x00037420
`DeviceProperties_RunDLLA` | 5 (0x5) | Exported Function | 0x5fcb7390 | 0x00037390
`DeviceProblenWizard_RunDLLW` | 24 (0x18) | Exported Function | 0x5fcb70a0 | 0x000370a0
`DllRegisterServer` | 26 (0x1a) | Exported Function | 0x5fc9a850 | 0x0001a850
`DeviceProblenWizard_RunDLLA` | 23 (0x17) | Exported Function | 0x5fcb7010 | 0x00037010
`DeviceProblemWizardA` | 13 (0xd) | Exported Function | 0x5fcb6ee0 | 0x00036ee0
`DeviceProblemTextW` | 12 (0xc) | Exported Function | 0x5fcb6ec0 | 0x00036ec0
`DeviceProblemTextA` | 11 (0xb) | Exported Function | 0x5fcb6de0 | 0x00036de0
`DeviceManager_ExecuteW` | 10 (0xa) | Exported Function | 0x5fcb6d70 | 0x00036d70
`DeviceManager_ExecuteA` | 9 (0x9) | Exported Function | 0x5fcb6d70 | 0x00036d70
`DeviceCreateHardwarePageEx` | 20 (0x14) | Exported Function | 0x5fcbbd70 | 0x0003bd70
`DeviceCreateHardwarePageCustom` | 25 (0x19) | Exported Function | 0x5fcbbcc0 | 0x0003bcc0
`DeviceCreateHardwarePage` | 19 (0x13) | Exported Function | 0x5fcbbca0 | 0x0003bca0
`DeviceAdvancedPropertiesW` | 18 (0x12) | Exported Function | 0x5fcb6cf0 | 0x00036cf0
`DeviceProblemWizardW` | 14 (0xe) | Exported Function | 0x5fcb6f90 | 0x00036f90
`DllUnregisterServer` | 27 (0x1b) | Exported Function | 0x5fc9a860 | 0x0001a860


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


