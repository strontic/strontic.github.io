---
title: mssign32.dll | Microsoft Trust Signing APIs
excerpt: What is mssign32.dll?
---

# mssign32.dll 

* File Path: `C:\Windows\system32\mssign32.dll`
* Description: Microsoft Trust Signing APIs

## Hashes

Type | Hash
-- | --
MD5 | `B37F89A11F2C2CF45205EA7625600CEF`
SHA1 | `4839124F3C11E183B92AC0045BA1789BDF21B01A`
SHA256 | `D8632345802607314F5C4D1FD05C82181321B2A0BA7F355735F61BE639AE6A64`
SHA384 | `6DF837C9399579203C1CCBDDBD50E5B032DADA6A17672F0B7CE833E1DD32957DA67ECE1B9B36B1A3BAA1BBEB9848913A`
SHA512 | `D1339A430F5F7F5A75A6591371E6280D4E5BC181BD6E18C207B55A13BF5D8F09B7908CA16517F8373AE59654CB2140937369EFADCEBA1F03004108E0339049F9`
SSDEEP | `1536:iW45/eO0Zs98/3bV5CI/zApIQOG7sQjjAkvzGXE2ffVlEnLYQRw:iD5mO0ZiYw4gIQOG7sQjjhbFQ0s`
IMP | `909F7748A82975862068DF1E6C3A47F4`
PESHA1 | `6A4A81DA8B812F04A118FC934359E6992B2AC3D4`
PE256 | `B1C05345E20A6A638637038F09D237713D0906D8DC17CE91404AC9B2B29AB93E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllRegisterServer` | 1 (0x1) | Exported Function | 0x00000001800020e0 | 0x000020e0
`PvkPrivateKeySaveToMemory` | 21 (0x15) | Exported Function | 0x0000000180001a30 | 0x00001a30
`PvkPrivateKeySaveToMemoryA` | 22 (0x16) | Exported Function | 0x0000000180001af0 | 0x00001af0
`SignerAddTimeStampResponse` | 24 (0x18) | Exported Function | 0x0000000180001bf0 | 0x00001bf0
`SignerAddTimeStampResponseEx` | 25 (0x19) | Exported Function | 0x0000000180001c20 | 0x00001c20
`SignerCreateTimeStampRequest` | 26 (0x1a) | Exported Function | 0x0000000180001c30 | 0x00001c30
`SignerFreeSignerContext` | 27 (0x1b) | Exported Function | 0x0000000180001cf0 | 0x00001cf0
`PvkPrivateKeySaveA` | 20 (0x14) | Exported Function | 0x00000001800019f0 | 0x000019f0
`SignError` | 23 (0x17) | Exported Function | 0x0000000180001bb0 | 0x00001bb0
`SignerSignEx` | 29 (0x1d) | Exported Function | 0x0000000180001d90 | 0x00001d90
`SignerSignEx2` | 30 (0x1e) | Exported Function | 0x0000000180001e00 | 0x00001e00
`SignerSignEx3` | 31 (0x1f) | Exported Function | 0x0000000180001e90 | 0x00001e90
`SignerTimeStamp` | 32 (0x20) | Exported Function | 0x0000000180001f20 | 0x00001f20
`SignerTimeStampEx` | 33 (0x21) | Exported Function | 0x0000000180001f60 | 0x00001f60
`SignerTimeStampEx2` | 34 (0x22) | Exported Function | 0x0000000180001fa0 | 0x00001fa0
`SignerSign` | 28 (0x1c) | Exported Function | 0x0000000180001d40 | 0x00001d40
`PvkPrivateKeySave` | 19 (0x13) | Exported Function | 0x00000001800019b0 | 0x000019b0
`PvkPrivateKeyReleaseContextA` | 18 (0x12) | Exported Function | 0x0000000180001920 | 0x00001920
`PvkPrivateKeyReleaseContext` | 17 (0x11) | Exported Function | 0x0000000180001890 | 0x00001890
`DllUnregisterServer` | 2 (0x2) | Exported Function | 0x00000001800020e0 | 0x000020e0
`FreeCryptProvFromCert` | 3 (0x3) | Exported Function | 0x0000000180001010 | 0x00001010
`FreeCryptProvFromCertEx` | 4 (0x4) | Exported Function | 0x0000000180001080 | 0x00001080
`GetCryptProvFromCert` | 5 (0x5) | Exported Function | 0x00000001800010d0 | 0x000010d0
`GetCryptProvFromCertEx` | 6 (0x6) | Exported Function | 0x00000001800011b0 | 0x000011b0
`PvkFreeCryptProv` | 7 (0x7) | Exported Function | 0x0000000180001470 | 0x00001470
`PvkGetCryptProv` | 8 (0x8) | Exported Function | 0x0000000180001290 | 0x00001290
`PvkPrivateKeyAcquireContext` | 9 (0x9) | Exported Function | 0x00000001800014b0 | 0x000014b0
`PvkPrivateKeyAcquireContextA` | 10 (0xa) | Exported Function | 0x0000000180001550 | 0x00001550
`PvkPrivateKeyAcquireContextFromMemory` | 11 (0xb) | Exported Function | 0x00000001800015f0 | 0x000015f0
`PvkPrivateKeyAcquireContextFromMemoryA` | 12 (0xc) | Exported Function | 0x0000000180001660 | 0x00001660
`PvkPrivateKeyLoad` | 13 (0xd) | Exported Function | 0x00000001800016d0 | 0x000016d0
`PvkPrivateKeyLoadA` | 14 (0xe) | Exported Function | 0x0000000180001750 | 0x00001750
`PvkPrivateKeyLoadFromMemory` | 15 (0xf) | Exported Function | 0x00000001800017d0 | 0x000017d0
`PvkPrivateKeyLoadFromMemoryA` | 16 (0x10) | Exported Function | 0x0000000180001830 | 0x00001830
`SignerTimeStampEx3` | 35 (0x23) | Exported Function | 0x0000000180002000 | 0x00002000
`SpcGetCertFromKey` | 36 (0x24) | Exported Function | 0x00000001800020d0 | 0x000020d0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSSIGN32.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/d8632345802607314f5c4d1fd05c82181321b2a0ba7f355735f61be639ae6a64/detection/





MIT License. Copyright (c) 2020 Strontic.


