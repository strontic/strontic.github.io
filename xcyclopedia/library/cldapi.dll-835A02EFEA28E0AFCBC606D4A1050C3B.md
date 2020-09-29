---
title: cldapi.dll | Cloud API user mode API
excerpt: What is cldapi.dll?
---

# cldapi.dll 

* File Path: `C:\Windows\SysWOW64\cldapi.dll`
* Description: Cloud API user mode API

## Hashes

Type | Hash
-- | --
MD5 | `835A02EFEA28E0AFCBC606D4A1050C3B`
SHA1 | `ED92A31F02D50A6832412AB3633242487BD2D992`
SHA256 | `11FA23622DA9B79DE9C41876E3A9F28AF9E17B1A4A7B60D0D17A7D9AC8C2B918`
SHA384 | `6DE5C7584C280FC6E9B775FDB75E9D2A689610A536D4738C2AECB7FE5B76BDD0DC26EFCD629AD0AB612F9C20426E69A2`
SHA512 | `32B18499116D1935F322BB824E25556593299332E954115F42AB68EE46BCB347E648BA98A85F8A7D57A30F4B69A63A7AA9DBB77592173A6993D56854279F1797`
SSDEEP | `1536:lClq+m52joc/T8XuJQkudz+Qnpn4xiHo8VzdCKD2ALyTDcEotZ:lClq+mIi+sdz+61HoidH2yyTD3ot`
IMP | `8148D528DFEFF655392751FE1BC3407C`
PESHA1 | `733A25090458D163324693F71A09C3ED52C5F355`
PE256 | `A7221029584A5111F38AB92351E0290A4E75A476B059DA7966CBC618D3ACEAEE`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CfAbortOperation` | 1 (0x1) | Exported Function | 0x10004050 | 0x00004050
`CfOpenFileWithOplock` | 27 (0x1b) | Exported Function | 0x10004c30 | 0x00004c30
`CfOpenProgressEvent` | 28 (0x1c) | Exported Function | 0x10003650 | 0x00003650
`CfQueryProgress` | 29 (0x1d) | Exported Function | 0x100036f0 | 0x000036f0
`CfQuerySyncProviderStatus` | 30 (0x1e) | Exported Function | 0x1000c620 | 0x0000c620
`CfReferenceProtectedHandle` | 31 (0x1f) | Exported Function | 0x10005110 | 0x00005110
`CfRegisterSyncRoot` | 32 (0x20) | Exported Function | 0x10007960 | 0x00007960
`CfReleaseProtectedHandle` | 33 (0x21) | Exported Function | 0x10005160 | 0x00005160
`CfReleaseTransferKey` | 34 (0x22) | Exported Function | 0x1000d8b0 | 0x0000d8b0
`CfReportProviderProgress` | 36 (0x24) | Exported Function | 0x10003ad0 | 0x00003ad0
`CfOpenAppPolicy` | 26 (0x1a) | Exported Function | 0x10004640 | 0x00004640
`CfReportProviderProgress2` | 35 (0x23) | Exported Function | 0x10003b10 | 0x00003b10
`CfRetrieveProperties` | 38 (0x26) | Exported Function | 0x1000e020 | 0x0000e020
`CfRevertPlaceholder` | 39 (0x27) | Exported Function | 0x1000d320 | 0x0000d320
`CfSetAppPolicy` | 40 (0x28) | Exported Function | 0x100048c0 | 0x000048c0
`CfSetCorrelationVector` | 41 (0x29) | Exported Function | 0x1000d8d0 | 0x0000d8d0
`CfSetInSyncState` | 42 (0x2a) | Exported Function | 0x1000d730 | 0x0000d730
`CfSetPinState` | 43 (0x2b) | Exported Function | 0x1000d620 | 0x0000d620
`CfStoreProperties` | 44 (0x2c) | Exported Function | 0x1000dfb0 | 0x0000dfb0
`CfUnlockProperties` | 45 (0x2d) | Exported Function | 0x1000df30 | 0x0000df30
`CfUnregisterSyncRoot` | 46 (0x2e) | Exported Function | 0x10008910 | 0x00008910
`CfReportSyncStatus` | 37 (0x25) | Exported Function | 0x1000c6c0 | 0x0000c6c0
`CfLockProperties` | 25 (0x19) | Exported Function | 0x1000dea0 | 0x0000dea0
`CfHydratePlaceholder` | 24 (0x18) | Exported Function | 0x1000d3d0 | 0x0000d3d0
`CfGetWin32HandleFromProtectedHandle` | 23 (0x17) | Exported Function | 0x10005140 | 0x00005140
`CfCloseAppPolicy` | 2 (0x2) | Exported Function | 0x100046c0 | 0x000046c0
`CfCloseHandle` | 3 (0x3) | Exported Function | 0x10005180 | 0x00005180
`CfConnectSyncRoot` | 4 (0x4) | Exported Function | 0x10008b60 | 0x00008b60
`CfConvertToPlaceholder` | 5 (0x5) | Exported Function | 0x1000ce00 | 0x0000ce00
`CfCreatePlaceholders` | 6 (0x6) | Exported Function | 0x1000cbc0 | 0x0000cbc0
`CfDehydratePlaceholder` | 7 (0x7) | Exported Function | 0x1000d5f0 | 0x0000d5f0
`CfDehydratePlaceholderEx` | 8 (0x8) | Exported Function | 0x1000d4a0 | 0x0000d4a0
`CfDisconnectSyncRoot` | 9 (0x9) | Exported Function | 0x10009550 | 0x00009550
`CfEnumAppPolicy` | 10 (0xa) | Exported Function | 0x100046e0 | 0x000046e0
`CfExecute` | 11 (0xb) | Exported Function | 0x1000bdf0 | 0x0000bdf0
`CfGetCorrelationVector` | 12 (0xc) | Exported Function | 0x1000d980 | 0x0000d980
`CfGetLastSyncStatus` | 13 (0xd) | Exported Function | 0x100045e0 | 0x000045e0
`CfGetPlaceholderInfo` | 14 (0xe) | Exported Function | 0x1000da60 | 0x0000da60
`CfGetPlaceholderRangeInfo` | 15 (0xf) | Exported Function | 0x1000dd10 | 0x0000dd10
`CfGetPlaceholderStateFromAttributeTag` | 16 (0x10) | Exported Function | 0x10012ef0 | 0x00012ef0
`CfGetPlaceholderStateFromFileInfo` | 17 (0x11) | Exported Function | 0x10012f10 | 0x00012f10
`CfGetPlaceholderStateFromFindData` | 18 (0x12) | Exported Function | 0x10012f60 | 0x00012f60
`CfGetPlatformInfo` | 19 (0x13) | Exported Function | 0x1000da10 | 0x0000da10
`CfGetSyncRootInfoByHandle` | 20 (0x14) | Exported Function | 0x1000db80 | 0x0000db80
`CfGetSyncRootInfoByPath` | 21 (0x15) | Exported Function | 0x1000dc80 | 0x0000dc80
`CfGetTransferKey` | 22 (0x16) | Exported Function | 0x1000d840 | 0x0000d840
`CfUpdatePlaceholder` | 47 (0x2f) | Exported Function | 0x1000cfa0 | 0x0000cfa0
`CfUpdateSyncProviderStatus` | 48 (0x30) | Exported Function | 0x1000c010 | 0x0000c010


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cldapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/11fa23622da9b79de9c41876e3a9f28af9e17b1a4a7b60d0d17a7d9ac8c2b918/detection/





MIT License. Copyright (c) 2020 Strontic.


