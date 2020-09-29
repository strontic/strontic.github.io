---
title: edputil.dll | EDP util
excerpt: What is edputil.dll?
---

# edputil.dll 

* File Path: `C:\Windows\system32\edputil.dll`
* Description: EDP util

## Hashes

Type | Hash
-- | --
MD5 | `024FD8DA81E2277EAF914508D9E62F09`
SHA1 | `7B5834A4D70C5C28F4BDE1B25FFFC29A2852D1EE`
SHA256 | `FA96CC8F2438D4E7628BE4E3C7D48ABC91C776D4C4AF64A3641471B53DF62754`
SHA384 | `6C72326C88EDC26C5B7BF93DC1F34051D94B2D723E50CFDD3564A345724AA51F7F7A265599DEE1A9AEFA913B8D612450`
SHA512 | `BA9B70FD359564E03F832C6686F8FA1645FD391553B33C85E6A6A2E3F2E17AA3418255EB56D73730FEBA86B8F033783083CEC6EF85826A4425FA460C317CA5F2`
SSDEEP | `3072:T8ClSeVLtlkW7AoVHKGx9y+LbXzH+1fWpPkgy:T8ClSkJlJ7AaHn9y8AWp8`
IMP | `3173150472840D83979F027AE2D1081C`
PESHA1 | `DC0C4BC5AA44790914462B1362B4C168416E4AD4`
PE256 | `8404D9FD7F429EB1D159E73E67B4F79FACDFD9EBC2CE683D309D3F0C09BB7A38`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EdpAddAppClipboardConsentInCache` | 1 (0x1) | Exported Function | 0x00000001800077b0 | 0x000077b0
`EdpGetPrimaryIdentityIfManaged` | 30 (0x1e) | Exported Function | 0x0000000180008510 | 0x00008510
`EdpGetSourceAppIdForClipboard` | 31 (0x1f) | Exported Function | 0x0000000180008530 | 0x00008530
`EdpGetSourceIsEnlightenedForClipboard` | 32 (0x20) | Exported Function | 0x0000000180008540 | 0x00008540
`EdpGetWindowFromThreadId` | 33 (0x21) | Exported Function | 0x0000000180008550 | 0x00008550
`EdpIsAppClipboardConsentCached` | 34 (0x22) | Exported Function | 0x00000001800086f0 | 0x000086f0
`EdpIsContextExemptOrEnlightenedAllowed` | 35 (0x23) | Exported Function | 0x000000018000e320 | 0x0000e320
`EdpIsFileAccessAllowed` | 36 (0x24) | Exported Function | 0x0000000180008700 | 0x00008700
`EdpIsUIPolicyEvaluationEnabledForThread` | 37 (0x25) | Exported Function | 0x0000000180008710 | 0x00008710
`EdpIsValidSubjectForEncryption` | 38 (0x26) | Exported Function | 0x0000000180008730 | 0x00008730
`EdpRequestAccess` | 39 (0x27) | Exported Function | 0x000000018000e450 | 0x0000e450
`EdpRequestAccessForContext` | 40 (0x28) | Exported Function | 0x000000018000e590 | 0x0000e590
`EdpSetEnterpriseIdForClipboard` | 41 (0x29) | Exported Function | 0x00000001800088d0 | 0x000088d0
`EdpSetSourceAppIdForClipboard` | 42 (0x2a) | Exported Function | 0x0000000180008910 | 0x00008910
`EdpSetSourceIsEnlightenedForClipboard` | 43 (0x2b) | Exported Function | 0x0000000180008920 | 0x00008920
`EdpShouldShowEnterpriseIndicator` | 44 (0x2c) | Exported Function | 0x0000000180008930 | 0x00008930
`EdpUtilCreateEnterpriseContextFromEnterpriseId` | 45 (0x2d) | Exported Function | 0x0000000180008ac0 | 0x00008ac0
`EdpUtilFreeEnterpriseContext` | 46 (0x2e) | Exported Function | 0x0000000180008c00 | 0x00008c00
`EdpUtilGetEnterpriseContextByName` | 47 (0x2f) | Exported Function | 0x0000000180008c10 | 0x00008c10
`EdpUtilGetEnterpriseContextByProcess` | 48 (0x30) | Exported Function | 0x0000000180008c20 | 0x00008c20
`EdpUtilGetEnterpriseContextByWindowHandle` | 49 (0x31) | Exported Function | 0x0000000180008e50 | 0x00008e50
`EdpUtilGetEnterpriseContextForCurrentView` | 50 (0x32) | Exported Function | 0x0000000180008e60 | 0x00008e60
`EdpUtilGetEnterpriseContextForView` | 51 (0x33) | Exported Function | 0x0000000180008e50 | 0x00008e50
`EdpUtilIsAppEnlightened` | 52 (0x34) | Exported Function | 0x0000000180008e70 | 0x00008e70
`EdpGetPrimaryIdentities` | 29 (0x1d) | Exported Function | 0x0000000180008500 | 0x00008500
`EdpGetPersonalEnterpriseIdString` | 28 (0x1c) | Exported Function | 0x0000000180008370 | 0x00008370
`EdpGetIsManaged` | 27 (0x1b) | Exported Function | 0x0000000180001230 | 0x00001230
`EdpGetFilePathsForDataObject` | 26 (0x1a) | Exported Function | 0x000000018000a410 | 0x0000a410
`EdpAuditAction` | 2 (0x2) | Exported Function | 0x00000001800077c0 | 0x000077c0
`EdpCanCallerAccessWin32Clipboard` | 3 (0x3) | Exported Function | 0x0000000180009960 | 0x00009960
`EdpCheckAccess` | 4 (0x4) | Exported Function | 0x000000018000d840 | 0x0000d840
`EdpCheckAccessForContext` | 5 (0x5) | Exported Function | 0x000000018000d930 | 0x0000d930
`EdpCheckIsDpapiNgEntId` | 6 (0x6) | Exported Function | 0x0000000180007c20 | 0x00007c20
`EdpCheckIsRmsEntId` | 7 (0x7) | Exported Function | 0x0000000180007c30 | 0x00007c30
`EdpClearClipboardMetaData` | 8 (0x8) | Exported Function | 0x0000000180007c40 | 0x00007c40
`EdpConvertProtectorToExternalId` | 9 (0x9) | Exported Function | 0x0000000180007c50 | 0x00007c50
`EdpFreeContext` | 10 (0xa) | Exported Function | 0x000000018000d950 | 0x0000d950
`EdpGetAppLockerUniqueAppIdentifier` | 11 (0xb) | Exported Function | 0x0000000180007c70 | 0x00007c70
`EdpGetAppLockerUniqueAppIdentifierByToken` | 12 (0xc) | Exported Function | 0x0000000180007e40 | 0x00007e40
`EdpUtilQueryPolicy` | 53 (0x35) | Exported Function | 0x0000000180008e80 | 0x00008e80
`EdpGetAppLockerUniqueAppIdentifierByTokenEx` | 13 (0xd) | Exported Function | 0x0000000180007e60 | 0x00007e60
`EdpGetContextForBinaryPath` | 15 (0xf) | Exported Function | 0x000000018000da20 | 0x0000da20
`EdpGetContextForImpersonatedToken` | 16 (0x10) | Exported Function | 0x000000018000da30 | 0x0000da30
`EdpGetContextForPackageFullName` | 17 (0x11) | Exported Function | 0x000000018000dcc0 | 0x0000dcc0
`EdpGetContextForProcess` | 18 (0x12) | Exported Function | 0x000000018000dce0 | 0x0000dce0
`EdpGetContextForWindow` | 19 (0x13) | Exported Function | 0x000000018000df80 | 0x0000df80
`EdpGetDataInfoFromDataObject` | 20 (0x14) | Exported Function | 0x0000000180009e80 | 0x00009e80
`EdpGetDataInfoFromWin32Clipboard` | 21 (0x15) | Exported Function | 0x000000018000a100 | 0x0000a100
`EdpGetEnterpriseIdForClipboard` | 22 (0x16) | Exported Function | 0x0000000180007fb0 | 0x00007fb0
`EdpGetEnterpriseIdForDataObject` | 23 (0x17) | Exported Function | 0x000000018000a230 | 0x0000a230
`EdpGetEnterpriseIdForUIEnforcement` | 24 (0x18) | Exported Function | 0x0000000180007fc0 | 0x00007fc0
`EdpGetEnterpriseIdForUIEnforcementFromProcess` | 25 (0x19) | Exported Function | 0x0000000180007fd0 | 0x00007fd0
`EdpGetClipboardAccessDeniedData` | 14 (0xe) | Exported Function | 0x0000000180009bc0 | 0x00009bc0
`GetProcessUniqueIdFromToken` | 54 (0x36) | Exported Function | 0x0000000180008ee0 | 0x00008ee0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: EDPUTIL.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/fa96cc8f2438d4e7628be4e3c7d48abc91c776d4c4af64a3641471b53df62754/detection/





MIT License. Copyright (c) 2020 Strontic.


