---
title: sfc_os.dll | Windows File Protection
excerpt: What is sfc_os.dll?
---

# sfc_os.dll 

* File Path: `C:\Windows\SysWOW64\sfc_os.dll`
* Description: Windows File Protection

## Hashes

Type | Hash
-- | --
MD5 | `6DBC87C64F0F076E29E0BF5F8CDD23F1`
SHA1 | `0935768A32A80A4BE1C92CEC15AF7BFEFC1A8C33`
SHA256 | `BC902AC8D0236E20B4F214071E70BB962E5EDBAF471E616CBC05ADECD837CCE2`
SHA384 | `BDF78EFEC122547E32C2010ACC4644498E8ECF0310A712CEC2898D2F40E7BDF3650708BFDE2BC02FBA0A975990972191`
SHA512 | `7D4E27FE08159782FF8BE021E97A12B4A5BFC5E4E7BE302B3913693A8A90F69CE360BAD0C94DC1CE0B03A8AA3A66A6FDC6A5AA6394B4FBBAB4780259A0215B3E`
SSDEEP | `768:mhpLIAHOev0jiN6n/6J0kQP6t/s8oDSw94uWK9Iuj2mMo9I1PJ:mhpLIAuevi/6J5QP6VumWh9IuqM6PJ`
IMP | `3BC0CDB02B59F7C5EC49B1180EECD9DC`
PESHA1 | `8684D4C9EDD714CFBEA1DFA80E10616549AAF247`
PE256 | `6F07281F96B46220F9A63CD454CCFF1B946976C11AC2BEF254867582C6BEBB56`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BeginFileMapEnumeration` | 1 (0x1) | Exported Function | 0x10007400 | 0x00007400
`SfpVerifyFile` | 18 (0x12) | Exported Function | 0x10007770 | 0x00007770
`SfpInstallCatalog` | 17 (0x11) | Exported Function | 0x10007760 | 0x00007760
`SfpDeleteCatalog` | 16 (0x10) | Exported Function | 0x10007750 | 0x00007750
`SfcTerminateWatcherThread` | 15 (0xf) | Exported Function | 0x10005dd0 | 0x00005dd0
`SfcIsKeyProtected` | 14 (0xe) | Exported Function | 0x10007580 | 0x00007580
`SfcIsFileProtected` | 13 (0xd) | Exported Function | 0x10004050 | 0x00004050
`SfcInstallProtectedFiles` | 12 (0xc) | Exported Function | 0x10007740 | 0x00007740
`SfcInitProt` | 10 (0xa) | Exported Function | 0x10007720 | 0x00007720
`SfcInitiateScan` | 11 (0xb) | Exported Function | 0x10007730 | 0x00007730
`SfcGetNextProtectedFile` | 9 (0x9) | Exported Function | 0x10007510 | 0x00007510
`SfcFileException` | 8 (0x8) | Exported Function | 0x10007710 | 0x00007710
`SfcConnectToServer` | 7 (0x7) | Exported Function | 0x10007700 | 0x00007700
`SfcClose` | 6 (0x6) | Exported Function | 0x100076f0 | 0x000076f0
`GetNextFileMapContent` | 3 (0x3) | Exported Function | 0x10007490 | 0x00007490
`CloseFileMapEnumeration` | 2 (0x2) | Exported Function | 0x10007450 | 0x00007450
`SRSetRestorePointA` | 4 (0x4) | Exported Function | 0x100075f0 | 0x000075f0
`SRSetRestorePointW` | 5 (0x5) | Exported Function | 0x10007670 | 0x00007670


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/bc902ac8d0236e20b4f214071e70bb962e5edbaf471e616cbc05adecd837cce2/detection/


## Possible Misuse

*The following table contains possible examples of `sfc_os.dll` being misused. While `sfc_os.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ghostdragon_gh0st_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ghostdragon_gh0st_rat.yar) | $s3 = "\\sfc_os.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


