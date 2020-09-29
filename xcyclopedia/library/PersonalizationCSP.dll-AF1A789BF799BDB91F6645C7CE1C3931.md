---
title: PersonalizationCSP.dll | PersonalizationCSP
excerpt: What is PersonalizationCSP.dll?
---

# PersonalizationCSP.dll 

* File Path: `C:\Windows\system32\PersonalizationCSP.dll`
* Description: PersonalizationCSP

## Hashes

Type | Hash
-- | --
MD5 | `AF1A789BF799BDB91F6645C7CE1C3931`
SHA1 | `0BA02CCC9E68789726BB7EA4A0214A136DA6FEAE`
SHA256 | `E1F167684D719F0FC97640E25B29DC3E3315C8D8C2CFB8B4FA32C9E9A1BC6F82`
SHA384 | `5495B75ABCF317E9A994FD61C1A1CB41B9A63117E0D32F7DA0FAEBB2379BF50B13386FCE0BB2C982D33A7EF712645F21`
SHA512 | `002F8768E04E107BF4DF021BFC0363BC030324E5FE18882D7228D310F0A3EBF2A7A07C0AA56C2F08DBCBB9D9D7E920142B9D662064250E09A1EE2D5F754D38FA`
SSDEEP | `3072:s0UvQfPqWXCjIm9vsinAWF1vkBsqWSq8qvzgR4H:s0p6WG9vs3q4+S9qvzgR`
IMP | `3769AE6AD803AB20781DE5FAAA6A273A`
PESHA1 | `A5DD78DCC4A9B3674C0DFFF6E78B2C783D999694`
PE256 | `8A5F2FDFCC193DD960A8299CB48E09BB110F869D5CF6E9F9B9882D392E8C5718`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x0000000180004af0 | 0x00004af0
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x0000000180004b10 | 0x00004b10


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PersonalizationCSP.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/e1f167684d719f0fc97640e25b29dc3e3315c8d8c2cfb8b4fa32c9e9a1bc6f82/detection/


## Possible Misuse

*The following table contains possible examples of `PersonalizationCSP.dll` being misused. While `PersonalizationCSP.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_desktopimgdownldr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_desktopimgdownldr.yml) | `- '\PersonalizationCSP'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Desktopimgdownldr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Desktopimgdownldr.yml) | `- IOC: Change of HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\PersonalizationCSP\LockScreenImageUrl` | 



MIT License. Copyright (c) 2020 Strontic.


