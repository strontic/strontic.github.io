---
title: usermgrcli.dll | UserMgr API DLL
excerpt: What is usermgrcli.dll?
---

# usermgrcli.dll 

* File Path: `C:\Windows\SysWOW64\usermgrcli.dll`
* Description: UserMgr API DLL

## Hashes

Type | Hash
-- | --
MD5 | `ACF20A7CF8BDFA34960C10A262448780`
SHA1 | `0E11930FA9D12807214920142175A611A415D1DD`
SHA256 | `12F409FB3D390656821F13ECDA08392DAC99954C81F313DC6C725E25A9CF8152`
SHA384 | `A3DA9685563469BCA958C2DA7C825191A6346D484D08C4029CBDFC55EEEC192251A46C1D64A4A48CF092C576E8AB37CD`
SHA512 | `CA6919ACDBA7E5992DE09FC7EE06C291989428506FC59A098E20C496BE5D891DCF69E002D42AFF4AB5C556664F7AD19F8A32B3E3096B126219472EAF70EB3919`
SSDEEP | `1536:Xw4F++OVb/Y9Lxr1s/9g11mTPksqpoCII1++mfP/:Xw4F+xY9L/s/9g11mTPkBBIIGfH`
IMP | `FD490A0262FEBD37990BDBD445C01509`
PESHA1 | `38F1B30DEEA2F75C15A692CE9997C1EDDE9C8A71`
PE256 | `8AB2E55CA5EBCA5E9ED4929F263AF5E66D9F18353F41272C3FC8E419C31A12C1`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CamCleanupDisardedCandidateAccounts` | 1 (0x1) | Exported Function | 0x10004620 | 0x00004620
`UMgrGetSessionActiveShellUserToken` | 27 (0x1b) | Exported Function | 0x10009b70 | 0x00009b70
`UMgrInformFlags` | 28 (0x1c) | Exported Function | 0x100046f0 | 0x000046f0
`UMgrInformUserLogoff` | 29 (0x1d) | Exported Function | 0x10004610 | 0x00004610
`UMgrInformUserLogon` | 30 (0x1e) | Exported Function | 0x100047e0 | 0x000047e0
`UMgrIsAllowedToActivateAsUser` | 31 (0x1f) | Exported Function | 0x10003e30 | 0x00003e30
`UMgrLaunchShell` | 32 (0x20) | Exported Function | 0x100047c0 | 0x000047c0
`UMgrLaunchShellInfrastructureHost` | 33 (0x21) | Exported Function | 0x100047b0 | 0x000047b0
`UMgrLogonUser` | 34 (0x22) | Exported Function | 0x10003740 | 0x00003740
`UMgrOpenProcessHandleForAccess` | 35 (0x23) | Exported Function | 0x10004770 | 0x00004770
`UMgrGetImpersonationTokenForContext` | 26 (0x1a) | Exported Function | 0x10003b20 | 0x00003b20
`UMgrOpenProcessTokenForQuery` | 36 (0x24) | Exported Function | 0x10003660 | 0x00003660
`UMgrQueryDefaultAccountToken` | 37 (0x25) | Exported Function | 0x10004a00 | 0x00004a00
`UMgrQuerySessionUserToken` | 38 (0x26) | Exported Function | 0x10009b80 | 0x00009b80
`UMgrQuerySessionVirtualAccountToken` | 39 (0x27) | Exported Function | 0x10009b90 | 0x00009b90
`UMgrQueryUserContext` | 40 (0x28) | Exported Function | 0x100042d0 | 0x000042d0
`UMgrQueryUserContextFromName` | 41 (0x29) | Exported Function | 0x10009ba0 | 0x00009ba0
`UMgrQueryUserContextFromSid` | 42 (0x2a) | Exported Function | 0x10009bb0 | 0x00009bb0
`UMgrQueryUserToken` | 43 (0x2b) | Exported Function | 0x10004080 | 0x00004080
`UMgrQueryUserTokenFromName` | 44 (0x2c) | Exported Function | 0x10009bc0 | 0x00009bc0
`UMgrQueryUserTokenFromSid` | 45 (0x2d) | Exported Function | 0x10009bd0 | 0x00009bd0
`UMgrpGetRegistryLocation` | 48 (0x30) | Exported Function | 0x10009c20 | 0x00009c20
`UMgrGetDefaultSignInAccount` | 25 (0x19) | Exported Function | 0x10009b50 | 0x00009b50
`UMgrGetConstrainedUserToken` | 24 (0x18) | Exported Function | 0x10003a40 | 0x00003a40
`UMgrGetCachedCredentials` | 23 (0x17) | Exported Function | 0x10009b40 | 0x00009b40
`CamConnectCandidateUser` | 2 (0x2) | Exported Function | 0x100097f0 | 0x000097f0
`CamFreeAuthBuffer` | 3 (0x3) | Exported Function | 0x10009830 | 0x00009830
`CamFreeBuffer` | 4 (0x4) | Exported Function | 0x10009870 | 0x00009870
`CamGetCandidateAccountCredz` | 5 (0x5) | Exported Function | 0x100098a0 | 0x000098a0
`CamGetCandidateUserSessionIds` | 6 (0x6) | Exported Function | 0x100098b0 | 0x000098b0
`CamGetNonCandidateUserSessionIds` | 7 (0x7) | Exported Function | 0x100098c0 | 0x000098c0
`CamIsCandidateUser` | 8 (0x8) | Exported Function | 0x10004980 | 0x00004980
`CamIsEphemeralCandidateUser` | 9 (0x9) | Exported Function | 0x100098d0 | 0x000098d0
`CamRefreshCandidateUser` | 10 (0xa) | Exported Function | 0x100098e0 | 0x000098e0
`IsInteractiveUserSession` | 11 (0xb) | Exported Function | 0x10009c30 | 0x00009c30
`QueryActiveSession` | 12 (0xc) | Exported Function | 0x10009c80 | 0x00009c80
`QueryUserToken` | 13 (0xd) | Exported Function | 0x10009ce0 | 0x00009ce0
`RegisterUsertokenForNoWinlogon` | 14 (0xe) | Exported Function | 0x10009da0 | 0x00009da0
`UMgrChangeSessionActiveShellUser` | 15 (0xf) | Exported Function | 0x100099a0 | 0x000099a0
`UMgrChangeSessionUserToken` | 16 (0x10) | Exported Function | 0x100099e0 | 0x000099e0
`UMgrClearDefaultSignInAccount` | 17 (0x11) | Exported Function | 0x100099f0 | 0x000099f0
`UMgrConnectLocalUser` | 18 (0x12) | Exported Function | 0x10009a10 | 0x00009a10
`UMgrDisconnectLocalUser` | 19 (0x13) | Exported Function | 0x10009a80 | 0x00009a80
`UMgrEnumerateSessionUsers` | 20 (0x14) | Exported Function | 0x10003bf0 | 0x00003bf0
`UMgrFreeSessionUsers` | 21 (0x15) | Exported Function | 0x10003700 | 0x00003700
`UMgrFreeUserCredentials` | 22 (0x16) | Exported Function | 0x10009af0 | 0x00009af0
`UMgrSetCachedCredentials` | 46 (0x2e) | Exported Function | 0x10009be0 | 0x00009be0
`UMgrSetShellInformation` | 47 (0x2f) | Exported Function | 0x100047d0 | 0x000047d0


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/12f409fb3d390656821f13ecda08392dac99954c81f313dc6c725e25a9cf8152/detection/





MIT License. Copyright (c) 2020 Strontic.


