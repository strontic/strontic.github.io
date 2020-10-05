---
title: sfc_os.dll | Windows File Protection
excerpt: What is sfc_os.dll?
---

# sfc_os.dll 

* File Path: `C:\Windows\system32\sfc_os.dll`
* Description: Windows File Protection

## Hashes

Type | Hash
-- | --
MD5 | `C4237CEC18A10250BFDEB9ECD2DD9D34`
SHA1 | `36C612BC7507BB14A9678147E5A5ECDAFA8C73D4`
SHA256 | `E035E5094940242CB93E3D0797A98253A4CC4CE93D6C2E2CC04BC035126D4096`
SHA384 | `3C96B3D158ACD934F5C66D3EAA5A37ACF9813FEC131B4D35B5CC761D1D73BAD171D0C45A45CCE2FB3D142ACCFA6827AB`
SHA512 | `E871C2C44E24788C71333FE93DCA898327C398CEC05ECF50001991DBA336F393B32C153BAF05D078C046B44A11FB919C2F709E40E6EE51BB5FF4A9A25567A5BE`
SSDEEP | `768:4olg6kHrjoZwvBZwwh/77sKeAHOZv0jECJK9Iz5//I1P7:48g6AoKvBZDl7IlAuZvCw9Iz5/4P7`
IMP | `7F28D752A4EB5E4B8E5575364534CE32`
PESHA1 | `D8D6530A1242A2C3B1EC9B801792EDC251B1967B`
PE256 | `5CE2CAF77757F1DEF7D4640B0DD3151CD207C46007E00291CA03BCA2120AE25E`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SfcIsKeyProtected` | 14 | Exported Function
`SfcTerminateWatcherThread` | 15 | Exported Function
`SfcInstallProtectedFiles` | 12 | Exported Function
`SfcIsFileProtected` | 13 | Exported Function
`SfpDeleteCatalog` | 16 | Exported Function
`SRSetRestorePointA` | 4 | Exported Function
`SRSetRestorePointW` | 5 | Exported Function
`SfpInstallCatalog` | 17 | Exported Function
`SfpVerifyFile` | 18 | Exported Function
`GetNextFileMapContent` | 3 | Exported Function
`SfcClose` | 6 | Exported Function
`BeginFileMapEnumeration` | 1 | Exported Function
`CloseFileMapEnumeration` | 2 | Exported Function
`SfcConnectToServer` | 7 | Exported Function
`SfcInitiateScan` | 11 | Exported Function
`SfcInitProt` | 10 | Exported Function
`SfcFileException` | 8 | Exported Function
`SfcGetNextProtectedFile` | 9 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sfc_os.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/e035e5094940242cb93e3d0797a98253a4cc4ce93d6c2e2cc04bc035126d4096/detection/


## Possible Misuse

*The following table contains possible examples of `sfc_os.dll` being misused. While `sfc_os.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ghostdragon_gh0st_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ghostdragon_gh0st_rat.yar) | $s3 = "\\sfc_os.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


