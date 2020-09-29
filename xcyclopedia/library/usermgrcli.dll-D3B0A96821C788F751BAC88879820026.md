---
title: usermgrcli.dll | UserMgr API DLL
excerpt: What is usermgrcli.dll?
---

# usermgrcli.dll 

* File Path: `C:\Windows\system32\usermgrcli.dll`
* Description: UserMgr API DLL

## Hashes

Type | Hash
-- | --
MD5 | `D3B0A96821C788F751BAC88879820026`
SHA1 | `FE941B40240053AA1A735FAC16DD8A606EEF366A`
SHA256 | `BEE59FE5C727E8AEE1A36FDB6525B16C0DAD13202B61E76D60A59546864D117E`
SHA384 | `154E505E70A9EA03C95EB751824F5CF966F9E8F9103EFD4DA0D1960C6999A9E7ABA010C5BD7FD0B1512AEF3693BEA785`
SHA512 | `980CED5C9C2F162485A0FDF589C5E994444B1432E521874D20F34D261EF56FD23DEFE77C49D1E31B1BB90FC24BCD153F7A3DF2CA0F6CA52762EB0B27CF29639C`
SSDEEP | `1536:CcVpOud7iZ3n+cmwZ+svzwpHzQ5VvWBPc:CcVpliZPmwZ+awpUaBU`
IMP | `0A51776914DF4877E7C224045A441731`
PESHA1 | `994F8D472754BC5803B957B5284EEBB7A0BF2E2B`
PE256 | `ED726B2B41A676778FD938BF9F77CBCF2BD29B0CCC3F1AD66919C547E890C3BE`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CamCleanupDisardedCandidateAccounts` | 1 (0x1) | Exported Function | 0x0000000180003860 | 0x00003860
`UMgrGetSessionActiveShellUserToken` | 27 (0x1b) | Exported Function | 0x0000000180009650 | 0x00009650
`UMgrInformFlags` | 28 (0x1c) | Exported Function | 0x0000000180003930 | 0x00003930
`UMgrInformUserLogoff` | 29 (0x1d) | Exported Function | 0x0000000180003850 | 0x00003850
`UMgrInformUserLogon` | 30 (0x1e) | Exported Function | 0x00000001800039d0 | 0x000039d0
`UMgrIsAllowedToActivateAsUser` | 31 (0x1f) | Exported Function | 0x0000000180001aa0 | 0x00001aa0
`UMgrLaunchShell` | 32 (0x20) | Exported Function | 0x00000001800039b0 | 0x000039b0
`UMgrLaunchShellInfrastructureHost` | 33 (0x21) | Exported Function | 0x00000001800039a0 | 0x000039a0
`UMgrLogonUser` | 34 (0x22) | Exported Function | 0x00000001800012a0 | 0x000012a0
`UMgrOpenProcessHandleForAccess` | 35 (0x23) | Exported Function | 0x00000001800011a0 | 0x000011a0
`UMgrGetImpersonationTokenForContext` | 26 (0x1a) | Exported Function | 0x0000000180009620 | 0x00009620
`UMgrOpenProcessTokenForQuery` | 36 (0x24) | Exported Function | 0x0000000180001100 | 0x00001100
`UMgrQueryDefaultAccountToken` | 37 (0x25) | Exported Function | 0x0000000180003c40 | 0x00003c40
`UMgrQuerySessionUserToken` | 38 (0x26) | Exported Function | 0x0000000180009680 | 0x00009680
`UMgrQuerySessionVirtualAccountToken` | 39 (0x27) | Exported Function | 0x00000001800096b0 | 0x000096b0
`UMgrQueryUserContext` | 40 (0x28) | Exported Function | 0x00000001800023f0 | 0x000023f0
`UMgrQueryUserContextFromName` | 41 (0x29) | Exported Function | 0x00000001800096e0 | 0x000096e0
`UMgrQueryUserContextFromSid` | 42 (0x2a) | Exported Function | 0x0000000180009710 | 0x00009710
`UMgrQueryUserToken` | 43 (0x2b) | Exported Function | 0x0000000180001f50 | 0x00001f50
`UMgrQueryUserTokenFromName` | 44 (0x2c) | Exported Function | 0x0000000180009740 | 0x00009740
`UMgrQueryUserTokenFromSid` | 45 (0x2d) | Exported Function | 0x0000000180009770 | 0x00009770
`UMgrpGetRegistryLocation` | 48 (0x30) | Exported Function | 0x00000001800097e0 | 0x000097e0
`UMgrGetDefaultSignInAccount` | 25 (0x19) | Exported Function | 0x0000000180009610 | 0x00009610
`UMgrGetConstrainedUserToken` | 24 (0x18) | Exported Function | 0x00000001800016a0 | 0x000016a0
`UMgrGetCachedCredentials` | 23 (0x17) | Exported Function | 0x00000001800095e0 | 0x000095e0
`CamConnectCandidateUser` | 2 (0x2) | Exported Function | 0x0000000180009210 | 0x00009210
`CamFreeAuthBuffer` | 3 (0x3) | Exported Function | 0x0000000180009250 | 0x00009250
`CamFreeBuffer` | 4 (0x4) | Exported Function | 0x00000001800092a0 | 0x000092a0
`CamGetCandidateAccountCredz` | 5 (0x5) | Exported Function | 0x00000001800092d0 | 0x000092d0
`CamGetCandidateUserSessionIds` | 6 (0x6) | Exported Function | 0x0000000180009300 | 0x00009300
`CamGetNonCandidateUserSessionIds` | 7 (0x7) | Exported Function | 0x0000000180009330 | 0x00009330
`CamIsCandidateUser` | 8 (0x8) | Exported Function | 0x0000000180003b80 | 0x00003b80
`CamIsEphemeralCandidateUser` | 9 (0x9) | Exported Function | 0x0000000180009360 | 0x00009360
`CamRefreshCandidateUser` | 10 (0xa) | Exported Function | 0x0000000180009390 | 0x00009390
`IsInteractiveUserSession` | 11 (0xb) | Exported Function | 0x00000001800097f0 | 0x000097f0
`QueryActiveSession` | 12 (0xc) | Exported Function | 0x0000000180009860 | 0x00009860
`QueryUserToken` | 13 (0xd) | Exported Function | 0x00000001800098e0 | 0x000098e0
`RegisterUsertokenForNoWinlogon` | 14 (0xe) | Exported Function | 0x00000001800099d0 | 0x000099d0
`UMgrChangeSessionActiveShellUser` | 15 (0xf) | Exported Function | 0x0000000180009480 | 0x00009480
`UMgrChangeSessionUserToken` | 16 (0x10) | Exported Function | 0x00000001800094b0 | 0x000094b0
`UMgrClearDefaultSignInAccount` | 17 (0x11) | Exported Function | 0x00000001800094c0 | 0x000094c0
`UMgrConnectLocalUser` | 18 (0x12) | Exported Function | 0x00000001800094d0 | 0x000094d0
`UMgrDisconnectLocalUser` | 19 (0x13) | Exported Function | 0x0000000180009520 | 0x00009520
`UMgrEnumerateSessionUsers` | 20 (0x14) | Exported Function | 0x00000001800017f0 | 0x000017f0
`UMgrFreeSessionUsers` | 21 (0x15) | Exported Function | 0x0000000180001250 | 0x00001250
`UMgrFreeUserCredentials` | 22 (0x16) | Exported Function | 0x0000000180009580 | 0x00009580
`UMgrSetCachedCredentials` | 46 (0x2e) | Exported Function | 0x00000001800097a0 | 0x000097a0
`UMgrSetShellInformation` | 47 (0x2f) | Exported Function | 0x00000001800039c0 | 0x000039c0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: usermgrcli.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/bee59fe5c727e8aee1a36fdb6525b16c0dad13202b61e76d60a59546864d117e/detection/





MIT License. Copyright (c) 2020 Strontic.


