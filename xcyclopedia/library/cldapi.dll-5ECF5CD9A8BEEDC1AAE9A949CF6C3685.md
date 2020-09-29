---
title: cldapi.dll | Cloud API user mode API
excerpt: What is cldapi.dll?
---

# cldapi.dll 

* File Path: `C:\Windows\system32\cldapi.dll`
* Description: Cloud API user mode API

## Hashes

Type | Hash
-- | --
MD5 | `5ECF5CD9A8BEEDC1AAE9A949CF6C3685`
SHA1 | `3DFE753DDA2120596DC6701952E8261E4879C1CD`
SHA256 | `C31CC4ECA119BF92D3ED4C43FC48F4EFD8D5591818A4643B557080956E6181EF`
SHA384 | `4F29C9DC0F4826E9EFD95E2416F669C8156972DDF3BB3A46FFFCF3DD7EBE6BBC3243D3DFACFF146F8CC700BFC386476F`
SHA512 | `8ADE2E923063FB6CE06F51583197457E676CD433848D1E6AF8B4213628143D6CDB04B1CE1EBC376F6058BB151B099D93161C312F0ED0E748482059F60B5B7BDF`
SSDEEP | `3072:2eomoxUR7EOUHY67BbwEIEq91O0Y0vKyTD3bJ:hhCUlW7ijK6L`
IMP | `394DA184D86E7747F4BAFBB4E0AA335B`
PESHA1 | `8C59FE35CAE39995AB4950205D56899F9E97F6E6`
PE256 | `9FB11EAB57A258066EE44F53EBB3B48482C025DCD770CE1B7B15396EFAF16E41`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CfAbortOperation` | 1 (0x1) | Exported Function | 0x0000000180001de0 | 0x00001de0
`CfOpenFileWithOplock` | 27 (0x1b) | Exported Function | 0x0000000180002c30 | 0x00002c30
`CfOpenProgressEvent` | 28 (0x1c) | Exported Function | 0x00000001800013b0 | 0x000013b0
`CfQueryProgress` | 29 (0x1d) | Exported Function | 0x0000000180001470 | 0x00001470
`CfQuerySyncProviderStatus` | 30 (0x1e) | Exported Function | 0x000000018000b9c0 | 0x0000b9c0
`CfReferenceProtectedHandle` | 31 (0x1f) | Exported Function | 0x0000000180003280 | 0x00003280
`CfRegisterSyncRoot` | 32 (0x20) | Exported Function | 0x0000000180005eb0 | 0x00005eb0
`CfReleaseProtectedHandle` | 33 (0x21) | Exported Function | 0x00000001800032d0 | 0x000032d0
`CfReleaseTransferKey` | 34 (0x22) | Exported Function | 0x00000001800032d0 | 0x000032d0
`CfReportProviderProgress` | 35 (0x23) | Exported Function | 0x0000000180001840 | 0x00001840
`CfOpenAppPolicy` | 26 (0x1a) | Exported Function | 0x0000000180002410 | 0x00002410
`CfReportProviderProgress2` | 36 (0x24) | Exported Function | 0x0000000180001870 | 0x00001870
`CfRetrieveProperties` | 38 (0x26) | Exported Function | 0x000000018000dad0 | 0x0000dad0
`CfRevertPlaceholder` | 39 (0x27) | Exported Function | 0x000000018000c8f0 | 0x0000c8f0
`CfSetAppPolicy` | 40 (0x28) | Exported Function | 0x0000000180002740 | 0x00002740
`CfSetCorrelationVector` | 41 (0x29) | Exported Function | 0x000000018000d030 | 0x0000d030
`CfSetInSyncState` | 42 (0x2a) | Exported Function | 0x000000018000ce40 | 0x0000ce40
`CfSetPinState` | 43 (0x2b) | Exported Function | 0x000000018000ccd0 | 0x0000ccd0
`CfStoreProperties` | 44 (0x2c) | Exported Function | 0x000000018000da20 | 0x0000da20
`CfUnlockProperties` | 45 (0x2d) | Exported Function | 0x000000018000d970 | 0x0000d970
`CfUnregisterSyncRoot` | 46 (0x2e) | Exported Function | 0x0000000180007070 | 0x00007070
`CfReportSyncStatus` | 37 (0x25) | Exported Function | 0x000000018000bab0 | 0x0000bab0
`CfLockProperties` | 25 (0x19) | Exported Function | 0x000000018000d890 | 0x0000d890
`CfHydratePlaceholder` | 24 (0x18) | Exported Function | 0x000000018000c9f0 | 0x0000c9f0
`CfGetWin32HandleFromProtectedHandle` | 23 (0x17) | Exported Function | 0x00000001800032b0 | 0x000032b0
`CfCloseAppPolicy` | 2 (0x2) | Exported Function | 0x00000001800024c0 | 0x000024c0
`CfCloseHandle` | 3 (0x3) | Exported Function | 0x00000001800032e0 | 0x000032e0
`CfConnectSyncRoot` | 4 (0x4) | Exported Function | 0x0000000180007360 | 0x00007360
`CfConvertToPlaceholder` | 5 (0x5) | Exported Function | 0x000000018000c2d0 | 0x0000c2d0
`CfCreatePlaceholders` | 6 (0x6) | Exported Function | 0x000000018000c050 | 0x0000c050
`CfDehydratePlaceholder` | 7 (0x7) | Exported Function | 0x000000018000cca0 | 0x0000cca0
`CfDehydratePlaceholderEx` | 8 (0x8) | Exported Function | 0x000000018000cb00 | 0x0000cb00
`CfDisconnectSyncRoot` | 9 (0x9) | Exported Function | 0x0000000180007f90 | 0x00007f90
`CfEnumAppPolicy` | 10 (0xa) | Exported Function | 0x00000001800024f0 | 0x000024f0
`CfExecute` | 11 (0xb) | Exported Function | 0x000000018000ae80 | 0x0000ae80
`CfGetCorrelationVector` | 12 (0xc) | Exported Function | 0x000000018000d160 | 0x0000d160
`CfGetLastSyncStatus` | 13 (0xd) | Exported Function | 0x0000000180002380 | 0x00002380
`CfGetPlaceholderInfo` | 14 (0xe) | Exported Function | 0x000000018000d270 | 0x0000d270
`CfGetPlaceholderRangeInfo` | 15 (0xf) | Exported Function | 0x000000018000d670 | 0x0000d670
`CfGetPlaceholderStateFromAttributeTag` | 16 (0x10) | Exported Function | 0x0000000180013400 | 0x00013400
`CfGetPlaceholderStateFromFileInfo` | 17 (0x11) | Exported Function | 0x0000000180013410 | 0x00013410
`CfGetPlaceholderStateFromFindData` | 18 (0x12) | Exported Function | 0x00000001800134d0 | 0x000134d0
`CfGetPlatformInfo` | 19 (0x13) | Exported Function | 0x000000018000d230 | 0x0000d230
`CfGetSyncRootInfoByHandle` | 20 (0x14) | Exported Function | 0x000000018000d400 | 0x0000d400
`CfGetSyncRootInfoByPath` | 21 (0x15) | Exported Function | 0x000000018000d590 | 0x0000d590
`CfGetTransferKey` | 22 (0x16) | Exported Function | 0x000000018000cf90 | 0x0000cf90
`CfUpdatePlaceholder` | 47 (0x2f) | Exported Function | 0x000000018000c4f0 | 0x0000c4f0
`CfUpdateSyncProviderStatus` | 48 (0x30) | Exported Function | 0x000000018000b260 | 0x0000b260


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/c31cc4eca119bf92d3ed4c43fc48f4efd8d5591818a4643b557080956e6181ef/detection/





MIT License. Copyright (c) 2020 Strontic.


