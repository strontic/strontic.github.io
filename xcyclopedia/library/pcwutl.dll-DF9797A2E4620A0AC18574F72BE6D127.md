---
title: pcwutl.dll | Program Compatibility Troubleshooter Helper
excerpt: What is pcwutl.dll?
---

# pcwutl.dll 

* File Path: `C:\Windows\system32\pcwutl.dll`
* Description: Program Compatibility Troubleshooter Helper

## Hashes

Type | Hash
-- | --
MD5 | `DF9797A2E4620A0AC18574F72BE6D127`
SHA1 | `7240D2846AB0DAFB52971D46687FC73F3884AEEB`
SHA256 | `AF3E85EBC5517989E9FCB4AA1B65C5891F4280418B4B45B096FCE316A755418F`
SHA384 | `1048612128688F821C9EE313FB79637BBAAC3264607C7070423B8C5A0F3642BA6E6BBC04E06C3009C7D3B38A6E0BF892`
SHA512 | `5D1C2475AF6FFA29E8B9FACBC1B800D6D0F5F99B05BFB4EBDC9D4663996BD7449AF13BB3164B31A36D64357DADAC3D32791646B270CB1CDC6C305CAD7624EA8A`
SSDEEP | `3072:Rr/9dT2zK+Y+PV51dOfUXUGi/DkNJGw7VrHu4J:t1dT2zK+Tv1dMUXpz7hu`
IMP | `2C617008FBD6FFE1DA656330DF60F9D8`
PESHA1 | `CCE102E65D66FC7AF91CE9C2205DB7F74D65F3A1`
PE256 | `C71AA6CC9C1377F8A9396DEADDC0A3BC9667821D6626CF556363AE8389C7F60E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`GetAppInformationFromCloud` | 3 (0x3) | Exported Function | 0x0000000180002db0 | 0x00002db0
`GetLayerFromGenome` | 4 (0x4) | Exported Function | 0x0000000180002b90 | 0x00002b90
`GetMatchingInfo` | 5 (0x5) | Exported Function | 0x0000000180001d30 | 0x00001d30
`GetTempFile` | 6 (0x6) | Exported Function | 0x0000000180001ba0 | 0x00001ba0
`LaunchApplicationW` | 1 (0x1) | Exported Function | 0x0000000180002780 | 0x00002780
`LogAeEvent` | 7 (0x7) | Exported Function | 0x0000000180002370 | 0x00002370
`LogPCWDebugEvent` | 8 (0x8) | Exported Function | 0x0000000180002890 | 0x00002890
`RetrieveFileAndProgramId` | 9 (0x9) | Exported Function | 0x00000001800026b0 | 0x000026b0
`SanitizeFullPath` | 2 (0x2) | Exported Function | 0x0000000180002e90 | 0x00002e90
`SendPcwWerReport` | 10 (0xa) | Exported Function | 0x0000000180001c50 | 0x00001c50


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pcwutl.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/af3e85ebc5517989e9fcb4aa1b65c5891f4280418b4b45b096fce316a755418f/detection/


## Possible Misuse

*The following table contains possible examples of `pcwutl.dll` being misused. While `pcwutl.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Pcwutl.yml) | `Name: Pcwutl.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Pcwutl.yml) | `- Command: rundll32.exe pcwutl.dll,LaunchApplication calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Pcwutl.yml) | `- Path: c:\windows\system32\pcwutl.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pcwutl.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Pcwutl.yml) | `- Path: c:\windows\syswow64\pcwutl.dll` | 



MIT License. Copyright (c) 2020 Strontic.


