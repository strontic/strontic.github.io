---
title: dsreg.dll | AD/AAD User Device Registration
excerpt: What is dsreg.dll?
---

# dsreg.dll 

* File Path: `C:\Windows\system32\dsreg.dll`
* Description: AD/AAD User Device Registration

## Hashes

Type | Hash
-- | --
MD5 | `CFBD80826C73B03ECA55D3E6C25B2661`
SHA1 | `748255C166CE5B9A2D1F0906A835CAA193973F04`
SHA256 | `7141872B513B226A58A708476F3954C8AF3C6A9F09E03F54CE47C14100F15CD4`
SHA384 | `72F13239CE24AFF1591BD2F765054E01EEA90C58CFEBBEA0AAA7E095109A925E9BB2AE4E1AD594D02E30AE84D9E2AB07`
SHA512 | `4C2286577C0047CDC4AA3835794AEA3E38D69EB4EB51382D5E595F426B50E9BE184103676CCF30451FD1026A5D94055DCFA8E1E3F6D0F570A21C2376D4E27D76`
SSDEEP | `24576:wa/LgEFgjgj4yeoqxBZjGoK5OjFrGVKwluOciXvOC/:wa/nKjWXeoqx36oKMJrGVKwlu7iT/`
IMP | `E3A279785EBB753BD4F661380F7DEC69`
PESHA1 | `368A0B9395B87F5EEE2BE82A6CB44A9DB3249FDE`
PE256 | `8397BB81856527441AA4674D600E706067E688C38549B6ECFA3405C5810D3018`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DsrBeginDelegatedWorkplaceJoin` | 1 (0x1) | Exported Function | 0x0000000180003880 | 0x00003880
`DsrIsDeviceJoined` | 27 (0x1b) | Exported Function | 0x000000018004fb70 | 0x0004fb70
`DsrIsDeviceJoinedEx` | 28 (0x1c) | Exported Function | 0x000000018004fbc0 | 0x0004fbc0
`DsrIsWorkplaceJoined` | 29 (0x1d) | Exported Function | 0x000000018004fd20 | 0x0004fd20
`DsrSaveDeviceTokenProperties` | 30 (0x1e) | Exported Function | 0x000000018004fd70 | 0x0004fd70
`DsrSaveWorkplaceTokenProperties` | 31 (0x1f) | Exported Function | 0x000000018004fdf0 | 0x0004fdf0
`DsrWriteAutoJoinSvcAdminEvent` | 32 (0x20) | Exported Function | 0x0000000180004400 | 0x00004400
`DsrWriteAutoJoinSvcDebugEvent` | 33 (0x21) | Exported Function | 0x0000000180004460 | 0x00004460
`DsrWriteAutoJoinSvcTriggerEvent` | 34 (0x22) | Exported Function | 0x0000000180004080 | 0x00004080
`FidoDeregisterKey` | 35 (0x23) | Exported Function | 0x00000001800054a0 | 0x000054a0
`DsrGetResourceAccount` | 26 (0x1a) | Exported Function | 0x0000000180050200 | 0x00050200
`FidoRegisterKey` | 36 (0x24) | Exported Function | 0x00000001800053f0 | 0x000053f0
`NgcGetKeyId` | 38 (0x26) | Exported Function | 0x0000000180004f90 | 0x00004f90
`NgcGetLogonCertPolicy` | 39 (0x27) | Exported Function | 0x0000000180005830 | 0x00005830
`NgcGetStatistics` | 40 (0x28) | Exported Function | 0x0000000180005100 | 0x00005100
`NgcIncrementPinRetryAttempts` | 41 (0x29) | Exported Function | 0x00000001800059f0 | 0x000059f0
`NgcNeedProvision` | 42 (0x2a) | Exported Function | 0x0000000180005550 | 0x00005550
`NgcNeedProvisionForAccount` | 43 (0x2b) | Exported Function | 0x00000001800056c0 | 0x000056c0
`NgcReadRegistryValue` | 44 (0x2c) | Exported Function | 0x00000001800052a0 | 0x000052a0
`NgcRegisterKey` | 45 (0x2d) | Exported Function | 0x0000000180004ea0 | 0x00004ea0
`NgcResetPinRetryAttempts` | 46 (0x2e) | Exported Function | 0x0000000180005a70 | 0x00005a70
`NgcDeregisterKey` | 37 (0x25) | Exported Function | 0x0000000180004f50 | 0x00004f50
`DsrGetPrtAuthorityInfo` | 25 (0x19) | Exported Function | 0x0000000180005750 | 0x00005750
`DsrGetJoinInfoEx` | 24 (0x18) | Exported Function | 0x000000018004f3d0 | 0x0004f3d0
`DsrGetJoinInfo` | 23 (0x17) | Exported Function | 0x000000018004f1d0 | 0x0004f1d0
`DsrBeginDeviceAndResourceAccountJoin` | 2 (0x2) | Exported Function | 0x00000001800032f0 | 0x000032f0
`DsrBeginDeviceJoin` | 3 (0x3) | Exported Function | 0x0000000180002de0 | 0x00002de0
`DsrBeginDeviceUnjoin` | 4 (0x4) | Exported Function | 0x0000000180003ee0 | 0x00003ee0
`DsrBeginDeviceUpdate` | 5 (0x5) | Exported Function | 0x0000000180004040 | 0x00004040
`DsrBeginDiscover` | 6 (0x6) | Exported Function | 0x000000018002bab0 | 0x0002bab0
`DsrBeginPreprovisionedDeviceJoin` | 7 (0x7) | Exported Function | 0x0000000180003040 | 0x00003040
`DsrBeginRecovery` | 8 (0x8) | Exported Function | 0x00000001800044c0 | 0x000044c0
`DsrBeginWorkplaceJoin` | 9 (0x9) | Exported Function | 0x0000000180003600 | 0x00003600
`DsrBeginWorkplaceUnjoin` | 10 (0xa) | Exported Function | 0x0000000180003f60 | 0x00003f60
`DsrBeginWorkplaceUpdate` | 11 (0xb) | Exported Function | 0x0000000180004060 | 0x00004060
`DsrCanCurrentUserProvisionNgcKey` | 13 (0xd) | Exported Function | 0x00000001800054b0 | 0x000054b0
`DsrCanCurrentUserResetNgcKey` | 14 (0xe) | Exported Function | 0x00000001800054c0 | 0x000054c0
`DsrCLI` | 12 (0xc) | Exported Function | 0x000000018006a2f0 | 0x0006a2f0
`DsrEndRecovery` | 15 (0xf) | Exported Function | 0x0000000180004a30 | 0x00004a30
`DsrFreeCxhScenarioInfo` | 16 (0x10) | Exported Function | 0x00000001800501a0 | 0x000501a0
`DsrFreeDiscoveryMetadata` | 17 (0x11) | Exported Function | 0x000000018002c0c0 | 0x0002c0c0
`DsrFreeJoinInfo` | 18 (0x12) | Exported Function | 0x000000018004ed80 | 0x0004ed80
`DsrFreeJoinInfoEx` | 19 (0x13) | Exported Function | 0x000000018004ee70 | 0x0004ee70
`DsrGetCurrentUserNgcProvisionStatus` | 20 (0x14) | Exported Function | 0x00000001800054d0 | 0x000054d0
`DsrGetCxhScenarioInfo` | 21 (0x15) | Exported Function | 0x000000018004fe70 | 0x0004fe70
`DsrGetDomainRegistrationData` | 22 (0x16) | Exported Function | 0x00000001800056d0 | 0x000056d0
`NgcUpdateCertEnrollStatistics` | 47 (0x2f) | Exported Function | 0x0000000180005120 | 0x00005120
`NgcUpdateStatistics` | 48 (0x30) | Exported Function | 0x0000000180005110 | 0x00005110


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsreg.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/7141872b513b226a58a708476f3954c8af3c6a9f09e03f54ce47c14100f15cd4/detection/





MIT License. Copyright (c) 2020 Strontic.


