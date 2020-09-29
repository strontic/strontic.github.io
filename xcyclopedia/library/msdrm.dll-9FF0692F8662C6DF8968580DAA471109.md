---
title: msdrm.dll | Windows Rights Management client
excerpt: What is msdrm.dll?
---

# msdrm.dll 

* File Path: `C:\Windows\system32\msdrm.dll`
* Description: Windows Rights Management client

## Hashes

Type | Hash
-- | --
MD5 | `9FF0692F8662C6DF8968580DAA471109`
SHA1 | `FDB4BA72327E0F11A3DD83E682C192C03C92EBF3`
SHA256 | `7484C2D1C753F3954254A548E7AED52A1733000FFFF1A28A652B73DA8B807A6B`
SHA384 | `F9224E9923153914EB835547ACC693226ADA8FB950B34EC9A894B4FD1B38A476DA84EA058441D4689D50FDF0BD0838FC`
SHA512 | `39D32815575361DB19E722E759222DA3EC9C2439726341C1EC73FC0B561B6244365706AA8DC2BBD85087731C33FC67021E1F07C1E238D204D4179185F204C0F9`
SSDEEP | `12288:esVIJ81pHFeyoZA2G4jirkZhCVqxY4TudG3nYv6CvrkO:es2J81pHAyoO2Gs/vTudGXYvdvrkO`
IMP | `20488142217F9C8B86591FE0A7B4DAEB`
PESHA1 | `D5C117DE5C5BD98DCCB0D7B4792F122987823667`
PE256 | `43774A1C0241A93E9AE3CE7AB6EA06B2DBB2D3754ADA5EE7308C6590762ABB98`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`__AddMachineCertToLicenseStore` | 95 (0x5f) | Exported Function | 0x00000001669348d0 | 0x000348d0
`DRMGetUsagePolicy` | 64 (0x40) | Exported Function | 0x0000000166904820 | 0x00004820
`DRMGetUnboundLicenseObjectCount` | 63 (0x3f) | Exported Function | 0x000000016691caf0 | 0x0001caf0
`DRMGetUnboundLicenseObject` | 62 (0x3e) | Exported Function | 0x000000016691cbe0 | 0x0001cbe0
`DRMGetUnboundLicenseAttributeCount` | 61 (0x3d) | Exported Function | 0x000000016691cd50 | 0x0001cd50
`DRMGetUnboundLicenseAttribute` | 60 (0x3c) | Exported Function | 0x000000016691ce40 | 0x0001ce40
`DRMGetTime` | 59 (0x3b) | Exported Function | 0x000000016694f660 | 0x0004f660
`DRMGetSignedIssuanceLicenseEx` | 58 (0x3a) | Exported Function | 0x0000000166902ed0 | 0x00002ed0
`DRMGetSignedIssuanceLicense` | 57 (0x39) | Exported Function | 0x0000000166903280 | 0x00003280
`DRMGetServiceLocation` | 56 (0x38) | Exported Function | 0x0000000166919e80 | 0x00019e80
`DRMGetUserInfo` | 65 (0x41) | Exported Function | 0x00000001669039d0 | 0x000039d0
`DRMGetSecurityProvider` | 55 (0x37) | Exported Function | 0x0000000166919020 | 0x00019020
`DRMGetRightExtendedInfo` | 53 (0x35) | Exported Function | 0x0000000166903d20 | 0x00003d20
`DRMGetRevocationPoint` | 52 (0x34) | Exported Function | 0x00000001669046b0 | 0x000046b0
`DRMGetProcAddress` | 51 (0x33) | Exported Function | 0x000000016694f590 | 0x0004f590
`DRMGetOwnerLicense` | 50 (0x32) | Exported Function | 0x0000000166904b10 | 0x00004b10
`DRMGetNameAndDescription` | 49 (0x31) | Exported Function | 0x0000000166904a10 | 0x00004a10
`DRMGetMetaData` | 48 (0x30) | Exported Function | 0x00000001669042c0 | 0x000042c0
`DRMGetIssuanceLicenseTemplate` | 47 (0x2f) | Exported Function | 0x0000000166902df0 | 0x00002df0
`DRMGetIssuanceLicenseInfo` | 46 (0x2e) | Exported Function | 0x00000001669044f0 | 0x000044f0
`DRMGetIntervalTime` | 45 (0x2d) | Exported Function | 0x0000000166904cb0 | 0x00004cb0
`DRMGetRightInfo` | 54 (0x36) | Exported Function | 0x0000000166903bc0 | 0x00003bc0
`DRMGetInfo` | 44 (0x2c) | Exported Function | 0x000000016694f440 | 0x0004f440
`DRMGetUserRights` | 66 (0x42) | Exported Function | 0x0000000166904020 | 0x00004020
`DRMInitEnvironment` | 68 (0x44) | Exported Function | 0x000000016694f750 | 0x0004f750
`DRMSetRevocationPoint` | 82 (0x52) | Exported Function | 0x00000001669028f0 | 0x000028f0
`DRMSetNameAndDescription` | 81 (0x51) | Exported Function | 0x0000000166902c90 | 0x00002c90
`DRMSetMetaData` | 80 (0x50) | Exported Function | 0x0000000166902300 | 0x00002300
`DRMSetIntervalTime` | 79 (0x4f) | Exported Function | 0x0000000166904c20 | 0x00004c20
`DRMSetGlobalOptions` | 78 (0x4e) | Exported Function | 0x0000000166917100 | 0x00017100
`DRMSetApplicationSpecificData` | 77 (0x4d) | Exported Function | 0x0000000166902b30 | 0x00002b30
`DRMRepair` | 76 (0x4c) | Exported Function | 0x000000016691a240 | 0x0001a240
`DRMRegisterRevocationList` | 75 (0x4b) | Exported Function | 0x000000016694fae0 | 0x0004fae0
`DRMRegisterProtectedWindow` | 74 (0x4a) | Exported Function | 0x000000016691a9a0 | 0x0001a9a0
`DRMGetUsers` | 67 (0x43) | Exported Function | 0x0000000166903f00 | 0x00003f00
`DRMRegisterContent` | 73 (0x49) | Exported Function | 0x0000000166916d50 | 0x00016d50
`DRMpFileUnprotect` | 89 (0x59) | Exported Function | 0x00000001669538c0 | 0x000538c0
`DRMpFileProtect` | 88 (0x58) | Exported Function | 0x0000000166953550 | 0x00053550
`DRMpFileIsProtected` | 87 (0x57) | Exported Function | 0x0000000166953ae0 | 0x00053ae0
`DRMpFileInitialize` | 86 (0x56) | Exported Function | 0x00000001669532a0 | 0x000532a0
`DRMpCloseFile` | 85 (0x55) | Exported Function | 0x0000000166953ca0 | 0x00053ca0
`DRMParseUnboundLicense` | 72 (0x48) | Exported Function | 0x000000016691c930 | 0x0001c930
`DRMLoadLibrary` | 71 (0x47) | Exported Function | 0x000000016694f9c0 | 0x0004f9c0
`DRMIsWindowProtected` | 70 (0x46) | Exported Function | 0x000000016691aae0 | 0x0001aae0
`DRMIsActivated` | 69 (0x45) | Exported Function | 0x0000000166917500 | 0x00017500
`DRMpFreeMemory` | 90 (0x5a) | Exported Function | 0x0000000166953cd0 | 0x00053cd0
`DRMSetUsagePolicy` | 83 (0x53) | Exported Function | 0x0000000166902600 | 0x00002600
`DRMGetEnvironmentInfo` | 43 (0x2b) | Exported Function | 0x000000016694f410 | 0x0004f410
`DRMGetCertificateChainCount` | 41 (0x29) | Exported Function | 0x0000000166939180 | 0x00039180
`DRMCreateBoundLicense` | 16 (0x10) | Exported Function | 0x000000016694e2f0 | 0x0004e2f0
`DRMConstructCertificateChain` | 15 (0xf) | Exported Function | 0x0000000166938f30 | 0x00038f30
`DRMCloseSession` | 14 (0xe) | Exported Function | 0x0000000166919140 | 0x00019140
`DRMCloseQueryHandle` | 13 (0xd) | Exported Function | 0x000000016691caa0 | 0x0001caa0
`DRMClosePubHandle` | 12 (0xc) | Exported Function | 0x0000000166903980 | 0x00003980
`DRMCloseHandle` | 11 (0xb) | Exported Function | 0x000000016694e210 | 0x0004e210
`DRMCloseEnvironmentHandle` | 10 (0xa) | Exported Function | 0x0000000166916c20 | 0x00016c20
`DRMClearAllRights` | 9 (0x9) | Exported Function | 0x0000000166902270 | 0x00002270
`DRMCheckSecurity` | 8 (0x8) | Exported Function | 0x000000016694e1a0 | 0x0004e1a0
`DRMCreateClientSession` | 17 (0x11) | Exported Function | 0x0000000166917300 | 0x00017300
`DRMAttest` | 7 (0x7) | Exported Function | 0x0000000166915f40 | 0x00015f40
`DRMAddLicense` | 5 (0x5) | Exported Function | 0x0000000166918bf0 | 0x00018bf0
`DRMActivate` | 4 (0x4) | Exported Function | 0x0000000166917b80 | 0x00017b80
`DRMAcquireLicense` | 3 (0x3) | Exported Function | 0x00000001669184e0 | 0x000184e0
`DRMAcquireIssuanceLicenseTemplate` | 2 (0x2) | Exported Function | 0x000000016691afe0 | 0x0001afe0
`DRMAcquireAdvisories` | 1 (0x1) | Exported Function | 0x0000000166919390 | 0x00019390
`DllUnregisterServer` | 94 (0x5e) | Exported Function | 0x0000000166916340 | 0x00016340
`DllRegisterServer` | 93 (0x5d) | Exported Function | 0x0000000166916330 | 0x00016330
`DllGetClassObject` | 92 (0x5c) | Exported Function | 0x00000001669161f0 | 0x000161f0
`DllCanUnloadNow` | 91 (0x5b) | Exported Function | 0x00000001669161c0 | 0x000161c0
`DRMAddRightWithUser` | 6 (0x6) | Exported Function | 0x0000000166902150 | 0x00002150
`DRMGetClientVersion` | 42 (0x2a) | Exported Function | 0x000000016691a8e0 | 0x0001a8e0
`DRMCreateEnablingBitsDecryptor` | 18 (0x12) | Exported Function | 0x000000016694e660 | 0x0004e660
`DRMCreateEnablingPrincipal` | 20 (0x14) | Exported Function | 0x000000016694eb60 | 0x0004eb60
`DRMGetBoundLicenseObjectCount` | 40 (0x28) | Exported Function | 0x000000016694f260 | 0x0004f260
`DRMGetBoundLicenseObject` | 39 (0x27) | Exported Function | 0x000000016694f310 | 0x0004f310
`DRMGetBoundLicenseAttributeCount` | 38 (0x26) | Exported Function | 0x000000016694f050 | 0x0004f050
`DRMGetBoundLicenseAttribute` | 37 (0x25) | Exported Function | 0x000000016694f100 | 0x0004f100
`DRMGetApplicationSpecificData` | 36 (0x24) | Exported Function | 0x0000000166904410 | 0x00004410
`DRMEnumerateLicense` | 35 (0x23) | Exported Function | 0x0000000166919a60 | 0x00019a60
`DRMEncrypt` | 34 (0x22) | Exported Function | 0x000000016694ef60 | 0x0004ef60
`DRMEncode` | 33 (0x21) | Exported Function | 0x00000001669191f0 | 0x000191f0
`DRMDuplicateSession` | 32 (0x20) | Exported Function | 0x0000000166919190 | 0x00019190
`DRMCreateEnablingBitsEncryptor` | 19 (0x13) | Exported Function | 0x000000016694e8e0 | 0x0004e8e0
`DRMDuplicatePubHandle` | 31 (0x1f) | Exported Function | 0x00000001669039c0 | 0x000039c0
`DRMDuplicateEnvironmentHandle` | 29 (0x1d) | Exported Function | 0x000000016694eec0 | 0x0004eec0
`DRMDeleteLicense` | 28 (0x1c) | Exported Function | 0x0000000166918dc0 | 0x00018dc0
`DRMDecrypt` | 27 (0x1b) | Exported Function | 0x000000016694ed30 | 0x0004ed30
`DRMDeconstructCertificateChain` | 26 (0x1a) | Exported Function | 0x0000000166938fe0 | 0x00038fe0
`DRMDecode` | 25 (0x19) | Exported Function | 0x00000001669192f0 | 0x000192f0
`DRMCreateUser` | 24 (0x18) | Exported Function | 0x0000000166901cd0 | 0x00001cd0
`DRMCreateRight` | 23 (0x17) | Exported Function | 0x0000000166901f20 | 0x00001f20
`DRMCreateLicenseStorageSession` | 22 (0x16) | Exported Function | 0x0000000166917f40 | 0x00017f40
`DRMCreateIssuanceLicense` | 21 (0x15) | Exported Function | 0x00000001669017f0 | 0x000017f0
`DRMDuplicateHandle` | 30 (0x1e) | Exported Function | 0x000000016694ee20 | 0x0004ee20
`DRMVerify` | 84 (0x54) | Exported Function | 0x0000000166915f40 | 0x00015f40


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msdrm.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/7484c2d1c753f3954254a548e7aed52a1733000ffff1a28a652b73da8b807a6b/detection/





MIT License. Copyright (c) 2020 Strontic.


