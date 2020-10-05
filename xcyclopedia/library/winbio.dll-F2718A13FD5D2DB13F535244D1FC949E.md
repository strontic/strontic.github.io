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

Function Name | Ordinal | Type
-- | -- | --
`WinBioNgcAuthorizeEnrollment` | 50 | Exported Function
`WinBioNgcCloseAuthorizationSession` | 51 | Exported Function
`WinBioLogonIdentifiedUser` | 48 | Exported Function
`WinBioMonitorPresence` | 49 | Exported Function
`WinBioNgcGetAuthorizationWithTicket` | 52 | Exported Function
`WinBioOpenSession` | 54 | Exported Function
`WinBioProtectData` | 55 | Exported Function
`WinBioNgcOpenAuthorizationSession` | 53 | Exported Function
`WinBioNotifyPasswordChange` | 1 | Exported Function
`WinBioGetProtectionPolicy` | 41 | Exported Function
`WinBioIdentify` | 42 | Exported Function
`WinBioGetPolicyProtectionSupport` | 39 | Exported Function
`WinBioGetProperty` | 40 | Exported Function
`WinBioIdentifyAndReleaseTicket` | 43 | Exported Function
`WinBioLocateSensorWithCallback` | 46 | Exported Function
`WinBioLockUnit` | 47 | Exported Function
`WinBioIdentifyWithCallback` | 44 | Exported Function
`WinBioLocateSensor` | 45 | Exported Function
`WinBioUnprotectData` | 67 | Exported Function
`WinBioUnregisterEventMonitor` | 68 | Exported Function
`WinBioSetProperty` | 65 | Exported Function
`WinBioUnlockUnit` | 66 | Exported Function
`WinBioUnregisterServiceMonitor` | 69 | Exported Function
`WinBioVerifyWithCallback` | 72 | Exported Function
`WinBioWait` | 73 | Exported Function
`WinBioVerify` | 70 | Exported Function
`WinBioVerifyAndReleaseTicket` | 71 | Exported Function
`WinBioRegisterServiceMonitor` | 58 | Exported Function
`WinBioReleaseFocus` | 59 | Exported Function
`WinBioProtectDataWithPolicy` | 56 | Exported Function
`WinBioRegisterEventMonitor` | 57 | Exported Function
`WinBioRemoveAllCredentials` | 60 | Exported Function
`WinBioSetCredential` | 63 | Exported Function
`WinBioSetMSACredential` | 64 | Exported Function
`WinBioRemoveAllDomainCredentials` | 61 | Exported Function
`WinBioRemoveCredential` | 62 | Exported Function
`WinBioGetLogonSetting` | 38 | Exported Function
`WinBioCloseFramework` | 13 | Exported Function
`WinBioCloseSession` | 14 | Exported Function
`WinBioCaptureSample` | 11 | Exported Function
`WinBioCaptureSampleWithCallback` | 12 | Exported Function
`WinBioControlUnit` | 15 | Exported Function
`WinBioDiscardTicket` | 18 | Exported Function
`WinBioEnrollAuthorize` | 19 | Exported Function
`WinBioControlUnitPrivileged` | 16 | Exported Function
`WinBioDeleteTemplate` | 17 | Exported Function
`WinBioAsyncEnumBiometricUnits` | 4 | Exported Function
`WinBioAsyncEnumDatabases` | 5 | Exported Function
`_BioLogonIdentifiedUser` | 2 | Exported Function
`WinBioAcquireFocus` | 3 | Exported Function
`WinBioAsyncEnumServiceProviders` | 6 | Exported Function
`WinBioAsyncOpenSession` | 9 | Exported Function
`WinBioCancel` | 10 | Exported Function
`WinBioAsyncMonitorFrameworkChanges` | 7 | Exported Function
`WinBioAsyncOpenFramework` | 8 | Exported Function
`WinBioFree` | 31 | Exported Function
`WinBioGetCredentialState` | 32 | Exported Function
`WinBioEnumEnrollments` | 29 | Exported Function
`WinBioEnumServiceProviders` | 30 | Exported Function
`WinBioGetCredentialWithTicket` | 33 | Exported Function
`WinBioGetEnrolledFactors` | 36 | Exported Function
`WinBioGetGestureMetadata` | 37 | Exported Function
`WinBioGetDomainLogonSetting` | 34 | Exported Function
`WinBioGetEnabledSetting` | 35 | Exported Function
`WinBioEnrollCaptureWithCallback` | 22 | Exported Function
`WinBioEnrollCommit` | 23 | Exported Function
`WinBioEnrollBegin` | 20 | Exported Function
`WinBioEnrollCapture` | 21 | Exported Function
`WinBioEnrollDiscard` | 24 | Exported Function
`WinBioEnumBiometricUnits` | 27 | Exported Function
`WinBioEnumDatabases` | 28 | Exported Function
`WinBioEnrollRevoke` | 25 | Exported Function
`WinBioEnrollSelect` | 26 | Exported Function


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


