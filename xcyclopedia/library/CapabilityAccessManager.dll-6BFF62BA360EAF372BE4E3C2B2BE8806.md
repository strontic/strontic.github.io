---
title: CapabilityAccessManager.dll | Capability Access Manager Service
excerpt: What is CapabilityAccessManager.dll?
---

# CapabilityAccessManager.dll 

* File Path: `C:\Windows\system32\CapabilityAccessManager.dll`
* Description: Capability Access Manager Service

## Hashes

Type | Hash
-- | --
MD5 | `6BFF62BA360EAF372BE4E3C2B2BE8806`
SHA1 | `6DA440550094638C137A9B747E63CE56CC899467`
SHA256 | `267265782A252C2F87EE0DF5FA71EEE2EE61A271E58DF98F520478220051ABF0`
SHA384 | `147B3E6E98C6FECEBA4D13622AFC9BF035DBFDA2942F6368730EF9E2337E6277BDE1E2372B76AA4F92284FBB52039D92`
SHA512 | `C808ED235B1C40729573C0F01B6335920BEA6186F464777EC5681DB21EEC75C2D76CE8632FFF9180A1D30E36A9E1F52BFF9787DAA34ED17B004F3F59167E72C7`
SSDEEP | `6144:M5C3Z4iCBr/Mr80/osggXGYcUTbZOmBI22dXtojTkCw4A40t3bv3OZXLqOqh6UrK:KC5CaBgEVBMxlk`
IMP | `AD5E96ED304D526C4C4ABAA4BFEA737D`
PESHA1 | `637CA133157EAE8CE9CE95597D19CB854666E110`
PE256 | `FB5EF68D4A2C193D2BCB78C36CA7522B027C98719E7862D36B108E723B9DD0F6`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ServiceMain` | 1 | Exported Function
`DllGetClassObject` | 3 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CapabilityAccessManager.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/267265782a252c2f87ee0df5fa71eee2ee61a271e58df98f520478220051abf0/detection/


## Possible Misuse

*The following table contains possible examples of `CapabilityAccessManager.dll` being misused. While `CapabilityAccessManager.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_mic_cam_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_susp_mic_cam_access.yml) | `- \Software\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\\*\NonPackaged` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


