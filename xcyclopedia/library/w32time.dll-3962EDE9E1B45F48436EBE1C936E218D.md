---
title: w32time.dll | Windows Time Service
excerpt: What is w32time.dll?
---

# w32time.dll 

* File Path: `C:\Windows\system32\w32time.dll`
* Description: Windows Time Service

## Hashes

Type | Hash
-- | --
MD5 | `3962EDE9E1B45F48436EBE1C936E218D`
SHA1 | `DBFFB9FDB9E698B6E989E846B2342D967BEECBB4`
SHA256 | `4C215BBFF5A2CB97A39E4F3181060DBB720438B4BAB0381B0EA35212173D6D34`
SHA384 | `35E5D236E57AB727CD7F67E110B90245EA2A448820A8064EF2175BE3E4A89551B23EF8B98686208FC331A450F77CF0F5`
SHA512 | `C872C917BB9F796D7E01AB6E24C50A0CF60DB20FCDC5CFAFF48CB679CCFD3CA2A299AAF525144284ED9C7869232C2CF6173C4C5D38E558C854DED717A0BDF447`
SSDEEP | `6144:jnxEs81LYus15tPc31IlWUfDuPTb3oQGQIju8NcTtxpwjFd6nYJu9YptA:jesIXspc8xruJ4NOwZFJu2vA`
IMP | `6E7ACBD5F914D164F0CA7F46F71E4D91`
PESHA1 | `24CFECDD72C23F65B301DDA440F9E5B65F516A59`
PE256 | `165C3817B2D47E85D4D16ED5BE63FDDE09FDB9A18CDA9C70F0D7D482E6E9FCA8`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllInstall` | 4 (0x4) | Exported Function | 0x0000000180021a70 | 0x00021a70
`W32TimeVerifyJoinConfig` | 26 (0x1a) | Exported Function | 0x0000000180021fa0 | 0x00021fa0
`W32TimeSyncNow` | 25 (0x19) | Exported Function | 0x000000018003f810 | 0x0003f810
`W32TimeSetConfig` | 24 (0x18) | Exported Function | 0x000000018003fe10 | 0x0003fe10
`W32TimeQueryStatus` | 23 (0x17) | Exported Function | 0x000000018003f5e0 | 0x0003f5e0
`W32TimeQuerySource` | 22 (0x16) | Exported Function | 0x000000018003f3b0 | 0x0003f3b0
`W32TimeQueryNTPProviderStatus` | 20 (0x14) | Exported Function | 0x000000018003f140 | 0x0003f140
`W32TimeQueryNtpProviderConfiguration` | 21 (0x15) | Exported Function | 0x000000018003f160 | 0x0003f160
`W32TimeQueryHardwareProviderStatus` | 19 (0x13) | Exported Function | 0x000000018003f120 | 0x0003f120
`W32TimeQueryConfiguration` | 18 (0x12) | Exported Function | 0x000000018003eef0 | 0x0003eef0
`W32TimeQueryConfig` | 17 (0x11) | Exported Function | 0x000000018003fd70 | 0x0003fd70
`W32TimeLog` | 16 (0x10) | Exported Function | 0x000000018003ed50 | 0x0003ed50
`W32TimeGetNetlogonServiceBits` | 15 (0xf) | Exported Function | 0x000000018003ebb0 | 0x0003ebb0
`W32TimeDeleteConfig` | 14 (0xe) | Exported Function | 0x000000018003fd00 | 0x0003fd00
`W32TimeDcPromo` | 13 (0xd) | Exported Function | 0x0000000180021c70 | 0x00021c70
`W32TimeBufferFree` | 12 (0xc) | Exported Function | 0x0000000180035cb0 | 0x00035cb0
`TimeProvOpen` | 11 (0xb) | Exported Function | 0x000000018001fd70 | 0x0001fd70
`TimeProvCommand` | 10 (0xa) | Exported Function | 0x000000018001fd20 | 0x0001fd20
`TimeProvClose` | 9 (0x9) | Exported Function | 0x000000018001fcb0 | 0x0001fcb0
`SvchostPushServiceGlobals` | 8 (0x8) | Exported Function | 0x00000001800328c0 | 0x000328c0
`SvchostEntry_W32Time` | 7 (0x7) | Exported Function | 0x0000000180032880 | 0x00032880
`fnW32TmSetServiceStatus` | 3 (0x3) | Exported Function | 0x0000000180069c00 | 0x00069c00
`fnW32TmRegisterServiceCtrlHandlerEx` | 2 (0x2) | Exported Function | 0x0000000180069c08 | 0x00069c08
`fnW32TmI_ScSetServiceBits` | 1 (0x1) | Exported Function | 0x0000000180069bf8 | 0x00069bf8
`DllUnregisterServer` | 6 (0x6) | Exported Function | 0x0000000180021c50 | 0x00021c50
`DllRegisterServer` | 5 (0x5) | Exported Function | 0x0000000180021c00 | 0x00021c00
`W32TimeVerifyUnjoinConfig` | 27 (0x1b) | Exported Function | 0x0000000180022140 | 0x00022140
`W32TmServiceMain` | 28 (0x1c) | Exported Function | 0x00000001800328d0 | 0x000328d0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: w32time.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/4c215bbff5a2cb97a39e4f3181060dbb720438b4bab0381b0ea35212173d6d34/detection/





MIT License. Copyright (c) 2020 Strontic.


