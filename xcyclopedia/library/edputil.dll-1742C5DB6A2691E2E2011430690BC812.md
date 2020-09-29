---
title: edputil.dll | EDP util
excerpt: What is edputil.dll?
---

# edputil.dll 

* File Path: `C:\Windows\SysWOW64\edputil.dll`
* Description: EDP util

## Hashes

Type | Hash
-- | --
MD5 | `1742C5DB6A2691E2E2011430690BC812`
SHA1 | `9EC36F391B332F19CBE0D93983728853859CE705`
SHA256 | `403D0A01298EE1875E7B4CD1A6FCD67953B6C19BC2FC92B547B8870E3EDC5B19`
SHA384 | `6B5FF4BF9F14C331DA85F3CFEEE521941EDD0F10EB3BDD02B063BD7560E2B0B9E43F595F211DBD545F6EA37D97E1A4B3`
SHA512 | `3291B0C77C89227D5235D21E57103500B4A51AE3445780A2005BBD13765BC1A1EDD8F39993E970800A4B540390BBB5BEB6BBD2883A1993F07467068374FC79AF`
SSDEEP | `1536:c+oa5BW0v6JZMRyECz7BNCCvntCVNFY2X8Dafwfh0BS44Fzc2hw2y1CIJjXkkm5s:c+jBW0vUNz7BXvcVNFY2caIfyc44Fzc1`
IMP | `171D1EA50A24EB69B0039D5D15FB9236`
PESHA1 | `975A12320DE86FB243914462B500D55B37775777`
PE256 | `D54D9C978849D522189A0C0E0E64455DC96D668478012C124F47F5FCBAB68F98`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EdpAddAppClipboardConsentInCache` | 1 (0x1) | Exported Function | 0x10008a70 | 0x00008a70
`EdpGetPrimaryIdentityIfManaged` | 30 (0x1e) | Exported Function | 0x10009510 | 0x00009510
`EdpGetSourceAppIdForClipboard` | 31 (0x1f) | Exported Function | 0x10009540 | 0x00009540
`EdpGetSourceIsEnlightenedForClipboard` | 32 (0x20) | Exported Function | 0x10009560 | 0x00009560
`EdpGetWindowFromThreadId` | 33 (0x21) | Exported Function | 0x10009580 | 0x00009580
`EdpIsAppClipboardConsentCached` | 34 (0x22) | Exported Function | 0x100096f0 | 0x000096f0
`EdpIsContextExemptOrEnlightenedAllowed` | 35 (0x23) | Exported Function | 0x1000de20 | 0x0000de20
`EdpIsFileAccessAllowed` | 36 (0x24) | Exported Function | 0x10009710 | 0x00009710
`EdpIsUIPolicyEvaluationEnabledForThread` | 37 (0x25) | Exported Function | 0x10009730 | 0x00009730
`EdpIsValidSubjectForEncryption` | 38 (0x26) | Exported Function | 0x10009750 | 0x00009750
`EdpRequestAccess` | 39 (0x27) | Exported Function | 0x1000df20 | 0x0000df20
`EdpRequestAccessForContext` | 40 (0x28) | Exported Function | 0x1000e0b0 | 0x0000e0b0
`EdpSetEnterpriseIdForClipboard` | 41 (0x29) | Exported Function | 0x100098a0 | 0x000098a0
`EdpSetSourceAppIdForClipboard` | 42 (0x2a) | Exported Function | 0x100098d0 | 0x000098d0
`EdpSetSourceIsEnlightenedForClipboard` | 43 (0x2b) | Exported Function | 0x100098f0 | 0x000098f0
`EdpShouldShowEnterpriseIndicator` | 44 (0x2c) | Exported Function | 0x10009910 | 0x00009910
`EdpUtilCreateEnterpriseContextFromEnterpriseId` | 45 (0x2d) | Exported Function | 0x10009a70 | 0x00009a70
`EdpUtilFreeEnterpriseContext` | 46 (0x2e) | Exported Function | 0x10009b90 | 0x00009b90
`EdpUtilGetEnterpriseContextByName` | 47 (0x2f) | Exported Function | 0x10009ba0 | 0x00009ba0
`EdpUtilGetEnterpriseContextByProcess` | 48 (0x30) | Exported Function | 0x10009bc0 | 0x00009bc0
`EdpUtilGetEnterpriseContextByWindowHandle` | 49 (0x31) | Exported Function | 0x10009d70 | 0x00009d70
`EdpUtilGetEnterpriseContextForCurrentView` | 50 (0x32) | Exported Function | 0x10009d90 | 0x00009d90
`EdpUtilGetEnterpriseContextForView` | 51 (0x33) | Exported Function | 0x10009d70 | 0x00009d70
`EdpUtilIsAppEnlightened` | 52 (0x34) | Exported Function | 0x10009db0 | 0x00009db0
`EdpGetPrimaryIdentities` | 29 (0x1d) | Exported Function | 0x100094f0 | 0x000094f0
`EdpGetPersonalEnterpriseIdString` | 28 (0x1c) | Exported Function | 0x100093c0 | 0x000093c0
`EdpGetIsManaged` | 27 (0x1b) | Exported Function | 0x10004370 | 0x00004370
`EdpGetFilePathsForDataObject` | 26 (0x1a) | Exported Function | 0x1000ae90 | 0x0000ae90
`EdpAuditAction` | 2 (0x2) | Exported Function | 0x10008a90 | 0x00008a90
`EdpCanCallerAccessWin32Clipboard` | 3 (0x3) | Exported Function | 0x1000a520 | 0x0000a520
`EdpCheckAccess` | 4 (0x4) | Exported Function | 0x1000d490 | 0x0000d490
`EdpCheckAccessForContext` | 5 (0x5) | Exported Function | 0x1000d600 | 0x0000d600
`EdpCheckIsDpapiNgEntId` | 6 (0x6) | Exported Function | 0x10008e20 | 0x00008e20
`EdpCheckIsRmsEntId` | 7 (0x7) | Exported Function | 0x10008e40 | 0x00008e40
`EdpClearClipboardMetaData` | 8 (0x8) | Exported Function | 0x10008e60 | 0x00008e60
`EdpConvertProtectorToExternalId` | 9 (0x9) | Exported Function | 0x10008e70 | 0x00008e70
`EdpFreeContext` | 10 (0xa) | Exported Function | 0x1000d640 | 0x0000d640
`EdpGetAppLockerUniqueAppIdentifier` | 11 (0xb) | Exported Function | 0x10008e90 | 0x00008e90
`EdpGetAppLockerUniqueAppIdentifierByToken` | 12 (0xc) | Exported Function | 0x10008ff0 | 0x00008ff0
`EdpUtilQueryPolicy` | 53 (0x35) | Exported Function | 0x10009dd0 | 0x00009dd0
`EdpGetAppLockerUniqueAppIdentifierByTokenEx` | 13 (0xd) | Exported Function | 0x10009010 | 0x00009010
`EdpGetContextForBinaryPath` | 15 (0xf) | Exported Function | 0x1000d6c0 | 0x0000d6c0
`EdpGetContextForImpersonatedToken` | 16 (0x10) | Exported Function | 0x1000d6e0 | 0x0000d6e0
`EdpGetContextForPackageFullName` | 17 (0x11) | Exported Function | 0x1000d8c0 | 0x0000d8c0
`EdpGetContextForProcess` | 18 (0x12) | Exported Function | 0x1000d8e0 | 0x0000d8e0
`EdpGetContextForWindow` | 19 (0x13) | Exported Function | 0x1000daf0 | 0x0000daf0
`EdpGetDataInfoFromDataObject` | 20 (0x14) | Exported Function | 0x1000a9d0 | 0x0000a9d0
`EdpGetDataInfoFromWin32Clipboard` | 21 (0x15) | Exported Function | 0x1000ac10 | 0x0000ac10
`EdpGetEnterpriseIdForClipboard` | 22 (0x16) | Exported Function | 0x10009100 | 0x00009100
`EdpGetEnterpriseIdForDataObject` | 23 (0x17) | Exported Function | 0x1000ad20 | 0x0000ad20
`EdpGetEnterpriseIdForUIEnforcement` | 24 (0x18) | Exported Function | 0x10009120 | 0x00009120
`EdpGetEnterpriseIdForUIEnforcementFromProcess` | 25 (0x19) | Exported Function | 0x10009140 | 0x00009140
`EdpGetClipboardAccessDeniedData` | 14 (0xe) | Exported Function | 0x1000a720 | 0x0000a720
`GetProcessUniqueIdFromToken` | 54 (0x36) | Exported Function | 0x10009e10 | 0x00009e10


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: EDPUTIL.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/403d0a01298ee1875e7b4cd1a6fcd67953b6c19bc2fc92b547b8870e3edc5b19/detection/





MIT License. Copyright (c) 2020 Strontic.


