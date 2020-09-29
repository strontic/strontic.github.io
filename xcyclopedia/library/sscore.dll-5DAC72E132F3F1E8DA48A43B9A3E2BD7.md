---
title: sscore.dll | Server Service Core DLL
excerpt: What is sscore.dll?
---

# sscore.dll 

* File Path: `C:\Windows\system32\sscore.dll`
* Description: Server Service Core DLL

## Hashes

Type | Hash
-- | --
MD5 | `5DAC72E132F3F1E8DA48A43B9A3E2BD7`
SHA1 | `DB4AB130632F336E18F319A1BAEDFF478E929A8E`
SHA256 | `045D2C49AFC52DFAA7E15D56F897D19CD5A666068F51941203B0D1EC4F01DBAC`
SHA384 | `F595B2B3DB9553EDE9F373634444ABA93B7F9F19952B8F23D814752E6C91BF499DCD32928326E904956615813A97EDEF`
SHA512 | `4A1E9B4F17FA4E3B398D8B3365CEC7849F095A9337E8CD9E35391E4B96BF696B13029955BF61BCEE9F94352DDBB9885C054877A903F894152A92902CE9AF9BAD`
SSDEEP | `768:xgIntMlas+qfbDK2G0Vx3WP9VbRDzGyf+i+HHLS2xneFpNOZNiTqEh:xgtarqfvKSVAllGyS224pNOHiT3`
IMP | `6D3A0587D1EC18708BA748462F2309F8`
PESHA1 | `ED05C1E968C0012DF1602DEF7188BB91ACE1A969`
PE256 | `460473A47D7E4C04FAAF5CB7DAF97A98006313EF2705A214D34F777E6ED5930F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`SsCoreAliasAdd` | 1 (0x1) | Exported Function | 0x0000000180003000 | 0x00003000
`SsCoreSessionDel` | 27 (0x1b) | Exported Function | 0x0000000180003dd0 | 0x00003dd0
`SsCoreSessionDelForInstance` | 28 (0x1c) | Exported Function | 0x0000000180003df0 | 0x00003df0
`SsCoreSessionEnlist` | 29 (0x1d) | Exported Function | 0x0000000180003e80 | 0x00003e80
`SsCoreSessionEnum` | 30 (0x1e) | Exported Function | 0x0000000180003f30 | 0x00003f30
`SsCoreSessionEnumForInstance` | 31 (0x1f) | Exported Function | 0x0000000180003f80 | 0x00003f80
`SsCoreSetMaxClusterDialect` | 32 (0x20) | Exported Function | 0x0000000180004150 | 0x00004150
`SsCoreShareAdd` | 33 (0x21) | Exported Function | 0x00000001800041c0 | 0x000041c0
`SsCoreShareAddEx` | 34 (0x22) | Exported Function | 0x0000000180001010 | 0x00001010
`SsCoreShareAddForInstance` | 35 (0x23) | Exported Function | 0x0000000180004200 | 0x00004200
`SsCoreServerTransportSetInfo` | 26 (0x1a) | Exported Function | 0x0000000180003d00 | 0x00003d00
`SsCoreShareCleanup` | 36 (0x24) | Exported Function | 0x00000001800043f0 | 0x000043f0
`SsCoreShareDelForInstance` | 38 (0x26) | Exported Function | 0x0000000180004450 | 0x00004450
`SsCoreShareGetInfo` | 39 (0x27) | Exported Function | 0x0000000180004520 | 0x00004520
`SsCoreShareGetInfoForInstance` | 40 (0x28) | Exported Function | 0x0000000180004550 | 0x00004550
`SsCoreShareSetInfo` | 41 (0x29) | Exported Function | 0x00000001800046f0 | 0x000046f0
`SsCoreShareSetInfoForInstance` | 42 (0x2a) | Exported Function | 0x0000000180004740 | 0x00004740
`SsCoreShareShutdownForScope` | 43 (0x2b) | Exported Function | 0x0000000180004910 | 0x00004910
`SsCoreStartCsvVolumeDrain` | 44 (0x2c) | Exported Function | 0x00000001800049f0 | 0x000049f0
`SsCoreStartInstance` | 45 (0x2d) | Exported Function | 0x0000000180004a70 | 0x00004a70
`SsCoreStopInstance` | 46 (0x2e) | Exported Function | 0x0000000180004b00 | 0x00004b00
`SsCoreShareDel` | 37 (0x25) | Exported Function | 0x0000000180004430 | 0x00004430
`SsCoreRegisterNetnameForMultichannel` | 25 (0x19) | Exported Function | 0x0000000180003ce0 | 0x00003ce0
`SsCoreRefreshSrvCredentialHandle` | 24 (0x18) | Exported Function | 0x0000000180003c80 | 0x00003c80
`SsCoreOpenInstance` | 23 (0x17) | Exported Function | 0x0000000180001440 | 0x00001440
`SsCoreAliasAddEx` | 2 (0x2) | Exported Function | 0x0000000180003010 | 0x00003010
`SsCoreAliasDel` | 3 (0x3) | Exported Function | 0x0000000180003130 | 0x00003130
`SsCoreAliasDelEx` | 4 (0x4) | Exported Function | 0x0000000180003140 | 0x00003140
`SsCoreCertificatesUpdate` | 5 (0x5) | Exported Function | 0x00000001800033b0 | 0x000033b0
`SsCoreCloseInstance` | 6 (0x6) | Exported Function | 0x0000000180001570 | 0x00001570
`SsCoreCompleteCsvVolumeDrain` | 7 (0x7) | Exported Function | 0x0000000180003410 | 0x00003410
`SsCoreDeregisterNetnameForMultichannel` | 8 (0x8) | Exported Function | 0x0000000180003490 | 0x00003490
`SsCoreFileDel` | 9 (0x9) | Exported Function | 0x00000001800034c0 | 0x000034c0
`SsCoreFileDelForInstance` | 10 (0xa) | Exported Function | 0x00000001800034e0 | 0x000034e0
`SsCoreFileEnum` | 11 (0xb) | Exported Function | 0x0000000180003570 | 0x00003570
`SsCoreFileEnumForInstance` | 12 (0xc) | Exported Function | 0x00000001800035d0 | 0x000035d0
`SsCoreFileNotifyClose` | 13 (0xd) | Exported Function | 0x00000001800037d0 | 0x000037d0
`SsCoreFileNotifyCloseForInstance` | 14 (0xe) | Exported Function | 0x00000001800037f0 | 0x000037f0
`SsCoreFreeBuffer` | 15 (0xf) | Exported Function | 0x0000000180003880 | 0x00003880
`SsCoreInitialize` | 16 (0x10) | Exported Function | 0x00000001800038a0 | 0x000038a0
`SsCoreInitializeEx` | 17 (0x11) | Exported Function | 0x00000001800038b0 | 0x000038b0
`SsCoreInvalidationRequest` | 18 (0x12) | Exported Function | 0x00000001800039d0 | 0x000039d0
`SsCoreLockVolumes` | 19 (0x13) | Exported Function | 0x0000000180003ad0 | 0x00003ad0
`SsCoreMarkAsClusterSvc` | 20 (0x14) | Exported Function | 0x0000000180003b40 | 0x00003b40
`SsCoreNodeResetInfo` | 21 (0x15) | Exported Function | 0x0000000180003bb0 | 0x00003bb0
`SsCoreNodeSetInfo` | 22 (0x16) | Exported Function | 0x0000000180003be0 | 0x00003be0
`SsCoreUninitialize` | 47 (0x2f) | Exported Function | 0x0000000180004b90 | 0x00004b90
`SsCoreUnlockVolumes` | 48 (0x30) | Exported Function | 0x0000000180004c20 | 0x00004c20


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SSCORE.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/045d2c49afc52dfaa7e15d56f897d19cd5a666068f51941203b0d1ec4f01dbac/detection/





MIT License. Copyright (c) 2020 Strontic.


