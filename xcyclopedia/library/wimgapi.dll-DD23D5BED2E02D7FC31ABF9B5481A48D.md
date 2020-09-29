---
title: wimgapi.dll | Windows Imaging Library
excerpt: What is wimgapi.dll?
---

# wimgapi.dll 

* File Path: `C:\Windows\system32\wimgapi.dll`
* Description: Windows Imaging Library

## Hashes

Type | Hash
-- | --
MD5 | `DD23D5BED2E02D7FC31ABF9B5481A48D`
SHA1 | `F392D6B0DE93C73EC82FD54D2841A2DB770C512D`
SHA256 | `6FF14D2A8F42A59C993AB529743B8E5CAA14733D2874035577E1A007255CAED8`
SHA384 | `975A802A2240646AABCAD1B529EB1E33A3AF2CE2747C9216E48CC88FDEEB019402DD794DEDB9E1ED747B96AE66CD0049`
SHA512 | `21625BB2BAFB4FFB6761ECE1BB6D93E32E47B56B6D331E499319715AE31131CB1B55A35FFDCE3A0C58585020408C4776219F2EF4A2DA1D93DC13E4B5C40CB005`
SSDEEP | `12288:3zJmRZqPqlQG9Pb7LOcPox1c/b+g9LisflGpOhaFQ8H7G9jg:3zIPqPqLNv/+UUKMDH7yU`
IMP | `E4360ED9E5EE17BC47267C1423CD8399`
PESHA1 | `3D844F2D453CCB5CB62C8BBEBA15698BEB82BCF4`
PE256 | `E5221F90B4F4CA8400350907B85E37090082790332109BD6C7F0CEBD12AA2B2D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x0000000180001050 | 0x00001050
`WIMInitializeWofDriver` | 33 (0x21) | Exported Function | 0x0000000180003f30 | 0x00003f30
`WIMIsCurrentSystemWimboot` | 34 (0x22) | Exported Function | 0x00000001800030b0 | 0x000030b0
`WIMIsReferenceWim` | 35 (0x23) | Exported Function | 0x0000000180017850 | 0x00017850
`WIMLoadImage` | 36 (0x24) | Exported Function | 0x000000018001f610 | 0x0001f610
`WIMMountImage` | 37 (0x25) | Exported Function | 0x00000001800104c0 | 0x000104c0
`WIMMountImageHandle` | 38 (0x26) | Exported Function | 0x000000018000e910 | 0x0000e910
`WIMProcessCustomImage` | 39 (0x27) | Exported Function | 0x0000000180025e10 | 0x00025e10
`WIMReadFileEx` | 40 (0x28) | Exported Function | 0x000000018000ba30 | 0x0000ba30
`WIMReadImageFile` | 41 (0x29) | Exported Function | 0x0000000180016050 | 0x00016050
`WIMRedirectFolderBeforeApply` | 42 (0x2a) | Exported Function | 0x0000000180005230 | 0x00005230
`WIMRegisterLogFile` | 43 (0x2b) | Exported Function | 0x0000000180028220 | 0x00028220
`WIMRegisterMessageCallback` | 44 (0x2c) | Exported Function | 0x000000018001de00 | 0x0001de00
`WIMInitFileIOCallbacks` | 32 (0x20) | Exported Function | 0x000000018001f110 | 0x0001f110
`WIMRemountImage` | 45 (0x2d) | Exported Function | 0x0000000180010770 | 0x00010770
`WIMSetFileIOCallbackTemporaryPath` | 47 (0x2f) | Exported Function | 0x000000018001f170 | 0x0001f170
`WIMSetImageInformation` | 48 (0x30) | Exported Function | 0x000000018001c980 | 0x0001c980
`WIMSetImageUserSpecifiedCreationTime` | 49 (0x31) | Exported Function | 0x0000000180009e90 | 0x00009e90
`WIMSetReferenceFile` | 50 (0x32) | Exported Function | 0x000000018000b340 | 0x0000b340
`WIMSetTemporaryPath` | 51 (0x33) | Exported Function | 0x000000018000af80 | 0x0000af80
`WIMSetWimGuid` | 52 (0x34) | Exported Function | 0x0000000180009e40 | 0x00009e40
`WIMSingleInstanceFile` | 53 (0x35) | Exported Function | 0x0000000180017400 | 0x00017400
`WIMSplitFile` | 54 (0x36) | Exported Function | 0x0000000180029600 | 0x00029600
`WIMUnmountImage` | 55 (0x37) | Exported Function | 0x0000000180010c40 | 0x00010c40
`WIMUnmountImageHandle` | 56 (0x38) | Exported Function | 0x000000018000ffb0 | 0x0000ffb0
`WIMUnregisterLogFile` | 57 (0x39) | Exported Function | 0x0000000180028470 | 0x00028470
`WIMUnregisterMessageCallback` | 58 (0x3a) | Exported Function | 0x000000018001df80 | 0x0001df80
`WIMSetBootImage` | 46 (0x2e) | Exported Function | 0x000000018000b080 | 0x0000b080
`WIMGetWIMBootWIMPath` | 31 (0x1f) | Exported Function | 0x0000000180002960 | 0x00002960
`WIMGetWIMBootEntries` | 30 (0x1e) | Exported Function | 0x0000000180002d20 | 0x00002d20
`WIMGetMountedImages` | 29 (0x1d) | Exported Function | 0x0000000180011c10 | 0x00011c10
`DllMain` | 2 (0x2) | Exported Function | 0x0000000180001010 | 0x00001010
`WIMAddImagePath` | 3 (0x3) | Exported Function | 0x0000000180001e20 | 0x00001e20
`WIMAddImagePaths` | 4 (0x4) | Exported Function | 0x0000000180002540 | 0x00002540
`WIMAddWimbootEntry` | 5 (0x5) | Exported Function | 0x0000000180002f00 | 0x00002f00
`WIMApplyImage` | 6 (0x6) | Exported Function | 0x0000000180005300 | 0x00005300
`WIMCaptureImage` | 7 (0x7) | Exported Function | 0x0000000180009bb0 | 0x00009bb0
`WIMCloseHandle` | 8 (0x8) | Exported Function | 0x000000018000aec0 | 0x0000aec0
`WIMCommitImageHandle` | 9 (0x9) | Exported Function | 0x000000018000f7c0 | 0x0000f7c0
`WIMCopyFile` | 10 (0xa) | Exported Function | 0x00000001800122a0 | 0x000122a0
`WIMCreateFile` | 11 (0xb) | Exported Function | 0x000000018000a230 | 0x0000a230
`WIMCreateImageFile` | 12 (0xc) | Exported Function | 0x0000000180017230 | 0x00017230
`WIMCreateWofCompressedFile` | 13 (0xd) | Exported Function | 0x0000000180005570 | 0x00005570
`WIMDeleteImage` | 14 (0xe) | Exported Function | 0x0000000180017e40 | 0x00017e40
`WIMDeleteImageMounts` | 15 (0xf) | Exported Function | 0x000000018000e420 | 0x0000e420
`WIMEnumImageFiles` | 16 (0x10) | Exported Function | 0x0000000180017000 | 0x00017000
`WIMExportImage` | 17 (0x11) | Exported Function | 0x0000000180018ea0 | 0x00018ea0
`WIMExtractImageDirectory` | 18 (0x12) | Exported Function | 0x000000018001a480 | 0x0001a480
`WIMExtractImagePath` | 19 (0x13) | Exported Function | 0x0000000180019c80 | 0x00019c80
`WIMFindFirstImageFile` | 20 (0x14) | Exported Function | 0x0000000180016bd0 | 0x00016bd0
`WIMFindNextImageFile` | 21 (0x15) | Exported Function | 0x0000000180016e80 | 0x00016e80
`WIMGetAttributes` | 22 (0x16) | Exported Function | 0x000000018000b600 | 0x0000b600
`WIMGetImageCount` | 23 (0x17) | Exported Function | 0x000000018000b5b0 | 0x0000b5b0
`WIMGetImageInformation` | 24 (0x18) | Exported Function | 0x000000018001c660 | 0x0001c660
`WIMGetMessageCallbackCount` | 25 (0x19) | Exported Function | 0x000000018001dd70 | 0x0001dd70
`WIMGetMountedImageHandle` | 26 (0x1a) | Exported Function | 0x0000000180011cd0 | 0x00011cd0
`WIMGetMountedImageInfo` | 27 (0x1b) | Exported Function | 0x00000001800116d0 | 0x000116d0
`WIMGetMountedImageInfoFromHandle` | 28 (0x1c) | Exported Function | 0x0000000180011950 | 0x00011950
`WIMUpdateWIMBootEntry` | 59 (0x3b) | Exported Function | 0x0000000180002ba0 | 0x00002ba0
`WIMWriteFileWithIntegrity` | 60 (0x3c) | Exported Function | 0x0000000180015990 | 0x00015990


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/6ff14d2a8f42a59c993ab529743b8e5caa14733d2874035577e1a007255caed8/detection/





MIT License. Copyright (c) 2020 Strontic.


