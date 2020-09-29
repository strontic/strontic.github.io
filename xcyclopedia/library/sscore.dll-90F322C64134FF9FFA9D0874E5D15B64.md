---
title: sscore.dll | Server Service Core DLL
excerpt: What is sscore.dll?
---

# sscore.dll 

* File Path: `C:\Windows\SysWOW64\sscore.dll`
* Description: Server Service Core DLL

## Hashes

Type | Hash
-- | --
MD5 | `90F322C64134FF9FFA9D0874E5D15B64`
SHA1 | `5CB62F58548E021F6C52167C7C56DBD7A96D61EC`
SHA256 | `D2C2F81EAEB4BE33AE1BB82E03BDE3805C78B50096F99542C6841735EBEB5DE4`
SHA384 | `F5310AC27DF9D58353CFE9709F92F78E7F44122215EA43C1A2592EBDEFD9AF56B1FF2E1B7E610081056837B6A4ACCC57`
SHA512 | `137457DAF704F00509E2D1652156638C2C7CE07EEB25C147F634632C66AAFE3311A5D345EEE579DB315573470C81ECB817A1E342D20384E7E5006730FFEFDA70`
SSDEEP | `768:wFP+kA9uXFkrxt8xJ0ltub+aTKV6mndPWNGFRh:wFguen8xJgaKNWNi`
IMP | `DB2829E3E5B600D4A96322559EA80890`
PESHA1 | `71F19B8F61DF3B591010FD574F0118032224E552`
PE256 | `B942E9322E714C772546216CF78E67A13EA3F1C7313491B07BC32B531250EB6E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`SsCoreAliasAdd` | 1 (0x1) | Exported Function | 0x10003c70 | 0x00003c70
`SsCoreSessionDel` | 27 (0x1b) | Exported Function | 0x10004650 | 0x00004650
`SsCoreSessionDelForInstance` | 28 (0x1c) | Exported Function | 0x10004670 | 0x00004670
`SsCoreSessionEnlist` | 29 (0x1d) | Exported Function | 0x100046e0 | 0x000046e0
`SsCoreSessionEnum` | 30 (0x1e) | Exported Function | 0x10004760 | 0x00004760
`SsCoreSessionEnumForInstance` | 31 (0x1f) | Exported Function | 0x10004790 | 0x00004790
`SsCoreSetMaxClusterDialect` | 32 (0x20) | Exported Function | 0x10004910 | 0x00004910
`SsCoreShareAdd` | 33 (0x21) | Exported Function | 0x10004980 | 0x00004980
`SsCoreShareAddEx` | 34 (0x22) | Exported Function | 0x10001dd0 | 0x00001dd0
`SsCoreShareAddForInstance` | 35 (0x23) | Exported Function | 0x10001e00 | 0x00001e00
`SsCoreServerTransportSetInfo` | 26 (0x1a) | Exported Function | 0x100045c0 | 0x000045c0
`SsCoreShareCleanup` | 36 (0x24) | Exported Function | 0x100024e0 | 0x000024e0
`SsCoreShareDelForInstance` | 38 (0x26) | Exported Function | 0x100049d0 | 0x000049d0
`SsCoreShareGetInfo` | 39 (0x27) | Exported Function | 0x10004a50 | 0x00004a50
`SsCoreShareGetInfoForInstance` | 40 (0x28) | Exported Function | 0x10004a80 | 0x00004a80
`SsCoreShareSetInfo` | 41 (0x29) | Exported Function | 0x10004ba0 | 0x00004ba0
`SsCoreShareSetInfoForInstance` | 42 (0x2a) | Exported Function | 0x10004bd0 | 0x00004bd0
`SsCoreShareShutdownForScope` | 43 (0x2b) | Exported Function | 0x10004d00 | 0x00004d00
`SsCoreStartCsvVolumeDrain` | 44 (0x2c) | Exported Function | 0x10004d80 | 0x00004d80
`SsCoreStartInstance` | 45 (0x2d) | Exported Function | 0x10004df0 | 0x00004df0
`SsCoreStopInstance` | 46 (0x2e) | Exported Function | 0x10004e50 | 0x00004e50
`SsCoreShareDel` | 37 (0x25) | Exported Function | 0x100049b0 | 0x000049b0
`SsCoreRegisterNetnameForMultichannel` | 25 (0x19) | Exported Function | 0x100045a0 | 0x000045a0
`SsCoreRefreshSrvCredentialHandle` | 24 (0x18) | Exported Function | 0x10004550 | 0x00004550
`SsCoreOpenInstance` | 23 (0x17) | Exported Function | 0x10001ce0 | 0x00001ce0
`SsCoreAliasAddEx` | 2 (0x2) | Exported Function | 0x10003c90 | 0x00003c90
`SsCoreAliasDel` | 3 (0x3) | Exported Function | 0x10003d60 | 0x00003d60
`SsCoreAliasDelEx` | 4 (0x4) | Exported Function | 0x10003d80 | 0x00003d80
`SsCoreCertificatesUpdate` | 5 (0x5) | Exported Function | 0x10003f50 | 0x00003f50
`SsCoreCloseInstance` | 6 (0x6) | Exported Function | 0x10001dc0 | 0x00001dc0
`SsCoreCompleteCsvVolumeDrain` | 7 (0x7) | Exported Function | 0x10003fb0 | 0x00003fb0
`SsCoreDeregisterNetnameForMultichannel` | 8 (0x8) | Exported Function | 0x10004020 | 0x00004020
`SsCoreFileDel` | 9 (0x9) | Exported Function | 0x10004040 | 0x00004040
`SsCoreFileDelForInstance` | 10 (0xa) | Exported Function | 0x10004060 | 0x00004060
`SsCoreFileEnum` | 11 (0xb) | Exported Function | 0x100040c0 | 0x000040c0
`SsCoreFileEnumForInstance` | 12 (0xc) | Exported Function | 0x10004100 | 0x00004100
`SsCoreFileNotifyClose` | 13 (0xd) | Exported Function | 0x100042a0 | 0x000042a0
`SsCoreFileNotifyCloseForInstance` | 14 (0xe) | Exported Function | 0x100042c0 | 0x000042c0
`SsCoreFreeBuffer` | 15 (0xf) | Exported Function | 0x10004320 | 0x00004320
`SsCoreInitialize` | 16 (0x10) | Exported Function | 0x10004330 | 0x00004330
`SsCoreInitializeEx` | 17 (0x11) | Exported Function | 0x10002220 | 0x00002220
`SsCoreInvalidationRequest` | 18 (0x12) | Exported Function | 0x10004340 | 0x00004340
`SsCoreLockVolumes` | 19 (0x13) | Exported Function | 0x10004410 | 0x00004410
`SsCoreMarkAsClusterSvc` | 20 (0x14) | Exported Function | 0x10004480 | 0x00004480
`SsCoreNodeResetInfo` | 21 (0x15) | Exported Function | 0x100044d0 | 0x000044d0
`SsCoreNodeSetInfo` | 22 (0x16) | Exported Function | 0x100044f0 | 0x000044f0
`SsCoreUninitialize` | 47 (0x2f) | Exported Function | 0x10004eb0 | 0x00004eb0
`SsCoreUnlockVolumes` | 48 (0x30) | Exported Function | 0x10004f20 | 0x00004f20


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SSCORE.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d2c2f81eaeb4be33ae1bb82e03bde3805c78b50096f99542c6841735ebeb5de4/detection/





MIT License. Copyright (c) 2020 Strontic.


