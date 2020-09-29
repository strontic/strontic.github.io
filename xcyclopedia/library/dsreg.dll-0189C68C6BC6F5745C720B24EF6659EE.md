---
title: dsreg.dll | AD/AAD User Device Registration
excerpt: What is dsreg.dll?
---

# dsreg.dll 

* File Path: `C:\Windows\SysWOW64\dsreg.dll`
* Description: AD/AAD User Device Registration

## Hashes

Type | Hash
-- | --
MD5 | `0189C68C6BC6F5745C720B24EF6659EE`
SHA1 | `B2FD62C86AAD424B7B9270E9EB7ACEDE079E9CC0`
SHA256 | `3C8637E4CD64B4D97C50B38B085692ED6C912DF901588A036E12BA3D08947433`
SHA384 | `6D24B0BB57B9F1639C9C35200C7E0B8369D06032F66805644329548927AE7A96DAE9FAFF82FA8822DB5D8B943D95F7CA`
SHA512 | `CEFEDA695C77D2E6A57799DCDAAABD80BF8CEE7AF7D08E1B2A94F1DD9AAE9D3E31508983932AA177890D409B4E2572E2AFED9FAD178AA8D022474B8FA01C1F09`
SSDEEP | `24576:BcGJGzb3TJISq51++2Nt0v9b8kN62uaVfL89E:BcGJGzb3TSFs+A0zN62H9Lr`
IMP | `44E66016AB57BEACA89C6D0E140D4E61`
PESHA1 | `B0DE4E5826291FF2A83B6D2C59AB903D54D9D1C7`
PE256 | `6C980B36A47C035A3EA3C54A08A4F1C550896C28480D803DECA58052DBFEE16F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DsrBeginDelegatedWorkplaceJoin` | 1 (0x1) | Exported Function | 0x1004ff00 | 0x0004ff00
`DsrIsDeviceJoined` | 27 (0x1b) | Exported Function | 0x10086530 | 0x00086530
`DsrIsDeviceJoinedEx` | 28 (0x1c) | Exported Function | 0x10086580 | 0x00086580
`DsrIsWorkplaceJoined` | 29 (0x1d) | Exported Function | 0x10086680 | 0x00086680
`DsrSaveDeviceTokenProperties` | 30 (0x1e) | Exported Function | 0x100866d0 | 0x000866d0
`DsrSaveWorkplaceTokenProperties` | 31 (0x1f) | Exported Function | 0x10086740 | 0x00086740
`DsrWriteAutoJoinSvcAdminEvent` | 32 (0x20) | Exported Function | 0x100505c0 | 0x000505c0
`DsrWriteAutoJoinSvcDebugEvent` | 33 (0x21) | Exported Function | 0x10050600 | 0x00050600
`DsrWriteAutoJoinSvcTriggerEvent` | 34 (0x22) | Exported Function | 0x10050330 | 0x00050330
`FidoDeregisterKey` | 35 (0x23) | Exported Function | 0x10050ed0 | 0x00050ed0
`DsrGetResourceAccount` | 26 (0x1a) | Exported Function | 0x10086ad0 | 0x00086ad0
`FidoRegisterKey` | 36 (0x24) | Exported Function | 0x10050e80 | 0x00050e80
`NgcGetKeyId` | 38 (0x26) | Exported Function | 0x10050de0 | 0x00050de0
`NgcGetLogonCertPolicy` | 39 (0x27) | Exported Function | 0x10051210 | 0x00051210
`NgcGetStatistics` | 40 (0x28) | Exported Function | 0x10050e00 | 0x00050e00
`NgcIncrementPinRetryAttempts` | 41 (0x29) | Exported Function | 0x10051330 | 0x00051330
`NgcNeedProvision` | 42 (0x2a) | Exported Function | 0x10050fc0 | 0x00050fc0
`NgcNeedProvisionForAccount` | 43 (0x2b) | Exported Function | 0x100510e0 | 0x000510e0
`NgcReadRegistryValue` | 44 (0x2c) | Exported Function | 0x10050e60 | 0x00050e60
`NgcRegisterKey` | 45 (0x2d) | Exported Function | 0x10050d40 | 0x00050d40
`NgcResetPinRetryAttempts` | 46 (0x2e) | Exported Function | 0x100513a0 | 0x000513a0
`NgcDeregisterKey` | 37 (0x25) | Exported Function | 0x10050db0 | 0x00050db0
`DsrGetPrtAuthorityInfo` | 25 (0x19) | Exported Function | 0x10051160 | 0x00051160
`DsrGetJoinInfoEx` | 24 (0x18) | Exported Function | 0x10085fb0 | 0x00085fb0
`DsrGetJoinInfo` | 23 (0x17) | Exported Function | 0x10085e20 | 0x00085e20
`DsrBeginDeviceAndResourceAccountJoin` | 2 (0x2) | Exported Function | 0x1004fbb0 | 0x0004fbb0
`DsrBeginDeviceJoin` | 3 (0x3) | Exported Function | 0x1004f8d0 | 0x0004f8d0
`DsrBeginDeviceUnjoin` | 4 (0x4) | Exported Function | 0x10050200 | 0x00050200
`DsrBeginDeviceUpdate` | 5 (0x5) | Exported Function | 0x100502f0 | 0x000502f0
`DsrBeginDiscover` | 6 (0x6) | Exported Function | 0x1006d060 | 0x0006d060
`DsrBeginPreprovisionedDeviceJoin` | 7 (0x7) | Exported Function | 0x1004fa10 | 0x0004fa10
`DsrBeginRecovery` | 8 (0x8) | Exported Function | 0x10050640 | 0x00050640
`DsrBeginWorkplaceJoin` | 9 (0x9) | Exported Function | 0x1004fdc0 | 0x0004fdc0
`DsrBeginWorkplaceUnjoin` | 10 (0xa) | Exported Function | 0x10050250 | 0x00050250
`DsrBeginWorkplaceUpdate` | 11 (0xb) | Exported Function | 0x10050310 | 0x00050310
`DsrCanCurrentUserProvisionNgcKey` | 13 (0xd) | Exported Function | 0x10050f00 | 0x00050f00
`DsrCanCurrentUserResetNgcKey` | 14 (0xe) | Exported Function | 0x10050f30 | 0x00050f30
`DsrCLI` | 12 (0xc) | Exported Function | 0x1009d390 | 0x0009d390
`DsrEndRecovery` | 15 (0xf) | Exported Function | 0x100509a0 | 0x000509a0
`DsrFreeCxhScenarioInfo` | 16 (0x10) | Exported Function | 0x10086a80 | 0x00086a80
`DsrFreeDiscoveryMetadata` | 17 (0x11) | Exported Function | 0x1006d460 | 0x0006d460
`DsrFreeJoinInfo` | 18 (0x12) | Exported Function | 0x10085aa0 | 0x00085aa0
`DsrFreeJoinInfoEx` | 19 (0x13) | Exported Function | 0x10085b70 | 0x00085b70
`DsrGetCurrentUserNgcProvisionStatus` | 20 (0x14) | Exported Function | 0x10050f50 | 0x00050f50
`DsrGetCxhScenarioInfo` | 21 (0x15) | Exported Function | 0x100867b0 | 0x000867b0
`DsrGetDomainRegistrationData` | 22 (0x16) | Exported Function | 0x10051100 | 0x00051100
`NgcUpdateCertEnrollStatistics` | 47 (0x2f) | Exported Function | 0x10050e40 | 0x00050e40
`NgcUpdateStatistics` | 48 (0x30) | Exported Function | 0x10050e20 | 0x00050e20


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3c8637e4cd64b4d97c50b38b085692ed6c912df901588a036e12ba3d08947433/detection/





MIT License. Copyright (c) 2020 Strontic.


