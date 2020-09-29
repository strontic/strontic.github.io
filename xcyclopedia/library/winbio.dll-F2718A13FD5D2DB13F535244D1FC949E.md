---
title: winbio.dll | Windows Biometrics Client API
excerpt: What is winbio.dll?
---

# winbio.dll 

* File Path: `C:\Windows\SysWOW64\winbio.dll`
* Description: Windows Biometrics Client API

## Hashes

Type | Hash
-- | --
MD5 | `F2718A13FD5D2DB13F535244D1FC949E`
SHA1 | `B5180DBDED730F754EED9B9DA4355B452A65E973`
SHA256 | `8FD634A78FE8493F94598BD7C007F4351EFFD8C3AD9636E95499EF5DDBE63103`
SHA384 | `9DE5B70818887FC61443BA78B6A5E7FAEA5132D8A9E13DB603D8678F87FC4D5EBDD04BED98935ECBE2AE23BA326B28E0`
SHA512 | `FBDE89D4C0007AF1BBEBEC78740ED02DFB35BF199B3199AAA0012AEE692D4AF9856186ACF5D7ED7B7090FCDF5DC806A8677A478F773A6A90255F0CC3E70A8D82`
SSDEEP | `3072:MDAjRbmA0LWm297NeVDyz37/DQ8zA8vQRhdgBX47QzKL:lbeKdNetwAmIdAo7Qzc`
IMP | `87B1DB78E48A0174388A35D22C441A21`
PESHA1 | `E113CA5EA2BE3BD16CAC91A8DD82109E957DBD60`
PE256 | `7DFCA6B0878AC98D7D8E0CAC6E9E0DBB53432BA2362E9036D5144B54FF37C31E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_BioLogonIdentifiedUser` | 2 (0x2) | Exported Function | 0x10013150 | 0x00013150
`WinBioNgcOpenAuthorizationSession` | 53 (0x35) | Exported Function | 0x10013950 | 0x00013950
`WinBioNgcGetAuthorizationWithTicket` | 52 (0x34) | Exported Function | 0x10013d90 | 0x00013d90
`WinBioNgcCloseAuthorizationSession` | 51 (0x33) | Exported Function | 0x10013c50 | 0x00013c50
`WinBioNgcAuthorizeEnrollment` | 50 (0x32) | Exported Function | 0x10013af0 | 0x00013af0
`WinBioMonitorPresence` | 49 (0x31) | Exported Function | 0x10010d80 | 0x00010d80
`WinBioLogonIdentifiedUser` | 48 (0x30) | Exported Function | 0x10012ff0 | 0x00012ff0
`WinBioNotifyPasswordChange` | 1 (0x1) | Exported Function | 0x10017690 | 0x00017690
`WinBioLockUnit` | 47 (0x2f) | Exported Function | 0x10011830 | 0x00011830
`WinBioLocateSensor` | 45 (0x2d) | Exported Function | 0x1000f4d0 | 0x0000f4d0
`WinBioIdentifyWithCallback` | 44 (0x2c) | Exported Function | 0x1000eee0 | 0x0000eee0
`WinBioIdentifyAndReleaseTicket` | 43 (0x2b) | Exported Function | 0x1000eff0 | 0x0000eff0
`WinBioIdentify` | 42 (0x2a) | Exported Function | 0x1000ebd0 | 0x0000ebd0
`WinBioGetProtectionPolicy` | 41 (0x29) | Exported Function | 0x10013690 | 0x00013690
`WinBioGetProperty` | 40 (0x28) | Exported Function | 0x10012590 | 0x00012590
`WinBioLocateSensorWithCallback` | 46 (0x2e) | Exported Function | 0x1000f780 | 0x0000f780
`WinBioOpenSession` | 54 (0x36) | Exported Function | 0x1000de60 | 0x0000de60
`WinBioProtectData` | 55 (0x37) | Exported Function | 0x10012cb0 | 0x00012cb0
`WinBioProtectDataWithPolicy` | 56 (0x38) | Exported Function | 0x100136a0 | 0x000136a0
`WinBioVerifyAndReleaseTicket` | 71 (0x47) | Exported Function | 0x1000e870 | 0x0000e870
`WinBioVerify` | 70 (0x46) | Exported Function | 0x1000e400 | 0x0000e400
`WinBioUnregisterServiceMonitor` | 69 (0x45) | Exported Function | 0x10014960 | 0x00014960
`WinBioUnregisterEventMonitor` | 68 (0x44) | Exported Function | 0x10010d10 | 0x00010d10
`WinBioUnprotectData` | 67 (0x43) | Exported Function | 0x10012e40 | 0x00012e40
`WinBioUnlockUnit` | 66 (0x42) | Exported Function | 0x10011b10 | 0x00011b10
`WinBioSetProperty` | 65 (0x41) | Exported Function | 0x10012940 | 0x00012940
`WinBioSetMSACredential` | 64 (0x40) | Exported Function | 0x10014410 | 0x00014410
`WinBioSetCredential` | 63 (0x3f) | Exported Function | 0x10014280 | 0x00014280
`WinBioRemoveCredential` | 62 (0x3e) | Exported Function | 0x10014420 | 0x00014420
`WinBioRemoveAllDomainCredentials` | 61 (0x3d) | Exported Function | 0x10014610 | 0x00014610
`WinBioRemoveAllCredentials` | 60 (0x3c) | Exported Function | 0x10014520 | 0x00014520
`WinBioReleaseFocus` | 59 (0x3b) | Exported Function | 0x10013550 | 0x00013550
`WinBioRegisterServiceMonitor` | 58 (0x3a) | Exported Function | 0x10014950 | 0x00014950
`WinBioRegisterEventMonitor` | 57 (0x39) | Exported Function | 0x10010c30 | 0x00010c30
`WinBioGetPolicyProtectionSupport` | 39 (0x27) | Exported Function | 0x10013650 | 0x00013650
`WinBioVerifyWithCallback` | 72 (0x48) | Exported Function | 0x1000e740 | 0x0000e740
`WinBioGetLogonSetting` | 38 (0x26) | Exported Function | 0x10013330 | 0x00013330
`WinBioGetEnrolledFactors` | 36 (0x24) | Exported Function | 0x10012fc0 | 0x00012fc0
`WinBioControlUnitPrivileged` | 16 (0x10) | Exported Function | 0x100121b0 | 0x000121b0
`WinBioControlUnit` | 15 (0xf) | Exported Function | 0x10011dd0 | 0x00011dd0
`WinBioCloseSession` | 14 (0xe) | Exported Function | 0x1000e330 | 0x0000e330
`WinBioCloseFramework` | 13 (0xd) | Exported Function | 0x1000d790 | 0x0000d790
`WinBioCaptureSampleWithCallback` | 12 (0xc) | Exported Function | 0x10011470 | 0x00011470
`WinBioCaptureSample` | 11 (0xb) | Exported Function | 0x10011120 | 0x00011120
`WinBioDeleteTemplate` | 17 (0x11) | Exported Function | 0x10011590 | 0x00011590
`WinBioCancel` | 10 (0xa) | Exported Function | 0x1000f3b0 | 0x0000f3b0
`WinBioAsyncOpenFramework` | 8 (0x8) | Exported Function | 0x1000d620 | 0x0000d620
`WinBioAsyncMonitorFrameworkChanges` | 7 (0x7) | Exported Function | 0x1000db50 | 0x0000db50
`WinBioAsyncEnumServiceProviders` | 6 (0x6) | Exported Function | 0x1000d860 | 0x0000d860
`WinBioAsyncEnumDatabases` | 5 (0x5) | Exported Function | 0x1000da50 | 0x0000da50
`WinBioAsyncEnumBiometricUnits` | 4 (0x4) | Exported Function | 0x1000d960 | 0x0000d960
`WinBioAcquireFocus` | 3 (0x3) | Exported Function | 0x10013450 | 0x00013450
`WinBioAsyncOpenSession` | 9 (0x9) | Exported Function | 0x1000e030 | 0x0000e030
`WinBioDiscardTicket` | 18 (0x12) | Exported Function | 0x100136b0 | 0x000136b0
`WinBioEnrollAuthorize` | 19 (0x13) | Exported Function | 0x1000fb00 | 0x0000fb00
`WinBioEnrollBegin` | 20 (0x14) | Exported Function | 0x1000f890 | 0x0000f890
`WinBioGetEnabledSetting` | 35 (0x23) | Exported Function | 0x100132a0 | 0x000132a0
`WinBioGetDomainLogonSetting` | 34 (0x22) | Exported Function | 0x100133c0 | 0x000133c0
`WinBioGetCredentialWithTicket` | 33 (0x21) | Exported Function | 0x10014800 | 0x00014800
`WinBioGetCredentialState` | 32 (0x20) | Exported Function | 0x10014700 | 0x00014700
`WinBioFree` | 31 (0x1f) | Exported Function | 0x10013280 | 0x00013280
`WinBioEnumServiceProviders` | 30 (0x1e) | Exported Function | 0x1000cdc0 | 0x0000cdc0
`WinBioEnumEnrollments` | 29 (0x1d) | Exported Function | 0x10010900 | 0x00010900
`WinBioEnumDatabases` | 28 (0x1c) | Exported Function | 0x1000d050 | 0x0000d050
`WinBioEnumBiometricUnits` | 27 (0x1b) | Exported Function | 0x1000cf10 | 0x0000cf10
`WinBioEnrollSelect` | 26 (0x1a) | Exported Function | 0x1000fe00 | 0x0000fe00
`WinBioEnrollRevoke` | 25 (0x19) | Exported Function | 0x1000fc90 | 0x0000fc90
`WinBioEnrollDiscard` | 24 (0x18) | Exported Function | 0x100106e0 | 0x000106e0
`WinBioEnrollCommit` | 23 (0x17) | Exported Function | 0x10010400 | 0x00010400
`WinBioEnrollCaptureWithCallback` | 22 (0x16) | Exported Function | 0x100102f0 | 0x000102f0
`WinBioEnrollCapture` | 21 (0x15) | Exported Function | 0x10010050 | 0x00010050
`WinBioGetGestureMetadata` | 37 (0x25) | Exported Function | 0x100137f0 | 0x000137f0
`WinBioWait` | 73 (0x49) | Exported Function | 0x1000f330 | 0x0000f330


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winbio.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/8fd634a78fe8493f94598bd7c007f4351effd8c3ad9636e95499ef5ddbe63103/detection/





MIT License. Copyright (c) 2020 Strontic.


