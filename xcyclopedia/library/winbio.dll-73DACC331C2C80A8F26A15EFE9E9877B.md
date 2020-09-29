---
title: winbio.dll | Windows Biometrics Client API
excerpt: What is winbio.dll?
---

# winbio.dll 

* File Path: `C:\Windows\system32\winbio.dll`
* Description: Windows Biometrics Client API

## Hashes

Type | Hash
-- | --
MD5 | `73DACC331C2C80A8F26A15EFE9E9877B`
SHA1 | `E49E16CC07F1366393569F68A0C2F6AB39B4E193`
SHA256 | `B82CAB36AB852421B548EA1EB91C639D7DEE9A099724BFB00170D5E1C267655F`
SHA384 | `4E5818B27C4F952CBC901A77C1A288B082D3370C35DD4C36B15F785B1BF7E148F79D8B8E4DE7E236395081AE29093A18`
SHA512 | `B54947D20702D9269D2BBBF26335D649219BE902C3FA8412D78CD4824AA2FF164E13FD9991BEA96660EE2B6933E5C06E554BE436842F6958EAF4664949DFAA48`
SSDEEP | `3072:5gxORDPWYJKzgMk8sTfnsX20zem9SvGW3lDgjHd32hutxqSqEcv/WmGuMziY:5vPWpWQzDw3Cd32humSh2Wm`
IMP | `9A3665AFF021436181CEA802B1865483`
PESHA1 | `96E62AFDE569DC88E533F03BA57268D7D9B593BB`
PE256 | `8EB6C2BAF7D64CF1C5574390D844AB2FB2118C0FB8C4C5914062116DFB045258`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_BioLogonIdentifiedUser` | 2 (0x2) | Exported Function | 0x0000000180015d40 | 0x00015d40
`WinBioNgcOpenAuthorizationSession` | 53 (0x35) | Exported Function | 0x00000001800166c0 | 0x000166c0
`WinBioNgcGetAuthorizationWithTicket` | 52 (0x34) | Exported Function | 0x0000000180016bb0 | 0x00016bb0
`WinBioNgcCloseAuthorizationSession` | 51 (0x33) | Exported Function | 0x0000000180016a40 | 0x00016a40
`WinBioNgcAuthorizeEnrollment` | 50 (0x32) | Exported Function | 0x00000001800168a0 | 0x000168a0
`WinBioMonitorPresence` | 49 (0x31) | Exported Function | 0x0000000180012e20 | 0x00012e20
`WinBioLogonIdentifiedUser` | 48 (0x30) | Exported Function | 0x0000000180015bd0 | 0x00015bd0
`WinBioNotifyPasswordChange` | 1 (0x1) | Exported Function | 0x000000018001bf50 | 0x0001bf50
`WinBioLockUnit` | 47 (0x2f) | Exported Function | 0x0000000180013d00 | 0x00013d00
`WinBioLocateSensor` | 45 (0x2d) | Exported Function | 0x0000000180010ca0 | 0x00010ca0
`WinBioIdentifyWithCallback` | 44 (0x2c) | Exported Function | 0x00000001800104d0 | 0x000104d0
`WinBioIdentifyAndReleaseTicket` | 43 (0x2b) | Exported Function | 0x0000000180010680 | 0x00010680
`WinBioIdentify` | 42 (0x2a) | Exported Function | 0x00000001800100f0 | 0x000100f0
`WinBioGetProtectionPolicy` | 41 (0x29) | Exported Function | 0x00000001800163a0 | 0x000163a0
`WinBioGetProperty` | 40 (0x28) | Exported Function | 0x0000000180014e60 | 0x00014e60
`WinBioLocateSensorWithCallback` | 46 (0x2e) | Exported Function | 0x0000000180010ff0 | 0x00010ff0
`WinBioOpenSession` | 54 (0x36) | Exported Function | 0x000000018000ef00 | 0x0000ef00
`WinBioProtectData` | 55 (0x37) | Exported Function | 0x0000000180015800 | 0x00015800
`WinBioProtectDataWithPolicy` | 56 (0x38) | Exported Function | 0x00000001800163a0 | 0x000163a0
`WinBioVerifyAndReleaseTicket` | 71 (0x47) | Exported Function | 0x000000018000fca0 | 0x0000fca0
`WinBioVerify` | 70 (0x46) | Exported Function | 0x000000018000f6c0 | 0x0000f6c0
`WinBioUnregisterServiceMonitor` | 69 (0x45) | Exported Function | 0x00000001800174e0 | 0x000174e0
`WinBioUnregisterEventMonitor` | 68 (0x44) | Exported Function | 0x0000000180012d90 | 0x00012d90
`WinBioUnprotectData` | 67 (0x43) | Exported Function | 0x00000001800159e0 | 0x000159e0
`WinBioUnlockUnit` | 66 (0x42) | Exported Function | 0x0000000180014080 | 0x00014080
`WinBioSetProperty` | 65 (0x41) | Exported Function | 0x0000000180015350 | 0x00015350
`WinBioSetMSACredential` | 64 (0x40) | Exported Function | 0x00000001800174e0 | 0x000174e0
`WinBioSetCredential` | 63 (0x3f) | Exported Function | 0x0000000180017320 | 0x00017320
`WinBioRemoveCredential` | 62 (0x3e) | Exported Function | 0x00000001800174f0 | 0x000174f0
`WinBioRemoveAllDomainCredentials` | 61 (0x3d) | Exported Function | 0x0000000180017740 | 0x00017740
`WinBioRemoveAllCredentials` | 60 (0x3c) | Exported Function | 0x0000000180017660 | 0x00017660
`WinBioReleaseFocus` | 59 (0x3b) | Exported Function | 0x0000000180016250 | 0x00016250
`WinBioRegisterServiceMonitor` | 58 (0x3a) | Exported Function | 0x00000001800174e0 | 0x000174e0
`WinBioRegisterEventMonitor` | 57 (0x39) | Exported Function | 0x0000000180012c00 | 0x00012c00
`WinBioGetPolicyProtectionSupport` | 39 (0x27) | Exported Function | 0x0000000180016360 | 0x00016360
`WinBioVerifyWithCallback` | 72 (0x48) | Exported Function | 0x000000018000fad0 | 0x0000fad0
`WinBioGetLogonSetting` | 38 (0x26) | Exported Function | 0x0000000180015fa0 | 0x00015fa0
`WinBioGetEnrolledFactors` | 36 (0x24) | Exported Function | 0x0000000180015ba0 | 0x00015ba0
`WinBioControlUnitPrivileged` | 16 (0x10) | Exported Function | 0x0000000180014920 | 0x00014920
`WinBioControlUnit` | 15 (0xf) | Exported Function | 0x00000001800143e0 | 0x000143e0
`WinBioCloseSession` | 14 (0xe) | Exported Function | 0x000000018000f5a0 | 0x0000f5a0
`WinBioCloseFramework` | 13 (0xd) | Exported Function | 0x000000018000e6a0 | 0x0000e6a0
`WinBioCaptureSampleWithCallback` | 12 (0xc) | Exported Function | 0x0000000180013790 | 0x00013790
`WinBioCaptureSample` | 11 (0xb) | Exported Function | 0x0000000180013350 | 0x00013350
`WinBioDeleteTemplate` | 17 (0x11) | Exported Function | 0x0000000180013950 | 0x00013950
`WinBioCancel` | 10 (0xa) | Exported Function | 0x0000000180010b40 | 0x00010b40
`WinBioAsyncOpenFramework` | 8 (0x8) | Exported Function | 0x000000018000e4b0 | 0x0000e4b0
`WinBioAsyncMonitorFrameworkChanges` | 7 (0x7) | Exported Function | 0x000000018000eb30 | 0x0000eb30
`WinBioAsyncEnumServiceProviders` | 6 (0x6) | Exported Function | 0x000000018000e7b0 | 0x0000e7b0
`WinBioAsyncEnumDatabases` | 5 (0x5) | Exported Function | 0x000000018000ea00 | 0x0000ea00
`WinBioAsyncEnumBiometricUnits` | 4 (0x4) | Exported Function | 0x000000018000e8e0 | 0x0000e8e0
`WinBioAcquireFocus` | 3 (0x3) | Exported Function | 0x0000000180016140 | 0x00016140
`WinBioAsyncOpenSession` | 9 (0x9) | Exported Function | 0x000000018000f180 | 0x0000f180
`WinBioDiscardTicket` | 18 (0x12) | Exported Function | 0x00000001800163b0 | 0x000163b0
`WinBioEnrollAuthorize` | 19 (0x13) | Exported Function | 0x00000001800114e0 | 0x000114e0
`WinBioEnrollBegin` | 20 (0x14) | Exported Function | 0x00000001800111a0 | 0x000111a0
`WinBioGetEnabledSetting` | 35 (0x23) | Exported Function | 0x0000000180015ed0 | 0x00015ed0
`WinBioGetDomainLogonSetting` | 34 (0x22) | Exported Function | 0x0000000180016070 | 0x00016070
`WinBioGetCredentialWithTicket` | 33 (0x21) | Exported Function | 0x00000001800179a0 | 0x000179a0
`WinBioGetCredentialState` | 32 (0x20) | Exported Function | 0x0000000180017820 | 0x00017820
`WinBioFree` | 31 (0x1f) | Exported Function | 0x0000000180015eb0 | 0x00015eb0
`WinBioEnumServiceProviders` | 30 (0x1e) | Exported Function | 0x000000018000db50 | 0x0000db50
`WinBioEnumEnrollments` | 29 (0x1d) | Exported Function | 0x00000001800127a0 | 0x000127a0
`WinBioEnumDatabases` | 28 (0x1c) | Exported Function | 0x000000018000de40 | 0x0000de40
`WinBioEnumBiometricUnits` | 27 (0x1b) | Exported Function | 0x000000018000dcd0 | 0x0000dcd0
`WinBioEnrollSelect` | 26 (0x1a) | Exported Function | 0x00000001800118b0 | 0x000118b0
`WinBioEnrollRevoke` | 25 (0x19) | Exported Function | 0x00000001800116f0 | 0x000116f0
`WinBioEnrollDiscard` | 24 (0x18) | Exported Function | 0x00000001800124c0 | 0x000124c0
`WinBioEnrollCommit` | 23 (0x17) | Exported Function | 0x00000001800120f0 | 0x000120f0
`WinBioEnrollCaptureWithCallback` | 22 (0x16) | Exported Function | 0x0000000180011f40 | 0x00011f40
`WinBioEnrollCapture` | 21 (0x15) | Exported Function | 0x0000000180011bc0 | 0x00011bc0
`WinBioGetGestureMetadata` | 37 (0x25) | Exported Function | 0x0000000180016520 | 0x00016520
`WinBioWait` | 73 (0x49) | Exported Function | 0x0000000180010a90 | 0x00010a90


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winbio.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/b82cab36ab852421b548ea1eb91c639d7dee9a099724bfb00170d5e1c267655f/detection/





MIT License. Copyright (c) 2020 Strontic.


