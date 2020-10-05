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


