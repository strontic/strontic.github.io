---
title: wimgapi.dll | Windows Imaging Library
excerpt: What is wimgapi.dll?
---

# wimgapi.dll 

* File Path: `C:\Windows\SysWOW64\wimgapi.dll`
* Description: Windows Imaging Library

## Hashes

Type | Hash
-- | --
MD5 | `B3A56C46D9B5B8BF28DEB743270C409E`
SHA1 | `50821EF7EE43B5AC901C820445F4B76DD4600D55`
SHA256 | `640BDEAE15BFDBF15637D33975DE696D4BFD82930FBFCABBD2F32B0842362C9D`
SHA384 | `EC0D6198C61967CE646144D9720241A1CCC69068B8455497BA8F11C616054B263B1E58186C0C7174964576A3CE713209`
SHA512 | `6DEE575A864E1EBFC03ACC9B6CAE07F0AA211852341C27119383BD75F0038AA7806A891563F2BA7C8C062E41DCCCB15340B9010BD42CE2D3F8DFCA2A717C962D`
SSDEEP | `12288:KaVT4wR9qY4HcHQaFbfoCuV0KeTNgBTviRmhgo9b6JH3uJfsMP/eC7uza:/EYaCQC0CceTNg5b6JH3WfskWC7p`
IMP | `5E277EAD715A675DD02C098E71CF080E`
PESHA1 | `3A416E422858B58D4B06FCF9D174ED34F24F0802`
PE256 | `585F582149F402334BB13E7D3AFB8455F335EE0EBBA7C6EE9B92CEA596880DD8`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x10015c60 | 0x00015c60
`WIMInitializeWofDriver` | 33 (0x21) | Exported Function | 0x10017e20 | 0x00017e20
`WIMIsCurrentSystemWimboot` | 34 (0x22) | Exported Function | 0x10017640 | 0x00017640
`WIMIsReferenceWim` | 35 (0x23) | Exported Function | 0x10026fc0 | 0x00026fc0
`WIMLoadImage` | 36 (0x24) | Exported Function | 0x1002d020 | 0x0002d020
`WIMMountImage` | 37 (0x25) | Exported Function | 0x100210e0 | 0x000210e0
`WIMMountImageHandle` | 38 (0x26) | Exported Function | 0x1001fc90 | 0x0001fc90
`WIMProcessCustomImage` | 39 (0x27) | Exported Function | 0x100318a0 | 0x000318a0
`WIMReadFileEx` | 40 (0x28) | Exported Function | 0x1001d770 | 0x0001d770
`WIMReadImageFile` | 41 (0x29) | Exported Function | 0x10025b50 | 0x00025b50
`WIMRedirectFolderBeforeApply` | 42 (0x2a) | Exported Function | 0x100188a0 | 0x000188a0
`WIMRegisterLogFile` | 43 (0x2b) | Exported Function | 0x100332e0 | 0x000332e0
`WIMRegisterMessageCallback` | 44 (0x2c) | Exported Function | 0x1002bee0 | 0x0002bee0
`WIMInitFileIOCallbacks` | 32 (0x20) | Exported Function | 0x1002cc70 | 0x0002cc70
`WIMRemountImage` | 45 (0x2d) | Exported Function | 0x10021310 | 0x00021310
`WIMSetFileIOCallbackTemporaryPath` | 47 (0x2f) | Exported Function | 0x1002ccb0 | 0x0002ccb0
`WIMSetImageInformation` | 48 (0x30) | Exported Function | 0x1002ad40 | 0x0002ad40
`WIMSetImageUserSpecifiedCreationTime` | 49 (0x31) | Exported Function | 0x1001c2a0 | 0x0001c2a0
`WIMSetReferenceFile` | 50 (0x32) | Exported Function | 0x1001d300 | 0x0001d300
`WIMSetTemporaryPath` | 51 (0x33) | Exported Function | 0x1001d050 | 0x0001d050
`WIMSetWimGuid` | 52 (0x34) | Exported Function | 0x1001c270 | 0x0001c270
`WIMSingleInstanceFile` | 53 (0x35) | Exported Function | 0x10026c40 | 0x00026c40
`WIMSplitFile` | 54 (0x36) | Exported Function | 0x10033d80 | 0x00033d80
`WIMUnmountImage` | 55 (0x37) | Exported Function | 0x10021620 | 0x00021620
`WIMUnmountImageHandle` | 56 (0x38) | Exported Function | 0x10020d50 | 0x00020d50
`WIMUnregisterLogFile` | 57 (0x39) | Exported Function | 0x10033490 | 0x00033490
`WIMUnregisterMessageCallback` | 58 (0x3a) | Exported Function | 0x1002c000 | 0x0002c000
`WIMSetBootImage` | 46 (0x2e) | Exported Function | 0x1001d0d0 | 0x0001d0d0
`WIMGetWIMBootWIMPath` | 31 (0x1f) | Exported Function | 0x100170b0 | 0x000170b0
`WIMGetWIMBootEntries` | 30 (0x1e) | Exported Function | 0x10017390 | 0x00017390
`WIMGetMountedImages` | 29 (0x1d) | Exported Function | 0x10022360 | 0x00022360
`DllMain` | 2 (0x2) | Exported Function | 0x10015c30 | 0x00015c30
`WIMAddImagePath` | 3 (0x3) | Exported Function | 0x10016760 | 0x00016760
`WIMAddImagePaths` | 4 (0x4) | Exported Function | 0x10016cf0 | 0x00016cf0
`WIMAddWimbootEntry` | 5 (0x5) | Exported Function | 0x10017500 | 0x00017500
`WIMApplyImage` | 6 (0x6) | Exported Function | 0x10018920 | 0x00018920
`WIMCaptureImage` | 7 (0x7) | Exported Function | 0x1001c0a0 | 0x0001c0a0
`WIMCloseHandle` | 8 (0x8) | Exported Function | 0x1001cfd0 | 0x0001cfd0
`WIMCommitImageHandle` | 9 (0x9) | Exported Function | 0x100207c0 | 0x000207c0
`WIMCopyFile` | 10 (0xa) | Exported Function | 0x100228c0 | 0x000228c0
`WIMCreateFile` | 11 (0xb) | Exported Function | 0x1001c550 | 0x0001c550
`WIMCreateImageFile` | 12 (0xc) | Exported Function | 0x10026ad0 | 0x00026ad0
`WIMCreateWofCompressedFile` | 13 (0xd) | Exported Function | 0x10018ac0 | 0x00018ac0
`WIMDeleteImage` | 14 (0xe) | Exported Function | 0x10027450 | 0x00027450
`WIMDeleteImageMounts` | 15 (0xf) | Exported Function | 0x1001f830 | 0x0001f830
`WIMEnumImageFiles` | 16 (0x10) | Exported Function | 0x10026900 | 0x00026900
`WIMExportImage` | 17 (0x11) | Exported Function | 0x100280d0 | 0x000280d0
`WIMExtractImageDirectory` | 18 (0x12) | Exported Function | 0x10029120 | 0x00029120
`WIMExtractImagePath` | 19 (0x13) | Exported Function | 0x10028a90 | 0x00028a90
`WIMFindFirstImageFile` | 20 (0x14) | Exported Function | 0x100265e0 | 0x000265e0
`WIMFindNextImageFile` | 21 (0x15) | Exported Function | 0x100267e0 | 0x000267e0
`WIMGetAttributes` | 22 (0x16) | Exported Function | 0x1001d500 | 0x0001d500
`WIMGetImageCount` | 23 (0x17) | Exported Function | 0x1001d4b0 | 0x0001d4b0
`WIMGetImageInformation` | 24 (0x18) | Exported Function | 0x1002aad0 | 0x0002aad0
`WIMGetMessageCallbackCount` | 25 (0x19) | Exported Function | 0x1002be70 | 0x0002be70
`WIMGetMountedImageHandle` | 26 (0x1a) | Exported Function | 0x10022410 | 0x00022410
`WIMGetMountedImageInfo` | 27 (0x1b) | Exported Function | 0x10021e10 | 0x00021e10
`WIMGetMountedImageInfoFromHandle` | 28 (0x1c) | Exported Function | 0x10022050 | 0x00022050
`WIMUpdateWIMBootEntry` | 59 (0x3b) | Exported Function | 0x10017250 | 0x00017250
`WIMWriteFileWithIntegrity` | 60 (0x3c) | Exported Function | 0x10025530 | 0x00025530


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WIMGAPI.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/640bdeae15bfdbf15637d33975de696d4bfd82930fbfcabbd2f32b0842362c9d/detection/





MIT License. Copyright (c) 2020 Strontic.


