---
title: ipnathlp.dll | Microsoft NAT Helper Components
excerpt: What is ipnathlp.dll?
---

# ipnathlp.dll 

* File Path: `C:\Windows\system32\ipnathlp.dll`
* Description: Microsoft NAT Helper Components

## Hashes

Type | Hash
-- | --
MD5 | `695E536B9372B209473FC3B29343DB27`
SHA1 | `03D946D3748EB7D81EE92FCFCA44CAED21D87D4C`
SHA256 | `EFD82274D4555457A44E8A9C7FC2A767075196218FD62790D9DEEED1732B2A86`
SHA384 | `C443D039586276BF842E0CC5D79223C379F70E2AF1A247E4A1267347E1C4D0068C4B18532721710797F7990340CE76F5`
SHA512 | `172C3307559E24AF4A214353B30BA603DFF2380F971F5E3C2D18FC8FFE0F9C71FCFDD6763C51B8A82D0FBAA3EEE19483B69575F67C9DFE6C2D27F443CDC9C198`
SSDEEP | `12288:0lD7oqg5h1YWjeIAMgMqKGLIlg7mR2YWZY:C3oXPYW8yGIl648ZY`
IMP | `3B89C98473CBC3685387F9493F1DC243`
PESHA1 | `799A0EECD4CBD8E9C060FB8C921EA640A51F75C2`
PE256 | `CE1BC9777013A1F789AFB2F6EA22175367273E063D346264422BF273F7363B6A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`NatAcquirePortReservation` | 16 (0x10) | Exported Function | 0x0000000180008c80 | 0x00008c80
`RegisterProtocol` | 14 (0xe) | Exported Function | 0x0000000180004570 | 0x00004570
`NhWriteStreamSocket` | 13 (0xd) | Exported Function | 0x00000001800079f0 | 0x000079f0
`NhWriteDatagramSocket` | 12 (0xc) | Exported Function | 0x0000000180007780 | 0x00007780
`NhReleaseBuffer` | 11 (0xb) | Exported Function | 0x0000000180001750 | 0x00001750
`NhReadStreamSocket` | 10 (0xa) | Exported Function | 0x0000000180007450 | 0x00007450
`NhReadDatagramSocket` | 9 (0x9) | Exported Function | 0x0000000180007100 | 0x00007100
`NhInitializeTraceManagement` | 8 (0x8) | Exported Function | 0x0000000180004b90 | 0x00004b90
`NhInitializeBufferManagement` | 7 (0x7) | Exported Function | 0x00000001800016a0 | 0x000016a0
`NhDeleteSocket` | 6 (0x6) | Exported Function | 0x0000000180006c90 | 0x00006c90
`NhCreateStreamSocket` | 5 (0x5) | Exported Function | 0x0000000180006920 | 0x00006920
`NhCreateDatagramSocket` | 4 (0x4) | Exported Function | 0x0000000180006230 | 0x00006230
`NhAcquireVariableLengthBuffer` | 3 (0x3) | Exported Function | 0x0000000180001430 | 0x00001430
`NhAcquireFixedLengthBuffer` | 2 (0x2) | Exported Function | 0x00000001800013d0 | 0x000013d0
`NhAcceptStreamSocket` | 1 (0x1) | Exported Function | 0x0000000180005a80 | 0x00005a80
`NatShutdownTranslator` | 31 (0x1f) | Exported Function | 0x000000018000a950 | 0x0000a950
`NatShutdownPortReservation` | 30 (0x1e) | Exported Function | 0x0000000180009300 | 0x00009300
`NatReleasePortReservation` | 29 (0x1d) | Exported Function | 0x0000000180009200 | 0x00009200
`NatQueryInformationRedirectHandle` | 28 (0x1c) | Exported Function | 0x000000018000a8e0 | 0x0000a8e0
`NatQueryInformationRedirect` | 27 (0x1b) | Exported Function | 0x000000018000a630 | 0x0000a630
`NatLookupAndQueryInformationSessionMapping` | 26 (0x1a) | Exported Function | 0x0000000180009d60 | 0x00009d60
`NatInitializeTranslator` | 25 (0x19) | Exported Function | 0x0000000180009b90 | 0x00009b90
`NatInitializePortReservation` | 24 (0x18) | Exported Function | 0x0000000180008db0 | 0x00008db0
`NatCreateRedirectEx` | 23 (0x17) | Exported Function | 0x0000000180009940 | 0x00009940
`NatCreateRedirect` | 22 (0x16) | Exported Function | 0x00000001800098a0 | 0x000098a0
`NatCreateDynamicRedirectEx` | 21 (0x15) | Exported Function | 0x0000000180009820 | 0x00009820
`NatCreateDynamicRedirect` | 20 (0x14) | Exported Function | 0x00000001800097b0 | 0x000097b0
`NatCreateDynamicFullRedirect` | 19 (0x13) | Exported Function | 0x0000000180009560 | 0x00009560
`NatCancelRedirect` | 18 (0x12) | Exported Function | 0x0000000180009410 | 0x00009410
`NatCancelDynamicRedirect` | 17 (0x11) | Exported Function | 0x0000000180009380 | 0x00009380
`ServiceMain` | 32 (0x20) | Exported Function | 0x000000018003e730 | 0x0003e730
`SvchostPushServiceGlobals` | 15 (0xf) | Exported Function | 0x000000018003e3e0 | 0x0003e3e0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IPNATHLP.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/efd82274d4555457a44e8a9c7fc2a767075196218fd62790d9deeed1732b2a86/detection/





MIT License. Copyright (c) 2020 Strontic.


